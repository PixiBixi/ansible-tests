# Ansible

Ce repository contiendra mes playbooks ainsi que mes tests :-) 

## Optimisations

Le fichier de configuration se trouve dans __/etc/ansible/ansible.cfg__

```
pipelining=True
```

  * Permet de réduire le nombre de connexions SSH nécéssaires. Augmente **grandement** la rapidité d'exécution

    * Par défaut désactiver car certaines configurations nécessitant _requiretty_ posent problème

## Sources

  * Documentation officielle : [Ansible](https://docs.ansible.com/ansible/latest/playbooks_intro.html)
  * Tutoriel DeveloppeZ : [Buzut](http://buzut.developpez.com/tutoriels/ansible)