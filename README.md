# Add On Guns for FiveM QB-Core

This is a FREE release.. thats not my models.. credits goes to the Model maker.. and credits to Xandrice for helping me out a little

## Features

- 17 Add-On Weapons
- Code for qb-core/qb-weapons/qb-smallresources/qb-policejob/qb-jewelery/qb-ambulancejob for easy installation
- Images for every gun

## Installation

- Put the ``[custom_weapons]`` into your ``resource`` folder.
- Drop first code in ``items.lua`` in qb-core

```lua

		-- Custom Weapons
	['weapon_ak47'] 		 = {['name'] = 'weapon_ak47', 	 	  	['label'] = 'AK-47', 			['weight'] = 13000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_assaultrifle.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A rapid-fire, magazine-fed automatic rifle designed for infantry use'},
	['weapon_de'] 			 = {['name'] = 'weapon_de', 		 	  	['label'] = 'Desert Eagle', 			    ['weight'] = 8000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'deagle.png', 		['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A .50 caliber firearm designed to be held with both hands'},
	['weapon_fnx45'] 		 = {['name'] = 'weapon_fnx45', 	 	  	['label'] = 'FN FNX-45', 			['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_combat-pistol.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A combat version small firearm designed to be held in one hand'},
	['weapon_glock17'] 				 = {['name'] = 'weapon_glock17', 			 	['label'] = 'PD Glock 17', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'glock-17.png', 		['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'PD GUN'},
	['weapon_m4'] 		 = {['name'] = 'weapon_m4', 	 	  	['label'] = 'PD M4A1', 			['weight'] = 13000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_carbinerifle.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A lightweight automatic rifle for the Police'},
	['weapon_m9'] 				 = {['name'] = 'weapon_m9', 			 	['label'] = 'Beretta M9A3', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'm1911.png', 		['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A M91'},
	['weapon_m70'] 		 = {['name'] = 'weapon_m70', 	 	  	['label'] = 'M70', 			['weight'] = 13000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'm70.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A rapid-fire, magazine-fed automatic rifle designed for infantry use'},
	['weapon_m1911'] 			 = {['name'] = 'weapon_m1911', 	 	  	['label'] = 'M1911', 			['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'browning.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A hefty firearm designed to be held in one hand (or attempted)'},
	['weapon_uzi'] 			 = {['name'] = 'weapon_uzi', 		 	  	['label'] = 'UZI', 				['weight'] = 10000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',				['image'] = 'uzi.png', 		['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A handheld lightweight machine gun'},
	['weapon_mac10'] 			 = {['name'] = 'weapon_mac10', 		 	  	['label'] = 'MAC-10', 				['weight'] = 10000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',				['image'] = 'mac-10.png', 		['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A handheld lightweight machine gun'},
	['weapon_mossberg'] 		 = {['name'] = 'weapon_mossberg', 	 	['label'] = 'Mossberg 500', 		['weight'] = 10000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SHOTGUN',			['image'] = 'mossberg500.png', ['unique'] = true, 	['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A sawn-off smoothbore gun for firing small shot at short range'},
	['weapon_remington'] 			 = {['name'] = 'weapon_remington', 	 	  	['label'] = 'Remington 870', 			['weight'] = 8000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SHOTGUN',			['image'] = 'remington.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A pump-action smoothbore gun for firing small shot at short range'},
	['weapon_scarh'] 		 = {['name'] = 'weapon_scarh', 	 	['label'] = 'PD SCAR-H', 			['weight'] = 13000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'scar.png', ['unique'] = true, 	['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'An extremely versatile assault rifle for any combat situation'},
	['weapon_shiv'] 				 = {['name'] = 'weapon_shiv', 			 	  	['label'] = 'Shiv', 					['weight'] = 3000, 		['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'shiv.png', 		['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 10.0,     	['description'] = 'An instrument composed of a blade fixed into a handle, used for cutting or as a weapon'},
	['weapon_ar15'] 		 = {['name'] = 'weapon_ar15', 	 	  	['label'] = 'PD AR-15', 			['weight'] = 13000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_mcx.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A lightweight automatic rifle for the Police'},
	['weapon_mk14'] 		 = {['name'] = 'weapon_mk14', 	 	  	['label'] = 'PD MK14', 			['weight'] = 23000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SNIPER',			['image'] = 'mk14.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A very accurate single-fire rifle'},
	['weapon_huntingrifle'] 		 = {['name'] = 'weapon_huntingrifle', 	 	  	['label'] = 'Hunting Rifle', 			['weight'] = 23000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SNIPER',			['image'] = 'huntingrifle.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A very accurate Rifle for hunting'},
```

