# Understanding Code Smell Detection via Code Review: A Study of the OpenStack Community

X. Han, A. Tahir, P. Liang, S. Counsell and Y. Luo, "Understanding Code Smell Detection via Code Review: A Study of the OpenStack Community," 2021 IEEE/ACM 29th International Conference on Program Comprehension (ICPC), 2021, pp. 323-334, doi: [10.1109/ICPC52881.2021.00038](https://doi.org/10.1109/ICPC52881.2021.00038).

## 1. Fichamento de Conteúdo

O artigo tem o objetivo de investigar a detecção de _code smells_ durante o processo de revisão de código e quais ações são sugeridas pelos revisores e atendidas pelos desenvolvedores para solucionar esses problemas. Para isso, os pesquisadores analisaram os dados de dois projetos armazenados no OpenStack e verificaram 19146 comentários utilizando uma técnica de identificação de palavras chaves e também fizeram 1064 análises manuais aleatórias. Como resultado, eles entenderam que _code smells_ geralmente não são encontrados nos processos de revisão, mas em caso contrário é mais comum que esses problemas estejam relacionados a código duplicado, má nomeação de entidades e código morto. Além disso, a principal causa desse cheiro ruim no código são as violações de convenções de código. Também vale ressaltar que quando os revisores encontram esses problemas e fornecem uma recomendação de refatoração, os desenvolvedores costumam aceitar a sugestão e corrigir o trecho de código relacionado. Vale dizer que o artigo conclui que convenções de código são importantes na redução do custo de manutenção do _software_, visto que o _code smell_ pode aumentar esse custo. Os autores planejam fazer essa pesquisa com outros repositórios para obter mais dados e evoluir suas perspectivas.

## 2. Fichamento Bibliográfico

- _Code review_ (revisão de código) é processo que tem como objetivo verificar a qualidade do código achando defeitos, problemas e garantindo que o código está legível, coeso e manutenível (página 1).
- _Code smells_ práticas ruins de programação que podem gerar defeitos ou problemas de manutenção (página 1).
- _Gerrit_ é um plataforma WEB (do inglês, _World Wide Web_) para ajudar a realização de revisão de código em equipe (página 3).
- _ignored the change_ (ignorar mudança) é quando nenhuma mudança é feita no código para tirar o _code smell_ (página 6).
- _Review-based smell detection mechanism_ (revisão baseada em encontrar _smells_) é a revisão de código onde os revisores encontram um _smell_ e reportam para o desenvolvedor (página 9).

## 3. Fichamento de Citações

- _"Code review plays an important role in software quality control. A typical review process would involve a careful check of a piece of code in an attempt to find defects and other quality issues/violations."_
- _"Code smells are identified as symptoms of possible code or design problems [1], which may potentially have a negative impact on software quality, such as maintainability [2], code readability [3], testability [4], and defect-proneness [5]."_
- _"Code smells are not widely identified in code reviews. Of the identified smells, duplicated code, bad naming, and dead code are the most frequently identified smells in code reviews."_
- _"Taken overall, over half of the reviews did not provide an explanation of the cause of the smells. In terms of the formulated causes, violation of coding conventions is the main cause for the smells as noted by reviewers and developers."_
- _"Coding conventions are important in reducing the cost of software maintenance while the existence of smells can increase this cost."_
- _"Another main observations is that more than half of review- ers (in review comments where they indicated that there was a code smell) simply pointed out the smell in the code, but did not provide any further explanation of why they considered that as a smell."_
