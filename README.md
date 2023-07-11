# Deploy

## Prérequis

Avoir ansible et ansible-galaxy installer sur la machine

## Configuration

Modifier l'`inventory` et mettre les serveur concerner

Puis lancer

```bash
cd ansible
ansible-galaxy install -r requirements.yml
ansible-playbook deploy.yml
```