## Drop the next code in ``weapons.lua`` in qb-core

```lua
	[`weapon_ak47`] 		 = {['name'] = 'weapon_ak47', 	 	['label'] = 'AK-47', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_m70`] 		 = {['name'] = 'weapon_m70', 	 	['label'] = 'M70', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_de`] 			 = {['name'] = 'weapon_de', 		['label'] = 'Desert Eagle', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_fnx45`] 			 = {['name'] = 'weapon_fnx45', 		['label'] = 'FN FNX45', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_glock17`] 			 = {['name'] = 'weapon_glock17', 		['label'] = 'PD Glock 17', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_m4`] 		 = {['name'] = 'weapon_m4', 	 	['label'] = 'PD M4A1', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_m9`] 			 = {['name'] = 'weapon_m9', 		['label'] = 'Beretta M9A3', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_m1911`] 			 = {['name'] = 'weapon_m1911', 		['label'] = 'M1911', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_uzi`] 			 = {['name'] = 'weapon_uzi', 		['label'] = 'UZI', 			['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_mac10`] 			 = {['name'] = 'weapon_mac10', 		['label'] = 'MAC-10', 			['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_mossberg`] 		 = {['name'] = 'weapon_mossberg', 	['label'] = 'Mossberg 500', 		['ammotype'] = 'AMMO_SHOTGUN',	['damagereason'] = 'Devastated / Pulverized / Shotgunned'},
	[`weapon_remington`] 		 = {['name'] = 'weapon_remington', 	['label'] = 'Remington 870', 		['ammotype'] = 'AMMO_SHOTGUN',	['damagereason'] = 'Devastated / Pulverized / Shotgunned'},
	[`weapon_scarh`] 		 = {['name'] = 'weapon_scarh', 	['label'] = 'PD SCAR-H', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_shiv`] 				 = {['name'] = 'weapon_shiv', 			['label'] = 'Shiv', 				['ammotype'] = nil,	['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`weapon_ar15`] 		 = {['name'] = 'weapon_ar15', 	 	['label'] = 'PD AR-15', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_mk14`] 		 = {['name'] = 'weapon_mk14', 	 	['label'] = 'PD MK14', 				['ammotype'] = 'AMMO_SNIPER',	['damagereason'] = 'Ended / Sniped / Shot down / Floored'},
	[`weapon_huntingrifle`] 		 = {['name'] = 'weapon_huntingrifle', 	 	['label'] = 'Hunting Rifle', 				['ammotype'] = 'AMMO_SNIPER',	['damagereason'] = 'Ended / Sniped / Shot down / Floored'},
```

## Drop the next code in ``config.lua`` in qb-weapons

```lua
    --Custom Weapons
    ['weapon_ak47'] 			    = 0.15,
	['weapon_de'] 	                = 0.15,
	['weapon_fnx45'] 			    = 0.15,
    ['weapon_glock17'] 		        = 0.15,
    ['weapon_m4'] 			        = 0.15,
    ['weapon_mk14'] 			        = 0.15,
    ['weapon_huntingrifle'] 			        = 0.20,
    ['weapon_ar15'] 			        = 0.15,
	['weapon_m9'] 	                = 0.15,
	['weapon_m70'] 			        = 0.15,
    ['weapon_m1911'] 		        = 0.15,
    ['weapon_mac10'] 			    = 0.15,
	['weapon_uzi'] 	                = 0.15,
	['weapon_mossberg'] 			= 0.15,
    ['weapon_remington'] 		    = 0.15,
    ['weapon_scarh'] 			    = 0.15,
	['weapon_shiv'] 	            = 0.15,
```
## Drop the next code in ``config.lua`` in qb-weapons (about line 209)

```lua
    ['WEAPON_M9'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_M9_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
        ['extendedclip'] = {
            component = 'COMPONENT_M9_CLIP_02',
            item = 'pistol_extendedclip',
            type = 'clip',
        },
        ['suppressor'] = {
            component = 'COMPONENT_AT_PI_SUPP_02',
            item = 'pistol_suppressor',
        },
    },
    ['WEAPON_M1911'] = {
        ['suppressor'] = {
            component = 'COMPONENT_AT_PI_SUPP_02',
            item = 'pistol_suppressor',
        },
    },
    ['WEAPON_DE'] = {
        ['suppressor'] = {
            component = 'COMPONENT_AT_PI_SUPP_02',
            item = 'pistol_suppressor',
        },
    },
    ['WEAPON_FNX45'] = {
        ['suppressor'] = {
            component = 'COMPONENT_AT_PI_SUPP_02',
            item = 'pistol_suppressor',
        },
    },
    ['WEAPON_UZI'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_MICROSMG_CLIP_01',
            item = 'microsmg_defaultclip',
            type = 'clip',
        },
        ['extendedclip'] = {
            component = 'COMPONENT_MICROSMG_CLIP_02',
            item = 'microsmg_extendedclip',
            type = 'clip',
        },
        ['suppressor'] = {
            component = 'COMPONENT_AT_AR_SUPP_02',
            item = 'pistol_suppressor',
        },
    },
    ['WEAPON_MAC10'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_MICROSMG_CLIP_01',
            item = 'microsmg_defaultclip',
            type = 'clip',
        },
        ['extendedclip'] = {
            component = 'COMPONENT_MICROSMG_CLIP_02',
            item = 'microsmg_extendedclip',
            type = 'clip',
        },
        ['flashlight'] = {
            component = 'COMPONENT_AT_PI_FLSH',
            item = 'pistol_flashlight',
        },
        ['suppressor'] = {
            component = 'COMPONENT_AT_AR_SUPP_02',
            item = 'pistol_suppressor',
        },
    },
    ['WEAPON_AK47'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_AK47_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
        ['extendedclip'] = {
            component = 'COMPONENT_AK47_CLIP_02',
            item = 'assaultrifle_extendedclip',
            type = 'clip',
        },
        ['suppressor'] = {
            component = 'COMPONENT_AT_AR_SUPP_02',
            item = 'rifle_suppressor',
        },
    },
    ['WEAPON_M70'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_M70_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
        ['suppressor'] = {
            component = 'COMPONENT_AT_AR_SUPP_02',
            item = 'rifle_suppressor',
        },
    },
