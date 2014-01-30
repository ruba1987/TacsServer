TacsServer
==========

A server implementing the TacsArena plugin

version: 1.1

### You can add new classes here
classes:
    warrior:
        displayName: "&4Warrior" ### Used for signs
        items:
            - iron_battleaxe: sharp:2 1
            - iron_helm: 1
            - iron_chest: 1 protection: 1
            - iroin_leggings: 1
            - iron_boots: 1
            - 373;8229: 3 # potion of healing lvl 2
	brute:
	    displayName: "&1Brute" ### Used for signs
        items:
			- iron_helm: 1 blast_protection: 1
            - iron_chest: thorns: 1 projectile_protection: 1 1
			- iron_hammer: 1
    ranger:
        displayName: "&2Ranger" ### Used for signs
        items:
            - iron_knife: sharp:1 1
            - bow: punch:1 infinity:1 1
		    - arrow: 64
            - leather_helm: 1
            - iron_chest: projectile_prot:1 1
            - leather_leggings: 1
            - leather_boots: 1
            - 373;8193: 3 # potion of regen
    monk:
        displayName: "&fMonk" ### Used for signs
        items:
            - leather_helm: projectile_protection: 2 1
            - leather_chest: protection: 2 1
            - leather_leggings: 1
            - leather_boots: 1
			- halibard: 1
            - 373;8229: 2 # potion of healing 2
            - 373;8193: 2 # potion of regen
            - 373;16424: 10 # splash potion of harming 1
			- 373:8264: 5 # potion of weakness
	assassin:
		displayName: "&8Assassin" ### Used for signs
		items:
			- iron_knife: sharp: 2 1
			- potion_of_slowness: 5
			- potion_of_invisibility: 5
			- blow_gun: 1
			- poison_dart: 20
			- leather_helm: 1
            - leather_chest: 1
			- 373;8193: 3 # potion of regen
	mercenary:
		displayName: "&cMercenary" ### Used for signs
		items:
			- leather_helm: projectile_protection: 2
			- musket: 1
			- musket_ball: 15
			- flint_lock_pistol: 1
			- 373;8193: 3 # potion of regen
	pyro:
		displayName: "&6Pyro" ### Used for signs
		items:
			- leather_helm: 1
            - leather_chest: fire_protection: 2 1
            - leather_leggings: 1
            - leather_boots: 1
			- crossbow: flame: 1 1
			- bolt: 64
			- fire_rod: 10
			- 373;8193: 3 # potion of regen
