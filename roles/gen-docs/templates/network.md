## IPV4
### Default interface: {{  ansible_default_ipv4.interface | default('na')  }}
- gateway: {{  ansible_default_ipv4.gateway | default('na')  }}
- address: {{  ansible_default_ipv4.address | default('na')  }}
- broadcast: {{  ansible_default_ipv4.broadcast | default('na')  }}
- netmask: {{  ansible_default_ipv4.netmask | default('na')  }}
- network: {{  ansible_default_ipv4.network | default('na')  }}
- macaddress: {{  ansible_default_ipv4.macaddress | default('na')  }}
- mtu: {{  ansible_default_ipv4.mtu | default('na')  }}
- type: {{  ansible_default_ipv4.type | default('na')  }}
- alias: {{  ansible_default_ipv4.alias | default('na')  }}

### DNS:
- nameservers: {{  ansible_dns.nameservers | default('na')  }}
- search: {{  ansible_dns.search | default('na')  }} 
- domain: {{  ansible_dns.domain | default('na')  }}
- options {{  ansible_dns.options | default('na')  }}