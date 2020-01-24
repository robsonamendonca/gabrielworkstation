#observao enquanto a versao do linux
Ubuntu (Linux Mint/elementary OS) 

No Ubuntu varia de acordo com a versão, caso você esteja usando a versão 17.10 ou superior, o flatpak já está no repositório e você pode instalar com um simples "sudo apt install flatpak", no entanto, para quem usa o Ubuntu 16.04 LTS ou 17.04 é necessário usar o PPA oficial, o mesmo vale para Linux Mint e elementary OS (ambos baseados na LTS) e as outras derivações oficiais do Ubuntu (Kubuntu, Xubuntu, Ubuntu MATE, etc) respeitando o seu versionamento.

    sudo add-apt-repository ppa:alexlarsson/flatpak

    sudo apt update

    sudo apt install flatpak

Isso cobre a maior parte das distribuições, agora vamos aprender a utilizar o Flatpak.


# gabrielworkstation
Automatização de instalação do Ubuntu

Certique-se do arquivo ter permissões de execução.

Para utilizar o Script, basta rodar o comando:

sudo ./gabrielworkstation.sh
