## Descrição

Aplicação com foco em widget para recebimento de feedbacks, com versões web e mobile. Contém funcionalidade de envio de e-mail do feedback, podendo enviar um screenshot da tela da aplicação.
O backend da aplicação foi feito com NodeJS e o banco de dados utiliza o ORM Prisma. Já no frontend foi utilizado React com Vite, com o TailwindCSS para estilização.
A aplicação Mobile foi construída com React Native e Expo.

Aplicação desenvolvida durante evento da Rocketseat.

## Tecnologias

- [React](https://reactjs.org)
- [Tailwindcss](https://tailwindcss.com)
- [Vite](https://vitejs.dev)
- [TypeScript](https://www.typescriptlang.org)
- [Express](https://expressjs.com/pt-br)
- [Prisma](https://www.prisma.io)
- [Jest](https://jestjs.io)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)

## Instalação e execução do projeto

As configurações do banco de dados do projeto devem ser informadas no arquivo .env localmente.
Para instalar e rodar o projeto, cada parte deve ser executada em separado, conforme segue abaixo:

```sh
# RODANDO O BACKEND
$ cd server
$ npm install
$ npm run dev
```

```sh
# RODANDO O FRONTEND
$ cd web
$ npm install
$ npm run dev
```

```sh
# RODANDO O MOBILE
$ cd mobile
$ npm install
$ npm run start

# Acessar o frontend mobile via aplicativo Expo através do smartphone
```

## Créditos

[![RocketSeat](https://img.shields.io/badge/Rocketseat-633BCC?style=for-the-badge)](https://www.rocketseat.com.br)
