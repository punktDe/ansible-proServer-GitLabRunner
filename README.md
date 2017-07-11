# proServer-GitLab-Runner

Ansible role to provision GitLab Runner on a proServer.

## Requirements

- Ansible >=2.3
- A proServer

## Configuration

```yml
---
gitlab_runner:
  ci_url: "https://gitlab.example.com/ci"
  registration_token: ReGiStRaTiOnToKeN
```
