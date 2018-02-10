<div class="isa_warning">
    <i class="fa fa-warning"></i>
    This page is not complete. Consider updating it.
</div>

# Constants

Constants are variables that represents numbers for all kinds of various things. You can use the number that the constant represents, but the constants help make the code alot easier to read and understand. Instead of magic effect 12, you would use CONST_ME_ENERGYHIT. And everyone would understand that the magic effect is an energy hit. Also if the ID/number would change in the future, the constant would be updated to the new ID, and all scripts using the constant would work as intended without the need to update every script with new numeric values.

# MagicEffect

```lua
CONST_ME_NONE,

CONST_ME_DRAWBLOOD = 1
CONST_ME_LOSEENERGY = 2
CONST_ME_POFF = 3
CONST_ME_BLOCKHIT = 4
CONST_ME_EXPLOSIONAREA = 5
CONST_ME_EXPLOSIONHIT = 6
CONST_ME_FIREAREA = 7
CONST_ME_YELLOW_RINGS = 8
CONST_ME_GREEN_RINGS = 9
CONST_ME_HITAREA = 10
CONST_ME_TELEPORT = 11
CONST_ME_ENERGYHIT = 12
CONST_ME_MAGIC_BLUE = 13
CONST_ME_MAGIC_RED = 14
CONST_ME_MAGIC_GREEN = 15
CONST_ME_HITBYFIRE = 16
CONST_ME_HITBYPOISON = 17
CONST_ME_MORTAREA = 18
CONST_ME_SOUND_GREEN = 19
CONST_ME_SOUND_RED = 20
CONST_ME_POISONAREA = 21
CONST_ME_SOUND_YELLOW = 22
CONST_ME_SOUND_PURPLE = 23
CONST_ME_SOUND_BLUE = 24
CONST_ME_SOUND_WHITE = 25
CONST_ME_BUBBLES = 26
CONST_ME_CRAPS = 27
CONST_ME_GIFT_WRAPS = 28
CONST_ME_FIREWORK_YELLOW = 29
CONST_ME_FIREWORK_RED = 30
CONST_ME_FIREWORK_BLUE = 31
CONST_ME_STUN = 32
CONST_ME_SLEEP = 33
CONST_ME_WATERCREATURE = 34
CONST_ME_GROUNDSHAKER = 35
CONST_ME_HEARTS = 36
CONST_ME_FIREATTACK = 37
CONST_ME_ENERGYAREA = 38
CONST_ME_SMALLCLOUDS = 39
CONST_ME_HOLYDAMAGE = 40
CONST_ME_BIGCLOUDS = 41
CONST_ME_ICEAREA = 42
CONST_ME_ICETORNADO = 43
CONST_ME_ICEATTACK = 44
CONST_ME_STONES = 45
CONST_ME_SMALLPLANTS = 46
CONST_ME_CARNIPHILA = 47
CONST_ME_PURPLEENERGY = 48
CONST_ME_YELLOWENERGY = 49
CONST_ME_HOLYAREA = 50
CONST_ME_BIGPLANTS = 51
CONST_ME_CAKE = 52
CONST_ME_GIANTICE = 53
CONST_ME_WATERSPLASH = 54
CONST_ME_PLANTATTACK = 55
CONST_ME_TUTORIALARROW = 56
CONST_ME_TUTORIALSQUARE = 57
CONST_ME_MIRRORHORIZONTAL = 58
CONST_ME_MIRRORVERTICAL = 59
CONST_ME_SKULLHORIZONTAL = 60
CONST_ME_SKULLVERTICAL = 61
CONST_ME_ASSASSIN = 62
CONST_ME_STEPSHORIZONTAL = 63
CONST_ME_BLOODYSTEPS = 64
CONST_ME_STEPSVERTICAL = 65
CONST_ME_YALAHARIGHOST = 66
CONST_ME_BATS = 67
CONST_ME_SMOKE = 68
CONST_ME_INSECTS = 69
CONST_ME_DRAGONHEAD = 70
CONST_ME_ORCSHAMAN = 71
CONST_ME_ORCSHAMAN_FIRE = 72
CONST_ME_THUNDER = 73
CONST_ME_FERUMBRAS = 74
CONST_ME_CONFETTI_HORIZONTAL = 75
CONST_ME_CONFETTI_VERTICAL = 76
// 77-157 are empty
CONST_ME_BLACKSMOKE = 158
// 159-166 are empty
CONST_ME_REDSMOKE = 167
CONST_ME_YELLOWSMOKE = 168
CONST_ME_GREENSMOKE = 169
CONST_ME_PURPLESMOKE = 170
CONST_ME_EARLY_THUNDER = 171
CONST_ME_RAGIAZ_BONECAPSULE = 172
CONST_ME_CRITICAL_DAMAGE = 173
// 174 is empty
CONST_ME_PLUNGING_FISH = 175
```

