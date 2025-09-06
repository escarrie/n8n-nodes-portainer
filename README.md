# n8n-nodes-portainer

<p align="center"><br>
This Community Node is a 100% free solution to help the community integrate and make the most of the features offered by <b>Portainer</b> in your n8n workflows.
</p>
<br>

<div align="center">
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.npmjs.org%2Fdownloads%2Fpoint%2Flast-year%2Fn8n-nodes-portainer&query=downloads&style=for-the-badge&label=Total%20Downloads&labelColor=%230d1117&color=%23359514&cacheSeconds=30&link=https%3A%2F%2Fwww.npmjs.com%2Fpackage%2Fn8n-nodes-portainer" alt="Downloads Badge">
  <img src="https://img.shields.io/npm/v/n8n-nodes-portainer?style=for-the-badge&label=Version&labelColor=%230d1117&color=%23007ACC" alt="Version Badge">
  <img src="https://img.shields.io/npm/l/n8n-nodes-portainer?style=for-the-badge&label=License&labelColor=%230d1117&color=%23FFA500" alt="License Badge">
</div>
<br>

<p align="center">
  <a href="mailto:contato@lumiaria.com.br"><img src="https://img.shields.io/badge/Email-Support-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/ramonmatias19/n8n-nodes-portainer"><img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://www.npmjs.com/package/n8n-nodes-portainer"><img src="https://img.shields.io/badge/NPM-Package-red?style=for-the-badge&logo=npm&logoColor=white" alt="NPM"></a>
</p>

> Note: This node was developed independently to simplify integrations with Portainer’s public API in n8n.  
> It is not affiliated with, endorsed, or maintained by Portainer.  
> All trademarks mentioned belong to their respective owners.

<h1></h1>

<h3>⚙️ Requirements</h3>

To use this Community Node, you need:  
- n8n version 1.54.4 or higher  
- Node.js version 16.0.0 or higher  
- An active Portainer account with an API token  

<h1></h1>

<h3>📌 Available Resources</h3>

<h3>🐳 Containers</h3>
📝 Full Docker container management including creation, execution, monitoring, and lifecycle control.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
    <summary>   ✅ <b>Get Logs</b> - Retrieve container logs</summary>
  </details>
  <details>
    <summary>   ✅ <b>Get Many</b> - List all containers</summary>
  </details>
  <details>
    <summary>   ✅ <b>Get Stats</b> - Get resource usage statistics</summary>
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
📝 Full Docker image management including build, pull, push, tag, and history inspection for complete image lifecycle control.
<br>
<details>
  <summary><b>Operation list</b></summary>
  <details>
    <summary>   ✅ <b>Build</b> - Build images from a Dockerfile</summary>
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
    <summary>   ✅ <b>Pull</b> - Pull images from a registry</summary>
  </details>
  <details>
    <summary>   ✅ <b>Push</b> - Push images to a registry</summary>
  </details>
  <details>
    <summary>   ✅ <b>Tag</b> - Create tags for images</summary>
  </details>
</details>

<h3>⚙️ Services (Docker Swarm)</h3>
📝 Full Docker Swarm service management: creation, scaling, updating, monitoring, and lifecycle operations for distributed containers.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
    <summary>   ✅ <b>Get Logs</b> - Retrieve service logs</summary>
  </details>
  <details>
    <summary>   ✅ <b>Get Many</b> - List all services</summary>
  </details>
  <details>
    <summary>   ✅ <b>Scale</b> - Scale number of replicas</summary>
  </details>
  <details>
    <summary>   ✅ <b>Update</b> - Update service configuration</summary>
  </details>
</details>

<h3>🔐 Secrets (Docker Swarm)</h3>
📝 Secure management of Docker Swarm secrets for safely storing and distributing sensitive data to services.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
📝 Manage Docker Swarm configs for distributing configuration files and non-sensitive data to services in the cluster.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
📝 Manage edge computing groups for centralized organization and control of geographically distributed endpoints.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
    <summary>   ✅ <b>Update</b> - Update group configuration</summary>
  </details>
</details>

<h3>📦 Edge Stacks</h3>
📝 Manage edge computing stacks for distributing application deployments across multiple edge locations.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
    <summary>   ✅ <b>Update</b> - Update stack configuration</summary>
  </details>
</details>

