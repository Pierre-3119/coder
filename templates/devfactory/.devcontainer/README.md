# DevFactory Unified Dev Container

This folder contains a single shared devcontainer for both projects:

- backend-dotnet
- frontend-react

## Included runtime

- .NET SDK 10
- Node.js 22
- Docker-in-Docker feature

## Included support services

- PostgreSQL on port 5432
- pgAdmin on port 8888
- LDAP on port 389
- phpLDAPadmin on port 8081

## Usage

1. Open the `templates/devfactory` folder in VS Code.
2. Run `Dev Containers: Reopen in Container`.
3. Work in:
   - `/workspace/devfactory/backend-dotnet`
   - `/workspace/devfactory/frontend-react`
