# Backend DoWhile 2021 - Node.js
* API construída durante a NLW Heat usando Node.js, typescript, socket.io, prisma e autenticação de usuário através da API do GitHub.

## Configuração
* Git clone
* ```npm install``` na raiz do projeto

## Configurando a api do GitHub
* Criar aplicativo OAuth. [Acesse aqui e siga o tutorial](https://docs.github.com/pt/developers/apps/building-oauth-apps/creating-an-oauth-app). Se você já possui um aplicativo OAuth do GitHub criado, pule esta etapa.
* Crie um arquivo .env na raiz do projeto e crie variáveis com as informações do aplicativo OAuth criado: ```GITHUB_CLIENT_SECRET= , GITHUB_CLIENT_ID= , JWT_SECRET=```. Lembrabdo que JWT_SECRET= pode ser um valor qualquer, desde que seja o mesmo que você esteja usando em outras partes da aplicação.

## Executando a aplicação
* Execute o comando ```yarn dev``` na raiz do projeto.
