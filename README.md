# Modulo06Tarefa2
Este projeto conclui o estudo de visualização exploratória no Módulo 6, focando na análise da distribuição de variáveis contínuas da base de dados do SINASC de Rondônia (2019).

O objetivo principal foi empregar Boxplots e Histogramas para entender a centralidade, a dispersão e a presença de valores atípicos (outliers) nas variáveis cruciais IDADEMAE e PESO.

Ferramentas Utilizadas
Pandas: Carregamento e manipulação do DataFrame.

Seaborn/Matplotlib: Criação das visualizações estatísticas.

Tarefas Executadas e Análise
As quatro questões da Tarefa 2 focaram em gerar visualizações para responder a perguntas sobre o formato dos dados:

1. Boxplot da Idade da Mãe (IDADEMAE)
Gráfico: sns.boxplot.

Análise: Mostra a mediana da idade e os outliers (casos de gravidez na adolescência ou tardia).

2. Boxplot do Peso do Bebê (PESO)
Gráfico: sns.boxplot.

Análise: Identifica a faixa de peso central (entre o 25º e 75º percentil) e destaca os outliers de baixo peso ao nascer, que são clinicamente importantes.

3. Histograma da Idade da Mãe (IDADEMAE)
Gráfico: sns.histplot (com kde=True).

Análise: Revela a forma da distribuição. O gráfico mostra o pico da frequência (a idade mais comum para partos) e a assimetria da distribuição.

4. Histograma do Peso do Bebê (PESO)
Gráfico: sns.histplot (com kde=True).

Análise: Visualiza a frequência de nascimentos por faixa de peso. O kde ajuda a confirmar se a distribuição do peso segue um padrão aproximadamente normal (curva em formato de sino).
