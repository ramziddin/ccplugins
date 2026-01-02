# Claude Code Plugins

A collection of comprehensive plugins for [Claude Code](https://claude.com/claude-code).

## Plugins

### NestJS Plugin

A comprehensive NestJS framework skills plugin with 27 individual skills covering every aspect of NestJS development.

**Location:** `plugins/nestjs/`

**Skills Included:**

#### Core Concepts (10 skills)
- **basics** - Project setup, installation, CLI usage, and core architecture
- **controllers** - HTTP request handling, routing, and decorators
- **providers** - Services, dependency injection, and IoC container
- **modules** - Application organization and module patterns
- **middleware** - Request/response preprocessing
- **guards** - Route protection and authorization
- **interceptors** - Response transformation and AOP
- **pipes** - Data validation and transformation
- **exception-filters** - Error handling and custom exceptions
- **custom-decorators** - Creating reusable decorators

#### Fundamentals (3 skills)
- **dependency-injection** - Custom providers, factories, and injection patterns
- **testing** - Unit testing, E2E testing, and mocking strategies
- **lifecycle** - Lifecycle hooks and application startup/shutdown

#### Techniques (6 skills)
- **configuration** - Environment variables and configuration management
- **validation** - Request validation with class-validator
- **database** - TypeORM, Prisma, and MongoDB integration
- **caching** - In-memory and Redis caching strategies
- **task-scheduling** - Cron jobs, intervals, and scheduled tasks
- **queues** - Background job processing with Bull

#### Security (3 skills)
- **authentication** - JWT authentication and Passport integration
- **authorization** - Role-based access control (RBAC)
- **security** - Security best practices (CORS, CSRF, helmet, rate limiting)

#### Advanced (5 skills)
- **graphql** - GraphQL integration with resolvers and subscriptions
- **websockets** - Real-time communication with WebSocket gateways
- **microservices** - Microservices architecture with various transports
- **cli** - NestJS CLI usage and code generation
- **openapi** - API documentation with Swagger/OpenAPI

### Installation

To use these plugins with Claude Code, pass the plugin directory when starting Claude:

```bash
claude --plugin-dir /path/to/ccplugins/plugins/nestjs
```

Or add to your Claude Code configuration.

### Features

Each skill includes:
- ✅ Clear descriptions for when to use the skill
- ✅ Comprehensive code examples with TypeScript
- ✅ Best practices and common patterns
- ✅ Real-world usage scenarios
- ✅ Complete, working examples

### Documentation

All skills are automatically extracted from the official [NestJS documentation](https://docs.nestjs.com/) and organized for optimal use with Claude Code's skill system.

### Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

### License

MIT

---

**Created with** [Claude Code](https://claude.com/claude-code) 🤖
