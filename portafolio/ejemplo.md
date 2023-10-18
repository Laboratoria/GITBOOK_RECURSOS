---
description: 'Podemos entender más a detalle con este ejemplo:'
---

# Ejemplo

#### <mark style="background-color:orange;">Recuerda que esto no es una guía para resolver los retos, sino un ejemplo para comprenderlos mejor.</mark>

_Nos pidieron hacer una página web de bicicletas. La página tendrá un encabezado, un menú de navegación, una sección de productos y un pie de página._&#x20;

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bike Shop</title>
</head>
<body>
    <!-- Encabezado -->
    <header>
        <h1>Bike Shop</h1>
    </header>
    
    <!-- Menú de navegación -->
    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Productos</a></li>
            <li><a href="#">Contacto</a></li>
        </ul>
    </nav>
    
    <!-- Sección de productos -->
    <section>
        <h2>Productos</h2>
        <article>
            <h3>Bicicleta de montaña</h3>
            <img src="mountain-bike.jpg" alt="Bicicleta de montaña">
            <p>La bicicleta de montaña es perfecta para explorar senderos y caminos en la naturaleza.</p>
            <p>Precio: $500</p>
        </article>
        
        <article>
            <h3>Bicicleta de carretera</h3>
            <img src="road-bike.jpg" alt="Bicicleta de carretera">
            <p>La bicicleta de carretera es ideal para recorrer distancias largas a altas velocidades.</p>
            <p>Precio: $800</p>
        </article>
    </section>
    
    <!-- Pie de página -->
    <footer>
        <p>&copy; 2023 Bike Shop</p>
    </footer>
</body>
</html>
```

1. `<!DOCTYPE html>`: Esta línea indica que estamos usando HTML5.
2. `<html lang="en">`: Este elemento engloba todo el documento HTML y define el lenguaje de la página, en este caso inglés.
3. `<head>`: Este elemento contiene información sobre la página, como el título y la descripción. La etiqueta `<meta>` define la codificación de caracteres y la escala de la página para dispositivos móviles.
4. `<body>`: Este elemento contiene todo el contenido visible de la página.
5. `<header>`: Este elemento define la cabecera de la página y contiene el título principal.
6. `<nav>`: Este elemento contiene una lista de enlaces de navegación para que los usuarios puedan moverse por la página. Los elementos de lista `<li>` contienen los enlaces `<a>`.
7. `<section>`: Este elemento define una sección de la página, en este caso la sección de productos. Los elementos `<article>` son contenedores para cada producto y contienen información como el nombre, la imagen y el precio.
8. `<footer>`: Este elemento define el pie de página y contiene información como el año de derechos de autor.
