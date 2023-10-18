---
description: 'Pode-se entender mais detalhadamente com este exemplo:'
---

# Exemplo

<mark style="background-color:orange;">**Lembrando que isso não é um guia para resolver desafios, mas um exemplo para compreendê-los melhor.**</mark>

Suponhamos que nos seja solicitado escrever uma função que calcule o total a pagar por uma compra em uma loja. A loja tem um imposto de 12% e deseja-se adicionar uma gorjeta de 18%. A função deve receber o valor da compra e retornar o total a ser pago, incluindo imposto e gorjeta, dividido igualmente entre 5 pessoas.

Primeiro, temos que definir uma função que receba o valor da compra como argumento:&#x20;

```javascript
const calcularTotal = (valorCompra) => { // Código aqui };
```

Agora, temos que calcular o imposto, que é 12% do valor da compra. Para isso, multiplicamos o valor da compra por 0.12:&#x20;

```javascript
const imposto = valorCompra * 0.12;
```

Em seguida, calculamos a gorjeta, que é 18% do valor da compra. Para isso, multiplicamos o valor da compra por 0.18:&#x20;

```javascript
const gorjeta = valorCompra * 0.18;
```

Agora, podemos calcular o total a ser pago, somando o valor da compra, o imposto e a gorjeta:&#x20;

```javascript
const total = valorCompra + imposto + gorjeta;
```

Por fim, podemos calcular o total a ser pago por pessoa, dividindo o total por 5 (pois queremos dividir igualmente entre 5 pessoas):

```javascript
const totalPorPessoa = total / 5;
```

Para exibir o resultado em formato de dinheiro, podemos adicionar o símbolo de dólar e retornar o resultado como uma string:

```javascript
return $${totalPorPessoa};
```

Testamos a função chamando-a com um exemplo de compra de $50 e imprimimos no console:

```javascript
console.log(calcularTotal(50)); // "$15"
```

E isso é tudo! Com esses passos, resolvemos o problema de calcular o total a ser pago por uma compra em uma loja, incluindo imposto e gorjeta, dividido igualmente entre 5 pessoas.
