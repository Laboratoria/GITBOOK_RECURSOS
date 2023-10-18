---
description: 'Pode-se entender mais detalhadamente com este exemplo:'
---

# Exemplo

<mark style="background-color:orange;">**Lembre-se de que isso não é um guia para resolver os desafios, mas um exemplo para compreendê-los melhor.**</mark>&#x20;

Nos pediram para criar uma página web de bicicletas. A página terá um cabeçalho, um menu de navegação, uma seção de produtos e um rodapé.

## Loja de Bicicletas

<pre class="language-html"><code class="lang-html">&#x3C;!DOCTYPE html>
&#x3C;html lang="pt">
&#x3C;head>
    &#x3C;meta charset="UTF-8">
    &#x3C;meta name="viewport" content="width=device-width, initial-scale=1.0">
    &#x3C;title>Loja de Bicicletas&#x3C;/title>
&#x3C;/head>
&#x3C;body>
    &#x3C;!-- Cabeçalho -->
    &#x3C;header>
        &#x3C;h1>Loja de Bicicletas&#x3C;/h1>
    &#x3C;/header>
<strong>&#x3C;!-- Menu de navegação -->
</strong>&#x3C;nav>
    &#x3C;ul>
        &#x3C;li>&#x3C;a href="#">Início&#x3C;/a>&#x3C;/li>
        &#x3C;li>&#x3C;a href="#">Produtos&#x3C;/a>&#x3C;/li>
        &#x3C;li>&#x3C;a href="#">Contato&#x3C;/a>&#x3C;/li>
    &#x3C;/ul>
&#x3C;/nav>

&#x3C;!-- Seção de produtos -->
&#x3C;section>
    &#x3C;h2>Produtos&#x3C;/h2>
    &#x3C;article>
        &#x3C;h3>Bicicleta de montanha&#x3C;/h3>
        &#x3C;img src="mountain-bike.jpg" alt="Bicicleta de montanha">
        &#x3C;p>A bicicleta de montanha é perfeita para explorar trilhas e caminhos na natureza.&#x3C;/p>
        &#x3C;p>Preço: $500&#x3C;/p>
    &#x3C;/article>
    
    &#x3C;article>
        &#x3C;h3>Bicicleta de estrada&#x3C;/h3>
        &#x3C;img src="road-bike.jpg" alt="Bicicleta de estrada">
        &#x3C;p>A bicicleta de estrada é ideal para percorrer longas distâncias em altas velocidades.&#x3C;/p>
        &#x3C;p>Preço: $800&#x3C;/p>
    &#x3C;/article>
&#x3C;/section>

&#x3C;!-- Rodapé -->
&#x3C;footer>
    &#x3C;p>&#x26;copy; 2023 Loja de Bicicletas&#x3C;/p>
&#x3C;/footer>
&#x3C;/body>
&#x3C;/html>
</code></pre>

1. `<!DOCTYPE html>` : Esta linha indica que estamos usando o HTML5.
2. `<html lang="en">`: Este elemento envolve todo o documento HTML e define o idioma da página, neste caso, inglês. A tag `<head>`: Este elemento contém informações sobre a página, como título e descrição.&#x20;
3. `<meta>` :define a codificação de caracteres e a escala da página para dispositivos móveis.
4. `<body>`: Este elemento contém todo o conteúdo visível da página.&#x20;
5. `<header>`: Este elemento define o cabeçalho da página e contém o título principal.&#x20;
6. `<nav>`: Este elemento contém uma lista de links de navegação para que os usuários possam se movimentar pela página. Os elementos de lista `<li>` contêm os links `<a>`.&#x20;
7. `<section>`: Este elemento define uma seção da página, neste caso, a seção de produtos. Os elementos `<article>` são contêineres para cada produto e contêm informações como nome, imagem e preço.&#x20;
8. `<footer>`: Este elemento define o rodapé e contém informações como o ano de direitos autorais."\
