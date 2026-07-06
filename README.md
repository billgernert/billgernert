### Hi, I'm Bill 👋

I've had a passion for IT and technology my whole life. Automation, innovation, and novel concepts are what genuinely excite me. I'm the person on the team who figures things out, improves the workflow, and builds the automation nobody else wants to tackle.

I'm a Senior IT Infrastructure Engineer with over 15 years experience across Windows, Active Directory, and virtualization, including five years running a Jenkins platform as the CI/CD backbone for my team. I came up the way a lot of infrastructure folks do: I started in PowerShell, moved into Python, then Groovy, and grew into platform engineering from there.

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

#### ⚙️ How I work

I treat my lab the way a real platform team treats production. Everything lives in Git. Changes go through branches and pull requests with branch protection, nothing gets committed straight to main. Every pipeline is code, every secret comes from Vault, and every job runs where I can audit it. I keep a backlog in the repo and work it one item at a time, and I lean on AI tooling heavily while keeping a hard rule: I verify everything before I trust it. Fast, but never sloppy.

I build things properly, then write down what I learned along the way. Have a look, and feel free to reach out.

#### 📫 Reach me
- 💼 [LinkedIn](https://www.linkedin.com/in/billgernert/)
