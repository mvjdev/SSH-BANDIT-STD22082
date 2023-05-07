# Level_22

```

ssh bandit22@bandit.labs.overthewire.org -p 2220

bandit22@bandit:~$ cd /etc/cron.d/

bandit22@bandit:/etc/cron.d$ ls

bandit22@bandit:/etc/cron.d$ cat cronjob_bandit23

bandit22@bandit:/etc/cron.d$ cat /usr/bin/cronjob_bandit23.sh

bandit22@bandit:/etc/cron.d$ /usr/bin/cronjob_bandit23.sh

bandit22@bandit:/etc/cron.d$ echo I am user bandit23 | md5sum | cut -d ‘ ‘ -f 1

bandit22@bandit:/etc/cron.d$ cat /tmp/8ca319486bfbbc3663ea0fbe81326349
QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G
```

## COMMANDE
```

ssh bandit22@bandit.labs.overthewire.org -p 2220

cd /etc/cron.d/

ls

cat cronjob_bandit23

cat /usr/bin/cronjob_bandit23.sh

/usr/bin/cronjob_bandit23.sh

echo I am user bandit23 | md5sum | cut -d ‘ ‘ -f 1

cat /tmp/8ca319486bfbbc3663ea0fbe81326349

```


## MOT DE PASSE POUR PASSER À LEVEL 23

```
password:QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G
```