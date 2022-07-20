#### Playbook para instalar los paquetes mas usados en server


#### Ejemplo de uso para un server puntual

    ansible-playbook -i <ipserver>, -u nss -K  --ask-pass install-packages.yml

#### En un grupo de servers

    ansible-playbook -i /path/to/ansible-test-inventory -l ubuntu-vm -u nss -K --ask-pass install-packages.yml
