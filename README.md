# 📊 Telecom X — Previsão de Evasão de Clientes (Churn)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio **Telecom X – Parte 2**, com o objetivo de aplicar técnicas de **estatística e machine learning** para prever a evasão de clientes (**Churn**) em uma empresa de telecomunicações.

Após a etapa inicial de **ETL e análise exploratória** realizada na primeira parte do desafio, esta fase foca na construção de **modelos preditivos** capazes de identificar clientes com maior risco de cancelamento de serviços.

A identificação antecipada desses clientes permite que a empresa implemente **estratégias de retenção**, reduzindo perdas financeiras e melhorando a fidelização.

---

# 🎯 Objetivo

O objetivo principal deste projeto é:

* Utilizar dados tratados para prever **evasão de clientes**
* Aplicar **técnicas de estatística e machine learning**
* Identificar **variáveis que mais influenciam o churn**
* Criar modelos capazes de **antecipar cancelamentos**

---

# 🧠 Técnicas Utilizadas

Durante o desenvolvimento do projeto foram aplicadas as seguintes técnicas de ciência de dados:

* Análise exploratória de dados (EDA)
* Análise de correlação entre variáveis
* Preparação de dados para modelagem
* Transformação de variáveis categóricas
* Separação de dados de treino e teste
* Treinamento e avaliação de modelos preditivos

---

# 🛠️ Tecnologias Utilizadas

* **Python**
* **Pandas** → Manipulação e análise de dados
* **Matplotlib** → Visualização de dados
* **Seaborn** → Visualizações estatísticas
* **Scikit-learn** → Modelagem de machine learning
* **Jupyter Notebook**

---

# 🔄 Pipeline do Projeto

O projeto foi desenvolvido seguindo um fluxo típico de ciência de dados:

1️. **Extração de dados**

Os dados foram obtidos a partir de um dataset público hospedado no GitHub em formato JSON.

2️. **Limpeza e preparação**

Foram realizados:

* tratamento de valores nulos
* padronização de colunas
* conversão de variáveis categóricas para numéricas
* preparação do dataset para modelagem

3. **Análise exploratória**

Foram geradas visualizações para entender padrões de churn, como:

* distribuição de evasão de clientes
* churn por tipo de contrato
* comportamento dos clientes em relação aos serviços contratados

4. **Modelagem preditiva**

Foram implementados dois modelos principais:

* **Regressão Logística**
* **Random Forest**

5️. **Avaliação dos modelos**

Os modelos foram avaliados utilizando:

* **Acurácia**
* **Relatório de classificação**
* **Matriz de confusão**

6️. **Interpretação do modelo**

Utilizando o modelo Random Forest foi possível identificar **quais variáveis possuem maior influência na evasão de clientes**.

---

# 📈 Principais Insights

A análise dos dados e dos modelos indicou que alguns fatores possuem forte relação com o churn:

* clientes com **contratos mensais** apresentam maior taxa de cancelamento
* clientes com **menor tempo de permanência** possuem maior risco de evasão
* valores mensais e serviços adicionais podem influenciar no cancelamento

Esses padrões permitem que a empresa identifique clientes com maior risco de churn e desenvolva estratégias de retenção mais eficientes.

---

# 🚀 Possíveis Aplicações

Os resultados deste projeto podem ser utilizados para:

* identificar clientes com **alto risco de cancelamento**
* desenvolver **campanhas de retenção direcionadas**
* oferecer **benefícios personalizados**
* melhorar a **fidelização de clientes**

---

# 📂 Estrutura do Projeto

```
telecomx-churn-prediction

│
├── telecomx_parte2.ipynb
├── README.md
└── dados_tratados.csv (opcional)
```

---

# 📚 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conhecimentos fundamentais da área de **Data Science**, incluindo:

* preparação e limpeza de dados
* análise exploratória
* estatística aplicada
* construção de modelos preditivos
* interpretação de resultados de machine learning

---

# 👩‍💻 Autora

Projeto desenvolvido como parte do desafio **Telecom X – Data Science**, por [Kiara (Suellen B.)]
