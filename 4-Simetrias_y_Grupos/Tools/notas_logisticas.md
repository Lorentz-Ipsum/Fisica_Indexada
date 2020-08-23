

# Cómo lo hacemos?

Alvaro toma apuntes.
Usa LaTeX con todas sus funcionalidades, así que aprovecha el \package{physics}

## Cosas de LaTeX

- Borrar imports
- Borrar \smallskip
- Borrar \newpage

- Cambiar \textbf{} por * *
- Cambiar \begin{equation}
- Quitar espacios antes de * y _

- Cambiar los itemize
- Eliminar:
	- \bigskip
	- \smallskip
	- \begin{center}\end{center}
	- $\bullet$

- Arreglar los tabular para que sean array y empiecen con \hline (si no en general no renderiza, y con la opcion [b] tampoco):

$\begin{array}{c|ccc}
\hline + & 0 & 1 & 2 \\
\hline 0 & 0 & 1 & 2 \\
1 & 1 & 2 & 0 \\
2 & 2 & 0 & 1
\end{array}$

## Caracteres

Find: \uppsi
Replace: \upsilon

## Paquete Physics
Pero en web no se puede usar eso así que estoy haciendo unas regex para transformar todos los latex del paquete a la libreria estandar:

### Ket:
Find: \\Ket\{(.+?)\}
Replace: \\mid$1\\rangle

## bra

### Braket

---

> NOTAS

---
# Notas para pasar de tex a md.

A la hora de pasar los apuntes a md hay dificultades.

Usamos la regex
```

```
para pasar de __ a ___



---

# Lista de cosas:

```
\newpage |-> --- \n\n New Page \n\n ---
```

```
\smallskip, \bigskip |-> ---
```

```
\\textbf\{Ejemplos:\} |-> **<span style="color:orange">Ejemplo:</span>**
```

```
\\textbf\{(.*)\} |-> **$1**
```

```
\mathds |-> \mathbb
```

Ojo al pasar esto porque mathbb no tiene fuentes para números. Para asegurarnos de que las identidades se ven bien además hay que hacer:

```
\mathbb{1} |-> \mathbb{I}
```

```
$\hspace{0.5cm}$ |-> >
```

Los brakets hay que pasarlos a mano:

Los bra:

```
\\bra\{(.+?)\}
```

a

```
\\langle $1 |
```

Y los ket:

```
\\ket\{(.+?)\}
```

a

```
| $1 \\rangle
```

Y luego hay que comprobar que no haya || repetidos.

Los entornos tabular no los pillan bien KaTeX o MathJax.
Podemos emularlo con un array:

```
$$
\begin{tabular}[b]{ c | c c c}

& e & a & $a^2$  \\
\hline
e & e & a & $a^2$ \\
a & a & $a^2$ & e  \\
$a^2$ & $a^2$ & e & a
\end{tabular}
$$
```

lo pasamos a

```
$$
\begin{array}{ c | c c c}
& e & a & a^2  \\
\hline
e & e & a & a^2 \\
a & a & a^2 & e  \\
a^2 & a^2 & e & a
\end{array}
$$
```

### Ecuaciones con $$

No me suele gustar que los $$ estén en la misma fila que el resto. las prefiero formateadas así:

```
$$
(M_{12},M_{23},M_{31})=(J_3,J_1,J_2)
$$
```

Es más fácil distinguirlas.

Para cambiarlas nos vale la regex:

```
\${2}((.+?\n?){1,})\${2}
```

a

```
$$$
$1
$$$
```

pero hay que tener cuidado de que no haya dos ecuaciones seguidas:

```
$$(M_{12},M_{23},M_{31})=(J_3,J_1,J_2)$$
$$(M_{01},M_{02},M_{03})=(K_1,K_2,K_3)$$
```

Habría que separarlas antes o la regex nos jugará una mala pasada.

---

# Para hacer los links a otros archivos

En el markdown hacemos un link a defs.html:

```
[**<span style="color:blue">Definición:</span> Acción de grupo.**](defs.html#definicion-de-accion)
```

Pero esto genera un texto normal, no se ve que es un enlace:

```
<a href="defs.html#definicion-de-accion"><strong><span style="color:blue">Definición:</span> Acción de grupo.</strong></a>
```

Sólo habría que añadir un breve estilo al anchor para que esté subrayado:

```
<a href="defs.html#definicion-de-accion" style="text-decoration:underline;"><strong><span style="color:blue">Definición:</span> Acción de grupo.</strong></a>
```

---
Para encontrarlas podemos usar:

```
\<span style\=\"color\:(.+?)\"\>(.*)\:<\/span\>(.*)
```

Donde se nos devuelve:

```
color: $1 tipo: $2 descri: $2
```

**Nota:** Coger el espacio en $2 es importante, por aquellas marcas sin descripción.

Así que queremos sustituirlo por:

```
**<span style="color:$1">$2:</span> $3**
```

Lo que nos interesa es hacer:

```
<details>
	<summary>
	</summary>
</details>


<details>
<summary>
</summary>
</details>
```

O sea:

```
<details>
	<summary>
	<strong>
	<span style="color:$1">$2:</span> $3
	</strong>
	</summary>
	Y aquí dentro irá lo de dentro.
</details>
```

**Nota:** Los dobles asteriscos no funcionan dentro del summary.

---
Me queda encontrar una forma de matchear de un marcador al siguiente para no tener que mover el details de arriba abajo.

Tal vez añadiendo una marca especial antes de las marcas y los títulos...

---
También habría que mirar si se puede hacer de alguna forma un botón de collapse/expande all o si tendré que buscar cómo hacerlo con javascript.

Seguro que coon javascript es más fácil a la larga. Tendría que añadir ids a cada span, o mejor a los strong? Si quiero que alguno sea título tendría que llevar el id...