```

## Replace the next code in ``weapdraw.lua`` in qb-smallresources

```lua
local weapons = {
	'WEAPON_KNIFE',
	'WEAPON_NIGHTSTICK',
	'WEAPON_BREAD',
	'WEAPON_FLASHLIGHT',
	'WEAPON_HAMMER',
	'WEAPON_BAT',
	'WEAPON_GOLFCLUB',
	'WEAPON_CROWBAR',
	'WEAPON_BOTTLE',
	'WEAPON_DAGGER',
	'WEAPON_HATCHET',
	'WEAPON_MACHETE',
	'WEAPON_SWITCHBLADE',
	'WEAPON_BATTLEAXE',
	'WEAPON_POOLCUE',
	'WEAPON_WRENCH',
	'WEAPON_PISTOL',
	'WEAPON_PISTOL_MK2',
	'WEAPON_COMBATPISTOL',
	'WEAPON_APPISTOL',
	'WEAPON_PISTOL50',
	'WEAPON_REVOLVER',
	'WEAPON_SNSPISTOL',
	'WEAPON_HEAVYPISTOL',
	'WEAPON_VINTAGEPISTOL',
	'WEAPON_MICROSMG',
	'WEAPON_SMG',
	'WEAPON_ASSAULTSMG',
	'WEAPON_MINISMG',
	'WEAPON_MACHINEPISTOL',
	'WEAPON_COMBATPDW',
	'WEAPON_PUMPSHOTGUN',
	'WEAPON_SAWNOFFSHOTGUN',
	'WEAPON_ASSAULTSHOTGUN',
	'WEAPON_BULLPUPSHOTGUN',
	'WEAPON_HEAVYSHOTGUN',
	'WEAPON_ASSAULTRIFLE',
	'WEAPON_CARBINERIFLE',
	'WEAPON_ADVANCEDRIFLE',
	'WEAPON_SPECIALCARBINE',
	'WEAPON_BULLPUPRIFLE',
	'WEAPON_COMPACTRIFLE',
	'WEAPON_MG',
	'WEAPON_COMBATMG',
	'WEAPON_GUSENBERG',
	'WEAPON_SNIPERRIFLE',
	'WEAPON_HEAVYSNIPER',
	'WEAPON_MARKSMANRIFLE',
	'WEAPON_GRENADELAUNCHER',
	'WEAPON_RPG',
	'WEAPON_STINGER',
	'WEAPON_MINIGUN',
	'WEAPON_GRENADE',
	'WEAPON_STICKYBOMB',
	'WEAPON_SMOKEGRENADE',
	'WEAPON_BZGAS',
	'WEAPON_MOLOTOV',
	'WEAPON_DIGISCANNER',
	'WEAPON_FIREWORK',
	'WEAPON_MUSKET',
	'WEAPON_STUNGUN',
	'WEAPON_HOMINGLAUNCHER',
	'WEAPON_PROXMINE',
	'WEAPON_FLAREGUN',
	'WEAPON_MARKSMANPISTOL',
	'WEAPON_RAILGUN',
	'WEAPON_DBSHOTGUN',
	'WEAPON_AUTOSHOTGUN',
	'WEAPON_COMPACTLAUNCHER',
	'WEAPON_PIPEBOMB',
	'WEAPON_DOUBLEACTION',
	--Custom Weapon
	'WEAPON_AK47',
	'WEAPON_M9',
	'WEAPON_FNX45',
	'WEAPON_DE',
	'WEAPON_GLOCK17',
	'WEAPON_M4',
	'WEAPON_MK14',
	'WEAPON_HUNTINGRIFLE',
	'WEAPON_AR15',
	'WEAPON_M70',
	'WEAPON_M1911',
	'WEAPON_MAC10',
	'WEAPON_UZI',
	'WEAPON_MOSSBERG',
	'WEAPON_REMINGTON',
	'WEAPON_SCARH',
	'WEAPON_SHIV',
}
--Weapons that require the Police holster animation
local holsterableWeapons = {
	--'WEAPON_STUNGUN',
	'WEAPON_PISTOL',
	'WEAPON_PISTOL_MK2',
	'WEAPON_COMBATPISTOL',
	'WEAPON_APPISTOL',
	'WEAPON_PISTOL50',
	'WEAPON_REVOLVER',
	'WEAPON_SNSPISTOL',
	'WEAPON_HEAVYPISTOL',
	'WEAPON_VINTAGEPISTOL',
	--Custom Weapon
	'WEAPON_DE',
	'WEAPON_GLOCK17',
	'WEAPON_M9',
	'WEAPON_M1911',
	'WEAPON_FNX45',
}
```

## Drop the next code in ``recoil.lua`` in qb-smallresources ( LINE 107 )

```lua
		-- CUSTOM WEAPONS
	[GetHashKey("weapon_ak47")] = 0.5,
	[GetHashKey("weapon_de")] = 0.5,
	[GetHashKey("weapon_fnx45")] = 0.3,
	[GetHashKey("weapon_glock17")] = 0.3,
	[GetHashKey("weapon_m4")] = 0.3,
	[GetHashKey("weapon_mk14")] = 0.4,
	[GetHashKey("weapon_huntingrifle")] = 0.4,
	[GetHashKey("weapon_ar15")] = 0.4,
	[GetHashKey("weapon_m9")] = 0.4,
	[GetHashKey("weapon_m70")] = 0.5,
	[GetHashKey("weapon_m1911")] = 0.4,
	[GetHashKey("weapon_mac10")] = 0.5,
	[GetHashKey("weapon_uzi")] = 0.5,
	[GetHashKey("weapon_mossberg")] = 0.7,
	[GetHashKey("weapon_remington")] = 0.7,
	[GetHashKey("weapon_scarh")] = 0.5,
