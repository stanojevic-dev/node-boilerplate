# Node-Typescript-Boilerplate

Skeleton for Node.js applications written in TypeScript

## Purpose

Our main purpose with this Skeleton is to start server application with node js and typescript.

Try it!! I am happy to hear your feedback or any kind of new features.

## Common Features

- Quick start
- Intgerated eslint, prettier and husky
- Common Error Handler
- Simple and Standard scaffolding
- Followed SOLID Principles
- Based on Typescript Syntax
- Simple Enviroment Configuration
- Easily Add new feature
- Integrated winston Logger
- Production Ready Skeleton
- Follwed Production Ready Best Practices: Security
- Added only used npm modules


## Core NPM Module

- [x] `express`, `@types/express`
- [x] `@types/node`
- [x] `typescript`
- [x] `dotenv`
- [x] `cors`
- [x] `helmet`
- [x] `http-status-codes`
- [x] `winston`, `@types/winston`

## Start The application in Development Mode

- Clone the Application `git clone https://github.com/santoshshinde2012/node-boilerplate.git`
- Install the dependencies `npm install`
- Start the application `npm start`

## Start The application in Production Mode

- Install the dependencies `npm install`
- Create the build `npm run build`
- Start the application `npm run start:production`
- Before starting make sure to creat prod environment `.env.prod` file

## Project Structure

| Name                              | Description |
| --------------------------------- | ----------- |
| **wiki/**                         | You can add project deocumenation and insructions file here |
| **src/**                          | Source files |
| **src/abstractions**              | Abstarct classes and Interfaces  |
| **src/components**                | REST API Components & Controllers  |
| **src/environments**              | Application Environments Handling utility  |
| **src/lib**                       | Reusabile utilies and library source code like logger |
| **src/middleware/**               | Express Middlewares like error handler feature |
| **.vscode/**                      | VSCode tasks, launch configuration and some other settings |
| **build/**                        | Compiled source files will be placed here |


## Notes

### 1. Why is my git pre-commit hook not executable by default?

- Because files are not executable by default; they must be set to be executable.

```
chmod ug+x .husky/*
chmod ug+x .git/hooks/*
```

### 2. [Production Best Practices: Security](https://expressjs.com/en/advanced/best-practice-security.html)

- Don’t use deprecated or vulnerable versions of Express
- Use TLS
- Use Helmet
- Use cookies securely
- Prevent brute-force attacks against authorization
- Ensure your dependencies are secure
- Avoid other known vulnerabilities
- Additional considerations


<hr/>

# Please connect with me on Twitter [@shindesan2012](https://twitter.com/shindesan2012)
