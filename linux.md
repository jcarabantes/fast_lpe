```bash
sudo -l
find $MYHOME
cat /etc/passwd
ls /opt /tmp
find / -perm -4000 -type f -ls 2>/dev/null
ss -tnlp
find / -writable -type f -exec ls -l {} \; 2>/dev/null
find / -readable -type f -exec ls -l {} \; 2>/dev/null | egrep -v "proc|kernel|snap|\/usr\/bin|\/usr\/share|devices|module"
ps aux | grep root
crontab -l
groups
```
