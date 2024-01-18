# windows-openssh-server

### Powershell as admin
```
cd $env:temp; Invoke-WebRequest -Uri https://raw.githubusercontent.com/zcxw-code/windows-openssh-server/main/install.ps1 -OutFile install-openssh.ps1; .\install-openssh.ps1
```

### Add pub keys
```
Add-Content -Path ~\.ssh\authorized_keys -Value "PUB" -ErrorAction Stop

OR


code ~\.ssh\authorized_keys
```
