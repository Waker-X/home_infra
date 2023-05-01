## Ansible playbook for deploy components my smarthome
### Get started
```shell
python3 -m venv venv
python3 install -r requirements.txt
ansible-galaxy install -r requirements.yml
ansible-playbook germes.yml -i hosts.yml --vault-password-file .vault.txt
```
