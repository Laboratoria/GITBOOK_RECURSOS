---
description: 'Podemos entender más a detalle con este ejemplo:'
---

# Ejemplo

#### <mark style="background-color:orange;">Recuerda que esto no es una guía para resolver los retos, sino un ejemplo para comprenderlos mejor.</mark>

_Imagina que has sido encomendado con la tarea de desentrañar el misterio detrás de la popularidad de los restaurantes y contribuir a que **FoodFusion** tome decisiones sólidas para su crecimiento. Acompáñame a través de este proceso guiado, donde exploraremos paso a paso cómo organizar restaurantes en categorías de acuerdo a su popularidad, tomando en cuenta la puntuación de las reseñas y la variedad en sus menús._

* Nuestro propósito es segmentar los restaurantes en grupos basados en su nivel de popularidad, considerando tanto la puntuación de las reseñas como la diversidad en su oferta de menú.
* Identificaremos un enfoque simple pero efectivo para categorizar los restaurantes. Combinaremos la puntuación promedio de las reseñas con la cantidad de platos en sus menús, creando así una métrica de valoración.
* Nos sumergiremos en el mundo de las fórmulas, las cuales utilizaremos con precisión para clasificar los restaurantes. De manera similar a resolver un enigma, emplearemos fórmulas prácticas para determinar si un restaurante es "Muy Popular" o "Moderadamente Popular".
* Al igual que detectives minuciosos, someteremos nuestras etiquetas a pruebas con ejemplos concretos. Esta etapa es crucial para garantizar la precisión y confiabilidad de nuestras categorías.

#### Las fórmulas que utilizaremos son:

1.  **Promedio de Popularidad**: Utilizaremos esta fórmula en una celda para calcular el promedio ponderado de la puntuación de reseñas y la cantidad de platos en los menús:

    ```excel-formula
    (Puntuación Promedio + Cantidad de Platos) / 2
    ```
2.  **Etiquetando con Fórmula IF**: Supongamos que el resultado del promedio de puntuaciones se encuentra en la celda `B2`. En este caso, la fórmula `IF` podría ser la siguiente:

    ```excel-formula
    =SI(B2 > 7.5, "Muy Popular", "Moderadamente Popular")
    ```

    Esta fórmula etiquetará un restaurante como "Muy Popular" si el promedio de puntuaciones es mayor a 7.5; de lo contrario, lo etiquetará como "Moderadamente Popular".
3.  **Buscando con VLOOKUP**: Imaginemos que el valor en la celda `B2` es 9, y tenemos una tabla de categorías en el rango `A10:B12`. La fórmula `VLOOKUP` sería:

    <pre class="language-excel-formula"><code class="lang-excel-formula"><strong>=BUSCARV(B2, A10:B12, 2, 0)
    </strong></code></pre>

    Esta fórmula buscará el valor en `B2` en la primera columna de la tabla `A10:B12` y devolverá el valor correspondiente de la segunda columna si encuentra una coincidencia. En este caso, estamos buscando la categoría de popularidad en la tabla.

A través de pasos metódicos y fórmulas efectivas, estableceremos un sistema de etiquetado que clasificará los restaurantes de manera precisa y sólida.
