# DP-Clothing-Remastered
Clean and Redesigned Clothing ui 

Installation Instructions:

Add dpclothing to your server.cfg (make sure the resource folder is named dpclothing, or whatever you wanna rename it to)
Make sure you are running the latest version of the fivem server artifact.
start dpclothing

Instructions:

Press (Y) to pull up the GUI, Or alternatively use the following commands:

/bag		(Variants)
/bracelet	(Toggle)
/ear		(Toggle)
/glasses	(Toggle)
/gloves		(Variants)
/hair		(Variants)
/hat		(Toggle)
/mask		(Toggle)
/neck		(Toggle)
/pants		(toggle)
/shirt		(Toggle) (Also takes off gloves)
/shoes		(Toggle)
/top 		(Variants)
/visor		(Variants)
/watch		(Toggle)
/revertclothing    (Simply puts every saved item back on)
/bagoff     (Toggle)
/clothingexit (if menu gets stuck open)
Variant ones change the way your equipped clothes look, and the toggle one puts on / takes off.

If you are using this on a roleplaying server, or just a server where people change their models/clothing somewhat often,
Please use the included TriggerEvent(“dpc:EquipLast”) when the player enters clothing stores/barber shop/using an outfit.
It will help with people for example doing /hair then going into a clothing store and saving, then doing /hair again it reverts and they’ve wasted money at the store.

Configuration:

For the Configuration you have some stuff you can mess with in Client/Config.lua
It’s all described in there but you can change the language and some GUI stuff.
I’ve tried to comment on as much code as possible, so modifications should be easy.

To add/change variants you can check Client/Variations.lua.
If you are for example using EUP or custom haircuts you might wanna go in here and change stuff around to fit your custom content.
It’s pretty simple and all explained in Variations.lua.
Put Config.Debug to true, to get an overview of the id’s your character is currently wearing.

Final Notes:

Theres included localization, i just used an online tool to translate to some other languages.
(If you’re downloading 1.0 these translations might not be perfect)
If you wanna help with translations make a pull request or just dm me.

FAQ:

“How do i change the /command name?” - Locale/Language.lua - en.lua is the default. Change lines that are in ALLCAPS.

Updates:
1.0.1  Added a reset button to quickly put everything back on.
1.0.2 Added /bagoff, with button.
1.0.3 Added option to toggle the menu instead of hold, minor changes including rotation when pushing some buttons, minor texture changes and 2 more events.
