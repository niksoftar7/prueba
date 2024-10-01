
-----------------------------------------------------------------------
# Diseño de Rejillas Parabólicas para la Reducción de Ruido en Aulas Universitarias

## Índice

1. [Introducción](#introducción)
2. [Planteamiento del Problema](#planteamiento-del-problema)
3. [Objetivos](#objetivos)
4. [Fundamentos Teóricos](#fundamentos-teóricos)
   - 4.1. [Propagación del Sonido](#propagación-del-sonido)
   - 4.2. [Frecuencia y Longitud de Onda](#frecuencia-y-longitud-de-onda)
   - 4.3. [Reflexión del Sonido en Superficies Curvas](#reflexión-del-sonido-en-superficies-curvas)
   - 4.4. [Parábolas y sus Propiedades](#parábolas-y-sus-propiedades)
5. [Datos Iniciales](#datos-iniciales)
6. [Desarrollo del Proyecto](#desarrollo-del-proyecto)
   - 6.1. [Análisis de la Frecuencia del Sonido](#análisis-de-la-frecuencia-del-sonido)
   - 6.2. [Diseño de la Parábola](#diseño-de-la-parábola)
   - 6.3. [Cálculos y Ecuaciones Necesarias](#cálculos-y-ecuaciones-necesarias)
   - 6.4. [Aplicación al Diseño de las Rejillas](#aplicación-al-diseño-de-las-rejillas)
7. [Resultados Esperados](#resultados-esperados)
8. [Conclusiones](#conclusiones)
9. [Referencias](#referencias)

---

## Introducción

En el edificio de ingeniería de nuestra universidad, se ha identificado un problema recurrente: el ruido proveniente de los pasillos interfiere con las actividades académicas dentro de las aulas. Esto se debe a la estructura actual de las rejillas en las ventanas, que permiten el paso directo del sonido. Este proyecto propone una solución basada en el rediseño de las rejillas utilizando cónicas, específicamente parábolas, para reducir la transmisión de sonido al interior sin alterar la estética del edificio.

## Planteamiento del Problema

Las rejillas actuales de las ventanas son rectas y permiten que el sonido del pasillo penetre en las aulas, dificultando la concentración y el desarrollo de las clases. Se busca una solución que:

- Reduzca la transmisión de sonido desde el pasillo hacia las aulas.
- Mantenga la estética y dimensiones originales de las rejillas.
- Sea viable desde un punto de vista constructivo y económico.

## Objetivos

- **Objetivo General**: Diseñar un modelo de rejilla parabólica que disminuya la transmisión de sonido al interior de las aulas.
- **Objetivos Específicos**:
  - Analizar las propiedades acústicas de las parábolas.
  - Calcular y definir la ecuación parabólica adecuada para las rejillas, considerando los datos físicos disponibles.
  - Integrar el diseño en las dimensiones actuales de las rejillas para mantener la estética del edificio.

## Fundamentos Teóricos

### Propagación del Sonido

El sonido es una onda mecánica longitudinal que se propaga a través de un medio elástico, como el aire. Las ondas sonoras pueden ser reflejadas, absorbidas o transmitidas al encontrarse con una superficie.

### Frecuencia y Longitud de Onda

La **frecuencia** (\(f\)) del sonido es el número de oscilaciones por segundo y se mide en hercios (Hz). La **longitud de onda** (\(\lambda\)) es la distancia que recorre la onda en un ciclo completo y está relacionada con la frecuencia y la velocidad del sonido (\(v\)) por la ecuación:
![image](https://github.com/user-attachments/assets/9f4f01d7-5de2-493d-8cab-57f16944be12)

Donde:

- \(v\) es la velocidad del sonido en el aire (aproximadamente 343 m/s a 20°C).
- \(f\) es la frecuencia del sonido en Hz.

### Reflexión del Sonido en Superficies Curvas

Las superficies curvas, como las parábolas, tienen propiedades reflectivas únicas. Una parábola puede redirigir las ondas sonoras que inciden en ella hacia direcciones específicas, dependiendo de la posición del foco y la forma de la parábola.

### Parábolas y sus Propiedades

Una **parábola** es una sección cónica que puede definirse como el conjunto de puntos equidistantes de un punto fijo (foco) y una línea fija (directriz). La ecuación estándar de una parábola con eje horizontal y vértice en el origen es:

![image](https://github.com/user-attachments/assets/2e50985d-a195-4996-ae40-9ae0f6c2a7f5)


Donde:

- \(p\) es la distancia desde el vértice al foco.
- \(x\) y \(y\) son las coordenadas en los ejes horizontal y vertical, respectivamente.

## Datos Iniciales

- **Ancho de cada rejilla (\(L\))**: 37 cm
- **Altura de cada rejilla (\(H\))**: 7 cm
- **Grosor del muro (\(G\))**: 5 cm
- **Cantidad de rejillas**: 36
- **Altura total de la ventana**: 2.92 m

## Desarrollo del Proyecto

### Análisis de la Frecuencia del Sonido

Para diseñar las rejillas de manera efectiva, es necesario considerar la frecuencia predominante del sonido en el pasillo.

- **Frecuencia promedio del habla humana**: entre 250 Hz y 4000 Hz.
- **Frecuencia seleccionada para el diseño**: 500 Hz (representativa del ruido general de conversaciones en el pasillo).

![image](https://github.com/user-attachments/assets/d16d3e65-e66c-497d-b290-5c51288f6f65)

### Diseño de la Parábola

Dado que el ancho de las rejillas es de 37 cm, que es menor que la longitud de onda de 68.6 cm, debemos optimizar la curvatura de la parábola para reflejar eficazmente las ondas sonoras.


![image](https://github.com/user-attachments/assets/7be282c2-f821-49de-ba58-c3cba2b51a1e)



   - Este valor de \( x \) es menor que el grosor del muro, por lo que \( p = 2.5 \, \text{cm} \) es adecuado cuando consideramos la altura de la rejilla.

### Aplicación al Diseño de las Rejillas

![image](https://github.com/user-attachments/assets/66e6ad30-4199-40d5-adbb-80263d16c0a5)

2. **Perfil de la Rejilla**:

   - La rejilla tendrá una curvatura parabólica definida por la ecuación anterior, con \( y \) variando desde \(-3.5 \, \text{cm}\) hasta \(3.5 \, \text{cm}\) (la mitad de la altura de la rejilla).

3. **Construcción Física**:

   - Las rejillas se fabricarán con esta forma parabólica, manteniendo el ancho y la altura originales, pero con una curvatura que permitirá reflejar y dispersar las ondas sonoras.

4. **Efecto en la Reflexión del Sonido**:

   - Las ondas sonoras que incidan en la rejilla serán reflejadas en diferentes direcciones, reduciendo la transmisión directa al interior del aula.

## Resultados Esperados

- **Reducción de la Transmisión de Sonido**: Se espera una disminución significativa en el nivel de ruido dentro del aula debido a la reflexión y dispersión de las ondas sonoras por las rejillas parabólicas.
- **Mantenimiento de la Estética**: Al conservar las dimensiones originales de las rejillas y utilizar una curvatura sutil, la apariencia del edificio no se verá afectada.
- **Viabilidad Constructiva**: El diseño propuesto es realizable con materiales y técnicas de fabricación estándar.

## Conclusiones

- La aplicación de principios matemáticos y físicos permite desarrollar soluciones prácticas a problemas cotidianos.
- El diseño de rejillas parabólicas basado en las propiedades reflectivas de las parábolas y considerando la frecuencia del sonido predominante puede reducir efectivamente la transmisión de ruido.
- Es fundamental ajustar los parámetros de la parábola para que sean compatibles con las dimensiones físicas y restricciones del entorno.
- Se recomienda la realización de prototipos y pruebas acústicas para validar el diseño y realizar ajustes si es necesario.

## Referencias

- Kinsler, L. E., Frey, A. R., Coppens, A. B., & Sanders, J. V. (2000). **Fundamentals of Acoustics**. Wiley.
- Stewart, J. (2015). **Cálculo Multivariable**. Cengage Learning.
- Beranek, L. L., & Vér, I. L. (1992). **Noise and Vibration Control Engineering**. Wiley.

---

![image](https://github.com/user-attachments/assets/3fc57cad-b7ad-43a6-aaf8-59422b60ef04)


---

**Notas Finales**

Este proyecto demuestra la importancia de integrar conocimientos de diferentes áreas (matemáticas, física y arquitectura) para resolver problemas prácticos. La consideración de la frecuencia del sonido y la aplicación de las propiedades de las parábolas permiten diseñar una solución efectiva y estéticamente coherente.
