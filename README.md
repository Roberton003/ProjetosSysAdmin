Projetos práticos em DevOps podem ser extremamente úteis para o desenvolvimento da carreira em tecnologia. DevOps é uma metodologia que enfatiza a colaboração e a integração entre equipes de desenvolvimento e operações, com o objetivo de entregar software de alta qualidade de maneira mais rápida e confiável.

Ao trabalhar em projetos práticos em DevOps, você pode adquirir habilidades valiosas em áreas como automação de implantação, gerenciamento de infraestrutura de TI, monitoramento e resolução de problemas. Essas habilidades são muito procuradas no mercado de trabalho, especialmente em organizações que estão adotando a metodologia DevOps.

Vagrant: é uma ferramenta para criar e gerenciar ambientes de desenvolvimento isolados e portáteis. Ele permite que você crie máquinas virtuais usando diferentes provedores de virtualização (como VirtualBox, VMWare ou Hyper-V) e provisione-as automaticamente com as configurações necessárias.

Docker: é uma plataforma de contêineres que permite empacotar e distribuir aplicativos em um formato portátil e escalável. Os contêineres do Docker são leves e rápidos de implantar, o que os torna ideais para implantação em ambientes de produção.

Ansible: é uma ferramenta de automação de TI que permite gerenciar configurações e implantar aplicativos em vários servidores simultaneamente. Ele usa uma linguagem de configuração simples e fácil de aprender para definir tarefas e automatizar processos.

Desafio 00 - Vagrant-ubuntu
Criar máquina virtual no vagrant do Ubuntu 20.04:
● Utilizar placa de rede modo bridge
● Definir:
○ Nome da máquina
○ memória ram: 1G
○ CPU: 01
Subir os arquivos para um repositório no Github
Desafio 01 - vagrant-shell-script
Criar máquina virtual no vagrant, em seguida padronizar pelo shell
● Instalar pacotes:
○ vim
○ curl
○ telnet
○ unzip
○ wget
○ net-tools
○ htop
○ nmap
● Definir nome da máquina
● Criar um usuário com o seu nome
● Instalar nginx na máquina
Subir os arquivos para um repositório no Github
Desafio 02 - vagrant-ansible
Criar máquina virtual no vagrant, em seguida criar uma role:
● Common
○ Instalar pacotes:
■ vim
■ curl
■ telnet
■ unzip
■ wget
■ net-tools
■ htop
■ nmap
○ Definir nome da máquina
○ Criar um usuário com o seu nome
● Nginx
○ Instalar nginx na máquina
○ Copiar um arquivo site.html
Subir os arquivos para um repositório no Github
Desafio 03 - docker
Criar máquina virtual no vagrant, em seguida:
● Instalar docker
● Executar o container com docker run
○ Com imagem do Nginx
○ Mapear um volume para adicionar index.html
Subir os arquivos para um repositório no Github
Desafio 04 - Docker-dockerfile
Criar máquina virtual no vagrant, em seguida:
● Instalar docker
● Criar uma Dockerfile com Ngnix
○ Copiar um arquivo index.html
○ Expor porta 80
● Build do Dockerfile
● Executar o container com docker run
Subir os arquivos para um repositório no Github
Desafio 05 - Docker-dockerfile-docker-compose
Criar máquina virtual no vagrant, em seguida:
● Instalar docker
● Criar uma Dockerfile com Ngnix
○ Copiar um arquivo index.html
○ Expor porta 80
● Criar um docker compose
○ Com build para imagem do nginx
○ Mapear a porta 8080
Subir os arquivos para um repositório no Github
Desafio 06 - vagrant-docker-ansible
Criar máquina virtual no vagrant, em seguida:
● Criar uma role do docker no Ansible
● Criar uma role para container do docker
○ Build da imagem do nginx pelo
○ Executar o container na porta porta 8080
Subir os arquivos para um repositório no Github
Desafio 07 - dokcer-compose-zabbix
Criar um docker compose do Zabbix com Grafana