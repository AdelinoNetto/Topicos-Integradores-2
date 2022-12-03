1. Quais os tipos de aprendizagem de máquina e suas definições.
R: Aprendizado de máquina supervisionado, Aprendizado de máquina não supervisionado e Aprendizado por reforço.

2. Para cada tipo de aprendizagem de máquina apresente um exemplo que se encaixa com a sua definição.
R: Aprendizado de máquina supervisionado
O aprendizado supervisionado é um paradigma de aprendizado de máquina, que tem como objetivo adquirir informações de relacionamento entre entrada e saída de um sistema, baseado em um conjunto de amostras de treinamento. 
Exemplo: Algoritmos de aprendizado supervisionado analisam dados de treinamento e geram funções de inferência que serão usadas para mapear novos exemplos. Vamos considerar um exemplo, classificando e-mails como spam. Você provavelmente usa e-mail e sabe que o conteúdo malicioso quase sempre é enviado para uma pasta específica para sua proteção. Mas como isso acontece. Um modelo de classificação baseado em entradas sinalizadas fornece uma experiência que evita que você tenha que classificar quais e-mails são maliciosos ou não. Entre essas entradas, classificamos os e-mails como confiáveis ​​ou não confiáveis, para que o modelo aprenda a reconhecer a categoria a que os novos dados pertencem com base no que já sabe sobre esses dados rotulados.

Aprendizado de máquina não supervisionado
O aprendizado não supervisionado consiste em treinar uma máquina a partir de dados que não estão rotulados e/ou classificados. Os algoritmos que fazem isso buscam descobrir padrões ocultos que agrupam as informações de acordo com semelhanças ou diferenças
Exemplo: Para que isso fique mais claro, vamos imaginar um algoritmo de aprendizado não supervisionado, que receba uma imagem contendo cachorros e gatos. Ao receber essa imagem nada se sabe sobre as características que cada animal possui, ou seja, não é possível categorizá-los. Porém, esse algoritmo será responsável por descobrir semelhanças, padrões ou diferenças que permitam diferenciar cães e gatos. 
Utilizamos uma técnica chamada de agrupamento (Clustering), porém existem outras técnicas como regras de associação (Association Rules) e redução de dimensionalidade (Dimensionality Reduction). Falaremos um pouco de cada uma delas abaixo. 
Agrupamento
A técnica de agrupamento como explicado no exemplo anterior, consiste em agrupar dados não rotulados com base em suas semelhanças ou diferenças.  Esses algoritmos de agrupamento ainda podem ser subdivididos em agrupamentos exclusivos, sobrepostos, hierárquicos e probabilísticos.
Regras de Associação
Ao usar as regras de associação, buscamos descobrir relações que descrevem grandes porções dos dados. A associação é muito utilizada em análises de cestas de compras, no qual a empresa pode tentar entender relações de preferências de compras entre os produtos.
Quando falamos de algoritmos para gerar regras de associação os principais são: Apriori, Eclat e FP-Growth.
Redução de dimensionalidade
Existem casos nos quais ao estudar um conjunto de dados, podemos encontrar nele um grande número de recursos (dimensões). Por mais que existam situações onde isso é positivo, o excesso pode impactar o desempenho dos algoritmos causando, por exemplo, o overfitting. 
Utilizando a técnica de redução de dimensionalidade, será feita uma redução no número de recursos, de forma que torne-os gerenciáveis por parte do modelo, além de preservar a integridade dos dados.
Aprendizado por reforço
Exemplo: Por fim, existe o aprendizado reforçado, no qual a máquina opera pautada em experiência. Nesse processo, ela lida com o erro e, depois, procura a abordagem correta para corrigi-lo e não o cometer novamente. 
O processo de aprendizado por reforço não acontece apenas uma vez. Na verdade, a máquina pode tentar diferentes soluções até encontrar a mais adequada para o problema que está lidando. 
Carros automáticos, softwares que traçam relatórios do mercado financeiro, projeções sobre determinado cenário e a ferramenta de indicação de vídeos do YouTube são alguns exemplos de aprendizagem reforçada. 


