# The Impact of Code Review Coverage and Code Review Participation on Software Quality

Shane McIntosh, Yasutaka Kamei, Bram Adams, and Ahmed E. Hassan. 2014. The impact of code review coverage and code review participation on software quality: a case study of the qt, VTK, and ITK projects. In Proceedings of the 11th Working Conference on Mining Software Repositories (MSR 2014). Association for Computing Machinery, New York, NY, USA, 192–201. doi: [10.1145/2597073.2597076](https://doi.org/10.1145/2597073.2597076).

## 1. Fichamento de Conteúdo

O artigo tem o objetivo de estudar a relação da cobertura e participação na revisão de código em relação a quantidade de componentes no _software_ propensos a ter algum defeito. Sendo assim, os objetos de pesquisa foram os projetos de código aberto: _Qt_, _VTK_, e _ITK_, onde através da API (do inglês, _Application Program Interface_) fornecida pelo _Gerrit_ foram minerados. Dessa forma, a cobertura da revisão de código foi medida usando as seguintes métricas: _”proportion of reviewed changes”_ (proporção de mudanças revisadas) e _”proportion of reviewed churn”_ (proporção de _churn_ revisado), e obteve como resultado que componentes com maior cobertura tendem a ter menos defeitos após o lançamento de novas versões. Já a participação na revisão tem como base três métricas: _”proportion of self-approved changes”_ (proporção de mudanças aprovadas pelo próprio autor), _”proportion of hastily reviewed changes”_ (proporção de mudanças revisadas precipitadamente) e _”proportion of changes without discussion”_ (proporção de mudanças sem discussões). Essa questão evidenciou que a falta de participação no processo de revisão tem um impacto negativo na qualidade do _software_. Vale ressaltar que o artigo apresenta muitas métricas interessantes para análise do processo de revisão de código e os autores pretendem fazer novas pesquisas no futuro para também relacioná-las à qualidade do _software_.

## 2. Fichamento Bibliográfico

- _Code review coverage_ (Cobertura da revisão de código) é a proporção de alterações que foram revisadas no processo de revisão de código (página 1).
- _Code review participation_ (Participação na revisão de código) é o grau de envolvimento dos revisores no processo de revisão de código (página 1).
- _Formal code inspection model_ (Modelo formal de inspeção de código) é o modelos de revisão de código onde um tempo é definido para que os autores e revisores discutam as mudanças realizadas (página 1).
- _Modern reviewing process_ (Processo moderno de revisão) é o processo de revisão de código onde os critérios não são obrigatórios e pode gerar menos discussão entre os desenvolvedores (página 1).
- _Post-release defects_ (Defeitos pós _release_) são os defeitos encontrados na versão oficial do _software_ (página 2).
- _Major authors_ (autores principais) são os autores que possuem mais expertise em algum componente de _software_ (página 5).

## 3. Fichamento de Citações

- _"Low code review coverage and participation are estimated to produce components with up to two and five additional post-release defects respectively."_
- _"Our results empirically confirm the intuition that poorly reviewed code has a negative impact on software quality in large systems using modern reviewing tools."_
- _"Components with higher review coverage tend to have fewer post-release defects."_
- _"Components with high rates of participation in code review tend to have fewer post-release defects."_
- _"Reviews without discussion are associated with higher post-release defect counts, suggesting that the amount of discussion generated during review should be considered when making integration decisions."_
