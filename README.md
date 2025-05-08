# Ansible Collection - namolabs.infra

- Ansible Rollen und Playbooks zur Installation und Verwaltung der privat genutzten Netzwerkinfrastur und Services
  - [ ] Hypervisor
    - [ ] Proxmox
  - [ ] Netzwerk
    - [ ] DHCP
    - [ ] DNS
    - [ ] AD (Samba)
    - [ ] CA - Implementierung im Dateisystem
  - Medien
    - Jellyfin
      - Verwaltung von Musik
    - immich
      - Bilder und Videos
    - immich-kiosk
      - Anzeige (Dauerschleife) von Bildern und Videos aus immich

## Roles

### namolabs.infra.fetchdata

Collect all data needed for all playbooks in the project from config and vault files and present them in one data structure.
After calling this role, the playbooks will then map the global data structure to the data needed by the individual roles called by the playbook.



## Development

Link from dev project to collection

```shell
ansible@d02:~/dev/ansible_infra/dev/plays/collections/ansible_collections/namolabs$ ln -s ~/dev/ansible_collections/namolabs/infra ./infra
```