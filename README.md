# mod-solo-lfg

## Description

Allows for players to use dungeon finder solo or in groups less than and up to 5 players. Use on azerothcore 3.3.5a. Good companion module for mod-solocraft and mod-autobalance. (Docker installations version).


## Installation
```
0. Go inside your /modules/ folder
1. git clone https://github.com/milestorme/mod-solo-lfg.git
2. Apply lfg-solo.patch to your core.
    a. In order to do this, please go to the root /azerothcore-wotlk of your installation.
    b. Then do git apply modules/mod-solo-lfg/lfg-solo.patch 
    (make sure the path is indeed pointing to your lfg-solo.patch file)
3. Re-run cmake and launch a clean build of AzerothCore.
    a. Go to your root folder and  ./bin/acore-docker-build
    b. Then do a docker-compose up
```

## Edit module configuration (optional)

If you need to change the module configuration, go to your server configuration folder (where your `worldserver` or `worldserver.exe` is)
rename the file SoloLfg.conf.dist to SoloLfg.conf and edit it.

## Uninstallation
```
1. Remove the /modules/mod-solo-lfg folder
2. Remove the lfg-solo.patch from y our core.
    a. In order to do this, please go to the root /azerothcore-wotlk of your installation.
    b. Then do git apply -R modules/mod-solo-lfg/lfg-solo.patch 
3. Re-run cmake and launch a clean build of AzerothCore.
    a. Go to your root folder and  ./bin/acore-docker-build
    b. Then do a docker-compose up
```

## Credits
*  [Micrah/Milestorme: Module Creator](https://github.com/milestorme).
*  [Conan513:](https://github.com/conan513).
*  [Artanisx](https://github.com/Artanisx) - Update for Docker installations.
