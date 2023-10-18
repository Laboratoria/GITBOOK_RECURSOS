---
description: 'Podemos entender más a detalle con este ejemplo:'
---

# Ejemplo

#### <mark style="background-color:orange;">Recuerda que esto no es una guía para resolver los retos, sino un ejemplo para comprenderlos mejor.</mark>

S_upongamos que se nos pide escribir una función que calcule el total a pagar por una compra en una tienda. La tienda tiene un impuesto del 12%, y se quiere agregar una propina del 18%. La función debe recibir el monto de la compra y devolver el total a pagar, incluyendo impuesto y propina, dividido en partes iguales entre 5 personas._

1. Primero, tenemos que definir una función que reciba el monto de la compra como argumento:

```javascript
const calculateTotal = (purchaseAmount) => {
  // Código aquí
};
```

2. Ahora, tenemos que calcular el impuesto, que es del 12% del monto de la compra. Para ello, multiplicamos el monto de la compra por 0.12:

```javascript
const tax = purchaseAmount * 0.12;
```

3. Luego, calculamos la propina, que es del 18% del monto de la compra. Para ello, multiplicamos el monto de la compra por 0.18:

```javascript
const tip = purchaseAmount * 0.18;
```

4. Ahora, podemos calcular el total a pagar, sumando el monto de la compra, el impuesto y la propina:

```javascript
const total = purchaseAmount + tax + tip;
```

5. Finalmente, podemos calcular el total a pagar por persona, dividiendo el total entre 5 (ya que se quiere dividir en partes iguales entre 5 personas):

```javascript
const totalPerPerson = total / 5;
```

6. Para mostrar el resultado en formato de dinero, podemos agregar el símbolo de dólar y devolver el resultado como un string:

```javascript
return `$${totalPerPerson}`;
```

7. Probamos la función llamándola con un ejemplo de compra de $50 y lo imprimimos en la consola:

<pre class="language-javascript"><code class="lang-javascript"><strong>console.log(calculateTotal(50)); // "$15"
</strong></code></pre>

¡Y eso es todo! Con estos pasos hemos resuelto el problema de calcular el total a pagar por una compra en una tienda, incluyendo impuesto y propina, dividido en partes iguales entre 5 personas.
