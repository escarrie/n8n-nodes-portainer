# n8n-nodes-portainer

<p align="center"><br>
This Community Node is a 100% free solution, created to simplify and help the entire community to integrate and make the most of the main features offered by <b>Portainer</b> in their n8n projects.
</p>
<br>

<div align="center">
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.npmjs.org%2Fdownloads%2Fpoint%2Flast-year%2Fn8n-nodes-portainer&query=downloads&style=for-the-badge&label=Total%20de%20Downloads&labelColor=%230d1117&color=%23359514&cacheSeconds=30&link=https%3A%2F%2Fwww.npmjs.com%2Fpackage%2Fn8n-nodes-portainer" alt="Downloads Badge">
  <img src="https://img.shields.io/npm/v/n8n-nodes-portainer?style=for-the-badge&label=Versão&labelColor=%230d1117&color=%23007ACC" alt="Version Badge">
  <img src="https://img.shields.io/npm/l/n8n-nodes-portainer?style=for-the-badge&label=Licença&labelColor=%230d1117&color=%23FFA500" alt="License Badge">
</div>
<br>

<p align="center">
  <a href="mailto:contato@lumiaria.com.br"><img src="https://img.shields.io/badge/Email-Suporte-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>     
  <a href="https://github.com/ramonmatias19/n8n-nodes-portainer"><img src="https://img.shields.io/badge/GitHub-Repositório-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>     
  <a href="https://www.npmjs.com/package/n8n-nodes-portainer"><img src="https://img.shields.io/badge/NPM-Package-red?style=for-the-badge&logo=npm&logoColor=white" alt="NPM"></a>
</p>

> **Notice:** This node was developed independently to facilitate integrations with the public Portainer API in n8n.  
> It is not affiliated with, endorsed, or maintained by Portainer.  
> All mentioned trademarks belong to their respective owners.

<h1></h1>

<h3>⚙️ Requirements</h3>

To use our **Community Node**, you must meet the following requirements:  
- **N8N** version **1.54.4** or higher  
- **Node.js** version **16.0.0** or higher  
- **Active account** on **Portainer** with API token  

<h1></h1>

<h3>📌 Available Features</h3>

<h3>🐳 Containers</h3>
📝 Full Docker container management with advanced operations for creation, execution, monitoring, and lifecycle control.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new containers</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete containers</summary>
    </details>
    <details>
      <summary>   ✅ <b>Exec</b> - Execute commands in containers</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific container information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Logs</b> - Get container logs</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all containers</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Stats</b> - Get usage statistics</summary>
    </details>
    <details>
      <summary>   ✅ <b>Inspect</b> - Inspect container details</summary>
    </details>
    <details>
      <summary>   ✅ <b>Pause</b> - Pause running containers</summary>
    </details>
    <details>
      <summary>   ✅ <b>Restart</b> - Restart containers</summary>
    </details>
    <details>
      <summary>   ✅ <b>Start</b> - Start stopped containers</summary>
    </details>
    <details>
      <summary>   ✅ <b>Stop</b> - Stop running containers</summary>
    </details>
    <details>
      <summary>   ✅ <b>Unpause</b> - Unpause paused containers</summary>
    </details>
</details>

<h3>🖼️ Images</h3>
📝 Full Docker image management including build, pull, push, tag, and history analysis for complete image lifecycle control.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Build</b> - Build images from Dockerfile</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete images</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific image information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get History</b> - Get image history</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all images</summary>
    </details>
    <details>
      <summary>   ✅ <b>Inspect</b> - Inspect image details</summary>
    </details>
    <details>
      <summary>   ✅ <b>Pull</b> - Pull images from registry</summary>
    </details>
    <details>
      <summary>   ✅ <b>Push</b> - Push images to registry</summary>
    </details>
    <details>
      <summary>   ✅ <b>Tag</b> - Create tags for images</summary>
    </details>
</details>

<h3>⚙️ Services (Docker Swarm)</h3>
📝 Full Docker Swarm service management with creation, scaling, updating, and monitoring for distributed container orchestration.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new services</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete services</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific service information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Logs</b> - Get service logs</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all services</summary>
    </details>
    <details>
      <summary>   ✅ <b>Scale</b> - Scale number of replicas</summary>
    </details>
    <details>
      <summary>   ✅ <b>Update</b> - Update service settings</summary>
    </details>
</details>

<h3>🔐 Secrets (Docker Swarm)</h3>
📝 Secure management of Docker Swarm secrets for safe storage and distribution of sensitive information in services.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new secrets</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete secrets</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific secret information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all secrets</summary>
    </details>
    <details>
      <summary>   ✅ <b>Inspect</b> - Inspect secret details</summary>
    </details>
</details>

