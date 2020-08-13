

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
