#### Playbook para instalar los paquetes mas usados en server


#### Ejemplo de uso para un server puntual

    ansible-playbook -i <ipserver>, -u nss -K  --ask-pass install-packages.yml
