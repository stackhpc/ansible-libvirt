# Ansible Libvirt

Ansible playbooks for managing Libvirt hosts and VMs.

Based on
[stackhpc.libvirt-host](https://galaxy.ansible.com/stackhpc/libvirt-host) and
[stackhpc.libvirt-vm](https://galaxy.ansible.com/stackhpc/libvirt-vm) roles.

## Installation

```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
ansible-galaxy install -r requirements.yml -p ansible/roles
deactivate
```

## Usage

```
source venv/bin/activate
ansible-playbook -i ansible/inventory ansible/libvirt-host.yml
ansible-playbook -i ansible/inventory ansible/libvirt-vm.yml
deactivate
```

## Author Information

Mark Goddard (mark@stackhpc.com)
