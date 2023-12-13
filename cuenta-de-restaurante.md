# 🍕 Cuenta de restaurante

Para resolver el problema "Cuenta de restaurante" debemos calcular el monto total a pagar de una cuenta de restaurante, incluyendo un impuesto del 10%. Para ello, podemos utilizar la fórmula siguiente:

* Calcular el impuesto: Multiplicamos el monto de la cuenta por 0.1 para obtener el valor del impuesto a pagar.
* Calcular el total: Sumamos el valor del impuesto al monto de la cuenta para obtener el monto total a pagar.
* Dividir el total entre el número de personas: En este caso, se especifica que el monto total se dividirá entre 5 personas. Por lo tanto, dividimos el monto total entre 5 para obtener el monto que cada persona debe pagar.

Para implementar esto en JavaScript, podemos crear una función llamada "restaurantBill" que tome como argumento el monto de la cuenta y devuelva el monto que cada persona debe pagar.

***

## Podemos entender más a detalle con este ejemplo:

<mark style="background-color:orange;">**Recuerda que esto no es una guía para resolver los retos, sino un ejemplo para comprenderlos mejor.**</mark>

Imagina que tienes un grupo de 5 amigas que salen a comer juntas. La cuenta total del consumo es de 100 dólares, pero necesitas agregarle el 15% de impuesto. Quieren dividir la cuenta equitativamente entre las cinco. Para resolver esto, vamos a crear un programa simple en JavaScript.

El ejercicio incluirá una función llamada "calculateBill" que tomará el monto de la cuenta antes de impuestos como argumento y calculará cuánto le toca pagar a cada persona, incluyendo el impuesto, y retornará un string con el monto que le corresponde pagar a cada una.

<pre class="language-javascript"><code class="lang-javascript"><strong>const calculateBill = (bill) => {
</strong>  const tax = /* Tu código aquí */;

  /* Tu código aquí */

  return /* Tu código aquí */;
};
</code></pre>

Asigna el resultado de multiplicar bill por 15% (en decimal, 0.15) a la variable "tax" (impuesto en inglés). Crea una variable llamada "total" y asígnale el resultado de sumar bill más tax. Retorna el monto que cada una debe pagar (total dividido entre 5), con el símbolo $ adelante (por ejemplo: $23).

La solución al ejercicio sería la siguiente:

```javascript
const calculateBill = (bill) => {
  const tax = bill * 0.15;
  const total = bill + tax;
  return `$${total / 5}`;
};

module.exports = calculateBill;
```

{% hint style="info" %}
Presta atención al ejemplo, ¡puedes encontrar la respuesta!
{% endhint %}
