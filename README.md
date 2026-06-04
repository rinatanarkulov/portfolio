# DevOps Portfolio - Rinat Anarkulov

Self-taught DevOps engineer building production-grade infrastructure on a self-hosted Kubernetes homelab.

## Featured Project: Scalable Multiplayer Game with Full CI/CD

**Tech Stack:** Jenkins, Docker, Kubernetes, Python, Flask-SocketIO, Redis, Nginx Ingress

Built an enterprise-grade, horizontally-scalable real-time multiplayer game (Infinite Tic-Tac-Toe) with complete CI/CD automation:

- **Automated Pipeline:** Code commit → Build → Test → Deploy
- **Three Environments:** Dev (auto), Staging (approval), Production (approval)
- **Real Testing:** Unit tests run in Docker, blocking deployment on failure
- **Horizontal Scaling:** 3 replicas with Redis-backed shared state
- **Session Affinity:** Cookie-based sticky sessions via Nginx Ingress for WebSocket stability
- **Resilient State:** Game data in Redis survives pod restarts
- **Startup Ordering:** Init containers ensure Redis is ready before app launch
- **Rolling Updates:** Zero-downtime deployments
- **HTTPS/TLS:** Secured with certificates

[View Code](https://github.com/rinatanarkulov/tictactoe-multiplayer)

## Other Projects

### Observability Stack: Prometheus + Grafana
**Tech Stack:** Prometheus, Grafana, ServiceMonitor, Custom Metrics

- Instrumented Flask app with custom Prometheus metrics
- Deployed full monitoring stack on Kubernetes
- Real-time visualization of application and infrastructure metrics
- Custom dashboards tracking business metrics
- Automatic service discovery via ServiceMonitor

### Ansible Automation
**Tech Stack:** Ansible, Jinja2, YAML

- Wrote playbooks for automated server configuration
- Built reusable roles (tasks, handlers, templates)
- Jinja2 templates for dynamic configuration
- Idempotent, repeatable infrastructure setup

[View Repository](https://github.com/rinatanarkulov/ansible-practice)

### Server Monitoring System
**Tech Stack:** Bash, Linux, Git

- Automated health check scripts (CPU, memory, disk, containers)
- Log rotation and cleanup automation
- Git-versioned infrastructure scripts

[View Repository](https://github.com/rinatanarkulov/monitoring-project)

### Self-Hosted Infrastructure
**Tech Stack:** Ubuntu Server, Docker, Kubernetes, AdGuard Home

- Built personal homelab from scratch on bare metal
- Configured Ubuntu Server with static IP and SSH
- Multiple services running in Kubernetes
- DNS-level ad blocking deployed via K8s
- HTTPS via Nginx Ingress with TLS certificates

## Technical Skills

**Containers & Orchestration:**
Docker, Kubernetes (microk8s), Docker Compose, multi-stage builds, init containers

**CI/CD:**
Jenkins, Pipeline as Code (Jenkinsfile), GitHub Actions, Multi-environment deployments, Manual approval gates

**Cloud-Native:**
Kubernetes namespaces, Services, Deployments, Ingress, Persistent Volumes, Rolling updates, Session affinity, Horizontal scaling

**Data & Caching:**
Redis (shared state, message broker), PostgreSQL

**Observability:**
Prometheus, Grafana, custom metrics, ServiceMonitor

**Configuration Management:**
Ansible (playbooks, roles, templates)

**Linux:**
Ubuntu Server administration, Bash scripting, systemd, networking, permissions

**Version Control:**
Git, GitHub, tokens, branching

**Programming:**
Python (Flask, SocketIO), Bash, YAML, Groovy

**Networking:**
SSH, static IP, NodePort, Ingress, DNS, TLS/HTTPS, sticky sessions

## Contact

GitHub: [@rinatanarkulov](https://github.com/rinatanarkulov)
