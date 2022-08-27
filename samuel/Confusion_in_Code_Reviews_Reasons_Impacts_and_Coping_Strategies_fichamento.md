# Confusion in Code Reviews: Reasons, Impacts, and Coping Strategies

F. Ebert, F. Castor, N. Novielli and A. Serebrenik, "Confusion in Code Reviews: Reasons, Impacts, and Coping Strategies," 2019 IEEE 26th International Conference on Software Analysis, Evolution and Reengineering (SANER), 2019, pp. 49-60, doi: [10.1109/SANER.2019.8668024](https://doi.org/10.1109/SANER.2019.8668024).

## 1. Fichamento de Conteúdo

O artigo tem o objetivo de investigar situações de confusão durante a revisão de código e quais estratégias que os desenvolvedores adotam para lidar com elas. Dessa forma, os pesquisadores realizaram uma triangulação dos dados obtidos em uma pesquisa estruturada e em uma análise de comentários em revisões de código. Esses dados foram categorizados através da técnica de ordenação de cartões (_open card sorting_) onde os revisores realizam esse processo sem tópicos pré definidos e depois iniciam uma nova rodada de pesquisa fazendo uma ordenação com os tópicos que já foram encontrados na primeira etapa. Se surgirem novos tópicos, os pesquisadores repetem o passo anterior. Dessa forma, foram encontrados três grupos de resultados: razões de confusão na revisão de código, quais os impactos dessas confusões e como os desenvolvedores lidam com elas. Como resposta a esses questionamentos, os pesquisadores encontraram que as principais razões para essa confusão são: falta de razão da submissão do código, discussões de requisitos não funcionais da solução e falta de familiaridade com o código. Em relação aos impactos, essas confusões geram um atraso no processo de integração do código, diminuição da qualidade da revisão e discussões adicionais. Por último, os desenvolvedores lidam com essa situação principalmente pedindo mais informações para quem submeteu o código e discutindo através de outros canais sobre o código do desenvolvedor. O artigo foi o primeiro a construir um _framework_ para compreender essas confusões que acontecem durante o processo de revisão de código.

## 2. Fichamento Bibliográfico

- _Code review_ (revisão de código) é uma prática para garantir a qualidade do código encontrando defeitos, transferindo conhecimento e encorajando a aderência de padrões de codificação (página 1).
- _Confusion_ (confusão) qualquer situação onde a pessoa fica em dúvida sobre algo ou é incapaz de entendê-lo (página 1).
- _review-then-commit_ (revisar-depois-submeter) é a prática da revisão de código antes que ele seja integrado ao código fonte principal (página 2).
- _commit-then-review_ (submeter-depois-revisar) é a prática da revisão de código depois que ele seja integrado ao código fonte principal (página 2).
- _Open card sorting_ é uma técnica para levantamento de tópicos onde os mesmos não são pré definidos e surgem durante o processo de ordenação (página 3).
- _Closed card sorting_ é um técnica para ordenação de tópicos que já foram levantados em outra etapa (_open card sorting_), se um novo tópico surgir é necessário uma nova etapa de ordenação com novos dados (página 3).

## 3. Fichamento de Citações

- _"Code review is a software quality assurance practice widely employed in both open source and commercial software projects to detect defects, transfer knowledge and encourage adherence to coding standards."_
- _"The most frequent reasons for confusion are the missing rationale, discussion of nonfunctional requirements of the solution, and lack of familiarity with existing code."_
- _"Active participation of developers in code reviews decreases the number of post- release defects and improves the software quality [6], [7]; knowledge transfer and adherence to the project coding stan- dards are additional benefits of code reviews [8], [9], [10]."_
- _"Our results suggest that the merge decision is delayed when developers experience confusion, there is an increase in the number of messages exchanged during the discussion, and the review quality decreases."_
- _"Formal code review was first defined by Fagan in 1976 as a software inspection practice, a structured process for reviewing source code with the single goal of finding defects, usually conducted by groups of reviewers in extended meetings [21]."_
- _"We identified 14 different impacts of confusion in code reviews. The most common are delaying, decrease of review quality, and additional discussions."_
- _"Similarly, integration of tools assessing the test coverage of a change might keep developers from committing changes with low test coverage, thus avoiding confusion due to lack of tests."_
