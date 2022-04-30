# Docker-Install

Instalacion de Docker

Actualización del sistema:

        apt update
        apt upgrade

Instalación de Docker:

        curl -fsSL https://get.docker.com -o get-docker.sh

        sh get-docker.sh

        sudo usermod -aG docker $USER

Instalación de Docker Compose:

        sudo curl -L "https://github.com/docker/compose/releases/download/v2.4.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
    
Confirmamos la versión más reciente disponible en su página de versiones.

        https://github.com/docker/compose/releases
