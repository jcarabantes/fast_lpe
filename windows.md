```powershell
systeminfo
net user
net localgroup administrators
whoami /priv
sc query
schtasks /query /fo LIST /v
tasklist /v
wmic startup get caption,command
icacls C:\ /find "BUILTIN\Users:F"
wmic product get name,version,vendor```
