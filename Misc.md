# Miscellaneous Issues 
Issues that don't fall into a specific category yet

<hr>

## Invalid Java Runtime Configuration
### Fix #1 (Most Common)
- Reinstall OptiFine

### Notes
- This fix is for stand-alone OptiFine. If OptiFine is being used with other mods, attempt [Fix #2](#fix-2), and then [Fix #3](#fix-3)

<br>

### Fix #2
1. Go to the installations tab of the launcher
2. Press the three dots next to the installation 
3. Press Edit
4. Press More Options
5. Remove anything in the Java Runtime field and JVM Arguments Field

<br>

### Fix #3 (With Other Mods)
- Refer to [Mod Troubleshooting](/UseAsAMod.md#Troubleshooting)

### Notes #3
- Try [Fix #2](#fix-2) before this

<hr>

## Incompatible Java Runtime
1. Go to the installations tab of the launcher
2. Press the three dots next to the installation 
3. Press Edit
4. Press Advanced
5. Remove anything in the Java Runtime field

### Notes 
- The fix for this issue is the same as one of the fixes for [Invalid Java Runtime Configuration](#Invalid-Java-Runtime-Configuration)

<hr>

## World “smearing” with shaders 
<img src="/images/Smearing.png" alt="World Smearing Screenshot" width="400"> <br>
(Screenshot provided by [ali3lewa3#2341](http://discordapp.com/users/356738342609747969))
1. Enable sky in `Options -> Video Settings -> Details -> Sky: ON`
