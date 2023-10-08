# Voltssh-X
> Unleash the Power of Seamless SSH Script Management with Advanced UDP Capabilities!

## Table of Contents
  - [Features](#features)
  - [Script - Supported OS](#script---supported-os)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Manually Port Blocking - UDP Custom](#manually-port-blocking---udp-custom)
  - [Disclaimer](#disclaimer)
  - [Telegram](#telegram)
  - [Credit](#credit)
---

## Features 
- UDP Custom ✅
- UDP Request ✅
- Hysteria [Legacy & v2] ❓

# Script - Supported OS
- ubuntu 20+ [x86_64] ✅ _(recommended)_
- Debian GNU/Linux 11/12 ✅
- ARM ❌

## Installation

Follow these steps to install and setup:

```
sudo -s
``` 
```
rm -f install.sh; apt-get update -y; apt-get upgrade -y; wget --no-cache "https://raw.githubusercontent.com/prjkt-nv404/VoltsshX/main/voltx.sh" -O install.sh >/dev/null 2>&1; chmod 777 install.sh;./install.sh; rm -f install.sh
```

## Usage

Here's how to call the menu:

> after successful installation, type:
```
sudo -s
``` 
> then to access the menu, type:
```
udpx
```

---

## Manually Port Blocking - UDP Custom

 * Use optional port exclude when port udp between ```1-65535``` already use by other udp tunnel, like badvpn, ovpn udp and other.
 * Edit path config ```/root/udp/config.json```, after changing it then reboot
 * Optional port exclude separated by coma, ex. ```53,5300```

_[A custom configuration, both "stream_buffer" and "receive_buffer" values are set to 209715200 bytes, which is equivalent to approximately 200MB.]_
```json
{
  "listen": ":36712",
  "stream_buffer": 209715200,
  "receive_buffer": 209715200,
  "auth": {
    "mode": "passwords"
  }
}

```

## Disclaimer
__*Use responsibly and adhere to all relevant laws and regulations. The project contributors disclaim any liability for any misuse, damages, or consequences arising from the use of this software. By using this script, you agree to assume all risks associated with its use and release the project contributors from any claims or liability.*__

---

## Telegram 
 > [💲 Pay](https://t.me/voltverifybot)

 > [👨🏽‍💻 𝚟𝚘𝚕𝚝𝚜𝚜𝚑 𝕏](https://t.me/voltsshx)

 > [📣 𝚅𝚘𝚕𝚝𝚂𝚂𝙷 𝙷𝚀 ⚝](https://t.me/voltsshhq)

## Credit

 > 

#
  > _made from pieces with ❤️_
#
