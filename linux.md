List a fast LPE commands

```bash
sudo -l
find / -perm -4000 -type f 2>/dev/null
ss -tnlp
find / -writable -type f -exec ls -l {} \; 2>/dev/null
find / -readable -type f -exec ls -l {} \; 2>/dev/null | egrep -v "proc|kernel"
ps aux | grep root
```