<h3>📋 Configs (Docker Swarm)</h3>
📝 Docker Swarm configs management for distributing configuration files and non-sensitive data to cluster services.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new configs</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete configs</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific config information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all configs</summary>
    </details>
    <details>
      <summary>   ✅ <b>Inspect</b> - Inspect config details</summary>
    </details>
</details>

<h3>🌐 Edge Groups</h3>
📝 Management of edge computing groups for organization and centralized control of geographically distributed endpoints.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new edge groups</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete edge groups</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific group information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all edge groups</summary>
    </details>
    <details>
      <summary>   ✅ <b>Update</b> - Update group settings</summary>
    </details>
</details>

<h3>📦 Edge Stacks</h3>
📝 Management of edge computing stacks for distributed deployment of applications across multiple edge locations.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new edge stacks</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete edge stacks</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific stack information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all edge stacks</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Status</b> - Get deployment status</summary>
    </details>
    <details>
      <summary>   ✅ <b>Update</b> - Update stack settings</summary>
    </details>
</details>

<h3>🖥️ Nodes (Docker Swarm)</h3>
📝 Docker Swarm node management for monitoring and controlling cluster nodes, including status and settings.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific node information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all nodes</summary>
    </details>
    <details>
      <summary>   ✅ <b>Inspect</b> - Inspect node details</summary>
    </details>
    <details>
      <summary>   ✅ <b>Update</b> - Update node settings</summary>
    </details>
</details>

<h3>📚 Stacks (Docker Compose)</h3>
📝 Docker Compose stack management for deployment and updating of multi-container applications defined in YAML files.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete stacks</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific stack information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all stacks</summary>
    </details>
    <details>
      <summary>   ✅ <b>Update</b> - Update stack settings</summary>
    </details>
</details>

<h3>📋 Registries</h3>
📝 Docker image registry management with support for multiple types including DockerHub, ECR, Azure, GitLab, and custom registries.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new registries</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete registries</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific registry information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all registries</summary>
    </details>
    <details>
      <summary>   ✅ <b>Update</b> - Update registry settings</summary>
    </details>
</details>

<h3>👥 Teams</h3>
📝 Portainer team management for group-based access control and collaborative permissions.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new teams</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete teams</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific team information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all teams</summary>
    </details>
    <details>
      <summary>   ✅ <b>Update</b> - Update team settings</summary>
    </details>
</details>

<h3>📄 Templates</h3>
📝 Portainer application template management for quick deployment of pre-configured applications.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific template information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all templates</summary>
    </details>
</details>

<h3>⚙️ Settings</h3>
📝 Portainer settings management including authentication, security policies, and global platform settings.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Get</b> - Get current settings</summary>
    </details>
    <details>
      <summary>   ✅ <b>Update</b> - Update settings</summary>
    </details>
</details>

<h3>🔗 Webhooks</h3>
📝 Webhook management for automation and integration with external systems through HTTP notifications.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Create</b> - Create new webhooks</summary>
    </details>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete webhooks</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all webhooks</summary>
    </details>
</details>

<h3>💻 System</h3>
📝 Portainer system information including status, version, and node information for platform monitoring.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Get Status</b> - Get system status</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Version</b> - Get Portainer version</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Nodes</b> - Get node information</summary>
    </details>
</details>

<h3>👤 Users</h3>
📝 Portainer user management for access control and account administration.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific user information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all users</summary>
    </details>
</details>

<h3>💾 Volumes</h3>
📝 Docker volume management for data persistence and sharing between containers.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete volumes</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all volumes</summary>
    </details>
</details>

<h3>🌐 Networks</h3>
📝 Docker network management for connectivity and isolation between containers.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Delete</b> - Delete networks</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all networks</summary>
    </details>
</details>

<h3>🏢 Environments</h3>
📝 Portainer environment/endpoint management for connecting to different Docker instances.
<br>
<details>
  <summary><b>List of operations</b></summary>
    <details>
      <summary>   ✅ <b>Get</b> - Get specific environment information</summary>
    </details>
    <details>
      <summary>   ✅ <b>Get Many</b> - List all environments</summary>
    </details>
</details>

<h1></h1>

<h3>🚀 Installation</h3>

**Via n8n Community Nodes:**
1. Open your n8n instance
2. Go to **Settings** → **Community Nodes**
3. Install the package: `n8n-nodes-portainer`
4. Restart n8n

**Via NPM:**
```bash
npm install n8n-nodes-portainer
```

<h1></h1>

<h3>🤝 Contribution</h3>

Contribute to the growth of this project! You can help in several ways:  
- **Pull Requests**: Submit improvements, fixes, or new features.  
- **Issues**: Report problems or suggest new ideas.  
- **Suggestions**: Share your opinions and feedback.  
- **Documentation**: Help improve or expand the existing documentation.  

<h1></h1>

<p align="center">
Developed with ❤️ by <b>Ramon Matias</b>
</p>