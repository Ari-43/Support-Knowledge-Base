# Installation Issues
Issues with the stand-alone installation of OptiFine  
For modded installation, see [Using OptiFine as a Mod](/UseAsAMod.md)

<hr>

## OptiFine Not Opening With Java
This is usually due to Java not being installed or .jar files being associated with a file archive tool
1. Download and run [Jarfix](https://johann.loefflmann.net/downloads/jarfix.exe). If Jarfix failed to find [Java](https://adoptium.net/?variant=openjdk17&jvmVariant=hotspot), it must be [installed](https://adoptium.net/?variant=openjdk17&jvmVariant=hotspot)
- Jarfix may fail if it is run from a remote drive such as OneDrive. Copy it onto a physical drive before using it. 
2. Re-download OptiFine if it was extracted by a file archive tool
3. Continue installing OptiFine as normal. If OptiFine still isn't opening with Java, it may be necessary to run [Jarfix](https://johann.loefflmann.net/downloads/jarfix.exe) again. 
	- Jarfix may fail to find Adoptium OpenJDK in some cases. If this happens, the command `.\jarfix.exe /z` should be used while in the folder Jarfix was downloaded to. 
4. If none of the previous steps worked, but Java installed sucessfully, the command line/a terminal emulator can be used to run the OptiFine installer. To do this, run `java -jar OptiFine_mcver_HD_U_ver.jar`, replacing "ver" with the OptiFine version. 
	- Video Instructions for Windows: https://youtu.be/_I0hl-i77AY

<hr>

## java.io.FileNotFoundException Error

### Fix #1:
`java.io.FileNotFoundException: C:\Users\Owner\AppData\Roaming\.minecraft\libraries\optifine\OptiFine\1.18.2_HD_U_H7\OptiFine-1.18.2_HD_U_H7.jar (Access is denied)`

Full Video Instructions for Windows: https://youtu.be/lBaUbS7FJAU

1. Press <img src="https://docs.microsoft.com/en-us/windows/images/windows-logo.png" alt="Windows Key" style="vertical-align: middle;display:inline-block;width:15px;height:15px;"> + R</li> and paste in `%AppData%\.minecraft\libraries\optifine\OptiFine`
2. Delete the folder matching both the OptiFine and Minecraft version that is being installed
	- For example, if installing `OptiFine_1.18.2_HD_U_H7`, the folder named `1.18.2_HD_U_H7` should be deleted.
3. Attempt to install Optifine again

<br> 

### Fix #2: 
`java.io.FileNotFoundException: C:\Users\Owner\AppData\Roaming\.minecraft\launcher_profiles.json (Access is denied)` 

1. Press <img src="https://docs.microsoft.com/en-us/windows/images/windows-logo.png" alt="Windows Key" style="vertical-align: middle;display:inline-block;width:15px;height:15px;"> + R</li> and paste in `%AppData%\.minecraft\`
2. Rename the file named `launcher_profiles.json` to something else. For example, `launcher_profiles.json_backup`. 
3. Attempt to install Optifine again

<br> 

### Notes
- Both of these fixes should be done with both Minecraft and the launcher closed.