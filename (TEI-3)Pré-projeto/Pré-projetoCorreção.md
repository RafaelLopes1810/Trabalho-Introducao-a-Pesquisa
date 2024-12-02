# Título do trabalho

* Rafael de Oliveira Caldeira Lopes
* Arthur Nunes Gontijo de Barcellos
* Carlos Magno Ferreira Silva
* Lesandro Ponciano dos Santos (orientador de acadêmico)

## Introdução

1. A área da Engenharia de Software tratada neste trabalho é o uso de ferramentas de inteligência artificial generativa para auxiliar alunos de graduação no aprendizado de programação.
1. O problema que este trabalho busca resolver nessa área é o quão eficiente é o estudo autônomo de programação, usando ferramentas de IA generativa, comparado ao estudo autônomo usando conteúdo de vídeos on-line?
1. Resolver este problema é relevante por que com o crescente acesso a ferramentas de IA generativa e à vasta quantidade de conteúdo educacional disponível online, é fundamental entender qual abordagem é mais eficaz para o estudo autônomo de programação. Identificar se o uso de IA generativa pode proporcionar um aprendizado mais eficiente, em comparação com o uso de vídeos online, pode ajudar a otimizar o processo de ensino, melhorar a retenção de conhecimento e fornecer diretrizes para o desenvolvimento de recursos educacionais mais eficazes para estudantes de programação.
1. O objetivo geral deste trabalho é medir o quão eficaz é o uso do ChatGPT para melhorar o aprendizado de programação de software entre estudantes de graduação.
1. Os *três* objetivos específicos deste trabalho são:
•Avaliar a eficácia do ChatGPT para o ensino de conceitos de programação entre alunos de graduação.
•Comparar o desempenho de alunos de graduação que utilizam o ChatGPT para geração assistida de código com aqueles que usam vídeo aulas.
•Analisar a retenção de conhecimento e a capacidade de resolver problemas complexos dos alunos após o uso do ChatGPT para aprendizado de programação.

## Fundamentação Teórica

