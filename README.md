<h1 align="center" id="head"><b>PROGRAMAÇÃO DINÂMICA E SEUS ALGORITMOS [ EM PRODUÇÃO ]</b></h1>

<p align="center"><b> - Repositório de Estudos sobre programação dinâmica -</b></p>
<br>

<p align="justify">&emsp; Bem-vindo ao Repositório de Estudos de Programação Dinâmica e seus Algoritmos! Este repositório foi criado com o objetivo de ser material de ensino sobre programação dinâmica e seus algoritmos.</p><br>
<br>


<h2 align="center">S U M A R I O</h2>
<br>

1. [Introdução](#intro)
1. [Algoritmos](#algoritmos)
1. [Referências Bibliográcas](#ref)




<h2 id="intro"> Introdução </h2>
<br>

<p align="justify">&emsp;A programação dinâmica é uma técnica de otimização utilizada para resolver problemas que podem ser divididos em subproblemas menores e onde as soluções para esses subproblemas podem ser reutilizadas para resolver o problema maior. Essa abordagem ajuda a evitar o cálculo repetitivo de soluções para os mesmos subproblemas, economizando tempo computacional. Aqui estão alguns dos algoritmos e problemas clássicos associados à programação dinâmica:</p>

<h2 id="algoritmos"> Algoritmos </h2>
<br>

### **Algoritmo de Fibonacci com Programação Dinâmica:**

- O problema de calcular o N-ésimo número de Fibonacci de forma eficiente.
- O algoritmo de Fibonacci com programação dinâmica armazena os resultados dos números de Fibonacci já calculados para evitar recálculos.

### **Algoritmo de Mochila (Knapsack Problem):**

- Um problema de otimização onde se deve selecionar itens com valores e pesos específicos para maximizar o valor total, com uma capacidade de peso limitada.
- A programação dinâmica é frequentemente usada para resolver este problema, calculando o valor máximo que pode ser alcançado em diferentes capacidades de mochila.

### **Algoritmo de Edição de Distância (Levenshtein Distance):**

- Usado para calcular a distância de edição (ou distância de Levenshtein) entre duas sequências, que é o número mínimo de operações (inserções, exclusões ou substituições) necessárias para transformar uma sequência na outra.
- A programação dinâmica é empregada para encontrar a solução eficiente.

### **Algoritmo de Longest Common Subsequence (LCS):**

- Usado para encontrar a subsequência comum mais longa entre duas sequências (strings ou listas).
- A programação dinâmica é aplicada para encontrar o comprimento da LCS e, em seguida, reconstruir a subsequência.

### **Algoritmo de Cadeia de Matrizes (Matrix Chain Multiplication):**

- Envolve determinar a ordem de multiplicação de várias matrizes para minimizar o número de operações de multiplicação.
- A programação dinâmica é usada para encontrar a ordem ideal de multiplicação.

### **Algoritmo de Caminho Mais Curto em Grafos (Dijkstra e Floyd-Warshall):**

- Para encontrar o caminho mais curto entre dois vértices em um grafo ponderado, como em problemas de roteamento de redes ou navegação.
- A programação dinâmica pode ser usada em variantes desses algoritmos.

### **Algoritmo de Crescimento de Sequências (Longest Increasing Subsequence):**

- Para encontrar a subsequência crescente mais longa em uma sequência de números.
- A programação dinâmica é usada para calcular o tamanho da subsequência e, em seguida, reconstruí-la.

### **Algoritmo de Partição de Palavras (Word Break Problem):**

- Usado para determinar se uma string pode ser dividida em palavras presentes em um dicionário.
- A programação dinâmica ajuda a verificar a divisibilidade da string.

<br>

<p align="justify">&emsp;Os algoritmos FP-Max, Apriori e FP-Growth não são algoritmos de programação dinâmica. Eles pertencem ao campo da mineração de dados e são usados para resolver problemas de mineração de regras de associação em conjuntos de dados transacionais. A programação dinâmica é uma técnica de otimização que se concentra na resolução de problemas de otimização divididos em subproblemas menores, enquanto os algoritmos mencionados se concentram na descoberta de padrões frequentes em dados.</p>



### **Algoritmo FP-Max**

<p align="justify">&emsp;O FP-Max é uma variação do algoritmo FP-Growth e é usado para encontrar conjuntos de itens frequentes que não são subconjuntos de outros conjuntos frequentes. Ele não emprega programação dinâmica, mas sim técnicas de estruturas de dados eficientes para identificar padrões frequentes.</p>

### **Apriori**

<p align="justify">&emsp;O algoritmo Apriori é usado para a mineração de regras de associação em dados transacionais. Ele é um dos algoritmos pioneiros nessa área e baseia-se em técnicas de geração de candidatos e poda para identificar regras de associação frequentes. Assim como o FP-Max e o FP-Growth, o Apriori não faz uso de programação dinâmica.</p>

### **FP-Growth**

<p align="justify">&emsp;O FP-Growth é um algoritmo de mineração de dados que se baseia em uma estrutura de dados chamada "Árvore de Projeto de Padrões" (FP-Tree) para encontrar padrões frequentes em dados. Ele também não utiliza programação dinâmica, mas é eficiente na identificação de padrões frequentes.</p>

<h2 id="ref">Refrência Bibliográfica</h2><br>

- [Incorporando Técnicas de Mineração de
Dados à Metaheurística GRASP](https://www.ic.uff.br/wp-content/uploads/2021/11/276.pdf)
- [A técnica da programação dinâmica no projeto de algoritmos](https://www.ime.usp.br/~pf/analise_de_algoritmos/aulas/dynamic-programming.html)
- [Algoritmos para Programação Dinâmica Baseados em Famílias Invariantes](http://www.din.uem.br/sbpo/sbpo2005/pdf/arq0024.pdf)
- [Complexidade de algoritmos - UFRGS](https://www.inf.ufrgs.br/~prestes/Courses/Complexity/aula17.pdf)
- [FPmax e suas possíveis utilizações](https://www.linkedin.com/pulse/o-algoritmo-fpmax-e-suas-poss%C3%ADveis-utiliza%C3%A7%C3%B5es-davi-j-leite-santos/)
- [python mlxted - FPgrowth - documentação](https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/fpgrowth/)
- [python mlxted - FPmax - documentação](https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/fpmax/)
- [python mlxted - Apriori - documentação](https://rasbt.github.io/mlxtend/user_guide/frequent_patterns/fpmax/)
- [Mineração de dados frequentes com Apriori e FPgrowth](https://medium.com/@abnersuniga7/encontre-padr%C3%B5es-nos-seus-dados-com-apriori-e-fp-growth-4a581ec1b22)

<br>
<h1 id="Equipe">Equipe</h1><br>

<div align="center">

|     Desenvolvedor              |           GitHub             |       LinkedIn     |
|--------------------------------|------------------------------|--------------------|
|👤 João Vitor Moraes            |<https://github.com/JohKemPo>   |<https://www.linkedin.com/in/joao-vitor-de-moraes/>|
</div>