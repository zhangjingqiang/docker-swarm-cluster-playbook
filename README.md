Docker Swarm Cluster Playbook
=============================

# Usage

## Initialize Docker Swarm

```
$ ansible-playbook -i hosts init.yml
```

## Setup Stack

```
$ ansible-playbook -i hosts stack.yml
```

## Deploy Application

```
$ ansible-playbook -i hosts deploy.yml --extra-vars "repo=[REPO] tag=[TAG]"
```

# Lisence

MIT
