# Predição de Fraudes em Anúncios de Emprego com Comitê de Classificadores

Este repositório contém o código-fonte utilizado no artigo submetido ao **SIMPEP 2025**, cujo objetivo foi desenvolver um sistema de apoio à decisão para identificar fraudes em anúncios de emprego utilizando técnicas de aprendizado de máquina supervisionado e ensemble learning.

## 🧠 Objetivo

Avaliar a eficácia de um comitê de classificadores supervisionados (Decision Tree, Logistic Regression, Naive Bayes, KNN e SVM), combinados por votação, na predição de fraudes em uma base textual desbalanceada.

## 📁 Conteúdo

- `20250619 Comite.ipynb`: Notebook Jupyter contendo todas as etapas do projeto, incluindo:
  - Pré-processamento textual com TF-IDF
  - Treinamento individual dos classificadores
  - Avaliação por métricas como acurácia, F1-score e matriz de confusão
  - Consolidação das predições por comitê via votação

## 📊 Base de dados

Utiliza a base pública **"Real or Fake Job Posting Prediction"**, disponível no Kaggle:
[https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)

## 🛠️ Requisitos

Crie um ambiente com Python 3.8+ e instale os pacotes com:

```bash
pip install -r requirements.txt
