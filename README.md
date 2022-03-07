# auto-gen-docs-ansible
## Automatic documentation of infrastructure

#### Point playbook at your linux infrastructure and get automatic documentation written in Markdown.
---
# Following values get documented for each host 
#### This is a linode host example. I have redacted all sensitive information

## Hardware
- Product Name: Standard PC (Q35 + ICH9, 2009)
### Memory 
- Memory in total: 3946 MB
### CPU
- Cores: 1
- Threads per count: 1

### Processors
``['0', 'AuthenticAMD', 'AMD EPYC 7642 48-Core Processor', '1', 'AuthenticAMD', 'AMD EPYC 7642 48-Core Processor']``

### Mounts
* Device Name: /dev/sda
    - mount point: /
    - FS type: ext4
    - Total size: 78.29902648925781
    - Size avail: 62.80337905883789

## IPV4
### Default interface: eth0
- gateway: REDACTED
- address: REDACTED
- broadcast: REDACTED
- netmask: 255.255.255.0
- network: REDACTED
- macaddress: REDACTED
- mtu: 1500
- type: ether
- alias: eth0
REDACTED
### DNS:
- nameservers: ['REDACTED', '<'REDACTED', 'REDACTED']
- search: ['members.linode.com'] 
- domain: members.linode.com
- options {'rotate': True}
  
## System
* Hostname: REDACTED
* System:Linux
    - Path: /etc/os-release
    - Variety: Debian
    - Major Version: 10
    - Release: buster
    - Dist Version: 10

- Product Serial: NA
- UUID: NA
  
## Services

|Service|Status|Source|State|
|-------|------|------|-----|
rsyslog | na | sysv| running |
systemd-timesyncd.service | enabled | systemd| running |
getty@tty1.service | unknown | systemd| running |
serial-getty@ttyS0.service | unknown | systemd| running |
apparmor | na | sysv| running |
openvpn | na | sysv| running |
cron.service | enabled | systemd| running |
ssh | na | sysv| running |
dbus | na | sysv| running |
netfilter-persistent | na | sysv| running |
ssh.service | enabled | systemd| running |
udev | na | sysv| running |
cron | na | sysv| running |
kmod | na | sysv| running |
rsyslog.service | enabled | systemd| running |
docker.service | enabled | systemd| running |
ufw | na | sysv| running |
haveged | na | sysv| running |
sysstat | na | sysv| running |
docker | na | sysv| running |
dbus.service | static | systemd| running |
fail2ban.service | enabled | systemd| running |
networking | na | sysv| running |
systemd-logind.service | static | systemd| running |
openvpn-server@server.service | unknown | systemd| running |
containerd.service | enabled | systemd| running |
procps | na | sysv| running |
fail2ban | na | sysv| running |
user@1000.service | unknown | systemd| running |
systemd-udevd.service | static | systemd| running |
user@1004.service | unknown | systemd| running |
haveged.service | enabled | systemd| running |
systemd-journald.service | static | systemd| running |
 
## Author: Símun Højgaard Lutzen | simunhojgaard@gmail.com
