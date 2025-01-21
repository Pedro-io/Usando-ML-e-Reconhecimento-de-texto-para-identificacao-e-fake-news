# Classificação de Textos com Naive Bayes

Este repositório contém o código e a documentação de um projeto que utiliza o algoritmo Naive Bayes para classificar notícias como "reais" ou "falsas". O objetivo principal é combater a desinformação, proporcionando um modelo simples e eficiente para análise de textos.

## Objetivo

Construir e avaliar um modelo de classificação de textos utilizando Naive Bayes, com foco na identificação de notícias falsas, com base em técnicas de aprendizado de máquina e pré-processamento textual.

## Funcionalidades

- Pré-processamento de textos:
  - Tokenização
  - Remoção de stop words
  - Stemming
- Transformação dos textos: Vetorização usando TF-IDF.
- Modelo de Machine Learning:
  - Classificador Naive Bayes multinomial.
  - Otimização de hiperparâmetros com GridSearchCV.
- Avaliação do modelo:
  - Relatório de classificação (precision, recall e F1-score).
  - Matriz de confusão.

## Resultados

- Acurácia: 60,21%.
- Relatório de Classificação:
  - Classe "Fake": 67% de precisão.
  - Classe "Real": 55% de precisão.
- Matriz de Confusão:
  - Exemplos classificados corretamente e incorretamente para cada classe.

## Metodologia

1. Pré-processamento de Texto: Conversão dos textos para tokens limpos e reduzidos.
2. Vetorização com TF-IDF: Conversão de textos para representações numéricas baseadas na importância das palavras.
3. Treinamento e Avaliação do Modelo: Treinamento do Naive Bayes e análise do desempenho com métricas padrão.

## Melhorias Futuras

- Aumentar o conjunto de dados: Incorporar textos de mais temas para melhorar a generalização.
- Testar outros algoritmos: Experimentar com modelos como SVM, Random Forest ou redes neurais.
- Aprimorar o pré-processamento: Usar lematização e embeddings de palavras para capturar melhor o significado semântico.


## Tecnologias Utilizadas

- Linguagem: Python
- Bibliotecas:
  - scikit-learn
  - NLTK
  - pandas
  - numpy

## Referências

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Kaggle: Sentiment Analysis in Portuguese](https://www.kaggle.com/code/leandrodoze/sentiment-analysis-in-portuguese/notebook)




