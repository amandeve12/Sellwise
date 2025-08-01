# Freelance Platform Monorepo

This monorepo contains all microservices and frontend for a freelance platform (similar to Upwork).

## Structure

- `apps/frontend`: Next.js frontend
- `services/auth-service`: Authentication
- `services/job-service`: Job management
- `services/payment-service`: Payment logic
- `shared/`: Shared TypeScript types and utilities
- `infra/`: Docker, database, and infrastructure files

## Getting Started

```bash
# Install all deps
npm install

# Start full stack
docker-compose up --build
