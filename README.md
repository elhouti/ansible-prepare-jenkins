# Automatisation de l'approvisionnement, installation et configuration de Jenkins sur un serveur distant using Ansible.

Pour faire il suffit de suivre ces étapes:
```
$ git clone git@github.com:elhouti/ansible-prepare-jenkins.git && cd ansible-prepare-jenkins
```

```
$ ansible-galaxy install -r requirements.yml
```

```
$ ansible-playbook -i inventory.ini provision.yml --ask-pass --ask-become-pass --become-method=su
```
