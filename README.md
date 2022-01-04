# ListIISApps

POWERSHELL

```
Import-Module Webadministration
Get-ChildItem -Path IIS:\Sites
```

CMD


```
Cd %windir%\system32\inetsrv
appcmd list site > c:\sites-list.txt
```
