# Dynamic Blog Platform

A modern blogging platform with scheduled post publishing capabilities.

## Features

- Author authentication and authorization
- Blog post management with draft system
- Scheduled publishing with timezone support
- Rich text editing

## Tech Stack

- Frontend: React, TypeScript, Tailwind CSS, React Query
- Backend: NestJS, Node.js, TypeORM
- Database: PostgreSQL
- Workflow Management: Temporal.io
- Build System: Turborepo, Dagger.io

## Prerequisites

- Node.js >= 20.11.1
- pnpm >= 8.9.0
- Docker
- PostgreSQL

## Getting Started

```bash
# Install dependencies
pnpm install

# Start development servers
pnpm dev
```

## Project Structure

```
├── apps
│   ├── web         # Frontend application
│   └── api         # Backend API
├── packages        # Shared packages
└── turbo.json     # Turborepo configuration
```

## Development

### Frontend (apps/web)

```bash
cd apps/web
pnpm dev
```

### Backend (apps/api)

```bash
cd apps/api
pnpm dev
```

## License

MIT
