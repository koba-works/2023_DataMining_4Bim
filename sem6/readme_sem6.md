# 6 Análise de associação

Olá, pessoal! O assunto desta semana é análise de associação. Usamos as regras de associação quando queremos descobrir relações entre itens distintos que, por exemplo, costumam ser comprados em conjunto com alguma frequência.
A análise de associação pode ajudar a descobrir relações que não são tão fáceis de imaginar diretamente, algo como “sempre que alguém compra um produto A, também compra um produto B”. Esse tipo de conhecimento pode ser muito útil para montar estratégias de vendas ou até mesmo para fazer gestão de controle de estoque.
Vamos conhecer as principais características da análise de associação e conhecer alguns dos principais algoritmos usados para essa finalidade.
Por fim, vamos fazer um exercício prático usando um algoritmo de regras de associação.
Ao final desta semana, você deverá ser capaz de:

   * conhecer os principais métodos de análise de associação;
   * entender como utilizar os métodos de análise de associação.

Desafio

Imagine uma loja de departamento, física ou online, que vende centenas de produtos diferentes diariamente. Certamente há produtos que conseguimos imaginar uma relação direta. Por exemplo, a compra de lápis associada com a compra de borracha. Além disso, pode existir outras relações entre produtos aparentemente distintos, mas que na prática acontecem.
Como fazemos para explorar e compreender possíveis relações entre uma grande quantidade de produtos em grandes bases de dados, contendo centenas de milhares ou mesmo milhões de transações? Escreva sua opinião no fórum temático.

Revisitando Conhecimentos

Nesta semana, vamos estudar o algoritmo FP-Growth, que usa estrutura de dados de árvore. Se necessário, reveja a videoaula sobre árvores da disciplina Algoritmos e Programação de Computadores II.

Árvores | Univesp

https://www.youtube.com/watch?v=xHFrkjKy11I
Nesta videoaula, aprenderemos o conceito de árvores e suas variações, com aplicações e exemplos de como estruturas não-sequenciais podem ser usadas para resolver problemas complexos.


Orientação de Estudo

Para esta semana, sugerimos que você estude da seguinte forma:

    Leia as seções 7.1 e 7.2 do livro de Leandro Castro e Daniel Ferrari;
    Assista a Videoaula 15;
    Leia as seções 7.3 e 7.4 do livro de Leandro Castro e Daniel Ferrari;
    Assista a Videoaula 16;
    Leia o texto sobre Regras de Associação, de Mauro Pichiliani;
    Faça as atividades práticas de apoio;
    Estude os materiais de apoio para complementar os seus conhecimentos sobre o conteúdo da semana;
    Participe do fórum temático;
    Lembre-se de realizar a Atividade Avaliativa desta semana.

Bons estudos!

Texto-base: 
Introdução à Mineração de Dados: Conceitos Básicos, Algoritmos e Aplicações (Leia as seções 7.1 e 7.2, das páginas 234 a 244, do capítulo 7) | 
Leandro Nunes de Castro e Daniel Gomes Ferrari

Videoaula 15 - Regras de associação 
Conhecer os principais conceitos sobre regras de associação.
https://www.youtube.com/watch?v=OhR4wZV0DPA

Texto-base: 
Introdução à Mineração de Dados: Conceitos Básicos, Algoritmos e Aplicações (Leia as seções 7.3 e 7.4, das páginas 244 a 266, do capítulo 7) | 
Leandro Nunes de Castro e Daniel Gomes Ferrari

Videoaula 16 - Algoritmos para mineração de regras de associação 
Apresentar os principais algoritmos de mineração de regras de associação.
https://www.youtube.com/watch?v=_15nUAC_dBE

Texto-base: Data mining na prática: regras de associação | Mauro Pichiliani, iMasters
https://imasters.com.br/back-end/data-mining-na-pratica-regras-de-associacao

Semana 6 - Quiz - Videoaulas
Pergunta 1
Sobre as bases de dados usadas em algoritmos de regras de associação, escolha a alternativa correta:

