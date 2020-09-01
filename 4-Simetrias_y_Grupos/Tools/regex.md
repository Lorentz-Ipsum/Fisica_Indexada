

### Find SPAN hasta ---

Para copiar y pegar rápidamente todas las instancias de ejercicio en un texto podemos usar:

```regex
### \<span style\=\"color\:red\"\>(.*)\<\/span\>(.*)(.*|\r?\n)*?\-{3}
```

La parte importante es ```(.|\r?\n)*?\-{3}```
Hace match a todas las lineas hasta que encuentra tres guiones[^multiline].
[^multiline]: [Multiline Search and replace in Atom Editor](https://stackoverflow.com/questions/41497325/multiline-search-and-replace-in-atom-editor)

Una vez encontrado el texto, en atom usamos ```alt+Enter``` para seleccionarlo, y de ahí copiarlo o lo que queramos.

Sirve también para soluciones, etc. Sé imaginativo.

#### Ejemplo 1

Sustituir la notación vieja con negrita

```
\*\*\<span style\=\"color\:red\"\>(.*)\<\/span\>(.*)\*\*((.*|\r?\n)*?)\-{3}
```

Por la notación nueva con h3

```
### <span style="color:red">Ej (S)</span>$2\$3---
```

#### Ejemplo 2

Si no hay separadores dentro de las soluciones, puedo añadir el details automáticamente:

```
\*\*\<span style\=\"color\:darkcyan\"\>(.*)\<\/span\>(.*)\*\*((.*|\r\n)*?)\r\n-{3}
```

Por la notación nueva con details y summary

```
<details><summary>
<span style="color:darkcyan">Solución</span>
</summary>$3</details>

---
```

#### Ejemplo 3

Para encontrar dicho details

```
\<details\>\<summary\>\r\n
\<span style\=\"color\:darkcyan\"\>(.*)\<\/span\>\r\n
\<\/summary\>((.*|\r\n)*?)\<\/details\>\r\n
\r\n\-{3}
```

Aunque ya no haría falta capturar los tres guiones del final.
Puesto en una línea sería:

```
\<details\>\<summary\>\r\n\<span style\=\"color\:darkcyan\"\>(.*)\<\/span\>\r\n\<\/summary\>((.*|\r\n)*?)\<\/details\>
```