<h3>🖥️ Nodes (Docker Swarm)</h3>
📝 Manage Docker Swarm nodes for monitoring and controlling cluster nodes, including status and configuration.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
    <summary>   ✅ <b>Update</b> - Update node configuration</summary>
  </details>
</details>

<h3>📚 Stacks (Docker Compose)</h3>
📝 Manage Docker Compose stacks for deploying and updating multi-container applications defined in YAML files.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
    <summary>   ✅ <b>Update</b> - Update stack configuration</summary>
  </details>
</details>

<h3>📋 Registries</h3>
📝 Manage Docker image registries supporting multiple providers including DockerHub, ECR, Azure, GitLab, and custom registries.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
    <summary>   ✅ <b>Update</b> - Update registry configuration</summary>
  </details>
</details>

<h3>👥 Teams</h3>
📝 Manage Portainer teams for group-based access control and collaborative permissions.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
    <summary>   ✅ <b>Update</b> - Update team configuration</summary>
  </details>
</details>

<h3>📄 Templates</h3>
📝 Manage Portainer application templates for quick deployment of preconfigured applications.
<br>
<details>
  <summary><b>Operation list</b></summary>
  <details>
    <summary>   ✅ <b>Get</b> - Get specific template information</summary>
  </details>
  <details>
    <summary>   ✅ <b>Get Many</b> - List all templates</summary>
  </details>
</details>

<h3>⚙️ Settings</h3>
📝 Manage Portainer settings including authentication, security policies, and global platform configuration.
<br>
<details>
  <summary><b>Operation list</b></summary>
  <details>
    <summary>   ✅ <b>Get</b> - Get current settings</summary>
  </details>
  <details>
    <summary>   ✅ <b>Update</b> - Update settings</summary>
  </details>
</details>

<h3>🔗 Webhooks</h3>
📝 Manage webhooks for automation and integration with external systems via HTTP notifications.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
📝 Portainer system information including status, version, and node details for platform monitoring.
<br>
<details>
  <summary><b>Operation list</b></summary>
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
📝 Manage Portainer users for access control and account administration.
<br>
<details>
  <summary><b>Operation list</b></summary>
  <details>
    <summary>   ✅ <b>Get</b> - Get specific user information</summary>
  </details>
  <details>
    <summary>   ✅ <b>Get Many</b> - List all users</summary>
  </details>
</details>

<h3>💾 Volumes</h3>
📝 Manage Docker volumes for data persistence and sharing across containers.
<br>
<details>
  <summary><b>Operation list</b></summary>
  <details>
    <summary>   ✅ <b>Delete</b> - Delete volumes</summary>
  </details>
  <details>
    <summary>   ✅ <b>Get Many</b> - List all volumes</summary>
  </details>
</details>

<h3>🌐 Networks</h3>
📝 Manage Docker networks for connectivity and isolation between containers.
<br>
<details>
  <summary><b>Operation list</b></summary>
  <details>
    <summary>   ✅ <b>Delete</b> - Delete networks</summary>
  </details>
  <details>
    <summary>   ✅ <b>Get Many</b> - List all networks</summary>
  </details>
</details>

<h3>🏢 Environments</h3>
📝 Manage Portainer environments/endpoints to connect to different Docker instances.
<br>
<details>
  <summary><b>Operation list</b></summary>
  <details>
    <summary>   ✅ <b>Get</b> - Get specific environment information</summary>
  </details>
  <details>
    <summary>   ✅ <b>Get Many</b> - List all environments</summary>
  </details>
</details>

<h1></h1>

<h3>🚀 Installation</h3>

<b>Via n8n Community Nodes:</b>
1. Open your n8n instance
2. Go to <b>Settings</b> → <b>Community Nodes</b>
3. Install the package: `n8n-nodes-portainer`
4. Restart n8n

<b>Via NPM:</b>
```bash
npm install n8n-nodes-portainer
```

<h1></h1>

<h3>🤝 Contributing</h3>

Contributions are welcome! You can help by:  
- <b>Pull Requests</b>: Submit improvements, fixes, or new features.  
- <b>Issues</b>: Report problems or suggest new ideas.  
- <b>Suggestions</b>: Share feedback and opinions.  
- <b>Documentation</b>: Improve or expand the existing docs.  

<h1></h1>

<p align="center">
Built with ❤️ by <b>Ramon Matias</b>
</p>

