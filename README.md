# AF-IA

# 🔬 Análise de Risco de Câncer com Regressão Logística e Linear

Este projeto visa analisar a relação entre fatores ambientais, clínicos e comportamentais no risco de desenvolvimento de câncer. Através de técnicas de regressão logística e linear, buscamos classificar os níveis de risco e prever sintomas associados como perda de peso.

---

## 📑 Descrição do Projeto

O câncer é uma das principais causas de mortalidade no mundo, e entender seus fatores de risco é essencial para a prevenção. Este estudo utilizou um dataset contendo *1.000 registros de pacientes*, com informações sobre:

- Idade
- Gênero
- Poluição do ar
- Tabagismo
- Consumo de álcool
- Obesidade
- Dieta
- Sintomas clínicos (fadiga, tosse, dor no peito, entre outros)
- Níveis de risco de câncer (Baixo, Médio e Alto)

---

## 🎯 Objetivos

### ✔ Objetivo Geral
- Aplicar regressão logística para classificar níveis de risco de câncer e regressão linear para prever a perda de peso, utilizando dados clínicos e ambientais.

### ✔ Objetivos Específicos
- Realizar análise exploratória dos dados (EDA);
- Aplicar regressão logística para classificação dos níveis de risco de câncer;
- Aplicar regressão linear para prever perda de peso;
- Avaliar os modelos utilizando métricas como Acurácia, F1-Score, R² e MSE.

---

## 🛠 Técnicas Utilizadas

- *Regressão Logística:* Classificação dos pacientes em três níveis de risco (Baixo, Médio e Alto).
- *Regressão Linear:* Predição da variável contínua Weight Loss (perda de peso).

---

## 📈 Resultados

- *Regressão Logística:*
  - Acurácia: *100%*
  - F1-Score: *1.00*
  - Observação: Embora o desempenho seja perfeito, há indícios de sobreajuste (overfitting) devido ao tamanho limitado do dataset.

- *Regressão Linear:*
  - R²: *0.72*
  - MSE: *1.41*
  - Boa capacidade preditiva na previsão de perda de peso.

---

## 📊 Ferramentas e Tecnologias

- Python (>=3.8)
- Bibliotecas:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
- Jupyter Notebook

---

## 📂 Como Executar o Projeto

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git 
