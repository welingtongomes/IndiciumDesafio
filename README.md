# IndiciumDesafio

# Equipe: Welington Henrique de Almeida Gomes

# Dataset: teste_indicium_precificacao (https://drive.google.com/file/d/122b3O7GoH2pouBcx411M1h0qegZytNpo/view?usp=drive_link)

# Objetivos 

Faça uma análise exploratória dos dados (EDA), demonstrando as principais características entre as variáveis e apresentando algumas hipóteses de negócio relacionadas. Seja criativo!

Responda também às seguintes perguntas:
Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, onde seria mais indicada a compra?
O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?

Existe algum padrão no texto do nome do local para lugares de mais alto valor?

Explique como você faria a previsão do preço a partir dos dados. Quais variáveis e/ou suas transformações você utilizou e por quê? Qual tipo de problema estamos resolvendo (regressão, classificação)? Qual modelo melhor se aproxima dos dados e quais seus prós e contras? 

Qual medida de performance do modelo foi escolhida e por quê?

Supondo um apartamento com as seguintes características:

{'id': 2595,
 'nome': 'Skylit Midtown Castle',
 'host_id': 2845,
 'host_name': 'Jennifer',
 'bairro_group': 'Manhattan',
 'bairro': 'Midtown',
 'latitude': 40.75362,
 'longitude': -73.98377,
 'room_type': 'Entire home/apt',
 'price': 225,
 'minimo_noites': 1,
 'numero_de_reviews': 45,
 'ultima_review': '2019-05-21',
 'reviews_por_mes': 0.38,
 'calculado_host_listings_count': 2,
 'disponibilidade_365': 355}

Qual seria a sua sugestão de preço?

# Instalação e Execução 

Para execução no google colab, basta realizar os comandos de importações à seguir:

* import pandas as pd
* import numpy as np
* import seaborn as sns
* import matplotlib.pyplot as plt
* from ydata_profiling import ProfileReport
* from sklearn.model_selection import train_test_split
* from sklearn.tree import DecisionTreeRegressor
* from sklearn.metrics import mean_squared_error

Para executar localmente, faz-se necessária instalação das bibliotecas, por favor, realize os os passos abaixo:

Abra o CMD;

Digite: pip install python e aguarde a instalação;

Digite: pip install pandas e aguarde a instalação;

Digite: pip install numpy e aguarde a instalação;

Digite: pip install seaborn e aguarde a instalação;

Digite: pip installmatplotlib e aguarde a instalação;

Digite: pip install ydata_profiling e aguarde a instalação;

Digite: pip install scikit-learn e aguarde a instalação;
