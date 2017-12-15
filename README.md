# ansible-scripts
Repository of various ansible scripts

virt-guest.yml:
   Create-kvm hosts, with preseed configuration files. You must public the preseed files in an accesible webserver to download by the kvm machine.

    Usage:
      ansible-playbook -i /scripts/ansible/hosts/hosts  virt-guests.yml --ask-sudo -u ansibleuser -v 


