---
description: 'Podemos entender más a detalle con este ejemplo:'
---

# Ejemplo

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

