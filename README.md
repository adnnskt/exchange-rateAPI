Descrição:

Este repositório contém um notebook em Python desenvolvido para realizar requisições a APIs de Modelos de Linguagem de Grande Escala (LLMs), incluindo integrações com o Google Generative AI.
O projeto tem como finalidade disponibilizar uma base estruturada para envio de prompts, análise de respostas e integração com fluxos de dados corporativos.

Funcionalidades:

Conexão e autenticação com APIs de LLM.

Integração com a biblioteca Google Generative AI.

Envio de requisições HTTP parametrizadas.

Processamento das respostas em formato JSON.

Organização e análise de resultados em ambiente Jupyter Notebook.

Estrutura do Repositório:

request-api-llm.ipynb   # Notebook principal com o script
requirements.txt        # Dependências do projeto (opcional)
README.md               # Documentação do projeto

Pré-requisitos: 

Python 3.9 ou superior.

Ambiente Jupyter Notebook.

Bibliotecas listadas em requirements.txt (requests, pandas, google-generativeai).

Instalação:

Clonar o repositório e instalar as dependências necessárias:

git clone https://github.com/seu-usuario/request-api-llm.git
cd request-api-llm
pip install -r requirements.txt

Utilização:

Abrir o notebook no Jupyter:

jupyter notebook request-api-llm.ipynb


Configurar as variáveis de ambiente com as chaves de API correspondentes (Google Generative AI):

export GOOGLE_API_KEY="sua_chave_aqui"


Executar as células para envio das requisições e análise das respostas.

Exemplos de Saída:

Respostas textuais retornadas pelo modelo de linguagem.

Estruturação dos resultados em tabelas para análise comparativa.

Logs de execução para acompanhamento de testes.

Próximos Passos:

Expansão do suporte para múltiplos provedores de LLM.

Implementação de testes unitários e automatizados.

Integração com pipelines de dados e orquestradores, como Airflow e AWS Lambda.

Contribuição:

Contribuições são bem-vindas. Para alterações significativas, recomenda-se a abertura de uma issue para discussão prévia antes da submissão de um pull request.
