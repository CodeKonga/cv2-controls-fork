# Castlevania II Improved Controls

This hack is a fork of nstbayless's hack for *Castlevania II: Simon's Quest* that modernizes the control scheme to make it more like Symphony of the Night or Mega Man, allowing the player more control while in the air.

The two new things in this fork:

1) Added the ability to drop down while on the stairs by holding down button before pressing the jump button. This is the same behavior Bisqwit's own down+A patch adds to his retranslation, implemented here independently so it works the same way on both the vanilla and Bisqwit-targeted builds, without depending on (or conflicting with) Bisqwit's own implementation.

2) Fixed a glitch that would sometimes occur when taking damage in the air when attacking. This glitch was particularly pronounced when being hit by a projectile while using a secondary attack in the air, causing Simon to continuously appear as though he was climbing invisible stairs. This was caused by the knockback-injection code unconditionally forcing the player into the "on stairs" state whenever they were hit while attacking, regardless of whether they were actually on stairs beforehand. The fix checks player_substate (which already stores what the player was doing before the attack began) before re-entering the stairs state, and falls back to ordinary knockback otherwise.

## Using or Contributing to This Repository

[Read instructions here.](./SETUP.md)
