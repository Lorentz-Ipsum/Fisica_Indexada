# Apuntes de Miguel
## 0. Introducción y Redes
### 0.0. Historia
- Las bases
    - Ley de Ohm
    - Efecto Hall
    - Ley de Wiedemann-Franz
- Modelo de Drude
- Conductividad de un metal
- Conductividad térmica
- Historia y materiales
- Ruptura espontánea de simetría

### 0.1. Redes cristalinas
- Celda primitiva
- Redes en 3D
- Red recíproca
    - Ejemplos de redes recíprocas
- Planos cristalinos
    - Índices de Miller
- Simetrías en cristales (Este punto en realidad aparece al final del apartado 0.2.)
  - Grupos puntuales
  - Grupos espaciales
  - Ejemplo: Operaciones de simetría en la red HCP

### 0.2. Difracción de rayos X por cristales
- Scattering
    - Condición de Laue
    - Ley de Bragg
    - Esfera de Ewald
    - Amplitud total
- Base compleja
    - Ejemplo: Factor de estructura de una red BCC

### 0.3. Enlaces cristalinos: Interacción entre sitios de la red
- Tipos de enlaces
    - Covalente
        - Varios electrones
        - Enlace de diamante
    - Enlace iónico
        - Orbitales
        - Energía de cohesión
        - Repulsión de corto alcance
        - Constante de Madelung
        - Distancia de equilibrio
    - Enlace de Van der Waals
        - Polarizabilidad
    - Enlace metálico

---
👅
---
---

## 1. Electrones de la red en sólidos
### 1.0. Lo básico
- Aproximaciones
    - Aproximación adiabática o de Born-Oppenheimer
    - Aproximación de campo medio (mean field)
- Electrones
    - Teorema de Bloch
    - Ondas de electrones libres
    - Velocidad del electrón
    - Relación entre momento, velocidad y derivada de la energía
- Electrones libres
    - Volumen que ocupa cada estado k
    - Densidad electrónica
    - Energía interna a temperatura 0K
    - Densidad de estados
    - Densidad de electrones en función de la densidad de estados de Fermi
    - Energía interna de un gas de electrones a T=0K
    - Distribución de Fermi-Dirac
    - Número de electrones efectivo
- Apantallamiento, transición de Mott
    - Apantallamiento
    - Aislante de Mott

### 1.1. Nearly Free Electrons (NFE)
- Desarrollo matemático
- PZB en 2D

### 1.2. Tight Binding Electrons (TBE)
- Desarrollo matemático
    - Ondas de Bloch
    - Método variacional
- Ejemplo para SC
- Bandas

---
👅
---
---

## 2. Vibraciones de la red
### 2.0. Interacción entre iones
- Potencial de interacción de los iones con sus vecinos
- Constante recuperadora de la red
- Aparecen nuevas direcciones de difracción

### 2.1. Cadena 1D
- Ecuación de movimiento
    - Tres maneras de proceder
        - Excitación en muelles
        - Red de diferencias finitas
        - Teorema de Bloch
        - CC periodicas
    - Relación de dispersión
    - Velodicad del sonido
- Cristal 1D en base doble
    - Modos ópticos y acústicos
- Sólido en 3D
    - Segunda cuantización (Apéndice 1 (¿ó L?) del Ashcroft)
    - Colección de OA cuánticos independientes
        - Superposición de hamiltonianos
        - Modos normales
        - Temperaturas altas
          - Ley de Dulong-Petit
        - Temperaturas bajas
    - Densidad de estados
- Relación de dispersión de fonones para un cristal FCC
- Debye
    - Temperatura de Debye
    - Contribuciones al calor específico de la red y de los electrones
- Einstein

### 2.2. Scattering inelástico de rayos X
- Desarrollo matemático
- Experimento de dispersión de neutrones
- Con electrones

---
👅
---
---

## 3. Teoría semiclásica del transporte (electrónico)
### 3.0. Modelo de Drude
- Paquetes de anchura Dk
- Tensor de masa efectiva
- Banda con 1 hueco
- Proceso de segundo órden: Scattering
    - Aproximación a segundo órden
    - Fuerza recuperadora
