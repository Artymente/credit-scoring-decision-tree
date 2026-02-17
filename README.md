# Modelagem de Credit Scoring com Árvores de Decisão

Este projeto faz parte do curso "Profissão: Cientista de Dados" (Módulo 21) e tem como foco a criação de um modelo de classificação de score de crédito para suporte à concessão de empréstimos, utilizando técnicas avançadas de Machine Learning.

## 🎯 Objetivo
Desenvolvimento de um modelo preditivo de **Credit Scoring** utilizando **Python** e a biblioteca **Scikit-Learn**. O projeto realiza a transição de modelos estatísticos simples para o algoritmo de **Árvores de Decisão (Decision Tree Classifier)**, buscando identificar perfis de risco com maior precisão e interpretabilidade.

**Skills e Palavras-chave:**
* **Linguagens e Libs:** Python, Pandas, Scikit-Learn, Matplotlib, Seaborn.
* **Machine Learning:** Árvores de Decisão, Naive Bayes (comparativo), Avaliação de Modelos.
* **Processamento de Dados:** Balanceamento de classes, Tratamento de variáveis categóricas, Feature Engineering.
* **Métricas:** Acurácia, F1-Score, Recall, Matriz de Confusão.

---

## 🛠️ Etapas do Projeto
1.  **Pré-processamento:** Limpeza e tratamento de bases de dados de crédito (treino e teste).
2.  **Análise de Dados:** Exploração de variáveis críticas como renda, idade e escolaridade.
3.  **Modelagem:** Implementação do `DecisionTreeClassifier` para categorizar o nível de crédito do cliente.
4.  **Avaliação:** Análise detalhada de desempenho e comparação com o algoritmo Naive Bayes.
5.  **Visualização:** Plotagem da estrutura da árvore de decisão para análise de regras de negócio.



---

## 📊 Resultados Obtidos
A Árvore de Decisão apresentou um desempenho superior no equilíbrio entre as classes, atingindo:
* **Acurácia e F1-Score (ponderado):** 0.98.
* **Destaque:** Melhoria significativa no *Recall* para perfis de crédito específicos em comparação ao modelo Naive Bayes utilizado anteriormente.

---

## 📂 Estrutura do Repositório
* `Profissao Cientista de Dados M21 Pratique.ipynb`: Notebook principal com todo o código e análises.
* `requirements.txt`: Lista de bibliotecas necessárias para rodar o projeto.
* `x_train_balanced.csv` / `y_train_balanced.csv`: Bases utilizadas para o treinamento do modelo.