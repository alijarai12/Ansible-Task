
## Prerequisites

Before running the playbook, ensure you have the following installed and configured:

1. **Install Ansible**  
   Ansible must be installed on your local machine to run the playbook. You can install it by following the [official installation guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html).

2. **Install Ansible Collections and AWS Plugin**  
   Install the necessary AWS Ansible collection and AWS plugin to manage EC2 provisioning and DNS configurations.
   ```bash
   ansible-galaxy collection install amazon.aws
   ansible-galaxy collection install cloudflare.cloudflare
