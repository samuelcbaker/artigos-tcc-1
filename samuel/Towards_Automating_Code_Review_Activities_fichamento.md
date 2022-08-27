# Towards Automating Code Review Activities

R. Tufano, L. Pascarella, M. Tufano, D. Poshyvanyk and G. Bavota, "Towards Automating Code Review Activities," 2021 IEEE/ACM 43rd International Conference on Software Engineering (ICSE), 2021, pp. 163-174, doi: [10.1109/ICSE43902.2021.00027](https://doi.org/10.1109/ICSE43902.2021.00027).

## 1. Fichamento de Conteúdo

O artigo tem o objetivo de propor uma _DP_ (do inglês, _Deep Learning_) para automatizar parcialmente o processo de revisão de código. A ideia não é substituir o processo manual onde os desenvolvedores analisam o código, mas complementar essa tarefa dando sugestões de alterações para os revisores e contribuidores do projeto, fazendo com que esse processo tenha menor custo. Para os contribuidores, a ferramenta desenvolvida propõe possíveis alterações no código antes que ele confirme a abertura do _Pull Request_, dando a possibilidade do desenvolvedor descobrir uma possível melhoria antes de enviar o pacote para revisão. Já para os revisores, a ferramenta busca sugerir um código a partir de um comentário feito em linguagem natural. Os códigos analisados e estudados pelos modelos da _DP_ (do inglês, _Deep Learning_) foram extraídos do _GitHub_ e _Gerrit_ na linguagem Java e depois foram submetidos a um refinamento pela ferramenta chamada de _src2abs_. Os resultados da _DP_ foram avaliados utilizando o método de _BLEU score_ e foi concluído que a ferramenta possui a capacidade de gerar recomendações significantes para os contribuidores em até 16% e para os revisores em até 31% dos casos analisados. Esses resultados mostram que a pesquisa ainda precisa evoluir para que o aproveitamento da ferramenta seja mais assertivo, possibilitando o seu uso de maneira prática por parte dos desenvolvedores. Vale ressaltar que os autores pretendem explorar diferentes arquiteturas de _DL_ para melhorar os resultados da ferramenta de automação.

## 2. Fichamento Bibliográfico

- _Code Review_ (revisão de código) é o processo de análise de código do time para decidir se o mesmo pode ser vinculado a código fonte principal (página 1).
- _Contributor_ (contribuidor) é o desenvolvedor que submete um código para o processo de _code review_ (página 1).
- _Reviewer_ (revisor) é o indivíduo que revisa o código enviado para análise no _code review_ (página 1).
- _Noisy comments_ (comentários barulhentos) são comentários feitos no _code review_ que são improváveis de resultar em mudanças no código (página 4).
- _BLEU score_ é uma métrica para avaliação do texto gerado automaticamente por uma tarefa de NMT (do inglês _Neural Machine Translation_) (página 6).
- _Reference code_ (código referência) é o código escrito manualmente pelo desenvolvedor (página 7).

## 3. Fichamento de Citações

- _"The benefits of code reviews are widely recognized and include better code quality and lower likelihood of introducing bugs."_
- _"Code Review is the process of analyzing source code written by a teammate to judge whether it is of sufficient quality to be integrated into the main code trunk."_
- _"Given these benefits, code reviews are widely adopted both in industrial and open source projects with the goal of finding defects, improving code quality, and identifying alternative solutions."_
- _"The BLEU score is a metric used for assessing the quality of text automatically generated in the context of a NMT task."_
