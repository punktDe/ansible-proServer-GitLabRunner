# proServer-GitLab-Runner

Ansible playbook to configure GitLab Runner on a proServer.

## Requirements

- Ansible >=2.3
- A proServer

## Usage example

```
ansible-playbook gitlab_runner.yaml -e gitlab_url=https://gitlab.example.com -e gitlab_runner_registration_token=ReGiStRaTiOnToKeN -i ~/my-ansible-project/inventory.ini --ask-vault-pass --limit testing
```
