Previsão de Vendas de Sorvetes

Este projeto utiliza aprendizado de máquina para prever vendas de sorvetes com base em dados históricos. Foram exploradas três abordagens principais no Microsoft Azure:

## Tecnologias Utilizadas
- *Azure Machine Learning (AML)*
- *Azure ML Designer*
- *Azure AutoML*
- *Azure Notebooks (Jupyter)*
- *Python*
- *Pandas, Scikit-learn, Matplotlib, entre outros*

---

## Estrutura do Projeto

### 1. Designer (Interface Gráfica)
Utilizado para montar pipelines de forma visual:
- Leitura do dataset sorvetes.csv
- Seleção de colunas relevantes
- Divisão dos dados (train/test)
- Treinamento do modelo
- Avaliação e publicação via endpoint

### 2. AutoML
Automação do processo de modelagem:
- Upload do dataset
- Definição da variável alvo
- Execução automática de múltiplos algoritmos
- Escolha do melhor modelo com base em métricas (ex: R², MAE)

### 3. Notebooks
Processamento e análise manual:
- Pré-processamento de dados
- Exploração visual (matplotlib/seaborn)
- Treinamento com modelos do scikit-learn
- Salvamento do modelo (.pkl)

---
