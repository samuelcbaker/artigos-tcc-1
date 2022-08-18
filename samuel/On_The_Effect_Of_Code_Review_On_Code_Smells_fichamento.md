# On The Effect Of Code Review On Code Smells

Pascarella, L., Spadini, D., Palomba, F., & Bacchelli, A. (2019). On the effect of code review on code smells. arXiv preprint arXiv:1912.10098. doi: [10.48550/arXiv.1912.10098](https://doi.org/10.48550/arXiv.1912.10098)

## 1. Fichamento de Conteúdo

O artigo tem o objetivo de analisar a relação do _code review_ com problemas de código denominados _code smells_. Com esse propósito, os pesquisadores analisaram mais de 21.000 _code reviews_ em 7 projetos Java diferentes. Dessa forma, foi levantado 3 questões a serem respondidas na pesquisa: "Como o _code review_ influencia na severidade geral de _code smells_?", "Como o _code review_ influencia na severidade de diferentes tipos de _code smells_?" e "Por que a severidade de _code smells_ diminui durante o _code review_?". Como resultado, os autores entenderam que apesar de que em 96% dos casos o _code review_ não influenciou na diminuição da severidade dos _code smells_, esse processo de revisão está significativamente ligado a redução desses maus cheiros no código, na maioria das vezes de forma não proposital por parte dos revisores. Além disso, vale ressaltar que os _code smells_ de "_Lazy Class_" e "_God Class_" estão mais relacionados à diminuição durante o processo de revisão de código do que as outras métricas analisadas. Para percepção dos resultados foram feitos modelos estatísticos usando a classificação de Pearson, Wilcoxon e Cohen's. Os autores propoem que é importante o surgimento de mais estudos sobre o _code review_, suas vantagens e como esse processo pode ser melhorado, utilizando gamificação por exemplo. Eles também fazem uma reflexão sobre a falta da detecção de _code smells_ no código estar relacionada a complexidade de enxergar as falhas ou por causa dos desenvolvedores preferirem não lidarem com esse tipo de mudança quando as percebem. Por fim, para pesquisas futuras, a ideia é replicar em outros projetos com repositórios privados que possuem diferentes guias e regras para atividades de _code review_.

## 2. Fichamento Bibliográfico

- _Code smells_ são decisões de _design_ que são abaixo do ideal (página 1).
- _CROP_ (do inglês, _Code Review Open Platform_) é um plataforma pública com um banco de dados ideal para utilização em pesquisas relacionadas a _Code Review_ (página 4).
- _Code smell severety_ (severidade do _code smell_) é calculado pelo valor do _code smell_ detectado dividido pelo limite estabelecido (página 4).
- _Code smell severety variation_ (variação de severidade do _code smell_) é calculado pelo subtração do _code smell severity_ de depois da revisão dos desenvolvedores pelo _code smell severity_ de antes da revisão (página 4).
- _SelfApproved_ (aprovação própria) é quando um código enviado para revisão é aprovado somente pelo próprio autor (página 5).

## 3. Fichamento de Citações

- _"Code smells are symptoms of poor design quality."_
- _"Our research community has found empirical evidence of the negative impact of code smells on software maintainability [2]-[5] , program comprehensibility [6], and development effort [7], as well as on the problems that developers encounter when dealing with these smells [8]-[13]."_
- _"Not all code reviews are done with the same care. Indeed, past research has defined proxy metrics to define engagement and participation in code review and has shown that higher values in these metrics related to a better outcome for a code review [37]."_
- _"In 96% of the cases, the severity of the code smells in the files under review does not decrease. However, higher values of code review quality dimensions are indeed significantly related to a decrease in code smell severity."_
