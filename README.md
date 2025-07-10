# 📊 Análise Estatística dos Dados de Ações da NVIDIA

Este projeto realiza uma análise estatística exploratória sobre os preços históricos das ações da empresa **NVIDIA**, utilizando a linguagem Python com as bibliotecas `pandas`, `matplotlib`, `seaborn`, `numpy` e `scipy`.

---

## 🎯 Objetivo

Investigar a **volatilidade diária** das ações da NVIDIA e avaliar se ela aumentou a partir do ano de 2020.

> **Hipótese:** A volatilidade diária das ações da NVIDIA aumentou a partir de 2020, influenciada por fatores globais como a pandemia e a crescente demanda por tecnologia.

---

## 🧪 Metodologia

As análises foram feitas com base nos seguintes passos:

- Leitura e pré-processamento dos dados (`Date`, `High`, `Low`, `Close`, `Volume` etc.)
- Criação da variável `Daily_Amplitude` (diferença entre `High` e `Low`)
- Categorização dos dados em dois períodos: `Antes_2020` e `2020_em_diante`
- Cálculo de estatísticas descritivas
- Visualização dos dados com histogramas, boxplots, gráficos de linha e heatmaps
- Cálculo de **Skewness** e **Kurtosis**
- Análise de **correlação** entre variáveis

---

## 📈 Principais Gráficos e Indicadores

- Histograma da volatilidade diária
- Boxplot comparativo entre os períodos
- Gráfico de linha com tendência da volatilidade
- Mapa de calor de correlação entre variáveis
- Análise de Skewness e Kurtosis para verificar distribuição dos dados
- Análise da Evolução do Preço de Fechamento das Ações da Nvidia (2015-2025)

---

## ✅ Conclusão

A análise confirmou a hipótese levantada: **houve um aumento na volatilidade das ações da NVIDIA a partir de 2020**. Esse comportamento pode ser atribuído a fatores externos, como a pandemia e oscilações no mercado de tecnologia.

---

## 📁 Arquivos

- `arquivo_completo.ipynb`: Notebook com todo o código, gráficos e análises
- `Nvidia_stock_data.csv`: Base de dados utilizada
- `README.md`: Este arquivo

---

## 👨‍💻 Tecnologias Utilizadas

- Python 3.11
- pandas
- numpy
- matplotlib
- seaborn
- scipy

---

## ✍️ Autores

- Vinícius Castelhano Mantovani
- Vitor Hugo Cavalcante
