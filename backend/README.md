# Backend

## Requirements

- **Node.js**: v22.22.0
- **TypeScript**: v5.9+

## Project Structure

```
src/
├── index.ts          # Application entry point
├── controllers/      # Request handlers (business logic coordination)
├── routes/           # API route definitions
├── services/         # Business logic and external service integrations
├── models/           # Data models and database schemas
├── middleware/       # Express middleware (auth, validation, etc.)
├── utils/            # Helper functions and utilities
└── config/           # Configuration files and environment setup
```

## Getting Started

### Install dependencies

```bash
npm install
```

### Run in development mode

```bash
npm run dev
```

This starts the server with **nodemon**, which automatically restarts on file changes.

### Build for production

```bash
npm run build
```

### Run production build

```bash
npm start
```

## Available Scripts

| Script          | Description                          |
| --------------- | ------------------------------------ |
| `npm run dev`   | Start dev server with nodemon        |
| `npm run build` | Compile TypeScript to `dist/`        |
| `npm start`     | Run compiled JavaScript from `dist/` |
