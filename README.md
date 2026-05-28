# DevOps Portfolio - Rinat Anarkulov

Self-taught DevOps engineer building production-grade infrastructure.

## Featured Project: Multi-Environment CI/CD Pipeline

**Tech Stack:** Jenkins, Docker, Kubernetes, Python, Flask-SocketIO, GitHub

Built a complete enterprise-grade CI/CD pipeline for a real-time multiplayer game:

- **Automated Pipeline:** Code commit → Build → Test → Deploy
- **Three Environments:** Dev (auto), Staging (approval), Production (approval)
- **Real Testing:** Unit tests run in Docker, blocking deployment on failure
- **Kubernetes Namespaces:** Isolated dev/staging/prod environments
- **Rolling Updates:** Zero-downtime deployments via kubectl
- **GitHub Integration:** SCM polling triggers builds on push

[View Tic-Tac-Toe Code](https://github.com/rinatanarkulov/tictactoe-multiplayer)

## Other Projects

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
- Multiple services running in Kubernetes (game, AdGuard, Jenkins)
- DNS-level ad blocking deployed via K8s

### Observability Stack: Prometheus + Grafana

**Tech Stack:** Prometheus, Grafana, ServiceMonitor, Custom Metrics

- Instrumented Flask app with custom Prometheus metrics
- Deployed full monitoring stack on Kubernetes
- Real-time visualization of application and infrastructure metrics
- Custom dashboards tracking business metrics (games created, moves made)
- Automatic service discovery via ServiceMonitor

### Ansible Automation
**Tech Stack:** Ansible, Jinja2, YAML

- Wrote playbooks for automated server configuration
- Built reusable roles with proper structure (tasks, handlers, templates)
- Used Jinja2 templates for dynamic configuration
- Deployed Nginx and Docker containers via automation
- Implemented idempotent, repeatable infrastructure setup

[View Repository](https://github.com/rinatanarkulov/ansible-practice)

## Technical Skills

**Containers & Orchestration:**
Docker, Kubernetes (microk8s), Docker Compose, multi-stage builds

**CI/CD:**
Jenkins, Pipeline as Code (Jenkinsfile), Multi-environment deployments, Manual approval gates

**Cloud-Native:**
Kubernetes namespaces, Services, Deployments, Persistent Volumes, Rolling updates

**Linux:**
Ubuntu Server administration, Bash scripting, systemd, user/group management, file permissions

**Version Control:**
Git, GitHub, Pull requests, branching strategies

**Programming:**
Python (Flask, SocketIO), Bash, YAML, Groovy (Jenkinsfile)

**Networking:**
SSH, static IP configuration, NodePort services, DNS, port forwarding

## Contact

GitHub: [@rinatanarkulov](https://github.com/rinatanarkulov)
