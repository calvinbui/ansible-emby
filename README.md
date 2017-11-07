# Ansible Emby

This role sets up a new Ubuntu host with open-vm-tools, nfs shares and Emby.

**You will need networking and python first. Recommend python-minimal**

`ansible-playbook site.yml -i hosts --ask-vault-pass`

1.  Edit vars
2.  Run ubuntu-setup role
3.  Restart computer
4.  Run the rest of the roles
