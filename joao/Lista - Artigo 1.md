# Comments on Comments: Where Code Review and Documentation Meet

Rao, N., Tsay, J., Hirzel, M., & Hellendoorn, V. J. (2022). Comments on Comments: Where Code Review and Documentation Meet. arXiv preprint arXiv:[2204.00107](https://arxiv.org/abs/2204.00107).

## 1. Fichamento de Conteúdo

O artigo se baseia em um estudo quantitativo e qualitativo ressaltando a importância do code review como uma atividade fundamental na compreensão do código, bem como os comentários contidos neste, o qual também tem papel de transmissão de conhecimento entre os desenvolvedores. A partir disto é analisada a relação entre ambos, mostrando a relevância de revisões em cima da documentação do código, tendo em foco a realizada através dos comentários, e o impacto que isto gera em torno da compreensão do código. Sendo assim, o artigo traz como metodologia a coleta de dados de _pull request_ dos 1000 projetos, do GitHub, mais comentados durante as revisões, para as linguagens Java e Python, dos quais foram pegos para análise 700 mil comentários de revisão. Após a coleta, realizaram a filtragem e agrupamento dos dados de acordo com sua possível intenção de modificação. A partir da obtenção dos resultados foi possível perceber que: os revisores de código consideram a documentação de código durante o code review, visto que 55,8% dos comentários totais selecionados discutiam algo relacionado à documentação; a maior parte dos comentários visam esclarecimento do código para eles ou para futuros leitores, isto pois 70/134 avaliaram a clareza descrita; os desenvolvedores realizam as alterações solicitadas a partir do code review realizado, isto se deve ao fato que 76,4% dos comentários levaram à alguma alteração no código.

## 2. Fichamento Bibliográfico 

* _Taxonomy_ (Taxonomia) é uma disciplina biológica que define os grupos com base em características comuns e realiza a nomenclatura destes grupos (página 1)  .
* _Coalescence_ (Coalescência) é uma palavra utilizada para aferir um ponto de relação entre dois fatores, utilizado para identificá-lo sobre code review e documentação (página 1).
* _Diff Chunks_ (Pedaços de diferença) termo utilizado para representar os trechos de código com alguma mudança evidenciados durante o processo de code review  (página 2).
* _Comments on Comments_ (Comentários sobre comentários) é a definição dada à comentários realizados durante o processo de Code Review sobre a documentação feita dentro do próprio código, como comentários ou arquivos de documentação (página 2).
* _Clopper-Pearson method_ (Método de Clopper-Pearson) é uma maneira de calcular intervalos de confiança binomial utilizando aproximação normal, muito comum para encontrar intervalos de confiança (página 4).

## 3. Fichamento de Citações 

* _"A central function of code review is to increase understanding; helping reviewers understand a code change aids in knowledge transfer and finding bug"_
* _"Code review is an important mechanism for preventing bugs in software projects"_
* _"Reviewers frequently consider documentation when reviewing code. They are more likely to comment when contributors updated code comments initially."_
* _"Review comments in response to a code comment change often result in the code comment getting updated"_
* _"Most reviewer comments seek some form of clarification to increase or enshrine their understanding of the change made to the code, followed by fixing issues in the comments themselves"_
* _"A shared understanding of code is vital in open source project maintenance"_
* _"Code review is a key mechanism for transferring knowledge"_
