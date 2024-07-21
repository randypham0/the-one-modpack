# Prerequisites

1. [Prism Launcher](https://prismlauncher.org/download/)
2. Java 17 JRE, like [Adoptium](https://adoptium.net/temurin/releases/?arch=x64&package=jre&version=17)

# Getting modpack

## Download

Install .zip from server, import to Prism Launcher, then launch

## Manual
1. Create a **1.20.1** Forge **47.3.0** Prism Launcher instance  
2. Right-click on newly created instance and select edit  
3. Find Settings tab  
4. Find Custom Commands tab  
5. Enable Custom Commands checkbox  
6. In Pre-launch command, copy and paste:  

   ```"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://randypham0.github.io/the-one-modpack/pack.toml```

7. Launch instance

# Known issues

Valkyrien Skies and related mods do not work with the server, so they are/will be removed.

Some mods have to be installed manually. This is unavoidable, but the launcher provides a link to the mod page(s).

[Create: Design n' Decor](https://www.curseforge.com/minecraft/mc-mods/create-design-n-decor)  
[The Digimod](https://www.curseforge.com/minecraft/mc-mods/the-digimod-beta)  
[Entity Culling Fabric/Forge](https://www.curseforge.com/minecraft/mc-mods/entityculling)  
[Prime Punch | One Punch](https://www.curseforge.com/minecraft/mc-mods/prime-punch-one-punch-mod)  

# Other stuff

Thanks to packwiz for creating [packwiz](https://github.com/packwiz/packwiz) tool and making modpacks easy.
