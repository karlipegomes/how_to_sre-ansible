### Lab03 

- Criar um template de instalação base para o host2.
    - Definir hostname igual a inventário
    - Instalar pacotes bases:
	- ( tcpdump, net-tools, bind-utils, vim, git, open-vm-tools, htop, screen, epel-release )
        - iniciar serviço vmtoolsd utilizando handler
    - Atualizar servidor
    - Copiar arquivo motd personalizado apra /etc/motd
    - Personalizar bash
        - Adicionar o conteudo do arquivo block.txt, ao final do arquivo /etc/bashrc
