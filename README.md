# Desafio DevOps Com Ansible

Execução: ansible-playbook playbook.yml

- default -> instala as ferramentas de troublesooting
EXTRA_VARS
- ipv6=true -> habilita suporte a ipv6
- kernelml=true -> instala o kernel-ml de elrepo.org
- webserver=true -> instala Nginx com suporte a PHP

Exemplo: ansible-playbook playbook.yml -e "ipv6==true,kernelml=true,webserver=true"

Meu endpoint: http://35.202.70.129/index.php
