# DevOps Portfolio — Rinat Anarkulov

Self-taught DevOps engineer building production-style infrastructure on a self-hosted, multi-node Kubernetes homelab.

## Featured: Scalable Multiplayer Game with Full CI/CD
**Stack:** Jenkins · Docker · Kubernetes · Python · Flask-SocketIO · Redis · Nginx Ingress

A horizontally-scalable real-time multiplayer game (Infinite Tic-Tac-Toe) built with production-style CI/CD automation.
- Code commit → Build → Test → Deploy
- Dev / Staging / Prod environments with approval gates
- Unit tests in Docker block bad deploys
- 3 replicas with Redis-backed shared state
- Cookie-based session affinity via Nginx Ingress for WebSocket stability
- Init containers for startup ordering; HTTPS/TLS

[View Code](https://github.com/rinatanarkulov/tictactoe-multiplayer)

## Other Projects

### Self-Hosted Multi-Node Infrastructure
**Stack:** Ubuntu Server · Kubernetes · Private Registry
- Multi-node MicroK8s cluster built from bare-metal hardware
- Private container registry with TLS, distributing images across nodes
- Ubuntu Server: static IP (netplan), SSH, systemd, LVM storage
- HTTPS via Nginx Ingress with TLS certificates
- DNS-level ad blocking (AdGuard Home) deployed via K8s

### Observability Stack: Prometheus + Grafana
**Stack:** Prometheus · Grafana · ServiceMonitor
- Custom application metrics, ServiceMonitor auto-discovery, Grafana dashboards

### Ansible Automation
**Stack:** Ansible · Jinja2 · YAML
- Reusable roles (tasks, handlers, templates); idempotent playbooks

[View Repository](https://github.com/rinatanarkulov/ansible-practice)

### Server Monitoring System
**Stack:** Bash · Linux · Git
- Health-check scripts (CPU, memory, disk, containers); log rotation; Git-versioned

[View Repository](https://github.com/rinatanarkulov/monitoring-project)

## Technical Skills
**Containers & Orchestration:** Docker, Kubernetes (MicroK8s), multi-node clusters, private registry, init containers
**CI/CD:** Jenkins, GitHub Actions, multi-environment pipelines, approval gates
**Cloud-Native:** Ingress, Services, Deployments, session affinity, horizontal scaling, Persistent Volumes
**Data & Observability:** Redis, PostgreSQL, Prometheus, Grafana
**Automation & Linux:** Ansible, Bash, Ubuntu Server, systemd, networking
**Version Control:** Git, GitHub
**Programming:** Python (Flask, SocketIO), Bash, YAML, Groovy

## Contact
GitHub: [@rinatanarkulov](https://github.com/rinatanarkulov)
