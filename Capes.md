# Cape Issues
Issues with OptiFine capes and donations.

<hr>

## Unable To See Cape
1. Ask the user for their in game name and check if they have an OptiFine cape active 
2. If the user has a cape active, continue these steps. If not, help them [reacivate their cape](#Reactivate-Cape) 
3. Have the user check `Options -> Video Settings -> Details -> Capes:` and confirm that it is set to `ON` 
4. Ask the user if they can see [http://s.optifine.net/capes/Ari43.png](http://s.optifine.net/capes/Ari43.png)
5. If the user cannot view the cape hyperlink, use `!faq cape servers` and help the user follow it as needed. 
	- For MacOSX and Linux, the hosts file is located at `/etc/hosts`
	
### Notes: 
- If the user has an antivirus or internet restrictions they may not be able to access the cape server. 
- It's possible that their ISP or networking hardware cached the cape. In this case, restarting their access point will usually fix it. 
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

## Invalid Cape Design 
1. Expain the the user that capes cannot have more than 8 layers or use the Mojang logo 
2. Ask for the banner pattern to see if it's possible to make the banner without them 
3. If sucessful at removing the Mojang logo or a sufficient number of layers, send the edited banner back to the user 

### Notes
- This means the user is trying to use a cape that has more than 8 layers and/or uses the Mojang logo pattern.

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

## Can't Open Cape Editor 

In the log file:
```
[xx:xx:xx] [Render thread/WARN]: [OptiFine] Error opening OptiFine cape link 
[xx:xx:xx] [Render thread/WARN]: [OptiFine] com.mojang.authlib.exceptions.AuthenticationUnavailableException: Cannot contact authentication server
```  

1. The user needs to remove any entried related to mojang (Including `authserver.mojang.com` and `sessionserver.mojang.com`) from the hosts file located at `C:\Windows\System32\drivers\etc\hosts`. 
- The user must have administrator priveliges to edit this file
- The entire line must be removed
- The hosts file is not the same as hosts.ics

<hr>
