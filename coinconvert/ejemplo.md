---
description: 'Podemos entender más a detalle con este ejemplo:'
---

# Ejemplo

#### <mark style="background-color:orange;">Recuerda que esto no es una guía para resolver los retos, sino un ejemplo para comprenderlos mejor.</mark>

_Imagina que te piden escribir una función que convierta una temperatura de grados Celsius a grados Fahrenheit._

1. Lo primero que debes hacer es entender la fórmula matemática para convertir Celsius a Fahrenheit:

$$°F = °C * 1.8 + 32$$

2. Se define la función `tempConvert` con un parámetro `celsius`.

```javascript
const tempConvert = (celsius) => {
```

3. Dentro de la función se calcula la temperatura en grados Fahrenheit utilizando la fórmula `F = (C * 1.8) + 32` y se guarda en la variable `fahrenheit`.

```javascript
const fahrenheit = celsius * 1.8 + 32;
```

4. Se calcula la temperatura en grados Kelvin utilizando la fórmula `K = C + 273.15` y se guarda en la variable `kelvin`.

```javascript
const kelvin = celsius + 273.15;
```

5. Se retorna un arreglo con las temperaturas en grados Fahrenheit y Kelvin.

```javascript
return [fahrenheit, kelvin];
```

6. Se llama a la función `tempConvert` con un valor de 25 para el parámetro `celsius` y se imprime en la consola el arreglo de temperaturas en grados Fahrenheit y Kelvin.

```javascript
console.log(tempConvert(25)); // [77, 298.15]
```

Así la función `tempConvert` toma una temperatura en grados Celsius como parámetro, la convierte a grados Fahrenheit y Kelvin, y retorna un arreglo con las dos conversiones. En la llamada a la función con un valor de 25, se imprime en la consola el arreglo `[77, 298.15]`, que representa la temperatura de 25 grados Celsius en grados Fahrenheit y Kelvin, respectivamente.
