# Bioinformática 2023/2024
###### Mestrado em Engenharia Biomédica, Universidade do Minho

## Dataset 3 - Brain Lower Grade Glioma
### Descrição
Neste dataset encontram-se **530 amostras** de pacientes portadores de gliomas, sendo este, no fundo, composto por 3 datasets diferentes data_patient, data_sample e data_glioma.

No dataset **data_patient**, podem ser observados atributos relativos a históricos clinicos de **515 pacientes**, bem como o seu diagnostico e o desfecho do seu caso.

Relativamente ao dataset **data_sample**, verifica-se a presença de informações relativas às dimensões da amostra e à sua natureza.

Por fim, no dataset **data_glioma** averigua-se a expressão de cada um dos genes considerados para cada amostra obtida.

### Acesso
Dataset disponível em: https://www.cbioportal.org/study/summary?id=lgg_tcga 


### Metodologia
Para a execução deste projeto foram utilizadas técnicas de **análise de dados**, **redução de dimensionalidade**, **_clustering_** e **_Machine Learning_ (ML)**. Estando o processo dividido em 3 etapas fundamentais:

#### Etapa 1: 
Esta primeira etapa consiste, fundamentalmente, no carregamento e compreensão dos dados, identificação e tratamento de valores em falta, análises gráficas de metadados, avaliação de correlações e seleção de atributos.

#### Etapa 2:
Na etapa seguinte tem-se análises de variabilidade, redução de dimensionalidade e aplicação de métodos de _clustering_.

#### Etapa 3:
Por fim, é efetuada a aplicação de algoritmos de aprendizagem supervisionada recorrendo a métodos de partição de dados distintos. Nesta etapa, são utilizados 4 algoritmos de ML (_Decision Trees_, _Random Forest_, _Naive Bayes_ e _Suport Vector Machine_ (SVM)) e dois tipos de partição de dados (_Split Data_ e _Cross Validation_).


### Objetivos
Como objetivos principais do projeto tem-se:

- a obtenção de **_insights_ valiosos sobre a relação entre os graus de agressividade dos gliomas e genética**;
- o **desenvolvimento de modelos preditivos capazes de identificar o grau de agressividade de gliomas** a partir das suas características associadas.

Deste modo, e em caso de sucesso, este seria um caminho possível para a aplicação de sistemas de auxílio ao diagnóstico não evasivo, fundamentais para determinar o prognóstico e orientar as opções de tratamento.

#
### Grupo 5
  Diana Azevedo, PG53488

  Lara Martins, PG53490

  Madalena Passos, PG54023

  Tayan Peller, PG54451




