## Supported Operating Systems

- Debian: Version 10 and newer
- Ubuntu: Version 20.04 and newer

## Update & Upgrade First Your VPS for Debian
  ```html
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot

  ```

## Update & Upgrade First Your VPS for Ubuntu

  ```html
  apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && sleep 2 && reboot

```
## INSTALLATION SCRIPT
```
apt update && apt install -y bzip2 gzip coreutils screen curl && apt install bc && wget https://raw.githubusercontent.com/Jesanne87/menyala/main/xray.sh && chmod +x xray.sh && ./xray.sh

```
## Autoclear Inject
```
wget https://raw.githubusercontent.com/Jesanne87/menyala/main/addon/autoclear/autoclear.sh && chmod +x autoclear.sh && ./autoclear.sh

```
## Autokick Inject
```
wget https://raw.githubusercontent.com/Jesanne87/menyala/main/autokick.sh && chmod +x autokick.sh && ./autokick.sh

```
