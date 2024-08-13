Aquí tienes el output actualizado:

```bash
sudo -l
find / -perm -4000 -type f 2>/dev/null
ss -tnlp
find / -writable -type f -exec ls -l {} \; 2>/dev/null
ps aux | grep root
