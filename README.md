# Telecom-X_Challenge_Alura

README - Projeto de Análise de Evasão de Clientes em Telecom X
Descrição do Projeto
Este projeto tem como objetivo analisar os fatores que influenciam a evasão de clientes (churn) na empresa de telecomunicações Telecom X. É realizado um processo completo de ETL (Extração, Transformação e Carga) e uma análise exploratória de dados (EDA) para identificar clientes e tendências que ajudam a compreender e mitigar a evasão de clientes.

Estrutura do Projeto
O projeto está organizado em um único notebook de Python com as seguintes seções:

Importação de Bibliotecas : Instalação e carregamento de todas as bibliotecas necessárias.
Carregar dados da API : extração de dados no formato JSON da API fornecida.
Exploração Inicial dos Dados : Análise preliminar da estrutura e características dos dados.
Dicionário de dados : descrição detalhada de cada variável e seu significado.
Verificação de Problemas nos Dados : Identificação de valores nulos, duplicados e problemas de formato.
Limpeza e transformação de dados : correção de inconsistências e preparação para análise.
Criação da coluna "Cuentas_Diarias" : Cálculo de valores diários a partir da fatura mensal.
Estandarização e Transformação (Opcional) : Conversão de variáveis ​​categóricas para numéricas e tradução de nomes.
Análise Descritiva : Cálculo de estatísticas para compreender a distribuição e o comportamento dos dados.
Visualizações : Gráficos para identificar padrões de evasão por diferentes variáveis.
Análise de Correlação (Extra) : Estudo da relação entre variáveis ​​e seu impacto na evasão.
Informe Final : Resumo de hallazgos, conclusões e recomendações estratégicas.
Requisitos e Dependências
Para executar este projeto, serão necessárias as seguintes bibliotecas de Python:

pandas
numpy
matplotlib
seaborn
requests
Você pode instalar estas dependências com o seguinte comando:

pip install pandas numpy matplotlib seaborn requests
Uso do Projeto
Clonar o repositório ou baixar o notebook :

git clone <url-del-repositorio>
Instalar as dependências :

pip install -r requirements.txt
Executar o notebook : Abra o notebook no Jupyter, Google Colab ou qualquer outro ambiente compatível e execute todas as células em ordem sequencial.

Dados Aplicados
Os dados são obtidos diretamente da API de Telecom X no formato JSON:

URL da API: https://github.com/CleverReis/Telecom-X_Challenge_Alura/blob/main/TelecomX_Data.json
O conjunto de dados contém informações sobre:

Características demográficas dos clientes
Serviços contratados
Tipo de contrato
Método de pagamento
Cargas mensais e totais
Estado de evasão (churn)
Resultados
Principais descobertas:

O relatório final inclui recomendações estratégicas detalhadas para abordar esses fatores e melhorar a retenção de clientes.
A falta de serviços adicionais como segurança on-line e suporte técnico está correlacionada com maior rotatividade.
Os clientes com cargas mensais mais altas têm maior probabilidade de abandono.
O período inicial (primeiros 12 meses) é crítico para a retenção de clientes.
Os clientes com serviço de fibra óptica apresentam maior tendência à evasão.
O tipo de contrato é o fator mais influente na rotatividade, com contratos mensais mostrando o maior risco.
