# GLOBAL-SOLUTION---DATA-SCIENCES2

# 📊 Data Science Salary Analysis — FIAP 2025

Este repositório apresenta uma análise completa de salários na área de **Data Science**, utilizando técnicas de **Análise Exploratória de Dados (EDA)** e modelos de **Regressão Linear** e **Regressão Logística**.  
O projeto foi desenvolvido como entrega da disciplina de **Data Science**, no 2º semestre do curso de Engenharia de Software — FIAP.

---

## 📁 Estrutura do Repositório

- `notebook.ipynb` — Notebook completo desenvolvido no Google Colab  
- `dataset/` — Arquivo CSV utilizado no projeto  
- `trabalho_data_science.pdf` — Documento final gerado com conclusões e análises  
- `README.md` — Documentação do projeto

---

## 📘 Sobre o Conjunto de Dados

O dataset contém registros de diferentes carreiras da área de Data Science, incluindo:
- Cargo  
- Nível de experiência  
- Modelo de trabalho (remote, hybrid, on-site)  
- Localização  
- Tamanho da empresa  
- Salário (em USD)

O objetivo foi identificar padrões salariais e construir modelos capazes de prever tendências e classificar profissionais com salários acima da mediana.

---

## 🧹 Etapas Realizadas

### 1. **Preparação dos Dados**
- Padronização de texto  
- Tratamento de valores nulos  
- Criação de variáveis auxiliares  
- One-Hot Encoding para categorias  
- Normalização das variáveis numéricas

---

### 2. **Análise Exploratória (EDA)**

Principais pontos analisados:
- Distribuição geral dos salários  
- Diferenças salariais por nível de experiência  
- Comparação entre modelos de trabalho  
- Impacto do tamanho da empresa  
- Top 5 cargos mais bem remunerados  
- Presença de outliers  
- Matriz de correlação entre variáveis

**Insights importantes:**
- Salários aumentam significativamente com a experiência  
- Empresas de porte médio apresentam os maiores salários médios  
- Remoto e presencial possuem padrões salariais semelhantes  
- Grande variação salarial dentro de níveis avançados  
- Correlações numéricas fracas sugerem maior influência de variáveis categóricas

---

## 📈 Modelagem Preditiva

### **Regressão Linear**
Modelo utilizado para prever o salário em USD.

**Resultados:**
- R² ≈ 0.3565  
- MAE ≈ 39.160 USD  
- RMSE ≈ 61.496 USD  

*A regressão linear apresentou desempenho moderado devido à alta variabilidade do dataset.*

---

### **Regressão Logística**
Variável-alvo criada:  
- `1` → salário acima da mediana  
- `0` → salário igual/abaixo da mediana  

**Resultados:**
- Acurácia: **91.67%**  
- Precisão: **88.66%**  
- Recall: **94.80%**  
- F1-Score: **91.63%**

*O modelo obteve excelente desempenho na classificação de altos salários.*

---

## 🧠 Conclusão

O estudo mostrou que:
- A área de Data Science possui grande variação salarial  
- Experiência, cargo e porte da empresa são fatores determinantes  
- Prever o salário exato é difícil, mas classificar altos salários é altamente eficiente  
- A Regressão Logística se mostrou ideal para esse tipo de problema  

O projeto evidencia o potencial das técnicas de machine learning para gerar insights reais sobre o mercado de trabalho em tecnologia.

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Pandas / NumPy  
- Matplotlib / Seaborn  
- Scikit-Learn  
- Google Colab  
- ReportLab  

---

## 👤 Autor


**Gabriel Leste**  RM: 558638
**Vitor Rivas** 
RM: 556404
**Otavio Santos** 
RM:556452
FIAP — Engenharia de Software  

---

