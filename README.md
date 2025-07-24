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

Come back soon for updates !

