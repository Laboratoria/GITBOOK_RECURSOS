---
description: 'Pode-se entender mais detalhadamente com este exemplo:'
---

# Exemplo

<mark style="background-color:orange;">**Lembre-se de que isso não é um guia para resolver desafios, mas sim um exemplo para compreendê-los melhor.**</mark>&#x20;

Imagine que você é solicitado a escrever uma função que converta uma temperatura de graus Celsius para graus Fahrenheit. O primeiro passo é entender a fórmula matemática para converter Celsius para Fahrenheit:

$$°F = °C * 1.8 + 32$$

Define-se a função `tempConvert` com um parâmetro celsius.&#x20;

```javascript
const tempConvert = (celsius) => {
```

Dentro da função, calcula-se a temperatura em graus Fahrenheit usando a fórmula F = (C \* 1.8) + 32 e armazena-se na variável fahrenheit.&#x20;

```javascript
const fahrenheit = celsius * 1.8 + 32;
```

Calcula-se a temperatura em graus Kelvin usando a fórmula K = C + 273.15 e armazena-se na variável kelvin.&#x20;

```javascript
const kelvin = celsius + 273.15;
```

Retorna-se um array com as temperaturas em graus Fahrenheit e Kelvin.&#x20;

```javascript
return [fahrenheit, kelvin]; 
```

Chama-se a função tempConvert com um valor de 25 para o parâmetro celsius e imprime-se no console o array de temperaturas em graus Fahrenheit e Kelvin.&#x20;

```javascript
console.log(tempConvert(25)); // [77, 298.15]
```

Assim, a função `tempConvert` recebe uma temperatura em graus Celsius como parâmetro, converte-a para graus Fahrenheit e Kelvin, e retorna um array com as duas conversões. Na chamada da função com um valor de 25, é impresso no console o array `[77, 298.15]`, que representa a temperatura de 25 graus Celsius em graus Fahrenheit e Kelvin, respectivamente."
