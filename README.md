# 🚢 Análise de Dados e Machine Learning: Titanic Dataset

Este projeto é um estudo completo do ciclo de vida de um projeto de Data Science, utilizando o clássico dataset do Titanic. O objetivo principal foi ir além da simples previsão, focando na interpretação dos dados, tratamento de variáveis complexas e preparação do modelo para produção (deploy).

## 🎯 Objetivos do Projeto
- Realizar uma **Análise Exploratória de Dados (EDA)** profunda para entender correlações e padrões de sobrevivência.
- Aplicar técnicas de **Engenharia de Atributos** para tratar valores nulos e variáveis categóricas.
- Comparar a performance de diferentes algoritmos de classificação (**KNN, Árvore de Decisão e Regressão Logística**).
- Implementar a **persistência do modelo** (salvamento) para simular um cenário real de deploy.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python 3
* **Análise e Manipulação:** Pandas, NumPy
* **Visualização:** Matplotlib, Seaborn, YData Profiling
* **Machine Learning:** Scikit-Learn
* **Persistência:** Joblib

## 📂 Estrutura do Projeto
O projeto foi dividido em etapas lógicas para facilitar o entendimento:

1.  **`1_Analise_Exploratoria.ipynb`**: Visão geral dos dados, identificação de outliers e padrões iniciais (EDA).
2.  **`2_Tratamento_de_Dados.ipynb`**: Limpeza do dataset, imputação de valores ausentes (ex: idades) e encoding de variáveis categóricas.
3.  **`3_Modelagem_Machine_Learning.ipynb`**: Treinamento, teste e comparação das métricas de acurácia entre os modelos.
4.  **`4_Persistencia_e_Deploy.ipynb`**: Exportação do modelo treinado para uso futuro sem necessidade de retreino.

## 📊 Principais Resultados
Durante a análise, foi possível identificar que variáveis como `Sex` e `Pclass` (Classe Social) foram determinantes para a sobrevivência. O tratamento adequado da coluna `Age` (Idade) e a remoção de colunas com alta cardinalidade (como `Ticket`) melhoraram a generalização dos modelos.

## 🚀 Como Executar
1. Clone este repositório.
2. Instale as dependências listadas no `requirements.txt`.
3. Execute os notebooks na ordem numérica para reproduzir a análise.

---
*Desenvolvido por Cauê Iafelix Manoel*
