Docker Swarm Cluster Playbook
=============================

# Usage

## Initialization

```
$ ansible-playbook -i hosts init.yml
```

## Deployment

```
$ ansible-playbook -i hosts deploy.yml --extra-vars "repo=[REPO] tag=[TAG]"
```

# Lisence

MIT
