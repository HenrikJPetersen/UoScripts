Alot of the handling for cooldowns was inspired by this following link:
https://gist.github.com/tstenhaug/7b8a8205da3d11d3a41ecabc354db746#file-wizardry-nuke-with-cooldowns-razor-L232



SETUP
1.
Place below file in your character folder to insert the entries in for your cooldowns.xml
https://github.com/HenrikJPetersen/UoScripts/blob/main/CooldownsForNecro/CoolDowns.razor

2.
Add ALL of the script files to your script folder found here: 
"Uo\ClassicUO\Data\Plugins\Assistant\Scripts"
3.
Set up the hotkeys.
You need to change your spells lasttarget and target self.


KNOWN ISSUE:
IF you spam your last target/target self - it will not active the cooldowns.
You can only press it once.


TODO:
Try to mitigate the spam issue by using global variables that are reset when pressing lasttarget/targetself more than once.
Find any kind of indicator that the spell/skill has been triggered.
Current mana vs mana before cast etc.






