---
layout: post
title: AGREGAR DISPOSITIVOS HTC ADB ANDROID STUDIO EN Linux Debian 9
---

Para que android studio reconozca los dispositivos con hardware HTC, es necesario ejecutar los siguientes comandos dentro del directorio del SDK de Android, por lo general lo encontramos en 
    
    cd /home/<tu-usuario>/Android/Sdk/platform-tools/

Una vez dentro y con nuestro dispositivo conectado, ejecutamos los siguientes comando en Linux debian 9 

Detenemos el servicio del adb de android studio
    
    # ./adb kill-server

Iniciamos nuevante el servicio
    
    # ./adb start-server

Listamos los dispositivos conectados
    
    # ./adb devices

Si todo va bien se debe listar el disposivo
