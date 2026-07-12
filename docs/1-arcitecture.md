# Version 0 Architecture - (2026-07-12)
## Systems/Layers
While each layer is a modular isolated piece of the system, each should easily integrate into each while also staying true and isolated to its primary purpose. 
### 1. Workspace
Responsible for day-to-day development and work. This is where I will spend most of my time writing code and working on projects.
  - Coding (VSCode, Git, etc.)
  - AI Work
  - Documentation
### 2. Compute (Needs review) - Is my understanding that this is stuff that always needs to be on. Can you give detail on what Docker and VMs specific uses/examples are here
Responsible for continuous computations and services. Services that need to stay on continuously.
- CI/CD
- Docker
- Virtual machines
### 3. Network
Responsible for managing network tools, traffic/monitoring, security, performance, connection, and the likes. Allows me to connect anyway anytime accessing whatever I need at any point
- VPN
- Network tool
- Monitoring
### 4. Storage
Responsible for storing, maintaining, and backing up my data, files, and more. Will also be used to store other resources so my environment can be used and viable offline
- Project files
- Mass storage
- Shared storage
### 5. Operations (Needs review) - Am I understanding this correctly that it should be kind of the main hub for connecting, monitoring, and managing the whole enivornment?
Responsible for providing centralized operation center for environment management. Should provide monitoring, logging, debugging, and general system management
- Environment dashboard
- Logs, debugging, alerts, and monitoring
- Documentation
### 6. Field
Responsible for mobile and field operations and projects, as well as hardware tool production. Should still easily integrate with in-place system
- Cyberdeck
- Flipper
- Hardware tool manufacturing
- Portable network tools
