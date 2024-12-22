### (a) Obtención de la fórmula de la fuerza electromotriz inducida (f.e.m.) mediante la fuerza electromotriz de movimiento

Queremos derivar la expresión de la f.e.m. inducida en la espira utilizando la fórmula de la fuerza electromotriz de movimiento y considerando cada segmento de la espira.

#### Fórmula base:
La f.e.m. inducida se calcula mediante la integral:
\[ \varepsilon = \oint (\vec{v} \times \vec{B}) \cdot d\vec{l} \]
Donde:
- \( \vec{v} \): velocidad del elemento de cable diferencial.
- \( \vec{B} \): campo magnético uniforme.
- \( d\vec{l} \): elemento de longitud del cable.

#### Geometría de la espira:
- La espira es rectangular, con lados \(a\) y \(b\).
- Gira en un campo magnético uniforme \(\vec{B}\) alrededor del eje central.
- La velocidad del elemento diferencial está dada por:
  \[ \vec{v} = \omega r \hat{t} \]
  Donde \(\omega\) es la velocidad angular y \(r\) es la distancia al eje de rotación.

#### Contribución de cada segmento de la espira:
1. **Lados horizontales:**
   - La velocidad \(\vec{v}\) es perpendicular al campo magnético \(\vec{B}\).
   - La contribución neta de estos lados es cero porque el flujo generado por las corrientes inducidas se cancela debido a la simetría.

2. **Lados verticales:**
   - La velocidad de las cargas móviles varía linealmente con \(r\).
   - La contribución de los lados verticales no se cancela y será la principal fuente de la f.e.m.
   
La fuerza electromotriz inducida en cada lado vertical se calcula como:
\[ \Delta V = \int_{0}^{a} \vec{v} \cdot (\vec{B} \times \hat{l}) \, dr \]

#### Cálculo de la f.e.m. total:
Sumando las contribuciones de los dos lados verticales (que actúan como generadores de tensión en serie), obtenemos:
\[ \varepsilon = 2 \int_{0}^{a} \omega r B dr \]
Integrando:
\[ \varepsilon = \omega B a^2 \]

Finalmente, considerando la orientación y variación del flujo magnético a lo largo del tiempo:
\[ \varepsilon(t) = \omega B a b \sin(\omega t) \]

Esta es la expresión buscada para la f.e.m. inducida en la espira.

