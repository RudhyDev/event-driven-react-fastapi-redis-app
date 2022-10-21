# Web App simples para controle de Delivery - feito com React, FastApi e Redis.
## Essa é uma Aplicação Web que tem por objetivo usar os conceitos de Event-Driven Architecture (EDA) e para tanto foi utilizado o Redis na persistência de dados em memória.

## Esse projeto está sendo finalizado, por tanto ainda não foi feito o deploy em um servidor. Caso queira rodar o projeto localmente você precisará ter instalado em sua maquina: `node`, `python (e a biblioteca uvicorn)`. Crie uma conta no Redis, siga as instruçoes do próprio site para gerar um path de conexão e token de acesso. Feito isso substitua suas credenciais no diretório ```fast-api/main.py``` nos campos: ```{ host="XXXXXXXXX", port=XXXXX, password="XXXXX" }```

## Como Rodar:

1. Clone o repositório
2. Abra o terminal e vá para o diretório fast-api: ```cd fast-api/```;
3. Rode o comando ```uvicorn main:app --reload```;
4. Abra outro terminal e vá para o diretório react-events: ```cd react-events/```;
5. Instale todas as dependências: ```npm install```;
6. E, finalmente, digite: ```npm run start```. Irá abrir a página no seu navegador.