- Velocidad de relajación

### 3.1. Interacción de los cristales con un campo magnético
- Medir experimentalmente la superficie de Fermi
- Discretización de los niveles
    - Niveles de Landau



--------------------------------------------------------------------
👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅👅
--------------------------------------------------------------------
--------------------------------------------------------------------

# Apuntes / Diapositivas de clase

## 4. Fonones / Vibraciones de la red


## 5. Magnetismo
### 5.0. Introducción
- Teoría clásica
  - Momento angular Orbital
    - Magnetón de Bohr
  - Momento angular de espín
  - Factor giromagnético orbital y de espín
  - Momento magnético total de un electrón
- Principio de Aufbau de llenado de capas electrónicas
  - Aumenta $n+l$
- Reglas de Hund (Esquema de acoplo de Russel-Saunders)
  - 1. Maximizar S cumpliendo Ppio exclusion Pauli
  - 2. Los estados de mayor $m_L$ se llenan antes
  - 3. Si la capa está menos de medio llena: $J=L-S$. Si está más de medio llena: $J= L+S$
  - Momento magnético atómico: Acoplo espín-orbita
- Multiplete: Ground state
  - Ejemplos
- Momento magnético total
  - Factor de Landé
- Función de onda de los electrones: ¿Por qué se alinean los momentos?
  - Fdo antisimétrica + Pauli

### 5.1. Ferro y antiferromagnetismo
- ¿Cómo interactuan los momentos magnéticos d los electrones?
  - Promedio térmico de la magnetización
  - Susceptibilidad magnética
  - Clasificación de sólidos
    - Paramagnetismo: $\chi> 0$. El campo induce momentos en su dirección.
    - Diamagnetismo: $\chi<0$. El campo induce momentos en dirección opuesta.
    - Ferromagnetismo: Es como si ya hubiera un campo efectivo.
  - Hamiltoniano
    - Término paramagnético
      - Expansión a baja temperatur
      - En función de $J$
    - Término diamagnético
      - Diamagnetismo de Larmor
      - Propiedades del diamagnetismo de Langevin
      - Ejemplos de diamagnetismo
      - Fórmula de Langevin
    - Resumen de términos de H
- Sólidos diamagnéticos
  - Susceptibilidad de Larmor
- Paramagnetismo de Pauli en metales

### 5.2. Magnetismo de momentos que interaccionan
- Interacción dipolar
- Interacción de canje
  - Hamiltoniano de Heisenberg
  - Signo interacción de canje determina ferro (J>0) o antiferro (J<0).
- Revisión del Tight Binding
  - Combinación lineal de orbitales atómicos
  - Teoría de perturbaciones
  - Aproximación de Hückel
  - Calculando autovaloires
  - Términos integrales, etc.
  - Aproximación de electrones independientes
  - Aproximación de Heitler-London
  - Expresión para la escala de energía de la interacción de intercambio
- Dos Electrones
  - Interacción de canje
  - Hamiltoniano de Heisenberg
- En Sólidos
  - Hamiltoniano de Heisenberg (de espín)
  - Interacción entre vecinos
  - Problema de Hubbard
  - Bether-Slater Curve
- Teoría de campo mediod el ferromagnetismo: Ferromagnetismo de Weiss
  - Campo molecular de Weiss
  - Hamiltoniano de Hubbard
- Magnetización espontánea (Paramagnetismo)
  - Temperatura crítica
  - Respuesta paramagnética
    - Ley de Curie-Weiss
  - Comportamiento de para, ferro, y antiferro cerca de la temperatura crítica
  - Ferromagnetismo de Stoner
    - Desdoblamiento de las bandas por el campo molecular
    - Criterio de Stoner para el campo molecular
    - [FALTAN COSAS]

### 5.3. Ondas de espín
-  Precesión de un campo magnético en un campo magnético
  - Precesión de Larmor
  - Campo molecular
  - Relación de dispersión
  - Momento angular de espín y matrices de Pauli
  - Actuación del hamiltoniano de Heisenberg
  - Voltear un espín
  - Número de magnones
  - Ley de 3/2 de Bloch
  - Anisotropía
  -

## 6. Superconductividad
