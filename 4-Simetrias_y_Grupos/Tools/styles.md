
---
# Styles

Notas sobre los estilos de las marcas usadas.

[TOC]

---
## Marcas Renderizadas

**<span style="color:blue">Definición:</span>**

**<span style="color:purple">Propiedades:</span>**

**<span style="color:lime">Proposiciones:</span>**

**<span style="color:green">Teorema:</span>**

**<span style="color:olive">Demostración:</span>**

**<span style="color:hotpink">Corolario:</span>**

**<span style="color:gold">Relaciones</span>**

**<span style="color:saddlebrown">Observaciones:</span>**

**<span style="color:sandybrown">Nota:</span>**

**<span style="color:red">Ejercicio:</span>**

**<span style="color:violet">Ejemplo:</span>**

**<span style="color:cyan">Pista:</span>**

**<span style="color:darkcyan">Solución:</span>**

**<span style="color:gold">Resumen:</span>**

**<span style="color:darkred">¡Ojo! (Trampa):</span>**

#### <span style="color:red">Ejercicio:</span>

##### <span style="color:darkcyan">Solución:</span>

---
## Marcas sin renderizar

```
**<span style="color:blue">Definición:</span>**

**<span style="color:green">Teorema:</span>**

**<span style="color:lime">Proposiciones:</span>**

**<span style="color:olive">Demostración:</span>**

**<span style="color:purple">Propiedades:</span>**

**<span style="color:hotpink">Corolario:</span>**

**<span style="color:violet">Observaciones:</span>**

**<span style="color:red">Ejercicio:</span>**

**<span style="color:orange">Ejemplo:</span>**

**<span style="color:cyan">Pista:</span>**

**<span style="color:darkcyan">Solución:</span>**

**<span style="color:gold">Resumen:</span>**

**<span style="color:darkred">¡Ojo! (Trampa):</span>**

#### <span style="color:red">Ejercicio:</span>

##### <span style="color:darkcyan">Solución:</span>
```

---
## Snippets de Atom para generarlos automáticamente

```
Falta añadir los del Mac


'.md':
    'Ejercicio':
        'prefix': 'eje'
        'body': '**<span style="color:red">Ejercicio:</span> $1**'
    'Solucion':
        'prefix': 'sol'
        'body': '**<span style="color:darkcyan">Solución:</span> $1**'
    'Titulo Ejercicio':
        'prefix': 'teje'
        'body': '### <span style="color:red">Ejercicio:</span> $1'
    'Titulo Solucion':
        'prefix': 'tsol'
        'body': '#### <span style="color:darkcyan">Solución:</span> $1'
```

---
# Marcas

La idea es que estas marcas aparezcan en una barra lateral (a la izquierda o a la derecha), separadas del texto principal.
