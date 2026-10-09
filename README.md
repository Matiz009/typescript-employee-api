# TypeScript Employee API

A small employee API built on Node's `http` module in TypeScript (no framework). It serves employee data as JSON.

## Features

Endpoints on port 8080:

- `/allemployees`
- `/juniors`, `/programmers`, `/engineers`, `/experts`, `/managers`
- `/admins`, `/nonadmins`

There's also a plain JavaScript version in `Server.js`.

## Tech stack

TypeScript, Node.js (`http`), ts-node, moment

## Getting started

```bash
git clone https://github.com/Matiz009/typescript-employee-api.git
cd typescript-employee-api
npm install
npx ts-node src/Server.ts
# open http://localhost:8080/allemployees
```

## Project structure

```
src/Server.ts       HTTP server and routes
src/DataService.ts  Employee data and filters
src/model/          Employee, header and model types
Server.js           Plain JavaScript version
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