1. O conceito principal associado a este trabalho é Inteligência Artificial. A sua definição neste trabalho é conforme definido no trabalho _"A Review on Artificial Intelligence with Deep Human Reasoning"_ [10.1109/ICAAIC53929.2022.9793310](https://ieeexplore.ieee.org/document/9793310) pelo autor Harika, Janmanchi do _"Department of Artificial Intelligence and Data Science, Vardhaman College of Engineering"_ onde fala: "A inteligência artificial (IA) é um termo amplo que pode ser interpretado como o foco no desenvolvimento e programação de computadores projetados para treinar máquinas e realizar tarefas. A inteligência artificial pode ser usada para testar teorias de raciocínio, como raciocínio cognitivo e consciência."
2. O segundo conceito associado a este trabalho é Ferramentas de IA generativa (ChatGPT). A sua definição neste trabalho é conforme definido no trabalho _"Does ChatGPT Help With Introductory Programming? An Experiment of Students Using ChatGPT in CS1"_ [10.1145/3639474.3640076](https://ieeexplore.ieee.org/document/10554703) pelo autor Xue, Yuankai de _Vanderbilt University, Tennessee, USA_, fala que: "Os avanços rápidos no aprendizado de máquina e no processamento de linguagem natural (_Natural Language Processing NLP_) deram origem a inovações revolucionárias, entre as quais a IA generativa se destaca. A IA generativa utiliza modelos de aprendizado profundo para gerar uma variedade de respostas semelhantes às humanas, por meio de prompts diversos e complexos. Impulsionado pela IA generativa, o ChatGPT alcançou amplo reconhecimento e tem sido usado como um dos principais modelos de IA conversacional."
3. O conceito terciário associado a este trabalho é de Estudos autônomos. A sua definição neste trabalho é conforme definido no trabalho _"College Students' Autonomous Learning Behavior in Blended Learning: Learning Motivation, Self-Efficacy, and Learning Anxiety"_ [10.1109/ISET49818.2020.00042](https://ieeexplore.ieee.org/document/9215481) pelo autor Bai, Xue de _Co-innovation Center of Informatization and Balanced Development of Basic Education, Central China Normal University, Wuhan, China_ fala que: "O aprendizado autônomo, também conhecido como aprendizado autorregulado, refere-se a pensamentos, sentimentos e comportamentos autogerados que são orientados para a conquista de objetivos durante o processo de aprendizado autônomo."
4. O quarto conceito associado a este trabalho são os Vídeos Educativos. A sua definição neste trabalho é conforme definido no trabalho _"Adaptive Video Learning by the Interactive E-partner"_ [10.1109/DIGITEL.2010.54](https://ieeexplore.ieee.org/document/5463770) pelo autor Chang, Chia-Hu de _Graduate Institute of Networking and Multimedia, National Taiwan University, Taiwan_ fala que: "Cada vez mais jogos e vídeos são projetados com propósitos educacionais, o que pode ajudar os estudantes a construir seu próprio conhecimento, melhorar sua capacidade de resolver problemas ou treiná-los para desenvolver um pensamento de ordem superior, em vez de se limitarem à memorização mecânica ou à simples compreensão. Consequentemente, os estudantes não apenas podem se divertir jogando ou assistindo a vídeos, mas também podem aprender em um ambiente virtual."

## Trabalhos Relacionados

1. O trabalho mais relacionado é "Students’ Experiences of Using ChatGPT in an Undergraduate Programming Course" [10.1109/ACCESS.2024.3380909](https://doi.org/10.1109/ACCESS.2024.3380909), publicado no ano 2024, por que ele analisa a experiencia e feedback dos estudantes de um curso de programação, com foco no uso do ChatGPT para auxiliar seu aprendizado.
2. O segundo trabalho mais relacionado é "Does ChatGPT Help Novice Programmers Write Better Code? Results From Static Code Analysis" [10.1109/ACCESS.2024.3445432](https://doi.org/10.1109/ACCESS.2024.3445432), publicado no ano 2024, por que ele investiga o impacto do ChatGPT na qualidade do codigo dos estudantes de um curso de programação.
3. O terceiro trabalho mais relacionado é "Can Autograding of Student-Generated Questions Quality by ChatGPT Match Human Experts?" [10.1109/TLT.2024.3394807](https://doi.org/10.1109/TLT.2024.3394807), publicado no ano 2024, por que ele investiga a capacidade do ChatGPT de realizar uma avaliação automatica de perguntas criadas por estudantes, para analisar o nivel de compreensão dos estudantes, comparando sua performance com a de especialistas humanos.

## Materiais e Métodos

1. O tipo de pesquisa adotado neste trabalho é quantitativa, pois será realizada uma investigação com base em dados numéricos obtidos através da análise do desempenho de 40 estudantes divididos em dois grupos. O aprendizado de cada grupo será medido com base na média aritmética dos acertos dos alunos em um questionário, após o período de estudo. A abordagem quantitativa é indicada em pesquisas de avaliação de métodos pedagógicos, pois possibilita a obtenção de resultados mensuráveis e comparáveis (Creswell, 2014).
2. Materiais utilizados:
Os tópicos abordados durante o estudo são recursividade e estruturas de dados como pilhas, filas e listas. Esses tópicos são comumente tratados no ensino de algoritmos e programação (Knuth, 1997), sendo fundamentais para o desenvolvimento do pensamento lógico e a compreensão de algoritmos eficientes.
Para o grupo 1, será utilizada a ferramenta ChatGPT como assistente de estudo, baseada em IA generativa, uma tecnologia que tem mostrado resultados promissores em tutoria personalizada (Vaswani et al., 2017).
Já o grupo 2 utilizará o YouTube como fonte de estudo, a partir de videoaulas sobre os mesmos tópicos. A utilização de videoaulas no processo de aprendizagem tem sido amplamente discutida, sendo apontada como uma ferramenta eficaz para a compreensão de conteúdos complexos (Berk, 2009).
3. Métodos empregados:
O método de amostragem utilizado neste estudo será o sorteio aleatório dos 30 participantes, o que garante uma distribuição imparcial entre os dois grupos e assegura a representatividade da amostra (Kothari, 2004).
O método de ensino assistido será a principal estratégia pedagógica, com o grupo 1 utilizando o ChatGPT como ferramenta de estudo assistido por IA e o grupo 2 utilizando o YouTube. Ambos os métodos têm se mostrado eficazes em diversos contextos educacionais, com o uso de IA aumentando a personalização e a interatividade no aprendizado (Luckin et al., 2016), e o uso de videoaulas sendo eficaz na promoção do aprendizado autônomo (Garrison, 2011).
A avaliação por questionário será realizada após o período de estudo, para medir a retenção de conhecimento e o desempenho dos estudantes em relação aos tópicos abordados. A aplicação de questionários pós-intervenção é uma prática comum em pesquisas educacionais para avaliar a eficácia de diferentes métodos de ensino (Liu et al., 2016).
A análise estatística será realizada para comparar os resultados dos dois grupos, calculando a média aritmética das pontuações obtidas. A utilização de testes estatísticos para comparar médias é uma prática padrão em estudos quantitativos, possibilitando a identificação de diferenças significativas entre os grupos (Field, 2013).
O método comparativo será utilizado para comparar os resultados de aprendizagem dos dois grupos, com o objetivo de identificar as possíveis vantagens de um método de ensino sobre o outro, com base nas médias de acertos e nas análises estatísticas.
4. Métricas de avaliação:
A principal métrica de avaliação será a taxa de acertos, que mede a porcentagem de acertos de cada grupo em relação ao total de questões do questionário. A taxa de acertos é uma métrica amplamente utilizada em avaliações de desempenho acadêmico (Pintrich, 2003).
5. Etapas de execução:
Seleção dos participantes.
Aplicação do teste 1
Divisão por notas dos participantes em dois grupos, com os seus respectivos temas.
Período de estudo dos tópicos (recursividade e estruturas de dados).
Aplicação do teste 2.
Análise da média dos resultados de cada aluno, com o respectivo grupo.
Comparação dos resultados das análises entre os dois grupos.
