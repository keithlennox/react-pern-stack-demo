# CRUD Demo

A simple CRUD app that can add, update, or delete users.

The front end is React.
The backend is Node.js + Express.
The database is PostgreSQL.
State management is handled by React hooks (useState, useEffect, useContext) + context API.
The API is GraphQL, which is auto generated by postgraphile.
Apollo is used in the frontend to make GraphQL calls to the backend.

Use the following commands to create the database required for this demo:

CREATE DATABASE users;
CREATE TABLE users ( id SERIAL PRIMARY KEY, name VARCHAR(20), username VARCHAR(20) );

The following tutorials were used:

## CRUD
https://www.taniarascia.com/crud-app-in-react-with-hooks/

## Hooks + Context API
https://www.taniarascia.com/using-context-api-in-react/  

## Apollo
https://www.apollographql.com/docs/react/get-started/  
https://reactgo.com/react-hooks-apollo/

## Postgraphile
https://www.graphile.org/postgraphile/quick-start-guide/

## Postgres