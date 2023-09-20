# The place for old issues


## Can't Open Cape Editor (Authentication Error)
Removed from Capes.md 2023-09-20  
Reason: Issue not seen recently (solved)

If the following is in the log file:
```
[xx:xx:xx] [Render thread/WARN]: [OptiFine] Error opening OptiFine cape link 
[xx:xx:xx] [Render thread/WARN]: [OptiFine] com.mojang.authlib.exceptions.AuthenticationUnavailableException: Cannot contact authentication server
```  

1. The user needs to remove any entried related to mojang (Including `authserver.mojang.com` and `sessionserver.mojang.com`) from the hosts file located at `C:\Windows\System32\drivers\etc\hosts`. 
	- The user must have administrator priveliges to edit this file
	- The entire line must be removed
	- The hosts file is not the same as hosts.ics
	
If that exact error is not in the log:
1. Explained in `!faq cape editor not opening`

<hr>