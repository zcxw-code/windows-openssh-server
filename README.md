# windows-openssh-server

### Powershell as admin
```
cd $env:temp; Invoke-WebRequest -Uri https://raw.githubusercontent.com/zcxw-code/windows-openssh-server/main/install.ps1 -OutFile install-openssh.ps1; .\install-openssh.ps1
```

### Add pub keys
```
Add-Content -Path $env:ProgramData\ssh\administrators_authorized_keys -Value "" -ErrorAction Stop
```
