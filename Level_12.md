# Level_12

```

ssh -p 2220 bandit12@bandit.labs.overthewire.org

bandit12@bandit.labs.overthewire.org's password:JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

bandit12@bandit:~$ ls
data.txt

bandit12@bandit:~$ cat data.txt

bandit12@bandit:~$ mkdir /tmp/pavan

bandit12@bandit:~$ cp data.txt /tmp/pavan

bandit12@bandit:~$ cd /tmp/pavan

bandit12@bandit:/tmp/pavan$ ls
data.txt

bandit12@bandit:/tmp/pavan$ file data.txt
data.txt: ASCII text

bandit12@bandit:/tmp/pavan$ xxd -r data.txt data1

bandit12@bandit:/tmp/pavan$ file data1
data1: gzip compressed data, was "data2.bin", last modified: Sun Apr 23 18:04:23 2023, max compression, from Unix, original size modulo 2^32 581

bandit12@bandit:/tmp/pavan$ mv data1 data2.gz

bandit12@bandit:/tmp/pavan$ gzip -d data2.gz

bandit12@bandit:/tmp/pavan$ file data2
data2: bzip2 compressed data, block size = 900k

bandit12@bandit:/tmp/pavan$ mv data2 data3.bz2

bandit12@bandit:/tmp/pavan$ bzip2 -d data3.bz2

bandit12@bandit:/tmp/pavan$ file data3
data3: gzip compressed data, was "data4.bin", last modified: Sun Apr 23 18:04:23 2023, max compression, from Unix, original size modulo 2^32 20480

bandit12@bandit:/tmp/pavan$ mv data3 data4.gz

bandit12@bandit:/tmp/pavan$ gzip -d data4.gz

bandit12@bandit:/tmp/pavan$ file data4
data4: POSIX tar archive (GNU)

bandit12@bandit:/tmp/pavan$ tar -xvf data4
data5.bin

bandit12@bandit:/tmp/pavan$ file data5.bin
data5.bin: POSIX tar archive (GNU)

bandit12@bandit:/tmp/pavan$ tar -xvf data5.bin
data6.bin

bandit12@bandit:/tmp/pavan$ file data6.bin
data6.bin: bzip2 compressed data, block size = 900k

bandit12@bandit:/tmp/pavan$ mv data6.bin data7.bz2

bandit12@bandit:/tmp/pavan$ bzip2 -d data7.bz2

bandit12@bandit:/tmp/pavan$ file data7
data7: POSIX tar archive (GNU)

bandit12@bandit:/tmp/pavan$ tar -xvf data7
data8.bin
bandit12@bandit:/tmp/pavan$ file data8.bin
data8.bin: gzip compressed data, was "data9.bin", last modified: Sun Apr 23 18:04:23 2023, max compression, from Unix, original size modulo 2^32 49

bandit12@bandit:/tmp/pavan$ mv data8.bin data9.gz

bandit12@bandit:/tmp/pavan$ gzip -d data9.gz

bandit12@bandit:/tmp/pavan$ file data9
data9: ASCII text

bandit12@bandit:/tmp/pavan$ cat data9
The password is wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw

```

## COMMANDE
```

ssh -p 2220 bandit12@bandit.labs.overthewire.org

ls

cat data.txt

mkdir /tmp/pavan

cp data.txt /tmp/pavan

cd /tmp/pavan

ls

file data.txt

xxd -r data.txt data1

file data1

mv data1 data2.gz

gzip -d data2.gz

file data2

mv data2 data3.bz2

bzip2 -d data3.bz2

file data3

mv data3 data4.gz

gzip -d data4.gz

file data4

tar -xvf data4

file data5.bin

tar -xvf data5.bin

file data6.bin

mv data6.bin data7.bz2

bzip2 -d data7.bz2

file data7

tar -xvf data7

file data8.bin

mv data8.bin data9.gz

gzip -d data9.gz

file data9

cat data9
```


## MOT DE PASSE POUR PASSER À LEVEL 13

```
password :wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
```