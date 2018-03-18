# Ansible

Ce repository contiendra mes playbooks ainsi que mes tests :-) 

## Optimisations

Le fichier de configuration se trouve dans __/etc/ansible/ansible.cfg__

```
pipelining=True
```

  * Réduit le nombre de connexions SSH nécéssaires. Augmente **grandement** la rapidité d'exécution

    * Par défaut désactiver car certaines configurations nécessitant _requiretty_ posent problème

```
retry_files_enabled = False
```

  * Désactive la création de .retry lorsque la connexion à certains hosts échoue

## Sources

  * Documentation officielle : [Ansible](https://docs.ansible.com/ansible/latest/playbooks_intro.html)
  * Tutoriel DeveloppeZ : [Buzut](http://buzut.developpez.com/tutoriels/ansible)