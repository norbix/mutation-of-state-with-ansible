# mutation-of-state-with-ansible

## General info

Demonstrates the usage of Ansible for the state mutation use case within IaC. paradigm.

### Structure

- **inventory/** contains hosts managed
- **roles/** contains stub Ansible module (ansible galaxy repo as well) 

## Dry run 

Evaluates payloads with dry run.

```shell 
ansible-playbook ./mailserver_playbook.yml --check
```
