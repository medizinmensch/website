+++
title = "Install Windows"
date = 2019-11-27
+++
# Choco

## Install

Cmd as **Admin**:
```bash
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

## Universal Packages (Fracky/Lenno)


```bash
choco install -y adobereader git autohotkey windirstat cmder notepadplusplus irfanview 7zip nextcloud-client everything vlc firefox sharex vscode jdk8 keepassxc discord deluge chromium
```

## Desktop Exclusive Packges (Fracky)

First, **uninstall spotify** (Windows App) as this disturbs the install of spotify via Chocolately.

```bash
choco install -y audacity steam epicgameslauncher googlephotos blender docker-desktop duplicati spotify zotero-studio minecraft ffmpeg signal teamspeak
```

### Optional
- awscli
- conemu
- postman

# Additional Software

## Manually
- Office [login page](https://login.microsoftonline.com)
- [nvidia driver](https://www.nvidia.de/Download/index.aspx?lang=de)
- (Logitech Gaming Software (9.0))


## Windows Store

* Terminal
* python3

*Desktop addons*
- Adobe Suite

# Configuration

## Logins
- nextcloud
- Firefox
    - `about:config` changes:
      - disable Alt key: set `ui.key.menuAccessKeyFocuses` to false ([source](https://support.mozilla.org/en-US/questions/1278533))
      - don't select space after double clicking a word: set `layout.word_select.eat_space_to_next_word` to false ([source](https://superuser.com/a/1623999/1277585))
      - reduce delay on download: set `security.dialog_enable_delay` to 300ms ([source](https://support.mozilla.org/en-US/questions/1176544))
- Word
- steam
- vscode: Sync Settings
- Google, Telegram, Whatsapp, ...


## setup ssh agent:

In Admin shell, run:

```powershell
Get-Service -Name ssh-agent | Set-Service -StartupType Automatic`
Start-Service ssh-agent`
ssh-add.exe C:\Users\Youri\.ssh\id_rsa
$Env:GIT_SSH=$((Get-Command -Name ssh).Source)
```

In case it's not working when login into remote machine:  Download the latest [Windows OpenSSH release](https://github.com/PowerShell/Win32-OpenSSH/releases), uncomment the last 3 lines from the `install-sshd.ps1` so that it looks like this: 


## Software

- OBS (copy backup from `%APP_DATA\Roaming\obs-studio\`)
- autohotkey standardscript ( Win+R --> "shell:startup", copy ahk link from `Nextcloud\Document\NEGASAVE` there)
- openconnect-gui (`https://vpncl.htw-berlin.de`)
- everything:
    - Settings -> Keyboard -> Show window Hotkey `Ctrl + Alt + Shift + X`

## Windows Explorer

* View:
    * -> enable "Show file name extensions"
    * -> Options: 
        * -> Open File Explorer to -> "This PC"
        * -> View -> Show hidden files, folders and drives
