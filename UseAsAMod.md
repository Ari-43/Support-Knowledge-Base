# Using OptiFine a Mod
This refers to using OptiFine as a mod with [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/), [FabricMC](https://fabricmc.net/use/installer/), or as a jar mod, not using OptiFine in general.

<hr>

## FabricMC
1. Install [FabricMC](https://fabricmc.net/use/installer/) 
2. Put [OptiFabric](https://www.curseforge.com/minecraft/mc-mods/optifabric) in the `.minecraft/mods` folder 
3. Put [OptiFine](https://optifine.net/downloads) in the `.minecraft/mods` folder 
4. [Troubleshoot](#Troubleshooting) if necessary. 

### Notes
- If using OptiFabric on 1.18.1, [OptiFine release H4](https://optifine.net/adloadx?f=OptiFine_1.18.1_HD_U_H4.jar) must be used. If not, the loading screen will loop or the game with crash outright.

<hr>

## Forge
1. Install [Forge](https://files.minecraftforge.net/net/minecraftforge/forge/) 
2. Put OptiFine in the `.minecraft/mods` folder 
3. [Troubleshoot](#Troubleshooting) if necessary. 

### Notes
- OptiFine doesn't appear in the mods list. If the user asks, tell them to go to video settings and check for the OptiFine watermark in the bottom left of video settings.

<hr>

## Jar Mod
1. If the user is on H1_pre2 or lower, skip to step 5
2. Ask the user to press "Extract" in the installer.
3. Run `!jarmod` and ask the user to follow the steps
4. Ask the user to select all the files while still **inside** the OptiFine mod folder, and then send them to a zip file.
5. For MultiMC, add the jar mod to the Minecraft jar using the menu. On other launchers proceed as normal for installing jar mods on that launcher. 

<hr>

## Troubleshooting 
1. Check if the game crashes with only OptiFine/OptiFine and OptiFabric in the mods folder 
2. If not, run `!tm` to guide the user on how to find the incompatible mod. If it does, troubleshoot OptiFine/Optifabric 
