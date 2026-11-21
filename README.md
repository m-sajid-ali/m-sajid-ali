# Muhammad Sajid Ali
DevOps / DevSecOps Engineer — building, automating, and securing cloud-native infrastructure.

- ☁️ AWS (EKS, EC2, VPC, IAM, RDS) · Hetzner · IONOS
- ⚙️ Kubernetes · Docker · Terraform · Ansible · Traefik
- 🔁 CI/CD: Jenkins · GitHub Actions · AWS CodePipeline
- 📈 Observability: Prometheus · Grafana · CloudWatch
- 🔐 DevSecOps: Vault · SonarQube · OWASP Top 10 · threat modeling · CTF (SSRF, JWT forgery, DOM-XSS)

📫 [LinkedIn](www.linkedin.com/in/muhammad-sajid-ali-649aba107) · sajidali770@yahoo.com

### 🏭 Production Case Studies
Real systems I deployed and operated. The code is private, so the architecture, decisions and results are documented instead.
- **[University Admissions Portal](https://github.com/m-sajid-ali/case-studies/blob/main/admissions-portal.md)** — Diagnosed and fixed crashes under peak admission load (~8–12k applicants): containerized Django/Gunicorn/PostgreSQL behind Nginx, private database network, performance tuning, and centralized TLS for every app on the server.

### 🚀 Projects
- **k8s-cluster-from-scratch** — Kubernetes built from scratch: Terraform VMs, kubeadm, CNI, etcd backup/restore, upgrades
- **[domjudge-automation](https://github.com/m-sajid-ali/domjudge-automated-deployment)** — One-command deploy/stop/start/teardown of DOMjudge server + judgehosts with Docker, optional SSL, and auto-generated credentials. Used for ICPC Asia Regionals (300–400 teams) and a 1,500-student national contest.
- **devops-autograder** — Automated grading of hands-on infrastructure tasks (Node.js, React, Docker, Bash)
- **eda-containerization** — Containerized Xilinx Vivado deployed identically across 50 lab machines
- **[Sarai-e-Ilm](https://www.saraieilm.com)** — Multi-tenant managed LMS platform (Moodle): isolated per-tenant instances, automated subdomain + SSL provisioning, custom domains, daily backups with one-click restore.

### 🛡️ Capture-the-Flag — CISPA Helmholtz Center
- Solved a web-security challenge by chaining three flaws: a server-side request forgery (SSRF) allowing local file read via the `file://` scheme, sensitive data exposed in a signed-but-unencrypted JWT, and privilege escalation through a forged JWT using the `alg:none` technique.
- Solved a multi-stage cross-subdomain stored DOM-XSS challenge involving Same-Origin-Policy relaxation and `localStorage` exploitation, documenting the full attack chain from subdomain trust abuse to persistent payload delivery.
