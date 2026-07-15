#### Castlevania II Improved Controls ####

Version: 2.0

This hack modernizes the control scheme of Castlevania 2 to make it less frustrating to people
used to tighter controls as in Symphony of the Night and Mega Man. It primarily allows the player
greater control while jumping and on stairs.

############## Instructions ##############

Two basic versions are included:
* CV2-controls.ips
	- This is the basic version of the hack that should be applied to a standard ROM.
	- This version should be compatible with several other hacks, but not with Bisqwit's retranslation + map hack.

* CV2-controls-bisqwit-compat.ips
    - This version is only compatible with Bisqwit's retranslation + map hack,
	    located at https://bisqwit.iki.fi/cv2fin/
	- do NOT apply this unless Bisqwit's retranslation is already applied.
	- Compatible only with version 2.12.1.1 of the retranslation (released 2022-06-02) if you disable
	“Stairs feature,” which google translates as “Additional functions on the stairs.” Note that by default,
	the version on the website is set to 2.12.2 (2022-06-04), which is NOT compatible with this hack and even Bisqwit
	does not recommend using that version due to "known problems" with it. If you are an English speaker, do not forget
	to make sure the language is set to English. Note that Bisqwit's website, has a lot of great options, but it's
	impossible to test every one, so we can't promise that every change beyond the default options work.
	-This version is compatible with several other mods, assuming you apply bisqwit's mod first.
	    Compatability includes:
		  * Game Over Penalty Reduction: http://www.romhacking.net/hacks/4135/
		  * Castlevania II False Floor & Breakable Block Replacer: https://www.romhacking.net/hacks/5361/
		  * Castlevania 2 Increase Heart Drops: https://www.romhacking.net/hacks/8682/
		  * Castlevania 2 Revised Night Curse Effects (Bugs Fixed): https://www.romhacking.net/hacks/9783/
	
Use Lunar IPS or similar to apply the hack to your Castlevania 2 ROM file. 
https://fusoya.eludevisibility.org/lips/

In addition, no-vcancel versions are provided for those who prefer not having vcancel ("vcancel" is the ability to stop
your upward trajectory of a jump by releasing the jump button early).
	
	
################ Changes #################

Complete list of changes:

    Enables the player to control their x-velocity in mid-air while jumping (including while jump-attacking).
    When releasing the jump button, Simon immediately starts falling again; this allows the player to
    make smaller hops if desired.
    After being knocked back, the player regains control after a split second and can angle their fall.
    When walking off an edge, the player retains control instead of dropping straight down.
    The player can jump off of stairs at any point in the climb. (However, it is still impossible to land
    on stairs, so be careful jumping from long flights of stairs over pits.)
    If players holds down before pressing jump on the stairs, the player can fall downwards from the stairs.
    If the player is struck by an enemy while climbing stairs, they will not be knocked off the stairs. This
    is the same as the behaviour in Castlevania 1 and 3.
    Simon blinks rapidly after getting hit, as in Castlevania 1 and 3.


############### Licensing #################

Feel free to use or modify this hack, but be sure to
include a link to the NaOH's original version of this hack:
https://www.romhacking.net/hacks/4150/

No other crediting is necessary, but if you wish you may credit
the author (NaOH), as well as the author of this revision of the
mod (Pizzano).

If the hack is modified and distributed, please be sure
to note that it is not the original version of the hack
and that it was modified by someone other than the
original author.
