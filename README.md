# Projeto de Detecção de Fraudes em Cartões de Crédito usando Regressão Logística

## Introdução
Com o avanço da tecnologia e o uso crescente de cartões de crédito para transações financeiras, a detecção de fraudes tornou-se um desafio crítico.
As técnicas de aprendizado de máquina oferecem soluções poderosas para analisar grandes conjuntos de dados e identificar padrões indicativos de comportamentos fraudulentos. 
Este projeto tem como foco o desenvolvimento de um modelo de Regressão Logística para detectar transações fraudulentas de forma eficiente.

## Objetivo
O principal objetivo deste projeto é construir um modelo de Regressão Logística capaz de diferenciar com precisão entre transações legítimas e fraudulentas.
A Regressão Logística é adequada para problemas de classificação binária, tornando-se uma escolha ideal para a tarefa de detecção de fraudes.

## Fluxo de Trabalho e Ferramentas

  ### Manipulação e Visualização de Dados:
  * Pandas: Manipulação e pré-processamento dos dados.
  * Seaborn e Plotly: Visualização das distribuições, relacionamentos e padrões nos dados.
  
  ### Tratamento do Desbalanceamento de Classes:
   * Reamostragem: Correção do desbalanceamento usando técnicas como SMOTE (Synthetic Minority Oversampling Technique).
  
  ### Desenvolvimento e Avaliação do Modelo:
  * Statsmodels: Construção do modelo de Regressão Logística e avaliação da multicolinearidade utilizando VIF.
  * Divisão Treino-Teste: Separação dos dados em conjuntos de treinamento e teste.
  * Matriz de Confusão, Acurácia e Relatório de Classificação: Métricas utilizadas para avaliar o desempenho do modelo.
  
  ### Download Externo de Dados:
  * gdown: Download direto de conjuntos de dados de fontes externas.

  ### Principais Conclusões
  * O treinamento em dados desbalanceados resultou em um modelo com um aumento de 3% na acurácia geral.
  * No entanto, ao ser testado em dados reais, o treinamento em conjuntos de dados balanceados usando SMOTE apresentou uma melhoria de 11% na identificação de transações fraudulentas, destacando a importância de tratar o desbalanceamento de classes.


  ### Conjunto de Dados
  * O conjunto de dados inclui registros de transações com cartão de crédito, contendo variáveis como valor da transação, tempo e outras informações anonimizadas. A variável alvo indica se uma transação é legítima (0) ou fraudulenta (1).
  * Este projeto demonstra a eficácia da Regressão Logística na detecção de fraudes, especialmente quando combinada com técnicas adequadas de pré-processamento para tratar o desbalanceamento de dados.


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



# Credit Card Fraud Detection Project using Logistic Regression

## Introduction
With the advancement of technology and the increasing use of credit cards for financial transactions, fraud detection has become a critical challenge.
Machine learning techniques offer powerful solutions to analyze large datasets and identify patterns indicative of fraudulent behavior.
This project focuses on developing a Logistic Regression model to efficiently detect fraudulent transactions.

## Objective
The primary goal of this project is to build a Logistic Regression model capable of accurately distinguishing between legitimate and fraudulent transactions.
Logistic Regression is well-suited for binary classification problems, making it an ideal choice for fraud detection tasks.

## Workflow and Tools

  ### Data Handling and Visualization:
  * Pandas: For data manipulation and preprocessing.
  * Seaborn and Plotly: To visualize data distributions, relationships, and patterns.
  
  ### Class Imbalance Handling:
  * Resampling: Addressing class imbalance using techniques like SMOTE (Synthetic Minority Oversampling Technique).
  
  ### Model Development and Evaluation:
  * Statsmodels: Building the Logistic Regression model and evaluating multicollinearity using VIF.
  * Train-Test Split: Splitting the data into training and testing sets.
  * Confusion Matrix, Accuracy, and Classification Report: Metrics used to evaluate the model’s performance.
  
  ### External Data Download:
  * gdown: Directly downloading datasets from external sources.

    
  ### Key Findings
  * Training on unbalanced data resulted in a model with a 3% increase in overall accuracy.
  * However, when tested on real-world data, training on balanced datasets using SMOTE showed an 11% improvement in identifying fraudulent transactions, highlighting the importance of addressing class imbalance.

  ### Dataset
  * The dataset includes records of credit card transactions, containing variables such as transaction amount, time, and other anonymized information. The target variable indicates whether a transaction is legitimate (0) or fraudulent (1).
  * This project demonstrates the effectiveness of Logistic Regression for fraud detection, especially when combined with proper preprocessing techniques to handle class imbalance.
