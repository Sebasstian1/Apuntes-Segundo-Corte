# Introducción a la Dinámica de Sistemas

Este repositorio contiene una introducción a conceptos fundamentales de la Dinámica de Sistemas, útiles para modelar y analizar sistemas físicos en movimiento y sus energías asociadas. 

## Tabla de Contenidos
- [Energía Cinética](#energía-cinética)
- [Energía Potencial en un Resorte](#energía-potencial-en-un-resorte)
- [Potencia](#potencia)
- [Potencia en un Resorte](#potencia-en-un-resorte)
- [Potencia en una Masa](#potencia-en-una-masa)
- [Energía Disipada](#energía-disipada)
- [Potencia Disipada en un Amortiguador](#potencia-disipada-en-un-amortiguador)
- [Sistema Conservativo](#sistema-conservativo)

---

## Energía Cinética

La **energía cinética** (KE) es la energía que posee un cuerpo debido a su movimiento. Se calcula como:

\[
KE = \frac{1}{2}mv^2
\]

donde:
- \( m \) es la masa del cuerpo,
- \( v \) es la velocidad del cuerpo.

## Energía Potencial en un Resorte

La **energía potencial** almacenada en un resorte comprimido o estirado se describe por la Ley de Hooke. Su expresión es:

\[
PE = \frac{1}{2}kx^2
\]

donde:
- \( k \) es la constante de rigidez del resorte,
- \( x \) es la deformación (alargamiento o compresión) respecto a la posición de equilibrio.

## Potencia

La **potencia** es la rapidez con la que se realiza un trabajo o se transfiere energía. Se define como:

\[
P = \frac{dW}{dt} = F \cdot v
\]

donde:
- \( dW \) es el trabajo realizado,
- \( dt \) es el tiempo,
- \( F \) es la fuerza aplicada,
- \( v \) es la velocidad en la dirección de la fuerza.

## Potencia en un Resorte

La potencia en un resorte en movimiento se obtiene derivando la energía potencial respecto al tiempo:

\[
P_{\text{resorte}} = \frac{d}{dt} \left(\frac{1}{2}kx^2\right) = kx \cdot \frac{dx}{dt} = kx \cdot v
\]

donde \( v = \frac{dx}{dt} \) es la velocidad de deformación del resorte.

## Potencia en una Masa

Para una masa en movimiento bajo una fuerza, la potencia se calcula como:

\[
P_{\text{masa}} = F \cdot v = m \cdot a \cdot v
\]

donde:
- \( m \) es la masa,
- \( a \) es la aceleración,
- \( v \) es la velocidad.

## Energía Disipada

La **energía disipada** en un sistema es la energía perdida, usualmente como calor, debido a fuerzas de fricción o resistencia. Esta energía depende del amortiguamiento y se modela como:

\[
E_{\text{disipada}} = c \cdot x \cdot v
\]

donde:
- \( c \) es el coeficiente de amortiguamiento,
- \( x \) es la posición,
- \( v \) es la velocidad.

## Potencia Disipada en un Amortiguador

La **potencia disipada** en un amortiguador, que depende de la velocidad relativa y el coeficiente de amortiguación, se calcula como:

\[
P_{\text{amortiguador}} = c \cdot v^2
\]

donde:
- \( c \) es el coeficiente de amortiguamiento,
- \( v \) es la velocidad relativa.

## Sistema Conservativo

Un **sistema conservativo** es aquel en el cual la energía mecánica total (la suma de la energía cinética y la energía potencial) se conserva. En estos sistemas, no hay pérdida de energía debido a factores externos como la fricción, por lo que la energía se transfiere únicamente entre sus formas potencial y cinética:

\[
E_{\text{total}} = KE + PE = \text{constante}
\]

---

Este resumen proporciona una base para entender cómo se comportan sistemas físicos con movimiento, incluyendo los conceptos de energía, potencia y disipación. Cada uno de estos conceptos es crucial para analizar la dinámica de sistemas conservativos y no conservativos.

