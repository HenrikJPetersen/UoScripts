A lot of the handling for cooldowns was inspired by this: 
https://gist.github.com/tstenhaug/7b8a8205da3d11d3a41ecabc354db746#file-wizardry-nuke-with-cooldowns-razor-L232

I just wanted to get away from the 1 btn press for farm/grind - in the boss scenarios - that is fine.

SETUP 
All the needed files is found in this folder: https://github.com/HenrikJPetersen/UoScripts/tree/main/CooldownsForNecro

Place below file in your character folder to insert the entries in for your cooldowns.xml 
https://github.com/HenrikJPetersen/UoScripts/blob/main/CooldownsForNecro/CoolDowns.razor

Add ALL of the script files to your script folder, useally found in this folder: 
"Uo\ClassicUO\Data\Plugins\Assistant\Scripts" Do not put the cooldowns.xml file in your script folder.

Set up the hotkeys. You need to change your spells lasttarget and target self.

KNOWN ISSUE: 
IF you spam your last target/target self - it will not trigger the cooldowns. You can only press it once.

TODO: 
Try to mitigate the spam issue by using global variables that are reset when pressing lasttarget/targetself more than once. Find any kind of indicator that the spell/skill has been triggered. Current mana vs mana before cast etc.
