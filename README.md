# Realistic-Fox-Origin
A custom-made fox origin mod for Minecraft Fabric Origins Mod.
Language available: Simplified Chinese & English
**Needs Origins Mod and Pehkui Mod to function**

Origins Mod: https://www.curseforge.com/minecraft/mc-mods/origins

Pehkui Mod: https://www.curseforge.com/minecraft/mc-mods/pehkui

This is my first time writing a mod.
Technically it's not a mod, I just created the datapack first (also my first time) and added the fabric header file then converted it to .jar to make it work in mods folder.

Therefore, in case something breaks, you can add in the coment section, if there's any...
idk I just signed up github
hope you have fun with this mod ;)

################
Added Origin:
Red Fox

-Active Skill 1
	**Pounce**
	[Activate with Primary skill key]
    
	Cooldown 1.5s
	Cooldown Indicator On

	Adds velocity to forward and upward motions. When falling, your attack damage increase to 250% and damage done to you increase to 200%.
	Your reach is increaseed to 140% for more attack window.
	All effects reset when you land on blocks.
    
	Play sounds when the skill and the two damage modifier is activated.
	Spawn particles when the skill is activated.
    
	The two damage modifiers are disabled when you sneak during the fall (Hold sneak to defend).

	Apply 0.5 exhaustion when activate.
	Unable to use if foodlevel reaches 0, play a sound instead.

	Can use at most twice before landing, so that fireworks are not completely useless when using elytra.

-Active Skill 2
	**Hyper-sensing**
	[Activate with Primary skill key]

	Cooldown 5s
	Cooldown Indicator On

	Makes mobs in 50 radius glow for you in the duration of 10s.

	Hostle mobs/Enderman/Wolf/Polarbear glow red
	Players glow blue
	Fox glow green
	Other entities glow white

-Active Skill 3
	**Hunt**
	[Activate with sneak key]

	Cooldown Indicator On

	Sneak to charge a 3 seconds bar.
	Excceed 1.5 seconds become invisible.
	When fully charged, your attack increases by 50% in 5 seconds.

	Under these circumstances the charge will be interrupted:
	-No longer sneak
	-Use Active Skill 1
	-Fall distance more than 2
	-Receive more than 2 damage
    

-Passive Skill 1
	Agility

	While sprinting, movement speed and jump height increased by 40%.
	Ignore fall damage if Fall distance less than 24.
	If falling more than 23 blocks, hold sneak when landing to reduce fall damage by 80%.

-Passive Skill 2
	Smol

	Size shrinks to 70% of Human.
	Max Health Reduces to 8 hearts.
	Mob follow range halved.

-Passive Skill 3
	Foxiality

	Damage against chicken, rabbit, fishes increases to 400%.
	Will anger wolf in 18 blocks radius.
	Will anger Polar bear in 16 blocks radius.

	Does not get damaged by berry bush.(I have no idea how to remove the slow down effect)
    
	Trusted by foxes in 16 blocks radius.
	Receive a random item when wake up from sleep.(Items/Weights according to Minecraft wiki)

-Passive Skill 4
	Fluffy

	Received fire damage increases to 150%.
	
	Invulnerable against freezing damage.(Unless your upper body is in rain)
	
	When in rain/in water, movement speed reduce by 20%. Effect resets when under cover/out of water.
	Effect can be avoided by wearing armor with water protection enchantment level sum > 4.

	Trigger a shaking water effect like wolf when out of water/under cover.(Effect cooldown 10s)
	Will not trigger the shaking water effect if you are sneaking, in case you want to hide from something...

-Passive Skill 5
	Timidity

	When meeting certain conditions, add "fear" effect:
	-16 blocks around a Villager  (No longer applies when having advancement hero_of_the_village)
	-16 blocks around a Polar bear
	-18 blocks around a Wolf
	-30 blocks around a Warden  (No longer applies when killed 3 wardens)
	-50 blocks around a Wither  (No longer applies when killed 1 wither)
	-150 blocks around an Ender dragon  (No longer applies when killed 1 Ender dragon)
	-Spawn of lightning
	-Health < 3 (1.5 hearts)

	Fear Effect:
	-Speed 1 for 5 seconds
	-Weakness 1 for 5 seconds
	-Shaking for 8 seconds

	When health is less than 4 (2 hearts), spawn red particles like you leave a blood trail.
	Sneak to stop your bleeding to hide the blood trail effect, in case you want to hide from something...

-Passive Skill 6
	Unique Taste

	Glow berries/Sweet berries buffed to outmatch golden carrot.(From the base, +4 foodlevel, +16 saturation)
	Raw/cooked chicken/rabbit/cod/salmon/tropical fish buffed by addition.(From the base, +2 foodlevel, +5 saturation)
	The above foods are edible even foodlevel is at maximum.
	When consumed, apply regeneration 1 for 3 seconds.

	All other foods are nerfed that they only provide half as much foodlevel,saturation as before.
 
-Passive Skill 7
	Fast-Paced

	When foodlevel > 6, base exhaustion speed is increased to 150%.

	Attack speed is increased to 125%.

-Hidden Skiil
	Fox Sound Pack

	Playsound fox.death when death.
	Playsound fox.hurt when hurt.
	Playsound fox.eat when eat.
	Playsound fox.aggro when eat disliked food.(nerfed food)
	Playsound fox.sleep when sleeping.
	Playsound fox.ambient when wakeup
