# Santander Dev Week 2023 (ETL com Python)
Usar o poder da IA Generativa para criar mensagens de marketing personalizadas que serão entregues a cada cliente através do processo de ETL

## Condições do Problema:

Você recebeu uma planilha simples, em formato CSV ('SDW2023.csv'), com uma lista de IDs de usuário do banco (UserID):
Seu trabalho é consumir o endpoint GET https://sdw-2023-prd.up.railway.app/users/{id} (API da Santander Dev Week 2023) para obter os dados de cada cliente.
Depois de obter os dados dos clientes, você vai usar a API do ChatGPT (OpenAI) para gerar uma mensagem de marketing personalizada para cada cliente. Essa mensagem deve enfatizar a importância dos investimentos.
Uma vez que a mensagem para cada cliente esteja pronta, você vai enviar essas informações de volta para a API, atualizando a lista de "news" de cada usuário usando o endpoint PUT https://sdw-2023-prd.up.railway.app/users/{id}.
