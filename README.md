# Android Exploit Suggester

## Project Description
Este trabajo consiste en el desarrollo de una herramienta que permita automatizar la fase de explotación de vulnerabilidades para el sistema operativo Android. Concretamente la herramienta consistirá en una base de datos portable que permite obtener toda la información referente a las vulnerabilidades del sistema. El nombre de la herramienta será Android Exploit Suggester.

## Features
Android Exploit Suggester proporciona 3 modos de operación:
+ Modo Manual: el auditor proporciona la versión del sistema para obtener las vulnerabilidades asociadas a dicha versión.
+ Modo Automático: la herramienta obtiene automáticamente la versión del sistema operativo en la que está ejecutando y muestra las vulnerabilidades asociadas para dicha versión.
+ Modo Online: la aplicación se conectará a Internet para consultar las vulnerabilidades. De esta manera, se obtendrán todas las vulnerabilidades existentes. Si no se hace uso de este modo de operación, las vulnerabilidades se consultarán en el repositorio
local de la herramienta.

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