Alternativas: 

    Bases de dados não relacionais.
    Bases de dados geolocalizados.
    Bases de dados associativos.
    Bases de dados com dados rotulados.
    Bases de dados transacionais.

Pergunta 2
Escolha a alternativa que apresenta a ordem correta dos passos principais do processo de geração de itens frequentes do algoritmo Apriori. 

    I. Geração dos conjuntos-k. 
    II. Critério de parada. 
    III. Contagem de suporte. 
    IV. Determinação dos conjuntos frequentes. 
    
Alternativas: 

<br>    II, I, IV e III <br/>
<br>    I, IV, III e II <br/>
<br>    III, I, IV e II <br/>
<br>    III, II, IV e I <br/>
<br>    IV, III, II e I <br/>

Quiz - Objeto Educacional - Semana 6 - Para exercitar a leitura dos materiais-base
Pergunta 1
Escolha a alternativa que contém a definição correta de mineração de regras de associação: 
Alternativas: 
    Técnica usada na predição de regras de classificação de objetos de uma base de dados.
    Técnica que define um conjunto de regras associadas umas às outras para classificar um conjunto de dados.
    Técnica usada na construção de relações sob a forma de regras entre itens de uma base de dados transacional.
    Técnica que usa regras previamente definidas para separar itens de uma base de dados transacional.
    Técnica usada na definição de regras de predição de novos itens a partir de itens já existentes. 

Pergunta 2
Escolha a alternativa que apresenta a ordem correta dos passos principais do processo de construção da árvore de itens frequentes do algoritmo FP-Growth. 

    I. Determinação da lista de itens frequentes. 
    II. Função que insere itens na árvore (InsertTree). 
    III. Construção da árvore (FP-Tree). 
Alternativas: 
    I, II e III
    I, III e II
    III, I e II
    III, II e I
    II, III e I

Pergunta 3
Sobre regras de associação, qual das alternativas abaixo está correta?
Alternativas: 
    O suporte indica a frequência com que dois conjuntos de itens de uma regra aparecem no conjunto total de transações. 
    O suporte indica a frequência com que um conjunto de itens aparece no conjunto total de transações.
    A confiança indica a frequência com que um conjunto de itens aparece no conjunto total de transações.
    Suporte é uma medida usada para avaliar a qualidade de regras de associação.
    O suporte indica a diferença entre a quantidade de ocorrências de um conjunto de itens e a quantidade de ocorrências do conjunto total de transações.


Atividades práticas de apoio - Semana 6 
Videoaula 17: Tutorial e exercício: Analisando um conjunto de dados usando o algoritmo Apriori.
https://www.youtube.com/watch?v=sbqtg6GyZCc

Aprofundando o tema - Semana 6

    Uma introdução ao algoritmo Apriori | Bernardo Costa, Medium
    https://medium.com/@bernardo.costa/uma-introdu%C3%A7%C3%A3o-ao-algoritmo-apriori-60b11293aa5a
    
    Minerações de dados frequentes com Apriori e FP Growth | Abner Suniga, Medium
    https://medium.com/@abnersuniga7/encontre-padr%C3%B5es-nos-seus-dados-com-apriori-e-fp-growth-4a581ec1b22
    
    Data Mining and Machine Learning
    https://dataminingbook.info/book_html/

Em síntese - Semana 6
Nesta semana, falamos sobre regras de associação. Vimos quais são características das regras de associação e também vimos dois dos principais algoritmos para mineração de regras de associação.

Parabéns! Você chegou ao fim do conteúdo desta semana.
Na próxima semana o assunto será detecção de anomalias. Até lá!

Você está preparado para avançar? Faça uma auto-avaliação: você adquiriu todas as competências e habilidades esperadas? Marque os itens que acredita ter alcançado. Se faltar algum, revise o conteúdo da semana.

Nesta semana, eu:
conheci os principais métodos de análise de associação;
entendi como utilizar os métodos de análise de associação.

