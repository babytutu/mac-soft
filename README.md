# Awesome Soft for macOS

| Name | Desc | Links |
| -------- | ------------------ | ----------------------------------- |
| Visual Studio Code | Coding Editor | [Official Website](https://code.visualstudio.com/) |
| Oh-My-Zsh | Terminal | [Official Website](http://ohmyz.sh/)  |
| Node.js | JavaScript Runtime Built | [Official Website](https://nodejs.org/en/) |
| Git | Version Control System | [Official Website](https://git-scm.com/) |
| Sourcetree | Git GUI | [Official Website](https://www.sourcetreeapp.com/) |
| Charles | Official Website Debugging Proxy | [Official Website](https://www.charlesproxy.com/)  |
| Magnet | Window manager | [Official Website](http://magnet.crowdcafe.com/) |
| NTFS_for_Mac | Paragon Driver（Seagate） | [Download](https://www.seagate.com/cn/zh/support/software/paragon/)|
| Typora | Markdown Editor | [Official Website](https://www.typora.io/) |
| Dash | API Documentation Browser | [Official Website](https://kapeli.com/dash) |
| Linphone | SIP Soft | [Official Website](http://www.linphone.org/) |
| Zoiper |SIP Soft | [Official Website](https://www.zoiper.com/) |

## Key

### Charles

```
Registered Name:https: //zhile.io
License Key: 48891cf209c6d32bf4
```

### Axure RP 9

Turn your Internet connection OFF, install, register. Turn Internet connection on again when registration is finished.

Block outgoing connections with firewall

```
Pro edition:

Licensee: speedzodiac
Key: aPPDTWFbeBCDl3pdgeOQB15Z4CUGy3JDsQPktJ+/dVQRNmwTmsJZEDlslIyTVJ03


Team edition:

Licensee: speedzodiac
Key: o6hDTBsTUOCg4+iSPfjL8QkM73kG+oHYiXWjEEyNGJ6JdPimk7c6Sy9fQDm8KXNc



Enterprise edition:

Licensee: speedzodiac
Key: UpzmG6yPo/QyZbu4vhiNe5+Oy9U57YGqW6hglQC1B2uF1eHScD70uAHbZ+Gza0tf
```



## VScode Plugins

- GitLens

- Git Project Manager

- One Dark Pro

- Path Intellisense

- vetur

- vscode-icons

- volar



## V2rayU Subscribe URL

https://v2.itlao5.com/v2


## Office Download URL

### Office 2019
https://officecdn-microsoft-com.akamaized.net/pr/C1297A47-86C4-4C1F-97FA-950631F94777/MacAutoupdate/Microsoft_Office_16.39.20071300_Installer.pkg


### Office 2021
https://officecdn-microsoft-com.akamaized.net/pr/C1297A47-86C4-4C1F-97FA-950631F94777/MacAutoupdate/Microsoft_Office_16.62.22061100_Installer.pkg

### Office_License_Removal

https://officecdn-microsoft-com.akamaized.net/pr/C1297A47-86C4-4C1F-97FA-950631F94777/MacAutoupdate/Microsoft_Office_License_Removal_2.6.pkg


## Homebrew

```bash
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```

### Install App

e.g.

```
brew install tree
```

### Error

```
Error: The following directories are not writable by your user:
/usr/local/share/doc
/usr/local/share/man
/usr/local/share/man/man1
```

Fix it

```
sudo chown -R $(whoami) /usr/local/share
```

## oh-my-zsh

```bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

mirror in mainland China

```bash
sh -c "$(wget -O- https://gitee.com/mcornella/ohmyzsh/raw/master/tools/install.sh)"
```

### Error

#### Error

```
Insecure completion-dependent directories detected:
/usr/local/share/zsh
/usr/local/share/zsh/site-functions
```

To fix your permissions，set the variable ZSH_DISABLE_COMPFIX to "true"

```bash
nano ~/.zshrc
```

```
ZSH_DISABLE_COMPFIX="true"
```

Reload Setting

```bash
source .zshrc
```