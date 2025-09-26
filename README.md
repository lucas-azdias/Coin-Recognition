# Coin Recognition

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lucas-azdias/Coin-Recognition/blob/main/Coin%20Recognition.ipynb)

## Team (Integrantes)
- Lucas Azevedo Dias
- Guilherme Henrique de Lara Peres
- Henrique Anderle Schulz
- Pedro Lucas Ghezzi Bittencourt
- Rafaela de Miranda
- Victor Portelinha

## Overview
Coin recognition project using Computer Vision, aiming to correctly identify **European coins** in images.  
Both **shallow learning models** and **deep learning models** were trained in order to compare their performance, with experiments carried out on segmented images obtained through image processing techniques.

## Visão Geral
Projeto de reconhecimento de moedas utilizando Visão Computacional, com o objetivo de identificar corretamente **moedas europeias** em imagens.
Assim, são treinados **modelos rasos** e **modelos profundos** para comparação dos métodos e com testes realizados em segmentações com processamento de imagens.

## Dataset
Foi utilizado o dataset `EURO coins` com 150 imagens disponível no [Kaggle](https://www.kaggle.com/datasets/janstaffa/euro-coins-dataset) e na pasta `dataset`.
Onde, para cada imagem do dataset, pode haver mais de uma moeda de diferentes classes com ou sem sobreposição parcial entre elas.

## Abordagens Utilizadas

### Shallow Learning
- Modelos: Logistic Regression e RandomForest;
- Convoluções: HOG e Local Binary Patterns.

### Deep Learning
- Modelos: CNN própria e EfficientNetB0;
- Entrada: imagem bruta (sem necessidade de extração manual de features).
