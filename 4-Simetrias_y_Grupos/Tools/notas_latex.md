
---
# Notas de LaTeX


## Snippets de Atom para agilizar la toma de notas.

```
'.md':
    # Snippets de LaTeX
    'Grupo Lorentz ortocrono propio':
        'prefix': 'Lmas'
        'body': '\\\\mathcal{L}^{\\\\uparrow}_+'
        # Nota, en la notación CSON de atom hacen falta 4 \ para que salga uno solo
```

### Los snippets generan...

$\mathcal{L}^{\uparrow}_+$

### Generación de teoremas con nombre en LaTeX

Esto es sólo un comienzo, generando más comandos de esta forma se podrían generar las marcas de def, teo, etc en LaTeX:

```
\newtheorem*{theorem}{Teorema}
\newtheoremstyle{named}{}{}{\itshape}{}{\bfseries}{.}{.5em}{#1\thmnote{ #3}}
\theoremstyle{named}
\newtheorem*{namedtheorem}{Teorema}
```

Con esto, en el texto ponemos:

```
\begin{namedtheorem}[del límite central]
    Blabalblalbal
\end{namedtheorem}
```

Y todo sale bien.
