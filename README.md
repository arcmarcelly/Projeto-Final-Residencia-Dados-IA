# 📊 Segmentação de Risco Patrimonial

### Projeto Final — Residência Tecnológica em Análise de Dados e Inteligência Artificial

Projeto desenvolvido com foco na **segmentação de risco patrimonial para o mercado segurador**, utilizando técnicas de **Análise de Dados e Machine Learning**.

## 🎯 Sobre o projeto

O projeto utiliza dados de empresas para estimar o **risco relativo de ocorrência de sinistros patrimoniais**, apoiando processos de análise e segmentação de riscos de uma seguradora.

A variável-alvo utilizada no modelo é binária:

* `1` → ocorrência de sinistro
* `0` → ausência de sinistro

> O modelo estima a ocorrência geral de sinistros patrimoniais, não a previsão de um tipo específico de evento.

## 🧠 Metodologia

O desenvolvimento foi estruturado com base no **CRISP-DM**, contemplando:

* Entendimento do negócio e dos dados
* Preparação e tratamento dos dados
* Engenharia e seleção de atributos
* Modelagem preditiva
* Avaliação dos resultados

O projeto foi desenvolvido em **Python**, utilizando um **Jupyter Notebook** para análise, preparação dos dados, criação de atributos, treinamento e avaliação do modelo.

## 🤖 Modelo

Foi utilizado o algoritmo **Random Forest**, aplicado a um problema de **classificação binária**.

O modelo gera um **score de risco entre 0 e 1**, permitindo diferenciar empresas com diferentes níveis de risco relativo de ocorrência de sinistros.

## 📈 Resultados

| Métrica           | Resultado |
| ----------------- | --------: |
| AUC-ROC           | **0,656** |
| KS — teste        | **0,250** |
| Taxa de sinistros | **56,7%** |
| Lift              | **1,99x** |

Os resultados demonstram capacidade do modelo de **diferenciar grupos com diferentes níveis de risco relativo**, podendo apoiar a análise e segmentação de riscos patrimoniais.

## 🛠️ Tecnologias

* 🐍 **Python**
* 📓 **Jupyter Notebook**
* 🐼 **Pandas**
* 🔢 **NumPy**
* 📊 **Matplotlib**
* 📊 **Seaborn**
* 🤖 **Scikit-learn**
* 🌲 **Random Forest**

## 📂 Estrutura

```text
📦 segmentacao-risco-patrimonial
│
├── 📓 notebook/
│   └── AtividadeFinal_SIBILA_COMPLETO.ipynb
│
├── 📊 dados/
│
├── 📄 relatorio/
│
└── README.md
```

## 👥 Contribuidores

* **Emilly Cavalcanti**
* **Livia Lorrani**
* **Marcelly Arcanjo**
* **Rafael Moura**
* **Thiago Malta**
