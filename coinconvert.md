# 🍿 Cinemaster

En esta tarea de análisis estratégico para CineMaster, enfrentaremos la labor de procesar datos financieros y categorizar países según sus costos de contenido. El objetivo es proporcionar orientación estratégica basada en el costo de contenido por cada 1000 películas y series.

Para abordar esta tarea de manera efectiva, seguiremos estos pasos:

1. El propósito es categorizar países en función de sus costos de contenido, lo cual ayudará a CineMaster a determinar su enfoque en el mercado.
2. Utilizaremos el costo por cada 1000 películas como una métrica estandarizada para comparar costos de contenido entre países.
3. Desarrollaremos una función que emplee fórmulas como VLOOKUP (BUSCARV) y IF (SI) para unir datos de precios y tamaños de catálogos, y así categorizar países como "bajo costo" o "alto costo" basados en el costo por cada 1000 películas.
4. Es crucial probar la función con ejemplos de datos para asegurarnos de que esté proporcionando las categorías correctas.

En el contexto de CineMaster, este análisis estratégico ayudará a definir las decisiones de entrada al mercado. La categorización de países según sus costos de contenido permitirá a CineMaster:

* La clasificación en "bajo costo" podría guiar a CineMaster hacia estrategias específicas para aprovechar estos mercados.
* Los mercados clasificados como "alto costo" podrían inspirar estrategias que involucren contenido exclusivo o colaboraciones locales.

***

## Podemos entender más a detalle con este ejemplo:

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
