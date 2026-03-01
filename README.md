# Challenge-Telecom-X
Análise de Churn da Telecom X: Processo completo de ETL e Análise Exploratória (EDA) em Python. Extração de dados via API, tratamento de JSON aninhado com Pandas e visualização de insights de evasão com Seaborn e Matplotlib.

📌 Descrição do Projeto
Este projeto faz parte do desafio de Data Science do programa ONE (Oracle Next Education) em parceria com a Alura. O objetivo principal é atuar como Assistente de Dados para a Telecom X, uma empresa de telecomunicações que enfrenta um alto índice de evasão de clientes (Churn).
O foco deste repositório é a realização do processo de ETL (Extract, Transform, Load) e uma Análise Exploratória de Dados (EDA) detalhada para identificar padrões que levam ao cancelamento dos serviços.

🛠️ Tecnologias Utilizadas
Python 

Pandas: Manipulação e tratamento de dados.

Seaborn / Matplotlib: Visualização de dados e geração de insights.

Requests: Extração de dados via API do GitHub.

Google Colab: Ambiente de desenvolvimento.

🚀 Etapas do Projeto
1. Extração (Extract)
Os dados foram consumidos diretamente de uma API em formato JSON. Devido à estrutura aninhada do arquivo, utilizei técnicas de normalização (json_normalize) para estruturar as informações de clientes, contratos e serviços.

2. Transformação (Transform)
Limpeza de dados e tratamento de valores ausentes.

Conversão de tipos de dados (ex: strings para valores numéricos).

Padronização dos nomes das colunas para facilitar a análise.

3. Análise Exploratória (EDA)
Principais descobertas realizadas:

Contratos: Clientes com contratos mensais (Month-to-month) possuem uma taxa de evasão significativamente maior que contratos anuais.

Serviços: Identificamos padrões de churn relacionados ao tipo de serviço de internet (Fibra Óptica vs DSL).

Financeiro: Análise da correlação entre o valor da fatura mensal e a probabilidade de cancelamento.

📁 Estrutura do Repositório
notebooks/: Jupyter Notebooks com o código do desafio.

data/: Pasta contendo o arquivo TelecomX_Tratado.csv gerado.

reports/: Relatório final com os insights de negócio.

📈 Conclusão e Sugestões
Com base nos dados tratados, sugeri à equipe de Data Science o foco em campanhas de retenção para contratos de curto prazo e a revisão da estratégia de preços para serviços de fibra óptica.
