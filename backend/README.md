# NLW Heat

## Dia 1

# O que foi feito

https://github.com/mauro-moura/nlw-heat-impulse

* Introdução ao NLW Heat
* Criação do Projeto
* Instalação das bibliotecas
* Configurar Github OAuth
* Criar rota login Github
* Criar rota callback
* Autenticação do Usuário recebendo o código
* Cadastro de Mensagem
* Configuração do websocket
* Retornar ultimas 3 mensagens
* Criar Profile do User

### Sobre o dia

Comandos:
Iniciar o projeto
yarn init -y

Iniciar o typescript
yarn tsc --init

yarn add express
yarn add -D @types/express typescript ts-node-dev
yarn add dotenv
yarn add axios
yarn add @types/axios -D
yarn add jsonwebtoken
yarn add @types/jsonwebtoken -D
yarn add @prisma/client
yarn add socket.io
yarn add @types/socket.io -D
yarn add cors
yarn add @types/cors -D


Para Adicionar o prisma
yarn add prisma -D

Para iniciar o prisma
yarn prisma init


# Preciso Acessar o Developer Settings do Github para passar para o OAuth Apps

Homepage URL: http://localhost:4000
Autorization callback URL: http://localhost:4000/signin/callback

Erro 401: Erro de Autenticação

Para criar um banco de dados no prisma o comando é:
yarn prisma migrate dev


O que é migration?

É como um histórico do banco de dados

create-user
create-messages

yarn prisma studio - Usadp para avaliar os dados da tabela

### Configuração do websocket

socket.io

### Retornar ultimas 3 mensagens

### 

### Código do dia