```     
## Replace the next code in ``config.lua`` in qb-jewelery

```lua
Config.WhitelistedWeapons = {
    [`weapon_assaultrifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_carbinerifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pumpshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_sawnoffshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_compactrifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_microsmg`] = {
        ["timeOut"] = 10000
    },
    [`weapon_autoshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol_mk2`] = {
        ["timeOut"] = 10000
    },
    [`weapon_combatpistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_appistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol50`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m4`] = {
        ["timeOut"] = 10000
    },
    [`weapon_ar15`] = {
        ["timeOut"] = 10000
    },
    [`weapon_scarh`] = {
        ["timeOut"] = 10000
    },
    [`weapon_de`] = {
        ["timeOut"] = 10000
    },
    [`weapon_fnx45`] = {
        ["timeOut"] = 10000
    },
    [`weapon_glock17`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mossberg`] = {
        ["timeOut"] = 10000
    },
    [`weapon_remington`] = {
        ["timeOut"] = 10000
    },
    [`weapon_ak47`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m70`] = {
        ["timeOut"] = 10000
    },
    [`weapon_uzi`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mac10`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m9`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m1911`] = {
        ["timeOut"] = 10000
    },
}
```
## Replace the next code in ``config.lua`` in qb-ambulancejob

```lua
    [`WEAPON_DE`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_M4`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_AR15`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_AK47`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_M70`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_SCARH`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_UZI`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_MAC10`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_GLOCK17`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M9`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M1911`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_FNX45`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_REMINGTON`] = Config.WeaponClasses['SHOTGUN'],
    [`WEAPON_MOSSBERG`] = Config.WeaponClasses['SHOTGUN'],
    [`WEAPON_SHIV`] = Config.WeaponClasses['HEAVY_IMPACT'],
    [`WEAPON_MK14`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_HUNTINGRIFLE`] = Config.WeaponClasses['HIGH_CALIBER'],
```

## (OPTIONAL) Thats my Police Shop, u can just copy the Guns out

```lua
Config.Items = {
    label = "Police Armory",
    slots = 30,
    items = {
        [1] = {
            name = "pistol_ammo",
            price = 12,
            amount = 1000,
            info = {},
            type = "item",
            slot = 1,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [2] = {
            name = "rifle_ammo",
            price = 12,
            amount = 1000,
            info = {},
            type = "item",
            slot = 2,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [3] = {
            name = "shotgun_ammo",
            price = 12,
            amount = 1000,
            info = {},
            type = "item",
            slot = 3,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [4] = {
            name = "snp_ammo",
            price = 12,
            amount = 1000,
            info = {},
            type = "item",
            slot = 4,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [5] = {
            name = "taser_ammo",
            price = 12,
            amount = 1000,
            info = {},
            type = "item",
            slot = 5,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [6] = {
            name = "pdmdt",
            price = 172,
            amount = 1000,
            info = {},
            type = "item",
            slot = 6,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [7] = {
            name = "police_stormram",
            price = 1199,
            amount = 10,
            info = {},
            type = "item",
            slot = 7,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [8] = {
            name = "repairkit",
            price = 172,
            amount = 100,
            info = {},
            type = "item",
            slot = 8,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [9] = {
            name = "binoculars",
            price = 344,
            amount = 100,
            info = {},
            type = "item",
            slot = 9,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [10] = {
            name = "heavyarmor",
            price = 58,
            amount = 1000,
            info = {},
            type = "item",
            slot = 10,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [11] = {
            name = "weapon_glock17",
            price = 12,
            amount = 1,
            info = {
                serie = "PD-" .. tostring(Config.RandomInt(2) .. Config.RandomStr(3) .. Config.RandomInt(1) .. Config.RandomStr(2) .. Config.RandomInt(3)),
                attachments = {
                    {component = "COMPONENT_AT_PI_FLSH", label = "Flashlight"},
                }
            },
            type = "weapon",
            slot = 11,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [12] = {
            name = "weapon_stungun",
            price = 12,
            amount = 1,
            info = {
                serie = "PD-" .. tostring(Config.RandomInt(2) .. Config.RandomStr(3) .. Config.RandomInt(1) .. Config.RandomStr(2) .. Config.RandomInt(3)),
            },
            type = "weapon",
            slot = 12,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [13] = {
            name = "weapon_nightstick",
            price = 0,
            amount = 1,
            info = {},
            type = "weapon",
            slot = 13,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [14] = {
            name = "WEAPON_FIREEXTINGUISHER",
            price = 287,
            amount = 1,
            info = {},
            type = "weapon",
            slot = 14,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [15] = {
            name = "radio",
            price = 58,
            amount = 1000,
            info = {},
            type = "item",
            slot = 15,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [16] = {
            name = "camera",
            price = 2291,
            amount = 1000,
            info = {},
            type = "item",
            slot = 16,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [17] = {
            name = "weapon_flashlight",
            price = 287,
            amount = 1,
            info = {},
            type = "weapon",
            slot = 17,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [18] = {
            name = "ifaks",
            price = 10,
            amount = 1000,
            info = {},
            type = "item",
            slot = 18,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [19] = {
            name = "weapon_m4",
            price = 12,
            amount = 1,
            info = {
                serie = "PD-" .. tostring(Config.RandomInt(2) .. Config.RandomStr(3) .. Config.RandomInt(1) .. Config.RandomStr(2) .. Config.RandomInt(3)),
                attachments = {
                    {component = "COMPONENT_AT_AR_FLSH", label = "Flashlight"},
                }
            },
            type = "weapon",
            slot = 19,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [20] = {
            name = "weapon_ar15",
            price = 12,
            amount = 1,
            info = {
                serie = "PD-" .. tostring(Config.RandomInt(2) .. Config.RandomStr(3) .. Config.RandomInt(1) .. Config.RandomStr(2) .. Config.RandomInt(3)),
                attachments = {
                    {component = "COMPONENT_AT_AR_FLSH", label = "Flashlight"},
                    {component = "COMPONENT_AT_SCOPE_MEDIUM", label = "Scope"},
                    {component = "COMPONENT_AT_AR_AFGRIP", label = "AF-Grip"},
                }
            },
            type = "weapon",
            slot = 20,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [21] = {
            name = "weapon_remington",
            price = 12,
            amount = 1,
            info = {
                serie = "PD-" .. tostring(Config.RandomInt(2) .. Config.RandomStr(3) .. Config.RandomInt(1) .. Config.RandomStr(2) .. Config.RandomInt(3)),
                attachments = {
                    {component = "COMPONENT_AT_SG_FLSH", label = "Flashlight"},
                }
            },
            type = "weapon",
            slot = 21,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [22] = {
            name = "spikes",
            price = 573,
            amount = 1000,
            info = {},
            type = "item",
            slot = 22,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [23] = {
            name = "nightvision",
            price = 115,
            amount = 1000,
            info = {},
            type = "item",
            slot = 23,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [24] = {
            name = "weapon_scarh",
            price = 12,
            amount = 1,
            info = {
                serie = "PD-" .. tostring(Config.RandomInt(2) .. Config.RandomStr(3) .. Config.RandomInt(1) .. Config.RandomStr(2) .. Config.RandomInt(3)),
                attachments = {
                    {component = "COMPONENT_AT_AR_FLSH", label = "Flashlight"},
                }
            },
            type = "weapon",
            slot = 24,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [25] = {
            name = "weapon_mk14",
            price = 12,
            amount = 1,
            info = {
                serie = "PD-" .. tostring(Config.RandomInt(2) .. Config.RandomStr(3) .. Config.RandomInt(1) .. Config.RandomStr(2) .. Config.RandomInt(3)),
                attachments = {
                    {component = "COMPONENT_AT_SCOPE_LARGE", label = "Scope"},
                }
            },
            type = "weapon",
            slot = 25,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
    }
}
```

## This is a FREE release.. thats not my models.. credits goes to the Model maker.. and credits to Xandrice for helping me out a little
## This is a FREE release.. thats not my models.. credits goes to the Model maker.. and credits to Xandrice for helping me out a little
## This is a FREE release.. thats not my models.. credits goes to the Model maker.. and credits to Xandrice for helping me out a little
## This is a FREE release.. thats not my models.. credits goes to the Model maker.. and credits to Xandrice for helping me out a little
