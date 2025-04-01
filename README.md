Ansible Roles and Playbooks Assignment
# Ansible Roles and Playbooks Assignment

This repository contains all the Ansible roles and playbooks that I created during class assignments. The goal of this project is to showcase my practical skills in using Ansible. I am able to do this because I have an amazing tutor.

---

## Repository Structure

- **roles/**  
  Contains the custom Ansible roles developed during class.  
  Examples:
  - `role_database/` - Role for configuring and managing database servers.
  - `role_webserver/` - Role for setting up web server configurations.
  - `role_monitoring/` - Role for deploying monitoring tools.

- **playbooks/**  
  Contains playbooks that orchestrate these roles and tasks.  
  Examples:
  - `site.yml` - The main playbook to apply the complete configuration.
  - `deploy_db.yml` - Playbook for deploying and configuring the database.
  - `deploy_web.yml` - Playbook for setting up the web server.

- **inventory/**  
  Contains the inventory file listing the target hosts (or groups) on which the playbooks will run.

- **docs/**  
  Contains documentation for each role and guidelines on how to use the playbooks.

---

## How to Use

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Stephanie3107/ansible-roles-playbooks.git
   cd ansible-roles-playbooks`
