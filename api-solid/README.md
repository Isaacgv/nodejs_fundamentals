# Start new project
npm init -y

# Install dependencies
npm i typescript @types/node tsx tsup -D

# Generate tsconfig.json
npx tsc --init

npm i fastify
npm i dotenv
npm i zod
npm i eslint @rocketseat/eslint-config -D