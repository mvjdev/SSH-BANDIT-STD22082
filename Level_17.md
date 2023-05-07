# Level_17

```

ssh -p 2220 bandit17@bandit.labs.overthewire.org -p 2220

bandit17@bandit:~$ ls
passwords.new  passwords.old

bandit17@bandit:~$ diff passwords.old passwords.new
42c42
< glZreTEH1V3cGKL6g4conYqZqaEj0mte
---
> hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg

ssh bandit18@bandit.labs.overthewire.org -p 2220

bandit18@bandit.labs.overthewire.org's password:hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg

ssh bandit18@bandit.labs.overthewire.org -p 2220 -t /bin/sh
```

## COMMANDE
```

ssh -p 2220 bandit17@bandit.labs.overthewire.org -p 2220

ls

diff passwords.old passwords.new

ssh bandit18@bandit.labs.overthewire.org -p 2220

ssh bandit18@bandit.labs.overthewire.org -p 2220 -t /bin/sh

```


## MOT DE PASSE POUR PASSER À LEVEL 11

```
hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg
```