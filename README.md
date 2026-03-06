# 📊 Análise de Churn de Clientes

## 📌 Sobre o Projeto

Este projeto tem como objetivo realizar uma **análise exploratória de dados (EDA)** para entender os fatores que influenciam o **cancelamento de clientes (churn)** em um serviço.

A análise busca identificar padrões de comportamento que possam explicar por que determinados clientes cancelam seus contratos. A partir desses padrões, é possível gerar **insights estratégicos** que auxiliam empresas na criação de ações para **reduzir churn e melhorar a retenção de clientes**.

Este projeto foi desenvolvido como prática de **análise de dados com Python**, aplicando conceitos de manipulação de dados, análise estatística básica e interpretação de resultados.

---

## 🛠 Tecnologias Utilizadas

* **Python**
* **Pandas** – manipulação e análise de dados
* **Jupyter Notebook** – desenvolvimento e exploração dos dados

---

## 📂 Estrutura do Projeto

```
churn_analysis_project
│
├── churn_analysis.ipynb   # Notebook com toda a análise
├── dataset.csv            # Base de dados utilizada
└── README.md              # Documentação do projeto
```

---

## 🔎 Etapas da Análise

Durante o desenvolvimento do projeto foram realizadas as seguintes etapas:

1. **Importação e exploração inicial da base de dados**
2. **Limpeza e tratamento dos dados**
3. **Análise da variável de cancelamento (churn)**
4. **Cálculo da taxa de cancelamento**
5. **Identificação de padrões relacionados ao churn**
6. **Interpretação dos resultados e geração de insights**

---

## 📊 Exemplo de Análise

```python
# quantidade de clientes que cancelaram
tabela["cancelou"].value_counts()

# porcentagem de cancelamento
tabela["cancelou"].value_counts(normalize=True)
```

Essa análise permite entender **quantos clientes cancelaram o serviço e qual a taxa de churn da empresa**.

---

## 💡 Principais Insights

A análise indicou alguns padrões relevantes:

* Clientes com **contrato mensal** apresentam maior probabilidade de cancelamento.
* Clientes com **contratos de maior duração (trimestral ou anual)** tendem a permanecer mais tempo no serviço.
* Certas características do plano e do comportamento do cliente podem influenciar diretamente na decisão de cancelamento.

Esses insights podem ajudar empresas a desenvolver **estratégias de retenção de clientes**, como incentivos para contratos de maior duração.

---

## 🎯 Objetivo do Projeto

O objetivo principal deste projeto é **demonstrar habilidades em análise de dados utilizando Python**, incluindo:

* Manipulação de dados
* Análise exploratória
* Interpretação de resultados
* Extração de insights a partir de dados

---

## 🚀 Possíveis Melhorias Futuras

* Criação de **visualizações gráficas** para facilitar a interpretação dos dados
* Desenvolvimento de um **dashboard interativo**
* Aplicação de **modelos de machine learning para previsão de churn**

---

## 👨‍💻 Autor

**Nicolas Miranda de Carvalho**

Projeto desenvolvido como prática de **Análise de Dados com Python**.
