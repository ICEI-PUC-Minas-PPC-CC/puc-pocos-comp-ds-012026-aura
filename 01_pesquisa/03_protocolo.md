# Protocolo

Definimos o protocolo desta pesquisa para garantir que tudo seja feito de forma organizada, transparente e possa ser repetido sem problemas. Para isso, dividimos o processo em etapas independentes, o que significa que qualquer resultado pode ser obtido novamente executando o arquivo principal `pipeline.py`.

## Tipo de pesquisa

Estamos fazendo uma pesquisa aplicada, que é do tipo quantitativa e experimental. O objetivo é criar e avaliar modelos que possam prever se um crédito bancário deve ser concedido ou não.

## Estratégia metodológica

Usamos a abordagem de pipeline de ciência de dados, que é uma sequência de etapas que podem ser repetidas. Essas etapas incluem análise exploratória, pré-processamento, engenharia de atributos, treinamento e avaliação dos modelos. Para comparar os algoritmos, usamos uma técnica chamada validação cruzada estratificada com 5 partições, o que garante que as classes sejam proporcionalmente representadas em cada parte.

## Etapas previstas

- Análise exploratória dos dados (EDA) — é feita no arquivo `01_exploracao.ipynb`
- Pré-processamento e engenharia de atributos — é feito no arquivo `02_preprocessamento.ipynb`
- Treinamento dos modelos — é feito no arquivo `03_modelagem.ipynb`
- Avaliação e comparação dos resultados — é feita no arquivo `04_avaliacao.ipynb`

 
## Critérios de busca e seleção

Usamos um conjunto de dados público chamado *Loan Prediction Problem Dataset*, que está disponível na plataforma Kaggle. Esse conjunto de dados tem 614 instâncias e 12 atributos socioeconômicos. Escolhemos esse conjunto de dados porque está disponível publicamente, tem variáveis financeiras relevantes e é adequado para o problema de classificação binária que estamos estudando.
