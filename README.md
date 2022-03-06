# auto-gen-docs-ansible
##Automatic documentation of infrastructure

#### Point playbook at your linux infrastructure and get automatic documentation written in Markdown.
---
# Following values get documented for each host (this is a linode host example. I have retracted all sensitive information)

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
- gateway: <redacted>
- address: <redacted>
- broadcast: <redacted>
- netmask: 255.255.255.0
- network: <redacted>
- macaddress: <redacted>
- mtu: 1500
- type: ether
- alias: eth0
<redacted>
### DNS:
- nameservers: ['<redacted>', '<redacted>', '<redacted>']
- search: ['members.linode.com'] 
- domain: members.linode.com
- options {'rotate': True}
  
##System
* Hostname: <redacted>
* System:Linux
    - Path: /etc/os-release
    - Variety: Debian
    - Major Version: 10
    - Release: buster
    - Dist Version: 10

- Product Serial: NA
- UUID: NA
  
 
