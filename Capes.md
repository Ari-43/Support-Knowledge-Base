# Cape Issues
Issues with OptiFine capes and donations.

<hr>

## Unable To See Cape
1. Ask the user for their in-game-name and check if they have an OptiFine cape active 
2. If the user has a cape active, continue these steps. If not, help them [reacivate their cape](#Reactivate-Cape) 
3. Have the user check that `Options -> Video Settings -> Details -> Capes:` and `Options -> Skin Customization -> Cape:` are both set to `ON`
4. Ask the user if they can see [http://s.optifine.net/capes/Ari43.png](http://s.optifine.net/capes/Ari43.png)
	- If the user has an antivirus or internet restrictions they may not be able to access the cape server. 
	- It's possible that their ISP or networking hardware cached the cape (this is obvious when a user sees an outdated cape). If this is the case, restarting their access point will usually fix it. 
5. If the user cannot view the cape hyperlink, use `!faq cape servers` and help the user follow it as needed. 
	- For MacOSX and Linux, the hosts file is located at `/etc/hosts`
6. If the user could open [the link](http://s.optifine.net/capes/Ari43.png), ask if they are using any thrird party clients or launchers. 
	- PvP Clients, Legal (non-piracy) launchers, or similar: Ask the user to try [stand-alone OptiFine](https://optifine.net/downloads) on the [official launcher](https://launcher.mojang.com/download/MinecraftInstaller.msi). If the user can see their cape with stand-alone OptiFine on the official launcher, ask them to contact support for their PvP client or launcher.
	- Piracy Clients & Launchers: Run `!piracy` to explain to the user that support will not be provided for users commiting piracy. Once the game has been bought and the user is not using a launcher that supports piracy, support will be provided.
	- Cheat Clients/Mods: Support will not be provided for cheat clients/mods because doing so would be against the [Discord guidlines](https://discord.com/guidelines)
	
### Notes: 
- If the user belives their cape was stolen, refer to [Stolen Capes](#Stolen-Cape)

<hr>

## Reactivate Cape
1. Open the game
2. Open the OptiFine cape editor by pressing `Options -> Skin Customization -> OptiFine Cape... -> Open Cape Editor` or by going through [LivzMC](https://livzmc.net/microsoft/changeCape) if they are signed into Microsoft in their browser. 
3. Press "Activate" <br> ![Image of the "Activate" Button](/images/ReactivateCape.png) 
4. Restart the game
	- The user could reload the cape, but asking them to just restart their game is likely more familiar to them and there isn't a chance of them accidentally leaving the menu while it's reloading. 

<hr>

## Move A Cape
1. Go to [https://optifine.net/login](https://optifine.net/login)
2. Log in. If the user doesn't have a password, they will need to request one at [https://optifine.net/requestPassword](https://optifine.net/requestPassword) 
3. Press the "Edit" button as shown below <br> ![Image of the "Edit" button](/images/Cape_Edit_Button.png) 
4. Change the name in the "Username" field to the new username 
5. Press save 
6. Restart the game 
	- The user could reload the cape, but asking them to just restart their game is likely more familiar to them and there isn't a chance of them accidentally leaving the menu while it's reloading. 

### Notes
- Capes move automatically. Usually changing the name manually isn't necessarry. 

<hr>

## Broken Cape 
1. Direct the user to open an OptiFine support ticket (Discord channel: `<#904875214112956497>`). Only sp614x can fix this issue. 

### Notes
- Because only sp614x can fix this getting capes fixed may take a significant amount of time. 
- If the user doesn't see their cape's image (example below) when they are [signed in](https://optifine.net/login), the cape is broken. If the user *can* see the image of their cape, that doesn't necessarily mean it's working.  
![Example of broken cape](/archive/TemporaryIssues/2022/3/21/images/BrokenCape.png)

<hr>

## Invalid Cape Design 
1. Expain the the user that capes cannot have more than 8 layers
	- If the user is using the Mojang pattern, it will simply not be rendered on the cape and won't cause an error. 
2. Ask for the banner pattern to see if it's possible to make the banner without the extra layers
3. If sucessful at removing a sufficient number of layers, send the edited banner back to the user 

### Notes
- This means the user is trying to use a cape that has more than 8 layers

<hr>

## Email Changes
1. Ask the user if they  need to change the email because a typo after the @. If the error is after the @, tell them to contact and admin.
2. If the error was before the @, or the user needs to change the email entirely, ask the user how long ago they donated
3. If the donation was less than 30 days ago, direct them to request a [refund](#Refunds). If it was more than 30 days ago, nothing can be done besides deactivating the cape and re-donating.


### Notes
- Email changes in the normal sense are not possible. This functionality is not planned.

<hr>

## Refunds
1. Direct the user to contact [PaymentWall](https://www.paymentwall.com/en/contacts) support [(Email)](mailto:support@paymentwall.com)

<hr>

## Stolen Cape
- The user may think their cape was stolen when it's actually just deactivated or blocked. Ask them if they changed their name recently, if they moved the cape from another account, and what their username is (to check if there is a cape active on that account). If there is a cape active on their username, refer to [Unable to see cape](#Unable-To-See-Cape) 
- If their cape was actually stolen, there isn't much that can be done. We reccomend that they change their passwords (and enable 2FA when applicable) for their email account, Microsoft/Minecraft account, and their [optifine.net account](https://optifine.net/login) in that order. After that is done, if the user still has access to their email account, they can manually move the cape back to their username and [reactivate](#Reactivate-Cape) it. 

<hr>

## Can't Open Cape Editor (Authentication Error)

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
