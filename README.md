# react-node-postgraphile

PostGraphile automatically detects tables, columns, indexes, relationships, views, types, functions, comments and more. It builds a GraphQL server that is highly intelligent about your data, and that automatically updates itself without restarting when you modify your database.

GraphQL Code Generator is a CLI tool that can generate TypeScript typings out of a GraphQL schema. The codegen allows you to specify scripts it can run for you in certain events. (In our case, we will get hook-based queries and mutations.)

Database: PostgreSQL
Server: Node, ExpressJS and PostGraphile
Client: React+TypeScript, GraphQL, Apollo-Client
Schema handling: Knex Migrations

done: Step 1: PostgreSQL installation and create a database with the name 'postgraphiledb'
Step 2: Creating and setup node-express server
Step 3: Create and execute migrations using Knex-Migrations
Step 4: Integrate PostGraphile to enable graphiql