# ShootType

```lua
CONST_ANI_NONE

CONST_ANI_SPEAR = 1
CONST_ANI_BOLT = 2
CONST_ANI_ARROW = 3
CONST_ANI_FIRE = 4
CONST_ANI_ENERGY = 5
CONST_ANI_POISONARROW = 6
CONST_ANI_BURSTARROW = 7
CONST_ANI_THROWINGSTAR = 8
CONST_ANI_THROWINGKNIFE = 9
CONST_ANI_SMALLSTONE = 10
CONST_ANI_DEATH = 11
CONST_ANI_LARGEROCK = 12
CONST_ANI_SNOWBALL = 13
CONST_ANI_POWERBOLT = 14
CONST_ANI_POISON = 15
CONST_ANI_INFERNALBOLT = 16
CONST_ANI_HUNTINGSPEAR = 17
CONST_ANI_ENCHANTEDSPEAR = 18
CONST_ANI_REDSTAR = 19
CONST_ANI_GREENSTAR = 20
CONST_ANI_ROYALSPEAR = 21
CONST_ANI_SNIPERARROW = 22
CONST_ANI_ONYXARROW = 23
CONST_ANI_PIERCINGBOLT = 24
CONST_ANI_WHIRLWINDSWORD = 25
CONST_ANI_WHIRLWINDAXE = 26
CONST_ANI_WHIRLWINDCLUB = 27
CONST_ANI_ETHEREALSPEAR = 28
CONST_ANI_ICE = 29
CONST_ANI_EARTH = 30
CONST_ANI_HOLY = 31
CONST_ANI_SUDDENDEATH = 32
CONST_ANI_FLASHARROW = 33
CONST_ANI_FLAMMINGARROW = 34
CONST_ANI_SHIVERARROW = 35
CONST_ANI_ENERGYBALL = 36
CONST_ANI_SMALLICE = 37
CONST_ANI_SMALLHOLY = 38
CONST_ANI_SMALLEARTH = 39
CONST_ANI_EARTHARROW = 40
CONST_ANI_EXPLOSION = 41
CONST_ANI_CAKE = 42

CONST_ANI_TARSALARROW = 44
CONST_ANI_VORTEXBOLT = 45

CONST_ANI_PRISMATICBOLT = 48
CONST_ANI_CRYSTALLINEARROW = 49
CONST_ANI_DRILLBOLT = 50
CONST_ANI_ENVENOMEDARROW = 51

CONST_ANI_GLOOTHSPEAR = 53
CONST_ANI_SIMPLEARROW = 54
```

# TalkType

```lua
TALKTYPE_SAY = 1
TALKTYPE_WHISPER = 2
TALKTYPE_YELL = 3
TALKTYPE_PRIVATE_FROM = 4
TALKTYPE_PRIVATE_TO = 5
TALKTYPE_CHANNEL_Y = 7
TALKTYPE_CHANNEL_O = 8
TALKTYPE_PRIVATE_NP = 10
TALKTYPE_PRIVATE_PN = 12
TALKTYPE_BROADCAST = 13
TALKTYPE_CHANNEL_R1 = 14 //red - #c text
TALKTYPE_PRIVATE_RED_FROM = 15 //@name@text
TALKTYPE_PRIVATE_RED_TO = 16 //@name@text
TALKTYPE_MONSTER_SAY = 36
TALKTYPE_MONSTER_YELL = 37

TALKTYPE_CHANNEL_R2 = 0xFF //#d
```

