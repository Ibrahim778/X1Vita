# X1Vita

**Download**: https://github.com/Ibrahim778/X1Vita/releases

**Enable the plugin:**

1. Add X1Vita.skprx to taiHEN's config (ux0:/tai/config.txt) or (ur0:/tai/config.txt):
	```
	*KERNEL
	ux0:tai/X1Vita.skprx
	```
2. You need to refresh the config.txt by rebooting or through VitaShell.

**Using it for the first time (pairing the controller):**

1. Go to Settings -> Devices -> Bluetooth Devices
2. Press the pair on the controller for about 3-4 seconds, until the logo blinks very quickly
3. The controller will then connect and be paired (You may get a message saying "Do you want to connect to (blank)" just press ok and ignore the error)

**Using it once paired (see above):**
1. Just press the xbox button and it will connect to the Vita

**Note**: If you are using multiple controllers the controller ports will be set in the order you connect (if available), so first connection -> port 1 second connection -> port 2 etc, simply powering off the controller (ie removing batteries) will not trigger a disconnect on vita. You need to hold the Xbox Button till it turns off.  
**Note**: If you use Mai, don't put the plugin inside ux0:/plugins because Mai will load all stuff you put in there...  

Made for the kyuhen homebrew contest.  
Based on ds4vita  

# FAQ
**1. My controller connects but doesn't do anything!**  
There can several reasons but here are the most common:  
  1. Your using a 3rd party controller. (see note below)
  2. Your using an official controller other than the Xbox One (For e.g. Xbox One Eliete, Eliete 2) (see note below)
  3. Your using the new Xbox one controllers, ie the ones with the screenshot button (including the series controllers) are **not** suppourted, this is simply because the vita's      bluetooth version does not suppourt them so they simply cannot connect no matter what.
  4. You installed the plugin incorrectly (install and open the companion to see if X1Vita is detected)

**2. My controller doesn't show up in bluetooth devices!**  
Microsoft updated the controller firmware that for some reason made it invisible to the vita, to fix this, downgrade your controllers firmware with [this guide](https://support.xbox.com/en-GB/help/hardware-network/accessories/controller-firmware-reversion).
Note: This fix will *only* work on xbox one controllers. Xbox series controllers use an unsupported bluetooth version and as such will never be able to be used.

## Note about controllers not working
For now only official Xbox One controllers are suppourted all others will be ignored. I am no longer adding 3rd party suppourt as they use different payloads (sometimes).


