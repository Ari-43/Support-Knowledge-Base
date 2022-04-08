# Miscellaneous Issues 
Issues that don't fall into a specific category yet

<hr>

## Invalid Java Runtime Configuration 
1. Go to the installations tab of the launcher
2. Press the three dots next to the installation 
3. Press Edit
4. Press Advanced
5. Remove anything in the Java Runtime field

### Notes
- This doesnt solve it for all users. Some have their Java runtime already set to default. As best I can tell, when this happens something about Minecraft’s Java runtime has changed.

<hr>

## OptiFine Not Opening With Java
This is usually due to Java not being installed or .jar files being associated with a file archive tool
1. Download and run [Jarfix](https://johann.loefflmann.net/downloads/jarfix.exe). If Jarfix failed to find [Java](https://adoptium.net/?variant=openjdk17&jvmVariant=hotspot), it must be [installed](https://adoptium.net/?variant=openjdk17&jvmVariant=hotspot)
- Jarfix may fail if it is run from a remote drive such as OneDrive. Copy it onto a physical drive before using it. 
2. Re-download OptiFine if it was extracted by a file archive tool
3. Continue installing OptiFine as normal. If OptiFine still isn't opening with Java, it may be necessary to run [Jarfix](https://johann.loefflmann.net/downloads/jarfix.exe) again. 
4. If none of the previous steps worked, but Java installed sucessfully, the command line/a terminal emulator can be used to run the OptiFine installer. To do this, run `java -jar OptiFine_HD_U_ver.jar`, replacing "ver" with the OptiFine version. 
- Video Instructions for Windows: <br> https://youtu.be/_I0hl-i77AY

<hr>

## World “smearing” with shaders 
<img src="/images/Smearing.png" alt="World Smearing Screenshot" width="400"> <br>
(Screenshot provided by [ali3lewa3#2341](http://discordapp.com/users/356738342609747969))
1. Enable sky in `Options -> Video Settings -> Details -> Sky: ON`