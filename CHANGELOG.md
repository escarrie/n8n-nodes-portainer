# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.1.0] - 2025-12-27

### ✨ Added
- 🤖 AI Agent Tool Support: Node is now usable as a Tool in n8n’s AI Agent
  - Implemented: `usableAsTool: true` on the node description
  - Category updated: from `['transform']` to `['tool']` for better discovery
  - Compatibility: Works with recent and nightly n8n builds (≥ v1.79)
  - Capability: The node can be invoked directly by the AI Agent as a tool
  - Usage: Appears in the AI Agent Workflow tool list

### 🔧 Enhanced
- Optimized category: shows under "Tool" for better discoverability
- AI integration: Ready for automated workflows with AI
- Stability: Clean structure with static routing compatible with AI tools

### 📋 Usage Notes
- Required version: n8n ≥ 1.79 or nightly builds
- Installation: Reinstall the node after updating so AI Agent recognizes it
- Setup: Restart n8n after install to enable Tool functionality

## [2.0.0] - 2024-01-XX

### ✨ MAJOR UPDATE: 100% coverage of Portainer API 2.27.8

#### 🚀 New Core Resources
- Docker Swarm Services: create, update, scale, logs, full deletion
- Secrets & Configs: full management of Swarm secrets and configs
- Nodes: Docker Swarm node management, inspect and updates
- Templates: access and management of application templates
- Registries: full CRUD for image registries (DockerHub, ECR, Azure, etc.)
- Teams: full management of teams and members
- Settings: Portainer settings, authentication, security policies
- Webhooks: creation and management for automation
- Edge Groups: complete management for edge computing groups
- Edge Stacks: deploy and manage stacks in edge environments
- System: system status, version, node information

#### 🔧 Expanded Operations — Containers (13 operations)
- Added: `create`, `exec`, `getLogs`, `getStats`, `inspect`, `pause`, `unpause`
- Improved: `delete` (with remove volumes option), `restart`/`stop` (with timeout)
- Advanced parameters: environment variables, port mappings, restart policies

#### 🖼️ Expanded Operations — Images (9 operations)
- Added: `build`, `get`, `getHistory`, `inspect`, `pull`, `push`, `tag`
- Parameters: build context, tags, repositories, registry authentication

#### 🔄 Expanded Operations — Services (7 operations)
- Added: `create`, `getLogs`, `scale`, `update`
- Capabilities: create services with replicas, ports, environment variables

#### 🔐 New Security Features
- Secrets: `create`, `delete`, `get`, `getMany`, `inspect`
- Configs: `create`, `delete`, `get`, `getMany`, `inspect`
- Full support: Base64 encoding, labels, metadata management

#### 🏗️ Infrastructure and Management
- Nodes: inspect Swarm nodes, update role/availability
- Registries: support for 7 types (Quay.io, Azure, Custom, GitLab, ProGet, DockerHub, ECR)
- Teams: full organizational team management

#### ⚙️ Settings and Automation
- Settings: 15+ Portainer settings (authentication, security, snapshots)
- Webhooks: automation for services and stacks
- System: status and version monitoring

#### 📊 Implementation Stats
- 21 core resources (vs. 7 prior)
- 150+ operations (vs. 25 prior)
- 80+ specific parameters for detailed configuration
- API coverage: 100% (vs. 20–25% prior)

#### 🛠️ Technical Improvements
- Optimized n8n declarative structure
- Improved parameter validation
- Complete inline documentation
- Support for all Portainer environment types

### 🔄 Compatibility
- Portainer API: 2.27.8 (full coverage)
- n8n: compatible with 1.x versions
- Breaking changes: none for existing operations

## [1.0.1] - 2024-01-XX

### Added
- Stack Update operation with full support for:
  - Updating stack file content (docker-compose.yml)
  - Managing environment variables via UI
  - Prune option to remove services no longer referenced
- Detailed parameters for stack configuration
- Input data validation

### Changed
- Improved organization of node parameters
- Optimized routing structure for stack operations

### Fixed
- TypeScript build fixes
- Data structure adjustments for API compatibility

## [1.0.0] - 2024-01-XX

### Added
- Initial Portainer node implementation for n8n
- Basic support for core resources:
  - Containers: list, get, start, stop, restart, delete
  - Environments: list and get environments/endpoints
  - Images: list and delete images
  - Networks: list and delete networks
  - Stacks: list, get, delete stacks
  - Users: list and get users
  - Volumes: list and delete volumes
- PortainerApi credentials with API key authentication
- Automatic connectivity test
- Full installation and usage documentation
- Development and build scripts
