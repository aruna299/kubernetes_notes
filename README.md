# kubernetes_notes

## What is Kubernetes

- Kubernetes is an open source platform designed to automate the deployement, scaling, and managment of containerized applications, developed oroginally by google and now maintained by cloud native competion.
- Automated deployments and rollback
- Kubernetes manages the deployment of your applications and we can roll back changes automatically in case of failures
- It allows horizontal scaling of applications based on demand using metrics and memory usage
- It automatically assigns ip address and DNS names to services and balances traffic between containers in case of failing
- It will automatically restarts failed containers replace unresponsiveness once and kills containers that failed health check
- It supports mounting local storage, public cloud storage, and network attached storage to your containers
- Kubernetes helps to secuely manage sensitive data and application configuration seperately from application code
- It can run across on premisis, multi cloud, hybrid, public , private cloud environments

  ## Core Components
  - POD --> The smallest deployable unit, typically representing single container or group of tightly coupled containers
  - NODE --> A worker machine either physical or virtual
  - Cluster --> A group of nodes
  - deployment --> describes the desired state of Pods and manages their updates
  - service --> Exposes and application running on a set of pods to external traffic or internal componenets
  - config map & secrets --> tools to manage configuration and sensitive data respectively
  - 
