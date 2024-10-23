
npm i -D typecript
npx tsc --init
npm install -D @types/node

npx tsc src/server.ts
node src/server.js

# To no need to create .js files only to develop enviroment

  npm install tsx -D

## Then to execute the program: 
  npx tsx watch src/server.ts

npm i eslint -D
npm i eslint @rocketseat/eslint-config -D

# Database
npm install knex
npm install sqlite3

npm run knex -- migrate:make create-documents
npm run knex -- migrate:latest
npm run knex -- migrate:rollback