Este projeto foi desenvolvido para identificar os principais fatores que levam os clientes da Telecom X a cancelarem seus serviços (Churn) e construir modelos de Machine Learning capazes de prever esse comportamento com precisão.
Sobre o Projeto
A evasão de clientes é um dos maiores desafios de empresas de telecomunicações. Através deste projeto, realizamos uma análise completa desde o tratamento de dados brutos até a implementação de modelos preditivos, visando fornecer insights estratégicos para retenção
Tecnologias e Ferramentas
Linguagem: Python

Bibliotecas: Pandas, NumPy, Scikit-learn, Imbalanced-learn (SMOTE), Seaborn, Matplotlib

Ambiente: Google Colab


Etapas do Projeto
Limpeza e ETL: Remoção de IDs, conversão de tipos de dados (como TotalCharges) e tratamento de valores ausentes.

Análise Exploratória: Identificação de que clientes com contratos mensais e usuários de fibra óptica têm maior taxa de evasão.

Engenharia de Dados: Transformação de variáveis categóricas via One-Hot Encoding e normalização de escalas com StandardScaler.

Balanceamento: Aplicação da técnica SMOTE para equilibrar a base de dados, permitindo que o modelo aprenda melhor sobre a classe minoritária (quem sai).

Modelagem: Implementação e comparação entre Regressão Logística e Random Forest.
