# Choco

## Install

Cmd as Admin:
```bash
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

## Universal Packages (Fracky/Lenno)

```bash
choco install -y adobereader git autohotkey windirstat cmder notepadplusplus irfanview 7zip nextcloud-client everything vlc chrome firefox sharex vscode jdk8 keepassxc
```

## Desktop Exclusive Packges (Fracky)

```bash
choco install -y audacity steam epicgameslauncher googlephotos blender docker-desktop duplicati spotify zotero nvidia-display-driver obs-studio filezilla minecraft ffmpeg openconnect-gui nodejs
```

### Optional
- awscli
- conemu
- postman

# Additional Software

## Manual
- Office
    - [login page](https://login.microsoftonline.com)
- Logitech Gaming Software (9.0)

## Windows Store

* Terminal
* python3
* ...

*Desktop addons*
- Adobe Suite

# Config:

## Logins
- nextcloud
- Firefox
- Word
- steam
- vscode: Sync Settings


## setup ssh agent:

In Admin shell, run:

```powershell
Get-Service -Name ssh-agent | Set-Service -StartupType Automatic`
Start-Service ssh-agent`
ssh-add.exe C:\Users\Youri\.ssh\id_rsa
```

In case it's not working when login into remote machine:  Download the latest [Windows OpenSSH release](https://github.com/PowerShell/Win32-OpenSSH/releases), uncomment the last 3 lines from the `install-sshd.ps1` so that it looks like this: 


## Software

- OBS
- autohotkey standardscript ( Win+R --> "shell:startup", copy ahk link there)
- openconnect-gui (`https://vpncl.htw-berlin.de`)
- everything


