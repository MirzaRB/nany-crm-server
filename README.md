# NANY MOBILE APPLICATION CRM

## Quick Start

```bash
cd nanny-server
```

```bash
npm install
```

Running locally:

```bash
npm dev
```

Running in production:

```bash
npm start
```

Compiling to JS from TS

```bash
npm compile
```

Compiling to JS from TS in watch mode

```bash
npm compile:watch
```

Commiting changes

```bash
npm commit
```

Testing:

```bash
# npm all tests
npm test

# run TypeScript tests
npm test:ts

# run JS tests
npm test:js

# run all tests in watch mode
npm test:watch

# run test coverage
npm coverage
```

## SWAGGER UI
###  [SWAGGER-UI](http://localhost:3000/api-docs/)

## Project Structure

```
.
├── src                             # Source files
│   ├── app.ts                        # Express App
│   ├── config                        # Environment variables and other configurations
│   ├── custom.d.ts                   # File for extending types from node modules
│   ├── declaration.d.ts              # File for declaring modules without types
│   ├── index.ts                      # App entry file
│   ├── modules                       # Modules such as models, controllers, services 
│   └── routes                        # Routes
├── TODO.md                         # TODO List
├── package.json
└── README.md
```
