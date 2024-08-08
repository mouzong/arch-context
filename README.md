# How to Install ArchLinux

## 1 - Download archlinux from the nearest server to you:
Go to : https://archlinux.org/downloads

## 2 - Boot the Arch into a usb-key

```sh
ip addr show

iwctl

station wlan0 get-networks

exit

iwctl --passphrase "wireless-password" station wlan0 connect root-wifi-name

ip addr show

systemctl status sshd

passwd root

```

### Switch to another computer on tge same network and connect to it via SSH

```sh

```