# 🍕 Cuenta de restaurante

Para resolver el problema "Cuenta de restaurante" debemos calcular el monto total a pagar de una cuenta de restaurante, incluyendo un impuesto del 10%. Para ello, podemos utilizar la fórmula siguiente:

* Calcular el impuesto: Multiplicamos el monto de la cuenta por 0.1 para obtener el valor del impuesto a pagar.
* Calcular el total: Sumamos el valor del impuesto al monto de la cuenta para obtener el monto total a pagar.
* Dividir el total entre el número de personas: En este caso, se especifica que el monto total se dividirá entre 5 personas. Por lo tanto, dividimos el monto total entre 5 para obtener el monto que cada persona debe pagar.

Para implementar esto en JavaScript, podemos crear una función llamada "restaurantBill" que tome como argumento el monto de la cuenta y devuelva el monto que cada persona debe pagar.

***

Podemos entender más a detalle con este ejemplo:

#### <mark style="background-color:orange;">Recuerda que esto no es una guía para resolver los retos, sino un ejemplo para comprenderlos mejor.</mark>

S_upongamos que se nos pide escribir una función que calcule el total a pagar por una compra en una tienda. La tienda tiene un impuesto del 12%, y se quiere agregar una propina del 18%. La función debe recibir el monto de la compra y devolver el total a pagar, incluyendo impuesto y propina, dividido en partes iguales entre 5 personas._

```javascript
const storeBill = (bill) => {
  const taxRate = 0.12;
  const tipRate = 0.18;

  const total = bill * (1 + taxRate + tipRate);

  return `$${total / 5}`;
};

module.exports = storeBill;
```
