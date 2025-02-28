# GraphQL CLI Basic Full Stack Template

Starter Full Stack template using GraphQL CLI.

## Usage

This project has been created using GraphQL CLI. Run the project using the following steps:

- Install

```sh
yarn install
```

- Start the database

```sh
docker-compose up -d
```

- Generate resources(schema and resolvers) and create database

```sh
yarn graphql generate --backend
yarn graphql generate --db
```

- Start the server

```sh
cd server/ && yarn start
```

- Generate queries, mutations and subscriptions for client-side project

```sh
yarn graphql generate --client
```

- Generate React components

```sh
yarn graphql codegen
```

- Start React App

```sh
cd client/ && yarn start
```
