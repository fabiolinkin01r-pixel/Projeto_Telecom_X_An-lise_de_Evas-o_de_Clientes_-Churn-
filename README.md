🚀 Projeto Telecom X — Análise de Churn (Evasão de Clientes)

Este repositório apresenta uma análise completa sobre o Churn (evasão de clientes) da empresa fictícia Telecom X, utilizando técnicas de Ciência de Dados, ETL, Visualização e Modelagem Preditiva.
O objetivo é identificar os fatores que mais influenciam a saída dos clientes e construir uma base sólida para futuras estratégias de retenção.

📌 Principais Objetivos do Projeto

📥 Realizar ETL (Extração, Transformação e Carregamento) dos dados provenientes de uma API.

🔍 Realizar Análise Exploratória de Dados (EDA) detalhada.

🧪 Identificar padrões relevantes associados ao churn.

🤖 Criar e avaliar um modelo de Machine Learning para prever a evasão.

📈 Gerar insights acionáveis para o negócio.

🗂 Estrutura do Repositório
📦 Projeto-Telecom-X-Churn
├── 📓 notebook.ipynb               → Análise completa (ETL, EDA, ML)
├── 📄 README.md                    → Documentação do projeto
├── 📦 requirements.txt             → Dependências necessárias
└── 📁 TelecomX_Data.json           → Base de dados utilizada

📊 Principais Insights Gerais

Clientes com contrato mensal apresentam maior risco de churn.

O aumento nas taxas mensais (MonthlyCharges) está diretamente associado ao desligamento.

Usuários que não utilizam serviços como internet fibra, streaming ou telefone têm padrões diferentes de evasão.

Clientes com pouco tempo de casa tendem a cancelar mais rapidamente.

O notebook contém gráficos detalhados, correlações, análise por serviços e muito mais.

🤖 Modelagem Preditiva

Foi construído um pipeline utilizando:

ColumnTransformer

StandardScaler

OneHotEncoder

Logistic Regression

Métricas avaliadas:

📌 Acurácia

📌 Precisão, Recall e F1-score

📌 ROC-AUC

📌 Matriz de confusão

📌 Curva ROC

O modelo serve como baseline, deixando espaço para melhorias como:

SMOTE

XGBoost / Random Forest

Otimização de hiperparâmetros

Seleção de features

⚙️ Tecnologias Utilizadas

🐍 Python

📘 Pandas

📊 Matplotlib / Seaborn

🤖 Scikit-Learn

📒 Jupyter Notebook

☁️ API (GitHub Raw JSON)
