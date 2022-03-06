##System
* Hostname: {{ inventory_hostname }}
* System:{{  ansible_system  }}
    - Path: {{  ansible_distribution_file_path  }}
    - Variety: {{  ansible_distribution_file_variety  }}
    - Major Version: {{  ansible_distribution_major_version  }}
    - Release: {{  ansible_distribution_release  }}
    - Dist Version: {{  ansible_distribution_version  }}

- Product Serial: {{  ansible_product_serial  }}
- UUID: {{  ansible_product_uuid  }}