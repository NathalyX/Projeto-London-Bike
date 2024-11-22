# Projeto London Bike - Análise da quantdade de alugueis de bicicletas realizados em um período utilizando séries temporais


 Estamos atuando como analista de dados na empresa de aluguel de bicicletas London Bike**, de Londres, procurando, após tratar a base de dados, entender quais fatores afetam a demanda por bicletas. Com esses dados**, podemos criar planos de ação especíicos para atender a clientela. 

 Também foi criado, testado e ajustado um modelo que preveja a quantidade de bicicletas serão alugadas no dia ou me mês seguinte, com base em uma análise de série temporal.

 ** _Situação fictícia, projeto feito com base no curso da escola **Alura**_


 ## **Metodologia**

Para isso, passaremos pelas etapas:
 - Importação dos dados: Extração dos dados direto de sua fonte (Arquivo CSV)
 - Preparação de dados: Identificação e tratamento de dados nulos, vazios e duplicados
 - Análise exploratória: Análise das principais características e identificação de padrões e relações utilizando-se mapa de calor para observação da correlação de pearson, histogramas e boxplot, além de estatística descritiva.
 - Criação de modelo preditivo e análise de série temporal para identificação do comportamento do aluguel de bicicletas nos próximos dias, meses ou ano.


 ## **Tecnologias**

 O projeto foi realizado utilizando Python (Python 3.10.12), principalmente bibliotecas Pandas, Numpy, matplotlib e Prophet, em um Jupyter Notebook. 

 ## **Conclusões**

 Durante a análise exploratória, em relação às variáveis numéricas, foi possível observar diferentes comportamentos em relação a cada variável. Pode-se notar que, o número de alugueis de bicicletas foi maior em temperaturas e sensação térmica entre 10 e 15°C. Já com relação à umidade e velocidade do vento, apesar de se mostrarem distribuídas normalmente, apresentam distorções para direita e esquerda, respectivamente. Assim, percebemos que a contagem de alugueis se mostra maior quando a umidade está entre 70 e 80% e quando a velocidade do ar está entre 10 e 20km/h.

 Com relação às variáveis categóricas, foram analisadas: feriados, finais de semana, clima e estação. Foram observados mais alugueis durante dias da semana, ao contrário de finais de semana e feriados. Isso se dá tanto pelas maiores quantidades de dias normais em um ano, quanto pela utilização, já que observando os horários nessas ocorrências, percebe-se que se encontram principalmente as 8h da manhã e as 18h da tarde, coincidindo com o horário comercial e letivo. Com relação ao clima e estação do ano, encontramos maiores quantidades de alugueis no verão e em climas de céu limpo ou parcialmente nublado, situações mais favoráveis a um passeio ou transporte de bicicleta. 
 
 Considerando que estamos tratando de dados relativos à outra localidade (Londres), temos que nos ater às médias dessas variáveis em território europeu. Tendo isso como base, os resultados se encontram plausíveis e de acordo com a realidade.
 
 O modelo de série temporal construído foi ajustado apresentando uma previsão compatível com a realidade e componentes.

 