# Message

```lua
MESSAGE_STATUS_CONSOLE_BLUE = 4 /*FIXME Blue message in the console*/

MESSAGE_STATUS_CONSOLE_RED = 13 /*Red message in the console*/

MESSAGE_STATUS_DEFAULT = 17 /*White message at the bottom of the game window and in the console*/
MESSAGE_STATUS_WARNING = 18 /*Red message in game window and in the console*/
MESSAGE_EVENT_ADVANCE = 19 /*White message in game window and in the console*/

MESSAGE_STATUS_SMALL = 21 /*White message at the bottom of the game window"*/
MESSAGE_INFO_DESCR = 22 /*Green message in game window and in the console*/
MESSAGE_DAMAGE_DEALT = 23
MESSAGE_DAMAGE_RECEIVED = 24
MESSAGE_HEALED = 25
MESSAGE_EXPERIENCE = 26
MESSAGE_DAMAGE_OTHERS = 27
MESSAGE_HEALED_OTHERS = 28
MESSAGE_EXPERIENCE_OTHERS = 29
MESSAGE_EVENT_DEFAULT = 30 /*White message at the bottom of the game window and in the console*/
MESSAGE_LOOT = 31

MESSAGE_GUILD = 33 /*White message in channel (+ channelId)*/
MESSAGE_PARTY_MANAGEMENT = 34 /*White message in channel (+ channelId)*/
MESSAGE_PARTY = 35 /*White message in channel (+ channelId)*/
MESSAGE_EVENT_ORANGE = 36 /*Orange message in the console*/
MESSAGE_STATUS_CONSOLE_ORANGE = 37  /*Orange message in the console*/
```

# Skull

```lua
SKULL_NONE = 0
SKULL_YELLOW = 1
SKULL_GREEN = 2
SKULL_WHITE = 3
SKULL_RED = 4
SKULL_BLACK = 5
SKULL_ORANGE = 6
```

# Item

```lua
ITEM_BROWSEFIELD = 460 // for internal use

ITEM_FIREFIELD_PVP_FULL = 1487
ITEM_FIREFIELD_PVP_MEDIUM = 1488
ITEM_FIREFIELD_PVP_SMALL = 1489
ITEM_FIREFIELD_PERSISTENT_FULL = 1492
ITEM_FIREFIELD_PERSISTENT_MEDIUM = 1493
ITEM_FIREFIELD_PERSISTENT_SMALL = 1494
ITEM_FIREFIELD_NOPVP = 1500

ITEM_POISONFIELD_PVP = 1490
ITEM_POISONFIELD_PERSISTENT = 1496
ITEM_POISONFIELD_NOPVP = 1503

ITEM_ENERGYFIELD_PVP = 1491
ITEM_ENERGYFIELD_PERSISTENT = 1495
ITEM_ENERGYFIELD_NOPVP = 1504

ITEM_MAGICWALL = 1497
ITEM_MAGICWALL_PERSISTENT = 1498
ITEM_MAGICWALL_SAFE = 11098

ITEM_WILDGROWTH = 1499
ITEM_WILDGROWTH_PERSISTENT = 2721
ITEM_WILDGROWTH_SAFE = 11099

ITEM_BAG = 1987

ITEM_GOLD_COIN = 2148
ITEM_PLATINUM_COIN = 2152
ITEM_CRYSTAL_COIN = 2160

ITEM_DEPOT = 2594
ITEM_LOCKER1 = 2589
ITEM_INBOX = 14404
ITEM_MARKET = 14405

ITEM_MALE_CORPSE = 3058
ITEM_FEMALE_CORPSE = 3065

ITEM_DITTO_CORPSE = 2813

ITEM_FULLSPLASH = 2016
ITEM_SMALLSPLASH = 2019

ITEM_PARCEL = 2595
ITEM_LETTER = 2597
ITEM_LETTER_STAMPED = 2598
ITEM_LABEL = 2599

ITEM_AMULETOFLOSS = 2173

ITEM_DOCUMENT_RO = 1968 //read-only
```