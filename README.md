# Recipe Explorer Backend

## Description
This is the backend service for the Recipe Explorer application. It provides a RESTful API for searching recipes, managing favorite recipes, and retrieving recipe details. Built with Node.js, Express, and Prisma, it offers robust data management and efficient querying capabilities.

## Features
- Recipe search API integration
- Recipe details retrieval
- Favorite recipes management (add, remove, list)
- PostgreSQL database integration using Prisma ORM

## Technologies Used
- Node.js
- Express.js
- Prisma ORM
- PostgreSQL
- TypeScript
- dotenv for environment variable management
- cors for Cross-Origin Resource Sharing

## Spoonacular API:

Add the api key to the `API_KEY` variable in the .env file

## BD - Prisma Setup:
- Create a new database instance postgreSQL.
- Replace the DATABASE_URL in the .env file with a connection string of your instance. `DATABASE_URL="postgresql://username:password@localhost:5432/recipe-app-db"`
- Initialize Prisma and generate the Prisma client:
  
```
  npx prisma init
  npx prisma generate
```

## Start the backend server:
`npm start`

## Postman Importe
Puede descargar el archivo de pruebas haciendo click [Aqui](recipe.postman_collection).

