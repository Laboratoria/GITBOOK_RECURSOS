# 🪙 CoinConvert

El problema de CoinConvert es que nos pide convertir una cantidad de dólares a las monedas de tres países diferentes: Perú (Soles), México (Pesos Mexicanos) y Chile (Pesos Chilenos). Para resolver este problema, podemos seguir los siguientes pasos:

1. Entender el enunciado del problema y definir el objetivo: el objetivo es convertir una cantidad de dólares a las monedas de Perú, México y Chile.
2. Identificar la tasa de conversión: en el enunciado del problema se nos da la tasa de conversión para cada una de las monedas. Por ejemplo, para convertir dólares a soles, se nos dice que 1 dólar equivale a 3.25 soles.
3. Crear una función que reciba una cantidad de dólares como parámetro y retorne un arreglo con las conversiones a las tres monedas. Podemos crear variables que almacenen las conversiones para cada una de las monedas y luego retornar un arreglo con estas variables.
4. Verificar que la función está dando los resultados correctos para algunos casos de prueba.

Para resolver este problema en JavaScript, podemos crear una función llamada coinConvert que reciba como parámetro una cantidad de dólares y retorne un arreglo con las conversiones a soles, pesos mexicanos y pesos chilenos. Podemos utilizar las tasas de conversión proporcionadas en el enunciado del problema para realizar las conversiones.

```
1 dólar = 3.25 soles peruanos
1 dólar = 18 pesos mexicanos
1 dólar = 660 pesos chilenos
```

***

<mark style="background-color:orange;">**Recuerda que esto no es una guía para resolver los retos, sino un ejemplo para comprenderlos mejor.**</mark>

Para comprender mejor este concepto, consideremos el siguiente ejemplo: Imagina que te piden escribir una función que convierta una temperatura de grados Celsius a grados Fahrenheit. La función tempConvert realiza esta conversión y retorna un arreglo con las temperaturas en grados Fahrenheit y Kelvin.

```javascript
const tempConvert = (celsius) => {
  const fahrenheit = celsius * 1.8 + 32;
  const kelvin = celsius + 273.15;
  return [fahrenheit, kelvin];
};

console.log(tempConvert(25)); // [77, 298.15]
```

En este caso, al llamar a la función tempConvert con un valor de 25 para el parámetro celsius, se imprime en la consola el arreglo \[77, 298.15], que representa la temperatura de 25 grados Celsius en grados Fahrenheit y Kelvin, respectivamente.

Espero que esta versión sea de tu agrado. Si necesitas más cambios o alguna otra ayuda, no dudes en pedirlo.
