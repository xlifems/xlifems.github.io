---
layout: post
title: CONFIGURAR JAVA_HOME Linux Debian 9
---

*Configuración variable de entorno JAVA_HOME para java openjdk 8 en Linux debian 9*

crear fichero java.sh dentro de directorio /etc/profile.d/
    
    sudo nano /etc/profile.d/java.sh

Editar contenido del archivo con la configuracion para OpenJDK8:

    JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
    PATH=$PATH:$JAVA_HOME/bin
    export JAVA_HOME

Guardar cambios y modificar cambiar los permiso del archivo  y agregar al source para establecer como variable de entorno
    
    sudo chmod +x /etc/profile.d/java.sh
    source /etc/profile.d/java.sh
    
comprobar la variable:

    echo $JAVA_HOME

resultado debe ser el path de la ruta de instacion del openjdk

    /usr/lib/jvm/java-8-openjdk-amd64
