# mume
Collection of powwow scripts for MUME

QUICK START GUIDE
=================

In powwow type "#load master.txt" to load in everything. However, you will need to make some changes first!

At a minimum you'll need to edit master.txt. Open it up in a text editor and read the comments in the file.

A lot of these files are my own personal preferences and way of doing things which you may not like, especially when it comes to aliases.
Most can be found in aliases.txt, though magic ones are in magic.txt.


SPECIAL FEATURES
================

So why would you want to use these scripts at all? There are a bunch of features in these scripts that work with current powwow/powtty
which I think people may find desirable, including:

 * Basics like score reporting (type "sc" then "rep" to emote your hps/mana etc)
 * Magic.txt: The toolbox for your mage or cleric
  * Enhanced spell timer: My spell timer does the usual and also shows the previous time, to give an indication of how long you have left.
  * Spell translations and highlighting for up/down etc, but without overwriting the normal message in those cases.
  * Auto-spell: Type "as" to cast whichever spells have dropped. sx (stat) refreshes internal state.
   * Also has an "afk cast" feature to keep spells up while you get coffee (aron/ason for resting/sleeping).
  * Scroll/magic item/picklock upgrade identifications
 * Highlighting (whathere.txt): A suite of highlighting tools to aid in rapid identification of things and events. Useful for dyslexics, but WIP!
  * Highlights items and mobs in the room in a different colour.
  * Highlights communications and differentiates between mobs/shopkeepers saying things and players saying/telling you things
  * Highlights for mobs/players moving in and out of your room
  * Highlights for special events like "ACK! You lost xyz" etc
  * Combat events, eg bashing on/from you and your team, and combat status on look (who is fighting who, sitting/sneaking etc etc)
 * Herbs.txt: Comprehensive herb identification as well as herblore mixing assistance and mixed-kit identification
 * autodoor.txt: Automated door (and chest - experimental!) opening/unlocking/closing etc using MMapper (illegal in PK)
 * autotravel.txt: Travelling convenience, from zblam-auto-reride to catching the white ship & ferry while AFK
  * Actions for saying yes to various quests too, for the easily-distracted-by-their-droning among us
 * keys.txt: Keys identification (incomplete, but now much more up-to-date than what else I've found!)
 * Advanced container and mount management (grillions of aliases) for the bag-lovers out there

Experimental / partially-working:

 * Blindness indicator: Tells your group X.mob has been blinded. (experimental)
 * XP counter: This does work but you have to type "xpreset" at the start of your session (then "xprint" to get xp thus far). Needs work!


COMPATIBILITY
=============

Most of this will work in powtty, but not all. herbs.txt for example should work fine in powtty, but whathere.txt will mostly not due to my use 
of regular expressions. Likewise the more complex bits like the spelltimers likely wont work in powtty.


TODO
====

 * Finish this readme!
 * Fix XP counter so it starts up properly and shows time
 * Enhance reporting with percentages
 * Put stuff into prompt like % hps/mana etc
 * Improve powtty compatibility as far as is possible
 * ...see latest commits for more
