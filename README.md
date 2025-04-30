# 📊 Previsão de Churn — Case Inteli Academy

Este repositório contém a solução desenvolvida para o case de ciência de dados proposto pela **Inteli Academy**, cujo desafio é prever a **rotatividade de clientes (churn)** da empresa fictícia de telecomunicações **TelecomPlus** com base em dados históricos.

---

## 🎯 Objetivo

Desenvolver um modelo supervisionado capaz de identificar, com alta acurácia, quais clientes têm maior probabilidade de cancelar seus serviços nos próximos 3 meses, permitindo ações proativas de retenção.

---

## ⚙️ Tecnologias e Bibliotecas

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (modelagem tradicional)
- TensorFlow / Keras (rede neural)
- Jupyter Notebook

---

## 📁 Estrutura do Projeto

- `Case_Inteli_Academy.ipynb`: Notebook com todas as etapas do projeto
- `dados_clientes.csv`: base histórica de treino
- `desafio.csv`: base para teste (sem rótulo)
- `resultado_nome_sobrenome.csv`: arquivo final com previsões para entrega

---

## 🔄 Pipeline de Modelagem

1. **Exploração e limpeza dos dados**
2. **Engenharia de features**
3. **Codificação de variáveis categóricas**
4. **Padronização das variáveis numéricas**
5. **Modelagem com:**
   - Regressão Logística
   - Random Forest
   - Rede Neural com Keras (modelo final otimizado)
6. **Avaliação com métricas:**
   - Acurácia
   - F1-score
   - Matriz de confusão
7. **Geração do CSV de resultado final**

---

## 🧠 Principais Insights

- Variáveis como **tempo como cliente**, **total gasto**, e **valor mensal** foram altamente relevantes na previsão de churn.
- A **rede neural com camadas densas e Dropout** foi o modelo com melhor desempenho após ajustes.
- A visualização das importâncias ajudou a entender o perfil de risco dos clientes.

---

## 📄 Resultado

O modelo final gerou o arquivo `resultado_nome_sobrenome.csv` com as colunas `Id` e `Target`, conforme exigido, pronto para avaliação e entrega.
