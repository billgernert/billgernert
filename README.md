cat > /tmp/billgernert-profile/README.md << 'EOF'
### Hi, I'm Bill 👋

I've had a passion for IT and technology my whole life. Automation, innovation, and novel concepts are what genuinely excite me. I'm the person on the team who figures things out, improves the workflow, and builds the automation nobody else wants to tackle.

I'm a Senior IT Infrastructure Engineer with over 15 years experience across Windows, Active Directory, and virtualization, including five years running a Jenkins platform as the CI/CD backbone for my team. I came up the way a lot of infrastructure folks do: I started in PowerShell, moved into Python, then Groovy, and grew into platform engineering from there. I have very strong Windows background, but I have been developing my Linux skills and find I prefer Linux.

I love being the SME, and I love showing people how things work. I write my documentation so that anyone can pick it up and understand it. No assumed context, no hand-waving. If I can't explain something simply, I take that as a sign I don't understand it well enough yet.

#### 🔧 What I'm building

**[AutomationLab](https://github.com/billgernert/parsec-lab)** is a production-grade platform engineering environment I run at home. I operate it like production: monitored, backed up, restore-tested, and automated.

The centerpiece is a **self-service server build pipeline**. One click provisions a VM from nothing. It allocates an IP from NetBox, builds the machine with Terraform, waits for an approval gate, configures it with Ansible, registers it for monitoring in Zabbix, and can cleanly tear the whole thing back down. What used to be an afternoon of manual clicking is now a button, and every step is version-controlled and auditable.

Around that I've built:
- A 5-node Proxmox cluster running K3s
- GitOps with Argo CD and CI/CD pipelines
- Infrastructure as Code with Terraform, Ansible, and Packer
- HashiCorp Vault, enterprise PKI, Entra ID SSO, and MFA across the fleet
- Self-healing automation and local AI/LLM tooling on my own GPU

**[Production Automation](https://github.com/billgernert/production-automation)** is a collection of automation projects from my professional career, written up and sanitized for public consumption.

#### ⚙️ How I work

I treat my lab the way a real platform team treats production. Everything lives in Git. Changes go through branches and pull requests with branch protection, nothing gets committed straight to main. Every pipeline is code, every secret comes from Vault, and every job runs where I can audit it. I keep a backlog in the repo and work it one item at a time, and I lean on AI tooling heavily while keeping a hard rule: I verify everything before I trust it. Fast, but never sloppy.

I build things properly, then write down what I learned along the way. Have a look, and feel free to reach out.

#### 🛠️ Technical Skills

- **Cloud & IaC:** AWS, Azure (Entra ID, Intune, O365), Terraform, Packer, Ansible
- **CI/CD & GitOps:** Jenkins (shared libraries, JCasC), Argo CD, Gitea Actions, GitOps workflows, Kaniko
- **Containers & Orchestration:** Kubernetes (K3s), Helm, Docker, cert-manager, External Secrets
- **Languages & APIs:** Python, PowerShell, Groovy, REST APIs, Microsoft Graph API, Go (familiar)
- **Identity & Security:** Active Directory, Entra ID, hybrid identity (AD Connect), SAML/OIDC SSO, MFA, Conditional Access, gMSA, HashiCorp Vault, PKI (AD CS, step-ca, Let's Encrypt)
- **Observability:** Zabbix (API automation, self-healing), Prometheus, Grafana, SCOM, SolarWinds
- **Virtualization & Network:** VMware vSphere/vSAN/Horizon, Proxmox VE (HA clusters), OPNsense, VLAN design, Cloudflare Zero Trust

#### 📫 Reach me

- 💼 [LinkedIn](https://www.linkedin.com/in/billgernert/)
EOF
