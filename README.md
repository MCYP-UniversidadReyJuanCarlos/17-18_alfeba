# Android Exploit Suggester

## Project Description
Este proyecto ha consistido en el desarrollo de una herramienta para la automatización de la explotación de vulnerabilidades. La herramienta consiste en un Exploit Suggester que es un tipo de herramienta que nos da la información correspondiente a las diferentes vulnerabilidades existentes en un determinado sistema operativo. Esta información va desde el CVE, versiones afectadas, puntuación, hasta enlaces a exploits para la explotación de las vulnerabilidades.

Existen diferentes herramientas de esta tipología para sistemas operativos de ordenadores y servidores como son Linux y Windows, pero no existen para sistemas móviles. En este caso el objetivo de la herramienta será el sistema operativo para móviles Android. La herramienta ha sido bautizada con el nombre de Android Exploit Suggester.

## Features
Android Exploit Suggester proporciona 3 modos de operación:
+ Modo Manual: el auditor proporciona la versión del sistema para obtener las vulnerabilidades asociadas a dicha versión.
+ Modo Automático: la herramienta obtiene automáticamente la versión del sistema operativo en la que está ejecutando y muestra las vulnerabilidades asociadas para dicha versión.
+ Modo Online: la aplicación se conectará a Internet para consultar las vulnerabilidades. De esta manera, se obtendrán todas las vulnerabilidades existentes. Si no se hace uso de este modo de operación, las vulnerabilidades se consultarán en el repositorio
local de la herramienta.

La herramienta ha sido desarrollada en el lenguaje de programación Go.

## How to run
    ./android_exploit_suggester 7.1.0 -h
       _____              .___             .__    .___
      /  _  \   ____    __| _/______  ____ |__| __| _/
     /  /_\  \ /    \  / __ |\_  __ \/  _ \|  |/ __ | 
    /    |    \   |  \/ /_/ | |  | \(  <_> )  / /_/ | 
    \____|__  /___|  /\____ | |__|   \____/|__\____ | 
            \/     \/      \/                      \/ 

    ___________              .__         .__  __   
    \_   _____/__  _________ |  |   ____ |__|/  |_ 
     |    __)_\  \/  /\____ \|  |  /  _ \|  \   __\
     |        \>    < |  |_> >  |_(  <_> )  ||  |  
    /_______  /__/\_ \|   __/|____/\____/|__||__|
            \/      \/|__|                        

      _________                                    __                
     /   _____/__ __  ____   ____   ____   _______/  |_  ___________ 
     \_____  \|  |  \/ ___\ / ___\_/ __ \ /  ___/\   __\/ __ \_  __ \
     /        \  |  / /_/  > /_/  >  ___/ \___ \  |  | \  ___/|  | \/
    /_______  /____/\___  /\___  / \___  >____  > |__|  \___  >__|  
            \/     /_____//_____/      \/     \/            \/      
    Usage:
    For automatic mode enter: android_exploit_suggester
    For manual mode enter: android_exploit_suggester version_of_android
    For online mode enter: android_exploit_suggester -o


## Basic usage

    ./android_exploit_suggester 7.1.0
       _____              .___             .__    .___
      /  _  \   ____    __| _/______  ____ |__| __| _/
     /  /_\  \ /    \  / __ |\_  __ \/  _ \|  |/ __ | 
    /    |    \   |  \/ /_/ | |  | \(  <_> )  / /_/ | 
    \____|__  /___|  /\____ | |__|   \____/|__\____ | 
            \/     \/      \/                      \/ 

    ___________              .__         .__  __   
    \_   _____/__  _________ |  |   ____ |__|/  |_ 
     |    __)_\  \/  /\____ \|  |  /  _ \|  \   __\
     |        \>    < |  |_> >  |_(  <_> )  ||  |  
    /_______  /__/\_ \|   __/|____/\____/|__||__|
            \/      \/|__|                        

      _________                                    __                
     /   _____/__ __  ____   ____   ____   _______/  |_  ___________ 
     \_____  \|  |  \/ ___\ / ___\_/ __ \ /  ___/\   __\/ __ \_  __ \
     /        \  |  / /_/  > /_/  >  ___/ \___ \  |  | \  ___/|  | \/
    /_______  /____/\___  /\___  / \___  >____  > |__|  \___  >__|  
            \/     /_____//_____/      \/     \/            \/      
    Manual Mode
    Version selected:  7.1.0

     ---------------
    | CVE-2017-0845 |
     ---------------
        Vesion affected: 5.0 5.0.1 5.0.2 5.1 5.1.0 5.1.1 6.0 6.0.1 7.0 7.1.0 7.1.1 7.1.2 
        Score:  5
        Description:  A denial of service vulnerability in the Android framework (syncstorageengine). Product: Android. Versions: 5.0.2, 5.1.1, 6.0, 6.0.1, 7.0, 7.1.1, 7.1.2. Android ID: A-35028827.
        Ref:
            https://source.android.com/security/bulletin/pixel/2017-11-01
    *********************************************************
    
    
## Video Demo

<iframe src="https://player.vimeo.com/video/289135101" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
<p><a href="https://vimeo.com/289135101">Android Exploit Suggester</a> from <a href="https://vimeo.com/user49307830">afernandezb92</a> on <a href="https://vimeo.com">Vimeo</a>.</p>
