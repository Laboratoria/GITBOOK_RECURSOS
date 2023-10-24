---
description: 'Podemos entender mais detalhes com este exemplo:'
---

# Exemplo

#### <mark style="background-color:orange;">Recorda que este não é um guia para resolver o desafio, mas sim um exemplo para comprendê  melhor.</mark>

Imagine que você recebeu a tarefa de desvendar o mistério por trás da popularidade dos restaurantes e ajudá-los _**FoodFusion t**_ome decisões sólidas para o seu crescimento. Acompanhe-me neste processo guiado, onde exploraremos passo a passo como organizar restaurantes em categorias de acordo com sua popularidade, levando em consideração as pontuações das avaliações e a variedade em seus menus.

* Nosso objetivo é segmentar restaurantes em grupos com base em seu nível de popularidade, considerando tanto as pontuações das avaliações quanto a diversidade em suas ofertas de cardápio.
* Identificaremos uma abordagem simples, mas eficaz para categorizar restaurantes. Combinaremos a pontuação média da avaliação com o número de pratos em seus menus, criando uma métrica de classificação.
* Iremos mergulhar no mundo das fórmulas, que utilizaremos justamente para classificar restaurantes. Semelhante à resolução de um quebra-cabeça, usaremos fórmulas práticas para determinar se um restaurante é “Muito Popular” ou “Moderadamente Popular”.
* Como detetives cuidadosos, testaremos nossos rótulos com exemplos concretos. Esta etapa é crucial para garantir a precisão e confiabilidade de nossas categorias.

#### As fórmulas que utilizaremos são:

1.  **Média de Popularidade**: Usaremos esta fórmula em uma célula para calcular a média ponderada da pontuação da avaliação e da quantidade de pratos nos menus:

    ```excel-formula
    (Média Pontuação + Quantidade de pratos) / 2
    ```
2.  **Classificação com Fórmula SI**: Suponha que o resultado da pontuação média esteja na célula B2. Neste caso, a fórmula SI poderia ser a seguinte:

    ```excel-formula
    =SI(B2 > 7.5, "Muito Popular", "Moderadamente Popular")
    ```

    Esta fórmula classificará o restaurante como "Muito Popular" se a média de puntuações é maior que 7.5; caso contrario, o classificará como "Moderadamente Popular".
3.  **Buscando com VLOOKUP**: Imaginemos que o valor na célula `B2` é 9,  e temos uma tabela de categorias na faixa`A10:B12`. A fórmula `VLOOKUP` seria:

    <pre class="language-excel-formula"><code class="lang-excel-formula"><strong>=BUSCARV(B2, A10:B12, 2, 0)
    </strong></code></pre>

    Esta fórmula buscará o valor em `B2` na primeira coluna da tabela `A10:B12` e retornará o valor  da segunda coluna se encontrar uma correspondência. Neste caso, procuramos a categoria de popularidade na tabela.

Através Através de passos metódicos e fórmulas eficazes, estabeleceremos um sistema que classificará os restaurantes de forma precisa e robusta.
