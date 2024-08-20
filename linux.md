```bash
sudo -l
find $HOME
cat /etc/passwd
groups
ls -la /opt /tmp
find / -perm -4000 -type f -ls 2>/dev/null
find / -perm -6000 -type f -ls 2>/dev/null
ss -tnlp # netstat -tnlp
find / -writable -type f -ls 2>/dev/null
find / -readable -type f -ls 2>/dev/null | egrep -v "proc|kernel|snap|\/usr\/bin|\/usr\/share|devices|module"
find / -user $(whoami) -ls  2>/dev/null # dont forget to search for groups you belong
ps aux | grep root
crontab -l
```
