# Hi, I'm Mohamed Newish

**DevOps Engineer** · M.Sc. Embedded Systems student at TU Chemnitz · Chemnitz, Germany

DevOps engineer focused on container orchestration with **Docker** and **Kubernetes (AWS EKS)**, release management with **Helm**, and automating deployments through **CI/CD pipelines** (Jenkins, GitHub Actions) and **Infrastructure as Code** (Terraform) on AWS. Confident on Linux and with Bash automation.

## Currently

**DevOps Engineer** — Ambos Security GmbH, Dohna · since 05/2026

- Software and infrastructure architecture for productive operation
- Automated build and delivery with GitHub Actions, backed by a self-operated container registry
- Release and update processes, with certificate and PKI services securing delivery

## Featured Projects

### [journey-app-devops](https://github.com/Mohamed-Newish/journey-app-devops)
End-to-end CI/CD pipeline for a full-stack app on **AWS EKS**. Node.js/Express + PostgreSQL + Nginx, containerised with Docker and released with **Helm** through a **Jenkins** pipeline: image build, push to Docker Hub and Helm release on every git push. Zero-downtime rolling updates, path routing via NGINX Ingress (`/` frontend, `/api` backend), credentials in Kubernetes Secrets.

`Docker` · `Kubernetes` · `Helm` · `Jenkins` · `AWS EKS` · `NGINX Ingress` · `PostgreSQL`

### [portfolio-flask-docker](https://github.com/Mohamed-Newish/portfolio-flask-docker)
Containerised Flask application with an automated **GitHub Actions** CI pipeline that gates the deploy on a health check. Served by Gunicorn, deployed on **AWS EC2**.

`Flask` · `Docker` · `GitHub Actions` · `AWS EC2` · `Gunicorn`

### [shortly-chart](https://github.com/Mohamed-Newish/shortly-chart)
Helm chart for a multi-service app (API, frontend, Postgres, Redis), reconciled into Kubernetes by **ArgoCD** — GitOps rather than push-based deploys: Git is the source of truth, drift is detected and self-healed, and a `git push` is the deployment.

`Helm` · `ArgoCD` · `GitOps` · `Kubernetes` · `StatefulSets` · `Ingress`

## Application Security

**Certified AppSec Practitioner (CAP)** — The SecOps Group, 02/2023

Web application testing against authorized bug-bounty programs, OWASP Top 10, reproducing and documenting findings for developers. Tooling: Burp Suite, nmap, sqlmap, ffuf, the ProjectDiscovery stack (subfinder, httpx, naabu, katana), Linux/Kali.

### [sharingan-go](https://github.com/Mohamed-Newish/sharingan-go)
Recon orchestrator in Go — a rewrite of a Bash recon pipeline. An adaptive rate limiter, circuit breaker and WAF fingerprinting tune the load to how the target responds. Four modes behind separate scope gates (passive, active, origin-IP discovery, block isolation); drives established tools (subfinder, naabu, katana, jsluice) and skips missing ones cleanly.

`Go` · `concurrency` · `rate limiting` · `tool orchestration`

### [byakugan](https://github.com/Mohamed-Newish/byakugan)
Content inspection pipeline and companion to sharingan-go: seven concurrent phases for screenshots, path/parameter wordlists, SQLi and XSS candidates, and secrets in page source.

`Bash` · `concurrent phases` · `toolchain integration`

## Tech

**Containers & Orchestration:** Docker · Docker Compose · Kubernetes (AWS EKS) · Helm
**CI/CD & Automation:** Jenkins · GitHub Actions · ArgoCD · Terraform · container registry operation · Git
**Cloud & Networking:** AWS (EC2, EKS, VPC, load balancers, IAM) · TCP/IP · DNS · HTTP/HTTPS · NGINX Ingress · reverse proxy
**Systems:** Linux (Ubuntu/Debian) administration · Bash automation · cron · systemd · logging & troubleshooting
**Monitoring & Databases:** Prometheus · Grafana · PostgreSQL
**Programming:** Bash · Python · Go · JavaScript

## Education

- **M.Sc. Embedded Systems** — Chemnitz University of Technology (TU Chemnitz), 10/2025 – present
- **B.Sc. Electrical Engineering** — Faculty of Engineering Shoubra, Benha University, 09/2019 – 04/2024

## Languages

German B1 · English fluent · Arabic native

## Connect

- LinkedIn: [Mohamed Newish](https://www.linkedin.com/in/mohamed-newish-8470a5395)
- Email: mohamedsayed2646@gmail.com

<!-- profile -->
