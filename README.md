# Bounty Hunter Forest

Stuck on first level?

Pick up the colorful boxes and equip new weapons and shields.
To equip gear:
Press menu button (three horizontal bars).
Press INV button.
Tap arrows in red and blue fields.
Tap and then equip weapon with highest ATK.
Tap and then equip shield with highest DEF.

Still too difficult?

Press menu button (three horizontal bars).
Press TSS button.
Review tutorial. 
Master blocking; it's too good, providing 2 s of invincibility.
Player is invincibility when blue; player is constantly blue when playing really well.

Stuck in nightmare difficulty / cannot beat final level?

Approach 1:
Fight Carrick on Nightmare difficulty.
Collect 10 counts of the shield Carrick.
Fight Tunnel on Nightmare difficulty.
Collect 10 counts of Tunnel Arm.
This equipment has good drop rates and receives a match bonus.

Approach 2:
Fight Yip for Protoshield on Nightmare difficulty.
Fight Sip for Prototype00 on Nightmare difficulty.

Approach 3:
Get lucky with rarer drops (or collect Bounty Stars and enter the cave).

---
Definitions

ATK = attack

DUR = duration = number of frames of attack animation + follow through (game is 60 FPS)

DEF = defense

EVA = evasion = the blue bar

HP = health points = the red bar

INV = inventory

MON = monster

TSS = tutorial, settings, stats

---
Calculations

player.ATK = weapon.baseAtk * (1+rarity*(weapon.stack-1)/9) * bonusMultiplier * atkDrinkBoost * rankBoost

player.DEF = shield.baseDef * (1+rarity*(shield.stack-1)/9) * bonusMultiplier * defDrinkBoost * rankBoost

player.EVA = shield.baseEva


enemies receive damage equal to player.ATK
 
when player is hit and not shielding, HP lost = enemy.ATK / player.DEF

when player blocks a hit, EVA lost = enemy.ATK / player.DEF

if player blocks but enemy.ATK / player.DEF > player.EVA then HP lost = enemy.ATK / player.DEF - player.EVA


score = winCount * 10 + lossCount + totalRareLootCount * 200 + uniqueRareLootCount * 800

---
Found a bug?

Email me at natkatneal@gmail.com.

---
Privacy Policy:
I collect no user data, but this app contains ads via Google and IAPs via Apple.  Google and Apple may collect your data.  Google Analytics collects ad clickthrough data, etc.
