



# SNKRX

[SNKRX](https://store.steampowered.com/app/915310/SNKRX/) is an arcade shooter roguelite where you control a snake of heroes that automatically attack nearby enemies.
Combine different heroes to unlock class bonuses and create unique builds, and steer your unstoppable party as they ravage through endless waves of enemies.

https://user-images.githubusercontent.com/409773/119258159-ea982b00-bb9e-11eb-8082-37e2c65591ea.mp4

[**Check it out on Steam!**](https://store.steampowered.com/app/915310/SNKRX/)

### Running

Download this repository, `cd` into it and then run `engine/love/love.exe --console .`. You need to have Steam up to run it successfully.

### LICENSE

All assets have their specific licenses and they are linked to in the game's credits. All code is under the MIT license.

### Everything Mod Related

This mod is meant to rebalance the game. Make items and units more viable, nerf the OP stuff and maybe more. 
I'm planning to make this mod combine with Despacit2p0's mod but I'll include that in a different branch as I want to make this mod it's own standalone

If you're having difficulties opening the mod, just ask in the modding section or @ me in the discord server :)

Remember, this is an early version so changes may not be working properly. I also still have more changes to add and more testing to do.

Last but not least, don't savescum. It really does ruin the game to a certain extent. I hope that you'll live up to my expectations! (Yes, this is emotional blackmail)

There are many changes (Note that I may miss some important ones) in this mod but IMO, the most important changes are:
- New item and unit descriptions
- Ceremonial/Flying dagger nerf
- Dividends should have a cap of 1000%
- Other builds such as DoT, Knockback, Cursers, Builders and Rangers are more viable through better items and units
- New tier 1's are: Sentry
- New tier 2's are: Host
- New tier 3's are: Plague Doctor, Psykino, Cannoneer
- New tier 4's are: Gambler, Dual Gunners 
- Big item changes: Burning Strike, Noxious Strike, Baneling Burst, Whispers of Doom, Hextouch, Divine Punishment, Gravity Field, Oroboros Right, Porcupine Technique and more
- Big unit changes: Silencer, Vulcanist, Carver, Squire, Merchant, Bomber and more
- Class bonuses/class modifiers were slightly affected (Healer set and mage set bonus were buffed to 20/40 but isn't included in the description)

Every single change (Some might not work as expected, lvl 3 means lvl 3 ability)
Units:
- Sage now has 50% more area size and lvl 3 does 3x more damage
- Psykino is tier 3, lvl 3 does 4x damage and knockback force has been reduced (to 20 iirc)
- Plague Docotr is tier 3 and his circle lasts 250% longer
- Cryomancer always slows enemies in the radius but it scales with level (lvl 1 = 80% mvspd, lvl 2 = 50% mvspd, lvl 3 = 20% mvspd), lvl 3 does 400% damage
- Bane rifts lasts for 3 seconds instead of 1,does double damage and curses 8 enemies instead of 6
- Warden atk cooldown is now 10 seconds instead of 12
- Silencer lvl 3 hits 3 more units, slows them to 25% mvspd and deals 40 damage on curse instead of dealing DoT
- Engineer has +50% turret deploy speed and lvl 3 increases turret atk spd and dmg by 100% instead of 50%
- Pyromancer range increases by 10 per level up
- Vulcanist deploys volcanoes 66% faster, does 50% more dmg, has 25% more radius and lvl 3 triples the speed/amount of explosions instead of double
- Corruptor attacks twice as fast
- Sentry is tier 1, deploys sentries every 5 seconds instead of every 7, sentry atk speed scales with Sentry level and sentries last 5 seconds longer
- Host is tier 2 and attacks 20% faster
- Elementor does 50% more dmg
- Bomber does 50% more dmg and lvl 3 gives area size and dmg a buff of 150% instead of 100%
- Beastmaster-Attacks 50% faster and lvl 3 spawns 5 critters on contact instead of 4
- Artificer spawns an automation every 5 seconds instead of 6, automations move and shoot faster at lvl 3 and explodes into 12 projectiles
- Carver spawns trees/totems 50% faster
- Cannonneer is tier 3
- Flagellant has 5x health at lvl 3
- Psykeeper spawns healing orbs when it loses 20% of it's health, not 25 and lvl 3 does 3x dmg on contact instead of 2x
- Spellblade attacks twice as fast (probably will change)
- Barrager attacks twice as fast and the knockback force is increased by 28% (at both lvl 1 and lvl 3)
- Stormweaver deals double the damage and hit double the enemeis
- Witch lvl 3 projectiles chains twice
- Wizard attacks 40% faster
- Assassin has slightly less range but attacks every 1.8 seconds instead of 2
- Vagrant now gains a 15% stat increase for every set level instead of 10%
- Barbarian attacks every 6 seconds instead of 8 but the stun lasts for 3 seconds instead of 4
- Highlander lvl 3 repeats the attack 5 times in quick succession instead of 3 times
- Infestor curses two more enemies at lvl 3
- Miner lvl 3 projectiles pierce three times instead of twice
- Cleric is unchanged
- Priest prevents 4 unit deathes at lvl 3 instead of 3
- Psychic has a 50% beigger area size and attacks 0.5 seconds faster
- Squire at lvl 3 now gives 30% buff to all stats instead of adding it onto the original ability (and making dmg and atk spd 50%)
- Merchant interest cap is 8
- Scout and Thief's attack speed and range went down slightly
- Dual gunner is now tier 4
- Outlaw's range is slightly decreased
- Gambler is now tier 4
- Swordman lvl 3 triples damage instead of doubles
- Blade's range is increased by 20%

Sets:
Builder:Area size and area dmg is 25% up, along with dmg at 30%
Ranger:Health, defense and atk spd slightly down, dmg up 50%
Swarmer:Attack speed and movement speed slightly up
Rogue:Damage down but attack speed up
Sorcerer:Health and defense slightly up, damage slighty down, attack speed is 50% up
Voider: Deal 25/50% more damage at set lvl 1/2
Healer: 20/40% chance to spawn an extra healing orb at set lvl 1/2
Mage: enemies have -20/40 def at set lvl 1/2
Curser: All curser's range (actual attack range, not the first unit detected range) is increased by 25%

Items:
- Culling strike is now 20/35/50% to kill elites
- Annihilation lasts 10 seconds
- Burn field deals triple damage, double area size and lasts twice as long
- Seeping deals 20/35/50% of the enemy's max health instead of a flat amount
- Oroboros Technique R shoot 5/6/7 projectiles when going right
- Porcupine Technique projectlles ricochet 6 times, deal 5x dmg and releases double the projectiles
- Shoot 5's range is 33% larger and shoots 5 projectiles a second
- Freeze field has a 50% larger size, slows enemies to 25% base mvspd and lasts twice as long
- Kinetic bomb has 4x stronger knockback force
- Lasting 7 lasts 20 seconds
- Divine Barrage has a 30/60/90% chance of activating on healing orb pickup
- Gravity Field releases enemies at high speeds after holding them for 3 secodns
- Call of the void makes voiders deal 50/100/150% more damage
- Hextouch deals 10/15/20% of emeny's max health as damage per second for 3 seconds
- Chronomancy makes mages attack 25/35/45% faster
- Insurance: heroes have 6 times the emrcenary's bonus to drop 4 gold
- Fracture's projectiles now pierec 4 times
- Critical Strike has a 8/16/24% chance of activating
- Construct instability does 200/300/400% damage on death
- Oroboros Technique L now gives 50/75/100% defense
- Temporal Chains now slow enemies by 15/25/35%
- Deceleration now slows enemies taking DoT by 20/35/50%
- Tremors deals 4x damage
- Kinetic strike has a 20/40/60% chance of knocking back enemies
- Blunt arrow has a 15/30/45% chance of applying a knockback force (which is now 4 times stronger)
- Offensive stance gives first and last positions 20/40/60% more damage
- Centipede makes you move 15/25/35% faster
- Divine punishment now deals 6X enemy health as damage, x being amount of mages
- Haste-Unchanged
- Heavy Impact does 4x damage
- Damage 4 gives 60% more damage to position 4
- Baneling Burst does 2X/3X/4X% of enemy health as damage, x being critter hp
- Berserking gives warrior 200/300/400% damage based on missing health
- Whispers of Doom deals 20/35/50% of enemy health as damge
- Malediction-Unchanged
- Rearm-Unchanged
- Taunt now has a 15/30/45% of attracting enemy units with constructs
- Resonance gives 3/6/10% more dmg per unit hit with an AoE
- Psychosense-unchanged
- Psyker orbs give 1/3/5 psyker orbs
- Assassination deals 66% dmg if no crit is applied
- Death 6-Unchanged
- Noxious Strike has a 8/16/24% chance of dealing 25% dps for 4 seconds
- Burning Strike always deals 20% dps for 2 seconds
- Magnetism-Unchanged
- Speed 3 gives position 3 60% attack speed
- Psychosink increases psyker orbs dmg by 50/100/150%
- Orbitism increases psyker orb's movement speed by 33/66/99%
- Psycholeak spwans a psyker orb every 8 seconds
- Ultimatum deals 15/30/45% more dmg per chained attack
- Intimidation-Unchanged
- Balista makes projectiles deal 25/40/55% more damage
- Echo Barrage-Unchanged
- Magnify-Unchanged
- Amplify makes AoE deal 20/40/60% more damage
- Lucky strike has a 10% to spawn gold on kill
- Homing Barrage-Unchanged
- Blessing increases healing effectiveness by 15/25/35%
- Defensive Stance gives first and last position 20/40/60% more defense
- Last Stand buffs the last unit by 25%
- Dividends cap at 1000% damage
- Awakening-Unchanged
- Unleash gives 1% area size and area damage to all allies
- Lightning strike deals 33/41/50% damage to each unit (actually a buff)
- Ceremonial dagger now does 50% of its original damage
- Flying dagger chains 1/2/3 times if it's a rogue projectile
- Vulnerability-Unchanged
- Infesting strike has a 8/16/24% chance to spawn 2 critters on kill
- Unrelenting Stance-Unchanged
- Unwavering Stance-Unchanged
- Reinforce gives 8/16/24% attack speed, damage and defense if you have 1 enchanter
- Enchanted-Unchanged
- Payback gives 5/10/15% attack speed when an enchater is hit
- Divine Machine Arrow has a 15/25/35% chance to pierce 1/2/3 times

Other Changes:
- Negative Defense is calculated properly
- Loop scaling has been changed such that tougher difficulty kicks in earlier so looping is enjoyable and not drawn out
- Original loop scaling overtakes new scaling difficulty at level 174
- The speed cap is still approximately the same as in base game
- Level 25 gives half the gold it originally used to (also affects level 50,75,100,etc.)
- The gold multiplier after each loop (not including first 25 levels) has been reduced by 50%
- Maintenance Update 3 changes were included
