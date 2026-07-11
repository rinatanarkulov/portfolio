# DevOps Portfolio — Rinat Anarkulov

Self-taught DevOps engineer building production-style infrastructure on a self-hosted, multi-node Kubernetes homelab.

## Featured: Scalable Multiplayer Game — Full CI/CD + Autoscaling
**Stack:** Jenkins · Docker · Kubernetes · Python · Flask-SocketIO · Redis · Nginx Ingress · Cloudflare

A horizontally-scalable real-time multiplayer game, deployed to production on my own cluster and reachable on the public internet.

- **Autoscaling:** Kubernetes HPA scales the app from 2 to 12 pods based on live CPU load, verified under load testing (2 → 10 → 2)
- **Multi-node:** pods load-balanced across bare-metal nodes; scale-up distributes work to the least-busy node
- **CI/CD:** Jenkins pipeline — build, test, and promotion across dev → staging → prod with manual approval gates
- **Shared state:** Redis backs game state so any pod can serve any player; cookie-based session affinity via Nginx Ingress keeps WebSockets stable
- **Public hosting:** exposed securely via Cloudflare Tunnel on a custom domain, HTTPS end-to-end, no ports opened on the home network
- **Live demo:** [tictactoe.rinatanarkulov.com](https://tictactoe.rinatanarkulov.com) — three game modes with real-time mode switching, live scores, and player names

[View Code](https://github.com/rinatanarkulov/tictactoe-multiplayer)

## Self-Hosted Multi-Node Infrastructure
**Stack:** Ubuntu Server · Kubernetes (MicroK8s) · Docker · Private Registry

- Multi-node Kubernetes cluster built from bare-metal hardware, joining worker nodes to a control plane
- **Private container registry with TLS**, distributing images across all nodes
- metrics-server + resource requests/limits enabling CPU-based autoscaling
- Ubuntu Server administration: static IP (netplan), SSH, systemd, LVM storage, safe node draining and rolling reboots
- DNS-level ad blocking (AdGuard Home) deployed via K8s

## Observability Stack: Prometheus + Grafana
**Stack:** Prometheus · Grafana · ServiceMonitor
- Custom application metrics, ServiceMonitor auto-discovery, Grafana dashboards

## Infrastructure Automation with Ansible
**Stack:** Ansible · Jinja2 · YAML
- Reusable roles and idempotent playbooks for automated server configuration

[Ansible repo](https://github.com/rinatanarkulov/ansible-practice) · [Monitoring repo](https://github.com/rinatanarkulov/monitoring-project)

## Technical Skills
**Containers & Orchestration:** Docker, Kubernetes (MicroK8s), multi-node clusters, HPA autoscaling, private registry, init containers
**CI/CD:** Jenkins, GitHub Actions, multi-environment pipelines, approval gates
**Cloud-Native:** Ingress, Services, Deployments, session affinity, horizontal scaling, resource limits, Persistent Volumes
**Data & Observability:** Redis, PostgreSQL, Prometheus, Grafana
**Automation & Linux:** Ansible, Bash, Ubuntu Server, systemd, networking
**Networking & Hosting:** Nginx Ingress, TLS/HTTPS, Cloudflare Tunnel, DNS
**Programming:** Python (Flask), Bash, YAML, Groovy

## Contact
GitHub: [@rinatanarkulov](https://github.com/rinatanarkulov)
