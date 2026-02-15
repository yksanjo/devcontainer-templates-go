# Dev Container Template - Go

Pre-configured containerized development environment for Go applications.

## Features

- **Go 1.21** with Go modules
- **GoLand** language server (gopls)
- **golangci-lint** for linting
- **gotests** for testing
- **gofmt** for formatting
- **GitLens** for Git integration
- **SQLTools** for database management

## Quick Start

1. Copy `.devcontainer` folder to your project root
2. Open the project in VS Code
3. Press `F1` and select **"Dev Containers: Reopen in Container"**

## Configuration

### Ports
- `3000` - Application server
- `8080` - Alternative HTTP port
- `9090` - Debug/Metrics port

### Extensions Included
- Go (golang.go)
- PowerShell
- Docker
- SQLTools
- IntelliCode
- GitLens
- Resource Romulator

### Post-Create Commands
- Installs gotests
- Installs golint
- Shows Go version

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [VS Code](https://code.visualstudio.com/)
- [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## License

MIT
