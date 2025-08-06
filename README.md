# Deplautoy

### Presentation

Hello, thanks for the interest given to this project. A Platform to automatically deploy microservices application.

This is the very begining of production but here's what's intended for this project.

|   Domain    |   Stack    |
|---    |:-:    |
|   CI/CD    |   Github Action    | 
|    Containerization   |   Docker + Docker Compose    |  
|    Orchestration (light)   |    k3d or Docker Compose   |  
|    Infrastructure as Code (IaC)   |    Terraform   |
|    Monitoring   |   Grafana, Prometheus and Loki    |
|    Reverse Proxy    |    Nginx   |
|    Server    |   VPS    |

---

### Developement Planning 

#### 1 - PreProduction
* Documentation Reading
* UML
* Making of a roadmap using scrum method
  
#### 2 - Create the local environment 
* Container 
* Reverse Proxy
* Monitoring and logs
* Local Deployment (CI/CD)

#### 3 - Automate installation with IaC
* Use Terraform to :
  * Feed the server
  * Automatically install the environment
  * Manage network and firwall's configuration
 
#### 4 - Pipeline Test 
With an nginx hello world test :
**GitHub → CI → Build Docker → Deploy**

#### 5 - Prepare application's ground
Structuration of the repository to make easier the incoming application implementation

---
### Then What ?

The V1 of this project will have a light Django support made to test the pipeline 

Then for the V2 of this project will have an interface from which you can select a selection of language and framework, it will install the chosen environement thanks to IaC and using the reverse proxy to redirect user to the correct route and automating the chosen unit test for a given language to perform CI/CD, it will have support for multiple language and Framework, like Laravel or React and Next.js from which users can deploy their app

---

### 06/08/25 Update

Welcome back for this quick update, right now I'm gathering all the ressources, documentation and knowledge to start this project peacefully, here's the different subjects completed:
**Languages and Environement** :
- Shell Scripting
- Virtual Machine
- Cloud Platforms such as AWS 
- Linux OS, with Ubuntu distro
**Containerization**
- Docker Volumes
- Docker Multi Stage Building
- Docker Networking
**Proxy**
- Nginx

---

Come back soon for updates !

