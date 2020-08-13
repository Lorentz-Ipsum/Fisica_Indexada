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
