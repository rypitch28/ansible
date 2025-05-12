📁 Ansible Playbook Boilerplates
Welcome to my Ansible boilerplate repository. This repo serves as a centralized collection of reusable, production-ready playbooks and templates for common automation tasks.

📌 Purpose
This repository is where I store and maintain standardized boilerplates for frequently used Ansible playbooks — making it easier to spin up, configure, or manage systems across environments with consistent, version-controlled automation.

🧰 What You'll Find Here
✅ System package update & upgrade playbooks

✅ Passwordless sudo configuration

✅ Role scaffolding examples

✅ Inventory samples (YAML format)

✅ Future: Docker, Proxmox, NGINX, Cortex XDR, and more

🚀 Getting Started
Clone the repo:

bash
Copy
Edit
git clone https://github.com/rypitch28/ansible.git
cd ansible
Run a playbook:

bash
Copy
Edit
ansible-playbook -i hosts.yml playbooks/apt-upgrade.yml
Replace hosts.yml and playbooks/apt-upgrade.yml with your actual files.

🛠 Requirements
Ansible 2.10+

SSH access to target machines

(Optional) Semaphore or other Ansible automation UI

📄 License
This repository is open-sourced under the MIT License.
