# Dockerization Agent Skill

An autonomous DevOps agent designed to analyze existing projects, automatically containerize applications, execute validation tests, and prepare environments for production deployment.

## Features

- Automatic project analysis
- Framework and dependency detection
- Dockerfile generation
- Docker Compose generation
- Environment variable management
- SQLite support for development and testing
- PostgreSQL support for production
- Automatic database switching via environment variables
- Docker best practices implementation
- Healthcheck configuration
- Security hardening
- Automated validation and testing
- Error detection and self-correction
- Technical documentation generation

## Supported Technologies

- Python
- Django
- FastAPI
- Flask
- Node.js
- NestJS
- React
- Next.js
- PostgreSQL
- SQLite
- Docker
- Docker Compose

## Database Switching

The agent automatically configures the application to switch databases without code changes:

### Development

```env
DATABASE_MODE=sqlite
