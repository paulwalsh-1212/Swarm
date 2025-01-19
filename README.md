# Swarm Project

This is the **Swarm** project, a distributed system for managing clusters, tasks, and agents.

## Directory Structure
- **api/**: API definitions and OpenAPI specs.
- **cmd/**: CLI commands for swarm, swarmd, and swarmctl.
- **pkg/**: Core libraries for the project.
- **internal/**: Internal utilities such as caching, queuing, and webhooks.
- **test/**: Test cases (e2e, integration, and unit).
- **tools/**: Tools for CLI and code generation.
- **web/**: API and UI for the project.
- **.github/**: CI/CD workflows and templates.

## Build Instructions
Run the following commands to build:
```bash
make build
```

## License
[MIT License](LICENSE)
