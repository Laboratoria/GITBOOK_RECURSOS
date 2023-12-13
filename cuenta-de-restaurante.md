# 🍕 Cuenta de restaurante

Para resolver el problema "Cuenta de restaurante" debemos calcular el monto total a pagar de una cuenta de restaurante, incluyendo un impuesto del 10%. Para ello, podemos utilizar la fórmula siguiente:

* Calcular el impuesto: Multiplicamos el monto de la cuenta por 0.1 para obtener el valor del impuesto a pagar.
* Calcular el total: Sumamos el valor del impuesto al monto de la cuenta para obtener el monto total a pagar.
* Dividir el total entre el número de personas: En este caso, se especifica que el monto total se dividirá entre 5 personas. Por lo tanto, dividimos el monto total entre 5 para obtener el monto que cada persona debe pagar.

Para implementar esto en JavaScript, podemos crear una función llamada "restaurantBill" que tome como argumento el monto de la cuenta y devuelva el monto que cada persona debe pagar.

***

<mark style="background-color:orange;">**Recuerda que esto no es una guía para resolver los retos, sino un ejemplo para comprenderlos mejor.**</mark>

Podemos entender más a detalle con este ejemplo:

_Para comprender mejor este concepto, consideremos el siguiente ejemplo: Imaginemos que nos solicitan crear una función que calcule el monto total a pagar por una compra realizada en una tienda. La tienda desea incluir una propina del 18%. La función debe recibir el monto de la compra como entrada y retornar el total a pagar, el cual incluye la propina, dividido equitativamente entre 5 personas. Es importante recordar que este ejemplo no es una guía para resolver desafíos, sino más bien una ilustración destinada a facilitar la comprensión de los mismos. A continuación, se presenta la función storeBill, la cual lleva a cabo el cálculo mencionado:_

<pre class="language-javascript"><code class="lang-javascript"><strong>const storeBill = (bill) => {
</strong>  const tipRate = 0.18;

  const total = bill * (1 + tipRate);

  return `$${total / 5}`;
};

module.exports = storeBill;
</code></pre>

Espero que esta versión sea de tu agrado. Si necesitas más cambios o alguna otra ayuda, no dudes en pedirlo.
