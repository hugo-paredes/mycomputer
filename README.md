# Provision MacBook Pro

```bash
# Create file to store the admin password
ansible-vault create admin_password.yml
# Execute the playbook and pass the file with the admin password
ansible-playbook playbooks/main.yml --connection-password-file admin_password.yml
```
