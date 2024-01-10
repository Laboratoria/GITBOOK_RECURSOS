# 🍿 Cinemaster

Nesta tarefa de análise estratégica para o CineMaster, iremos  processar dados financeiros e categorizar os países de acordo com os seus custos de conteúdo. O objetivo é fornecer orientação estratégica com base no custo de conteúdo por 1.000 filmes e séries.

Para enfrentar esta tarefa de forma eficaz, seguiremos estas etapas:

1. O objetivo é categorizar os países com base nos seus custos por conteúdo, o que ajudará o CineMaster a determinar a sua abordagem ao mercado.
2. Usaremos o custo por 1.000 filmes como uma métrica padronizada para comparar os custos de conteúdo entre países.
3. Desenvolveremos uma função que usa fórmulas como VLOOKUP  e IF, juntar dados de preços, tamanhos de catálogos e, assim, categorizar os países como “baixo custo” ou “alto custo” com base no custo por 1000 filmes.
4. É crucial testar a função com exemplos de dados para garantir que ela forneça as categorias corretas.

No contexto do CineMaster, esta análise estratégica ajudará a definir as ações de entrada no mercado. Categorizar os países de acordo com seus custos por conteúdo permitirá ao CineMaster:

* A classificação de “baixo custo” poderá orientar o CineMaster em direção a estratégias específicas para explorar esses mercados.
* Mercados classificados como de “alto custo” poderão inspirar estratégias que envolvam conteúdo exclusivo ou colaborações locais.

***



<mark style="background-color:orange;">Lembre-se que este não é um guia para resolver o desafio, mas sim um exemplo para compreendê-lo  melhor.</mark>

Imagine que você recebeu a tarefa de desvendar o mistério sobre a popularidade dos restaurantes e ajudar que a  _**FoodFusion** t_ome decisões sólidas para o seu crescimento. Acompanhe-nos neste processo guiado, onde exploraremos passo- a -passo como organizar restaurantes em categorias de acordo com sua popularidade, levando em consideração as pontuações das avaliações e a variedade em seus menus.

* Nosso objetivo é segmentar restaurantes em grupos com base em seu nível de popularidade, considerando tanto as pontuações das avaliações quanto a diversidade em suas ofertas de cardápio.
* Identificaremos uma abordagem simples, mas eficaz para categorizar restaurantes. Combinaremos a pontuação média da avaliação com o número de pratos em seus menus, criando uma métrica de classificação.
* Iremos mergulhar no mundo das fórmulas, que utilizaremos justamente para classificar restaurantes. Semelhante à resolução de um quebra-cabeça, usaremos fórmulas práticas para determinar se um restaurante é “Muito Popular” ou “Moderadamente Popular”.
* Como detetives cuidadosos, testaremos nossos rótulos com exemplos concretos. Esta etapa é crucial para garantir a precisão e confiabilidade de nossas categorias.

#### As fórmulas que utilizaremos são:

1.  **Média de Popularidade**: Usaremos esta fórmula em uma célula para calcular a média ponderada da pontuação da avaliação e da quantidade de pratos nos menus:

    ```excel-formula
    (Média Pontuação + Quantidade de pratos) / 2
    ```
2.  **Classificação com Fórmula IF**: Suponha que o resultado da pontuação média esteja na célula B2. Neste caso, a fórmula IF poderia ser a seguinte:

    ```excel-formula
    =IF(B2 > 7.5, "Muito Popular", "Moderadamente Popular")
    ```

    Esta fórmula classificará o restaurante como "Muito Popular" se a média de pontuações é maior que 7.5; caso contrário, o classificará como "Moderadamente Popular".
3.  **Buscando com VLOOKUP**: Imaginemos que o valor na célula `B2` é 9,  e temos uma tabela de categorias na faixa`A10:B12`. A fórmula `VLOOKUP` seria:

    <pre class="language-excel-formula"><code class="lang-excel-formula"><strong>=VLOOKUP(B2, A10:B12, 2, 0)
    </strong></code></pre>

    Esta fórmula buscará o valor em `B2` na primeira coluna da tabela `A10:B12` e retornará o valor  da segunda coluna se encontrar uma correspondência. Neste caso, procuramos a categoria de popularidade na tabela.

Através de passos metódicos e fórmulas eficazes, estabeleceremos um sistema que classificará os restaurantes de forma precisa e robusta.

{% hint style="info" %}
Preste atenção ao exemplo, você pode encontrar a resposta!
{% endhint %}
