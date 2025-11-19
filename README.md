# Ustream
Este projeto em Python faz requisições à NewsAPI para buscar automaticamente as notícias mais recentes sobre criptomoedas, filtradas por termos como cryptocurrency, bitcoin e ethereum.
As notícias são exibidas de forma organizada, exibindo título, fonte e link para leitura completa.


# Funcionalidades

Busca as notícias mais recentes sobre:
Bitcoin
Ethereum
Criptomoedas em geral
Filtra as notícias por:
idioma (pt – português)
ordem de publicação (mais recentes primeiro)

# Exibe:
Título
Fonte
Link

# Tratamento completo de erros:
Falha na conexão
Respostas inválidas da API
Erros internos

 # Requisitos

Você precisa instalar:
pip install requests


E ter uma conta no NewsAPI.org para gerar sua API KEY.
# Configuração da API Key

No código, substitua:
NEWS_API_KEY = 'sua_api_key_aqui'


pela sua chave real.
