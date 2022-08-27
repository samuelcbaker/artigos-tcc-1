# What Code Is Deliberately Excluded from Test Coverage and Why?

A. Hora, "What Code Is Deliberately Excluded from Test Coverage and Why?," 2021 IEEE/ACM 18th International Conference on Mining Software Repositories (MSR), 2021, pp. 392-402, doi: [10.1109/MSR52588.2021.00051](https://doi.org/10.1109/MSR52588.2021.00051).

## 1. Fichamento de Conteúdo

A cobertura de código é amplamente difundida na indústria de _software_ e é muito importante para a avaliação da saúde do sistema. O artigo fornece o primeiro estudo empírico com o objetivo de entender as exclusões de trechos de código na análise da cobertura do mesmo. Essas exclusões são feitas para que a ferramenta que mede o percentual de código testado desconsidere trechos específicos. Os pesquisadores avaliaram 55 repositórios de projetos que utilizam Python e obtiveram 4 constatações. Em primeiro lugar, 1/3 dos projetos utilizam alguma estratégia de exclusão. Em segundo, sobre o momento que esse procedimento foi realizado, 75% da configuração de exclusão foram feitas no início do projeto. Em terceiro, em relação ao código, perceberam que a maioria das exclusões são de estruturas condicionais (42%) e tratamento de exceções (29%). Por fim, sobre o motivo dessas exclusões, na maior parte dos casos é feita por causa de códigos que não são possíveis de serem testados, ou são de baixo nível, ou são complexos. O artigo mostra a importância de ter relatórios de cobertura que sejam mais assertivos e que não considerem trechos que não precisam ser testados. Apesar disso, os autores entendem que existe um perigo dos desenvolvedores excluírem trechos complexos apenas para que a métrica tenha um bom resultado, indicando um falso positivo e sobre isso eles propõem que as ferramentas possibilitem a inclusão da justificativa que aqueles trechos foram retirados da cobertura. Vale ressaltar, que para trabalhos futuros, eles pretendem fazer a análise em projetos com outras linguagens como Java e JavaScript.

## 2. Fichamento Bibliográfico

- _Test coverage_ (Cobertura de testes) mede o percentual do código coberto por testes (página 1).
- _Conditional statement_ (estrutura condicional) é a estrutura que controla fluxos de execução, como a condição _if_ (página 5).
- _Defensive code_ (Código defensivo) é uma abordagem para melhorar a qualidade, compreensibilidade e até a previbilidade do código de software (Fonte [Wikipedia](https://en.wikipedia.org/wiki/Defensive_programming)).

## 3. Fichamento de Citações

- _"Test coverage is largely used to assess test effectiveness. In practice, not all code is equally important for coverage analysis, for instance, code that will not be executed during tests is irrelevant and can actually harm the analysis."_
- _"Test coverage measures the percentage of code that is covered (and uncovered) by tests, that is, which parts of a program are actually executed during a test run."_
- _"Test coverage can be used to support code review. Therefore, assessing and detecting code coverage exclusion practices can improve code review workflow by eliminating possible noisy code."_
- _"Test coverage is widespread in the software industry."_
