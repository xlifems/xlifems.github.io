---
layout: post
title: CONFIGURAR REOSITORIOS EN Linux Debian 9
---

Modificar contenido del fichero sources.list
    
    nano /etc/apt/sources.list

Configuración de repositorios en Linux debian 9

    deb http://mirrors.kernel.org/debian/ stretch main contrib non-free

# jessie-actualizaciones-seguridad   
    # jessie-actualizaciones-seguridad  
    deb http://security.debian.org/ stretch/updates main contrib non-free

# jessie-actualizaciones-sistema
    # jessie-actualizaciones-sistema    
    deb http://mirrors.kernel.org/debian/ stretch-updates main contrib non-free
    deb http://mirrors.kernel.org/debian stretch-proposed-updates main contrib non-free

# jessie-backports
    # jessie-backports
    deb http://mirrors.kernel.org/debian/ stretch-backports main contrib non-free

# debian-multimedia
    # debian-multimedia
    deb http://www.deb-multimedia.org stretch main non-free

