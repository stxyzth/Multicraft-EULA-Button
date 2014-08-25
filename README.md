### Multicraft (Minecraft Hosting Panel) EULA Acceptance Button
======================

Button for the minecraft hosting panel multicraft. Allows for accepting the EULA with one click.


####Instructions (Written for the linux version but can also be done on windows)

 1. Easy to implement, just upload the contents of the "*panel*" folder to your control panel's root directory. Replace any files it asks about.
 2. Add "*scripts.conf*" to every daemon server, This is located in the "*home*" folder.
   * The default multicraft daemon directory to upload is `/home/minecraft/multicraft/` (Yours may be different).
   * Make sure "*scripts.conf*" is owned by the multicraft user `chown minecraft:minecraft` (Yours may be different).
 3. Upload "*accept_eula.sh*" to `/home/minecraft/multicraft/scripts/` (Yours may be different).
   * Make sure to chmod and chown this file: `chmod 755 accept_eula.sh` & `chown minecraft:minecraft accept_eula.sh`


So far only one difference from the code on the [Multicraft](http://multicraft.org/site/docs?view=howto#12.2.2) website. 

This edit adds the "hint" (tooltip or light bulb beside the button) option to the button which enables the user to see what the button does.

Preview: <img src="http://i.imgur.com/SLBpljy.png">





