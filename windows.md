```powershell
gci -Recurse . | %{ $_.FullName} # search for files in your WD with credentials, etc.
systeminfo # any info that can lead u to find a CVE...
net user
net localgroup administrators
whoami /priv
sc query
schtasks /query /fo LIST /v
schtasks /query /tn "\Start Internal App" /fo LIST /v
tasklist /v
wmic startup get caption,command
icacls C:\ /find "BUILTIN\Users:F"
wmic product get name,version,vendor
netstat.exe -noa | findstr LISTEN
```
