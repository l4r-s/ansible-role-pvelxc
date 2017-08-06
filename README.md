# Ansible lxc proxmox role
This role will create an lxc container on proxmox pve


## Variables
The following variables will be used in the role and should be declared in the group_vars dir of the service:

### Grou variables

~~~yaml
---

  proxmox_node: pve
  proxmox_username: root@pam
  proxmox_password: "YOUR-PVE-PW"
  proxmox_fqdn: pve.example.com
  root_password: "CT-ROOT-PW"
~~~

### Host Variables

~~~yaml
gw: 192.168.55.1
ip: 192.168.55.33/24
~~~
