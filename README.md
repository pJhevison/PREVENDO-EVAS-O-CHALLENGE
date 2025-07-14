# 📊 Análise e Previsão de Evasão de Clientes (Churn) | Desafio Alura + Oracle ONE

Este repositório documenta a solução completa para o desafio de Data Science da **Alura + Oracle Next Education**, focado em **analisar e prever a evasão de clientes (Churn)** em uma empresa de telecomunicações.

---

## 🎯 Objetivo

O projeto foi dividido em duas fases estratégicas com um objetivo claro:

- **Análise Exploratória (Parte 1):** Investigar por que os clientes estão cancelando seus serviços, identificando os principais fatores e perfis de risco.
- **Modelagem Preditiva (Parte 2):** Utilizar os insights da análise para construir modelos de Machine Learning capazes de prever os clientes com maior probabilidade de evasão.

> O objetivo final é transformar dados brutos em inteligência acionável, permitindo que a empresa crie estratégias de retenção mais eficazes e proativas.

---

## 🛠️ Ferramentas e Tecnologias

- **Linguagem:** Python 3
- **Ambiente:** Google Colab / Jupyter Notebook

### 📚 Bibliotecas Principais

- `Pandas` – Manipulação e tratamento de dados  
- `Matplotlib` & `Seaborn` – Visualização de dados e gráficos  
- `Scikit-learn` – Modelagem, pré-processamento e avaliação  
- `Imbalanced-learn` – Técnicas de balanceamento (SMOTE)  

---

## 📂 Estrutura do Repositório


📁 Projeto Churn
├── Challenge_Intercon_x_.ipynb # Notebook principal (EDA + Modelagem)
├── churn_dados_tratados.csv # Dados tratados prontos para modelagem
└── README.md # Documentação do projeto


---

## 📈 Metodologia

### 🔍 Parte 1: Análise Exploratória de Dados (EDA)

- **Extração e Limpeza:** Dados extraídos via API (JSON), normalizados e padronizados.
- **Visualização:** Gráficos para entender a distribuição do churn e suas relações com variáveis categóricas e numéricas.

### 🤖 Parte 2: Modelagem Preditiva

- **Pré-processamento:** One-Hot Encoding aplicado às variáveis categóricas.
- **Balanceamento:** Técnica SMOTE para corrigir desbalanceamento (~27% churn).
- **Divisão e Padronização:** Dados divididos em treino/teste e normalizados com `StandardScaler`.

### 📊 Modelos Utilizados

- **Regressão Logística:** Modelo baseline, simples e interpretável.
- **Random Forest:** Modelo robusto e mais complexo baseado em ensemble.

### 🔎 Análise de Importância

- Avaliação dos coeficientes da Regressão Logística e `feature_importances_` do Random Forest para identificar as variáveis mais influentes na evasão.

---

## 💡 Principais Descobertas

A evasão de clientes está fortemente relacionada a fatores contratuais, temporais e de experiência. Os três principais fatores de risco são:

1. **Tipo de Contrato:** Mensalistas têm maior taxa de churn.
2. **Tempo de Contrato (Tenure):** Alta evasão nos primeiros meses.
3. **Método de Pagamento:** Formas manuais como "Cheque Eletrônico" aumentam o risco.

> **Conclusão Estratégica:**  
A empresa pode reduzir significativamente sua taxa de evasão com estratégias voltadas para:
- Incentivo a contratos de longo prazo  
- Aperfeiçoamento do onboarding de novos clientes  
- Automatização e praticidade nos métodos de pagamento  

---

## 👨‍💻 Autor

**Pedro Jhevison**

📧 Email: [seu-email-aqui@email.com]  
📱 WhatsApp: [(92) 99373-4720](https://wa.me/5592993734720)  
📸 Instagram: [@pj_.style](https://instagram.com/pj_.style)  
💼 LinkedIn: [Seu LinkedIn aqui](#)

---

📌 Projeto desenvolvido como parte do programa **Oracle Next Education + Alura**, com foco em resolução de problemas reais através da Ciência de Dados.
