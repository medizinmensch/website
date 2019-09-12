# Choco

## Install

Cmd as Admin:
```bash
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

## Packages

```bash
choco install -y adobereader git autohotkey python3 windirstat cmder notepadplusplus irfanview 7zip nextcloud-client everything vlc chrome firefox sharex vscode jdk8
```

*Desktop addons*

```bash
choco install -y audacity steam googlephotos blender docker-desktop dropbox duplicati epicgameslauncher handbrake mumble putty spotify zotero nvidia-display-driver
```


### Optional
- awscli
- conemu
- postman

# Additional Software

- Office
    - [login page](https://login.microsoftonline.com)

*Desktop addons*
- Adobe Suite

# Config:

## Logins
- nextcloud
- Firefox
- Word

## Setup
- add autohotkey to startup:
    - Win+R --> "shell:startup"
    - copy ahk link there

