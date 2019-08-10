# desafio-ansible
Just an Ansible POC

ansible-playbook playbook.yml -e "ipv6==true,kernelml=true"

- default -> instala as ferramentas de troublesooting
EXTRA_VARS
- ipv6=true -> habilita suporte a ipv6
- kernelml=true -> instala o kernel-ml de elrepo.org

Exemplo: ansible-playbook playbook.yml -e "ipv6==true,kernelml=true"
