# Astral Markdown compendium

## Common use Snippets

### Critical Hit
|  |  |
|--|--|
| **_Melee_ Crit** | !!?(1d[X,X,X,X,X,Disarmed,Shove,Cleave,Death-Strike,Dirt-Throw]) |
| **_Ranged_ Crit** | !!?(1d[X,X,X,X,X,Knee-Shot,Crippling Hit,Ricochet,Headshot,Eye-Shot]) |
| **_SpellAtk_ Crit** | !!?(1d[X,X,X,X,X,Dazed,Aftershock,Blast,Sweet Spot,Arcane Flash]) |

### Fumble
|  |  |
|--|--|
| **_Melee_ Funble** | !!?(1d[Re-directed,Flying Dirt,Open Wide,Pushed,Disarmed,X,X,X,X,X]) |
| **_Ranged_ Fumble** | !!?(1d[Wild Shot,Alerted,Distracted,Jammed,Recoil,X,X,X,X,X]) |
| **_SpellAtk_ Fumble** | !!?(1d[Bad Aim,Arcane Flash,Miscast,Drained,Dizzy,X,X,X,X,X]) |



## Spells
Click to run actions for Astral Tabletop

### Cantrips
Below are the cantrips...

#### Acid Splash
*Conjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You hurl a bubble of acid. Choose one creature you can see within range, or choose two creatures you can see within range that are within {"5 feet"} of each other.

| # | damage | crit |
|--|--|--|
| **Save** | *Dexterity* | DC {ssDC} |
| On Hit | !({CantripDmgDice}d6) *Acid* | !!({CantripDmgDice}d6) |


#### Blade Ward
*Abjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** 1 round
---
You extend your hand and trace a sigil of warding in the air. Until the end of your next turn, you have resistance against bludgeoning, piercing, and slashing damage dealt by weapon attacks.


#### Booming Blade
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self (5-foot radius)
- **Components:** S, M *(a melee weapon worth at least 1 sp)*
- **Duration:** 1 round
---
You brandish the weapon used in the spell's casting and make a melee attack with it against one creature within {"5 feet"} of you. On a hit, the target suffers the weapon attack's normal effects and then becomes sheathed in booming energy until the start of your next turn. 

|||
|--|--|
| Weapon Attack | {"WpnAtk"} |
| | |
| Weapon Damage | {"WpnDmg"} {"WpnDmgType"} |
| Duration | Until your next turn |
| Trigger | target willingly moves {"5 feet"} or more |
| Effect | target takes !!({CantripDmgDice}d8) *thunder* damage |


#### Chill Touch
*Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** 1{"20 feet"}
- **Components:** V, S
- **Duration:** 1 round
---
You create a ghostly, skeletal hand in the space of a creature within range. Make a ranged spell attack against the creature to assail it with the chill of the grave. On a hit, the target takes X necrotic damage, and it can't regain hit points until the start of your next turn. Until then, the hand clings to the target.

| # | damage | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | vs {"AC"} |
| Avd/Dis | !!(1d20 + {prof} + {CastStatMod}) | vs {"AC"} |
|  |  |  |
| on Hit | !({CantripDmgDice}d8) *necrotic* | Add !!({CantripDmgDice}d8) damage |
| Effect | Target can't regain HP | until your next turn |
If you hit an undead target, it also has disadvantage on attack rolls against you until the end of your next turn.


#### Control Flames
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** S
- **Duration:** Instantaneous or 1 hour (see below)
---
You choose nonmagical flame that you can see within range and that fits within a {"5-foot"} cube. You affect it in one of the following ways:

- You instantaneously expand the flame {"5 feet"} in one direction, provided that wood or other fuel is present in the new location.
- You instantaneously extinguish the flames within the cube.
- You double or halve the area of bright light and dim light cast by the flame, change its color, or both. The change lasts for {"1 hour"}.
- You cause simple shapes—such as the vague form of a creature, an inanimate object, or a location—to appear within the flames and animate as you like. The shapes last for {"1 hour"}.

If you cast this spell multiple times, you can have up to three non-instantaneous effects created by it active at a time, and you can dismiss such an effect as an action.


#### Create Bonfire
*Conjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
You create a bonfire on ground that you can see within range. Until the spell ends, the magic bonfire fills a {"5-foot"} cube. Any creature in the bonfire's space when you cast the spell must succeed on a *Dexterity* saving throw or take **X** fire damage. A creature must also make the saving throw when it moves into the bonfire's space for the first time on a turn or ends its turn there.

|  |  |
|--|--|
| **Save** | *Dexterity* DC {ssDC} |
|  |  |
| on Hit | !({CantripDmgDice}d6) *fire* | 
The bonfire ignites flammable objects in its area that aren't being worn or carried.


#### Dancing Lights
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 1{"20 feet"}
- **Components:** V, S, M *(a bit of phosphorus or wychwood, or a glowworm)*
- **Duration:** Concentration, up to 1 minute
---
You create up to four torch-sized lights within range, making them appear as torches, lanterns, or glowing orbs that hover in the air for the duration. You can also combine the four lights into one glowing vaguely humanoid form of Medium size. Whichever form you choose, each light sheds dim light in a {"10-foot"} radius.

As a bonus action on your turn, you can move the lights up to 60 feet to a new spot within range. A light must be within {"20 feet"} of another light created by this spell, and a light winks out if it exceeds the spell's range.


#### Druidcraft
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
Whispering to the spirits of nature, you create one of the following effects within range:

- You create a tiny, harmless sensory effect that predicts what the weather will be at your location for the next 24 hours. The effect might manifest as a golden orb for clear skies, a cloud for rain, falling snowflakes for snow, and so on. This effect persists for {"1 round"}.
- You instantly make a flower blossom, a seed pod open, or a leaf bud bloom.
- You create an instantaneous, harmless sensory effect, such as falling leaves, a puff of wind, the sound of a small animal, or the faint odor of skunk. The effect must fit in a {"5-foot cube"}.
- You instantly light or snuff out a candle, a torch, or a small campfire.


#### Eldritch Blast
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 1{"20 feet"}
- **Components:** V, S
- **Duration:** Instantaneous
---
A beam of crackling energy streaks toward a creature within range. Add more beams at levels {"5"}, {"11"} and {"17"}.

| Beam # | Attack | Adv/Dis | Damage |
|--|--|--|--|
| 1 | !(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) | !(1d10) *force* |
| 2 | !!(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) | !!(1d10) *force* |
| 3 | !!(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) | !!(1d10) *force* |
| 4 | !!(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) | !!(1d10) *force* |


#### Encode Thoughts
*Enchantment cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** S
- **Duration:** 8 hours
---
Putting a finger to your head, you pull a memory, an idea, or a message from your mind and transform it into a tangible string of glowing energy called a thought strand, which persists for the duration or until you cast this spell again. The thought strand appears in an unoccupied space within {"5 feet"} of you as a Tiny, weightless, semisolid object that can be held and carried like a ribbon. It is otherwise stationary.

If you cast this spell while concentrating on a spell or an ability that allows you to read or manipulate the thoughts of others (such as *detect thoughts* or *modify memory*), you can transform the thoughts or memories you read, rather than your own, into a thought strand.

Casting this spell while holding a thought strand allows you to instantly receive whatever memory, idea, or message the thought strand contains. (Casting *detect thoughts* on the strand has the same effect.)


#### Fire Bolt
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 1{"20 feet"}
- **Components:** V, S
- **Duration:** Instantaneous
---
You hurl a mote of fire at a creature or object within range.

| # | damage | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) (Adv/Dis) |
|  |  |  |
| on Hit | !({CantripDmgDice}d10) *fire* | Add !!({CantripDmgDice}d10) damage |
A flammable object hit by this spell ignites if it isn't being worn or carried.



#### Friends
*Enchantment cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** S, M *(a small amount of makeup applied to the face as this spell is cast)*
- **Duration:** Concentration, up to 1 minute
---
For the duration, you have advantage on all *Charisma* checks directed at one creature of your choice that isn't hostile toward you. When the spell ends, the creature realizes that you used magic to influence its mood and becomes hostile toward you. A creature prone to violence might attack you. Another creature might seek retribution in other ways (at the DM's discretion), depending on the nature of your interaction with it.


#### Frostbite
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous, 1 turn
---
You cause numbing frost to form on one creature that you can see within range. 

|  |  |
|--|--|
| **Save** | *Constitution* DC {ssDC} |
| on Hit | !({CantripDmgDice}d6) *cold* | 
| Effect | disadvantage on next weapon attack|
| Duration | Until your next turn |


#### Green-Flame Blade
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self (5-foot radius)
- **Components:** S, M *(a melee weapon worth at least 1 sp)*
- **Duration:** Instantaneous
---
You brandish the weapon used in the spell's casting and make a melee attack with it against one creature within {"5 feet"} of you. On a hit, the target suffers the weapon attack's normal effects, and you can cause green fire to leap from the target to a different creature of your choice that you can see within {"5 feet"} of it.

|  |  |
|--|--|
| **Action** | make a Melee Weapon Attack |
| on Hit | add !(({CantripDmgDice}-1)d8) *fire* | 
| 2nd enemy | {CastStatMod} *fire* damage |


#### Guidance
*Divination cantrip*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
You touch one willing creature. Once before the spell ends, the target can roll a d4 and add the number rolled to one ability check of its choice. It can roll the die before or after making the ability check. The spell then ends.


#### Gust
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** Instantaneous
- **Save** *Strength* DC {ssDC}
---
You seize the air and compel it to create one of the following effects at a point you can see within range:

- One Medium or smaller creature that you choose must succeed on a *Strength* saving throw or be pushed up to {"5 feet"} away from you.
- You create a small blast of air capable of moving one object that is neither held nor carried and that weighs no more than {"5 pounds"}. The object is pushed up to {"10 feet"} away from you. It isn't pushed with enough force to cause damage.
- You create a harmless sensory effect using air, such as causing leaves to rustle, wind to slam shutters closed, or your clothing to ripple in a breeze.


#### Hand of Radiance
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self (5-foot radius)
- **Components:** V, S
- **Duration:** Instantaneous
- **Save** *Constitution* DC {ssDC}
---
You raise your hand, and burning radiance erupts from it. Each creature of your choice that you can see within {"5 feet"} of you:

|  |  |
|--|--|
| **Save** | *Constitution* DC {ssDC} |
|  |  |
| on Hit | !({CantripDmgDice}d6) *radiant* | 


#### Infestation
*Conjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a living flea)*
- **Duration:** Instantaneous
- **Save** *Constitution* DC {ssDC}
---
You cause a cloud of mites, fleas, and other parasites to appear momentarily on one creature you can see within range. 

|  |  |  |
|--|--|--|
| Damage | !({CantripDmgDice}d6) *poison* | and effect: |
| Effect: | Move {"5 foot"} to the | !(1d[north,northeast,east,southeast,south,southwest,west,northwest]) |
This movement doesn't provoke opportunity attacks, and if the direction rolled is blocked, the target doesn't move.


#### Light
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, M *(a firefly or phosphorescent moss)*
- **Duration:** 1 hour
- **Save** *Dexterity,* DC {ssDC}
---
You touch one object that is no larger than {"10 feet"} in any dimension. Until the spell ends, the object sheds bright light in a {"20-foot"} radius and dim light for an additional {"20 feet"}. The light can be colored as you like. Completely covering the object with something opaque blocks the light. The spell ends if you cast it again or dismiss it as an action.

If you target an object held or worn by a hostile creature, that creature must succeed on a Dexterity saving throw to avoid the spell.


#### Lightning Lure
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self (15-foot radius)
- **Components:** V
- **Duration:** Instantaneous
- **Save** *Strength,* DC {ssDC}
---
You create a lash of lightning energy that strikes at one creature of your choice that you can see within {"15 feet"} of you. 
The target must succeed on a *Strength* saving throw or be pulled up to {"10 feet"} in a straight line toward you and then take !({CantripDmgDice}d8) lightning damage if it is within {"5 feet"} of you.


#### Mage Hand
*Conjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** 1 minute
---
A spectral, floating hand appears at a point you choose within range. The hand lasts for the duration or until you dismiss it as an action. The hand vanishes if it is ever more than {"30 feet"} away from you or if you cast this spell again.

You can use your action to control the hand. You can use the hand to manipulate an object, open an unlocked door or container, stow or retrieve an item from an open container, or pour the contents out of a vial. You can move the hand up to {"30 feet"} each time you use it.

The hand can't attack, activate magic items, or carry more than {"10 pounds"}.


#### Magic Stone
*Transmutation cantrip*
___
- **Casting Time:** 1 bonus action
- **Range:** Touch
- **Components:** V, S
- **Duration:** 1 minute
---
You touch one to three pebbles and imbue them with magic. You or someone else can make a ranged spell attack with one of the pebbles by throwing it or hurling it with a *sling*. If thrown, a pebble has a range of {"60 feet"}.
If someone else attacks with a pebble, that attacker adds your spellcasting ability modifier, not the attacker's, to the attack roll.
On a hit, the target takes *bludgeoning* damage equal to **1d6** + {CastStatMod} . Whether the attack hits or misses, the spell then ends on the stone.

If you cast this spell again, the spell ends on any pebbles still affected by your previous casting.


#### Mending
*Transmutation cantrip*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** V, S, M *(two lodestones)*
- **Duration:** Instantaneous
---
This spell repairs a single break or tear in an object you touch, such as broken chain link, two halves of a broken key, a torn cloak, or a leaking wineskin. As long as the break or tear is no larger than 1 foot in any dimension, you mend it, leaving no trace of the former damage.

This spell can physically repair a magic item or construct, but the spell can't restore magic to such an object.


#### Message
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 1{"20 feet"}
- **Components:** V, S, M *(a short piece of copper wire)*
- **Duration:** 1 round
---
{name} points at a creature within {"120 feet"} and whispers a message. Only the target hears the message and can reply in a whisper that only {name} can hear. 
{name} can cast this spell through solid objects, if {name} knows the target, it is beyond the barrier. Magical silence, {"1 foot"} of stone, {"1 inch"} of common metal, a thin sheet of lead, or {"3 feet"} of wood blocks the spell. The spell can travel freely around corners or through openings.


#### Mind Sliver
*Enchantment cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** 1 round
---
You drive a disorienting spike of psychic energy into the mind of one creature you can see within range. 

|  |  |
|--|--|
| **Save** | *Intelligence* DC {ssDC} |
| on Hit | !({CantripDmgDice}d6) *psychic* | 
| Effect | subtract !(1d4) from the next saving throw |


#### Minor Illusion
*Illusion cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** S, M *(a bit of fleece)*
- **Duration:** 1 minute
- **Check:** *Intelligence* DC {ssDC}
---
You create a sound or an image of an object within range that lasts for the duration. The illusion also ends if you dismiss it as an action or cast this spell again.

If you create a sound, its volume can range from a whisper to a scream. It can be your voice, someone else's voice, a lion's roar, a beating of drums, or any other sound you choose. The sound continues unabated throughout the duration, or you can make discrete sounds at different times before the spell ends.

If you create an image of an object—such as a chair, muddy footprints, or a small chest—it must be no larger than a 5-foot cube. The image can't create sound, light, smell, or any other sensory effect. Physical interaction with the image reveals it to be an illusion, because things can pass through it.

If a creature uses its action to examine the sound or image, the creature can determine that it is an illusion with a successful *Intelligence (Investigation)* check against your spell save DC. If a creature discerns the illusion for what it is, the illusion becomes faint to the creature.


#### Mold Earth
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** S
- **Duration:** Instantaneous or 1 hour (see below)
---
You choose a portion of dirt or stone that you can see within range and that fits within a {"5-foot cube"}. You manipulate it in one of the following ways:

- If you target an area of loose earth, you can instantaneously excavate it, move it along the ground, and deposit it up to {"5 feet"} away. This movement doesn't involve enough force to cause damage.
- You cause shapes, colors, or both to appear on the dirt or stone, spelling out words, creating images, or shaping patterns. The changes last for {"1 hour"}.
- If the dirt or stone you target is on the ground, you cause it to become difficult terrain. Alternatively, you can cause the ground to become normal terrain if it is already difficult terrain. This change lasts for {"1 hour"}.

If you cast this spell multiple times, you can have no more than two of its non-instantaneous effects active at a time, and you can dismiss such an effect as an action.


#### On/Off (UA)
*Transmutation cantrip (technomagic)*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
This cantrip allows you to activate or deactivate any electronic device within range, as long as the device has a clearly defined on or off function that can be easily accessed from the outside of the device. Any device that requires a software-based shutdown sequence to activate or deactivate cannot be affected by {"on/off"}.


#### Poison Spray
*Conjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** {"10 feet"}
- **Components:** V, S
- **Duration:** Instantaneous
---
You extend your hand toward a creature you can see within range and project a puff of noxious gas from your palm.

|  |  |
|--|--|
| **Save** | *Constitution* DC {ssDC} |
| on Hit | !({CantripDmgDice}d12) *poison* | 


#### Prestidigitation
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** {"10 feet"}
- **Components:** V, S
- **Duration:** Up to 1 hour
---
This spell is a minor magical trick that novice spellcasters use for practice. You create one of the following magical effects within range:

- You create an instantaneous, harmless sensory effect, such as a shower of sparks, a puff of wind, faint musical notes, or an odd odor.
- You instantaneously light or snuff out a candle, a torch, or a small campfire.
- You instantaneously clean or soil an object no larger than {"1 cubic foot"}.
- You chill, warm, or flavor up to 1 cubic foot of nonliving material for {"1 hour"}.
- You make a color, a small mark, or a symbol appear on an object or a surface for {"1 hour"}.
- You create a nonmagical trinket or an illusory image that can fit in your hand and that lasts until the end of your next turn.
---
If you cast this spell multiple times, you can have up to three of its non-instantaneous effects active at a time, and you can dismiss such an effect as an action.


#### Primal Savagery
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** S
- **Duration:** Instantaneous
---
You channel primal magic to cause your teeth or fingernails to sharpen, ready to deliver a corrosive attack. Make a melee spell attack against one creature within {"5 feet"} of you.
After you make the attack, your teeth or fingernails return to normal.

| # | damage | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) (Adv/Dis) |
| on Hit | !({CantripDmgDice}d10) *acid* | Add !!({CantripDmgDice}d10) damage |


#### Produce Flame
*Conjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** 10 minutes
---
A flickering flame appears in your hand. The flame remains there for the duration and harms neither you nor your equipment. The flame sheds bright light in a {"10-foot radius"} and dim light for an additional {"10 feet"}. The spell ends if you dismiss it as an action or if you cast it again.

You can also attack with the flame, although doing so ends the spell. When you cast this spell, or as an action on a later turn, you can hurl the flame at a creature within {"30 feet"} of you. Make a ranged spell attack. 

| # | damage | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) (Adv/Dis) |
| on Hit | !({CantripDmgDice}d8) *fire* | Add !!({CantripDmgDice}d8) damage |


#### Ray of Frost
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
A frigid beam of blue-white light streaks toward a creature within range. 

| # | damage | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) (Adv/Dis) |
| on Hit | !({CantripDmgDice}d8) *cold* | Add !!({CantripDmgDice}d8) damage |
| Effect | speed reduced by {"10 feet"} | for 1 turn |


#### Resistance
*Abjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M *(a miniature cloak)*
- **Duration:** Concentration, up to 1 minute

---
You touch one willing creature. Once before the spell ends, the target can roll a {"d4"} and add the number rolled to one saving throw of its choice. It can roll the die before or after making the saving throw. The spell then ends.


#### Sacred Flame
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
Flame-like radiance descends on a creature that you can see within range. The target gains no benefit from cover for this Dex saving throw.

|  |  |
|--|--|
| **Save** | *Dexterity* DC {ssDC} |
| on Hit | !({CantripDmgDice}d8) *radiant* | 



#### Sapping Sting
*Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You sap the vitality of one creature you can see in range. The target must succeed on a Constitution saving throw or take nd4 necrotic damage and fall prone.

|  |  |
|--|--|
| **Save** | *Dexterity* DC {ssDC} |
| on Hit | !({CantripDmgDice}d4) *necrotic* | 
| Effect | fall prone (on failed safe) |


#### Shape Water
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** S
- **Duration:** Instantaneous or 1 hour (see below)
---
You choose an area of water that you can see within range and that fits within a {"5-foot cube"}. You manipulate it in one of the following ways:

- You instantaneously move or otherwise change the flow of the water as you direct, up to {"5 feet"} in any direction. This movement doesn't have enough force to cause damage.
- You cause the water to form into simple shapes and animate at your direction. This change lasts for {"1 hour"}.
- You change the water's color or opacity. The water must be changed in the same way throughout. This change lasts for {"1 hour"}.
- You freeze the water, provided that there are no creatures in it. The water unfreezes in {"1 hour"}.

If you cast this spell multiple times, you can have no more than two of its non-instantaneous effects active at a time, and you can dismiss such an effect as an action.


#### Shillelagh
*Transmutation cantrip*
___
- **Casting Time:** 1 bonus action
- **Range:** Touch
- **Components:** V, S, M *(mistletoe, a shamrock leaf, and a club or quarterstaff)*
- **Duration:** 1 minute
---
The wood of a *club* or *quarterstaff* you are holding is imbued with nature's power. For the duration, you can use your *spellcasting ability* instead of *Strength* for the attack and damage rolls of melee attacks using that weapon, and the weapon's damage die becomes a {"d8"}. The weapon also becomes magical, if it isn't already. The spell ends if you cast it again or if you let go of the weapon.


#### Shocking Grasp
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Instantaneous
---
Lightning springs from your hand to deliver a shock to a creature you try to touch. You have advantage on the attack roll if the target is wearing armor made of metal. 

| # | damage | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) (Adv/Dis) |
| on Hit | !({CantripDmgDice}d8) *lightning* | Add !!({CantripDmgDice}d8) damage |
| Effect | it can't take reactions | start of its next turn. |


#### Spare the Dying
*Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Instantaneous
---
You touch a living creature that has {"0"} hit points. The creature becomes stable. This spell has no effect on undead or constructs.


#### Sword Burst
*Conjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** Self (5-foot radius)
- **Components:** V
- **Duration:** Instantaneous
- **Save** *Dexterity* DC {ssDC}
---
You create a momentary circle of spectral blades that sweep around you. All other creatures within {"5 feet"} of you must succeed on a Dexterity saving throw or take !({CantripDmgDice}d6) *force* damage.



#### Thaumaturgy
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V
- **Duration:** Up to 1 minute
---
You manifest a minor wonder, a sign of supernatural power, within range. You create one of the following magical effects within range:

- Your voice booms up to three times as loud as normal for {"1 minute"}.
- You cause flames to flicker, brighten, dim, or change color for {"1 minute"}.
- You cause harmless tremors in the ground for {"1 minute"}.
- You create an instantaneous sound that originates from a point of your choice within range, such as a rumble of thunder, the cry of a raven, or ominous whispers.
- You instantaneously cause an unlocked door or window to fly open or slam shut.
- You alter the appearance of your eyes for {"1 minute"}.

If you cast this spell multiple times, you can have up to three of its 1-minute effects active at a time, and you can dismiss such an effect as an action.


#### Thorn Whip
*Transmutation cantrip*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(the stem of a plant with thorns)*
- **Duration:** Instantaneous
---
You create a long, vine-like whip covered in thorns that lashes out at your command toward a creature in range. 

| # | damage | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | !!(1d20 + {prof} + {CastStatMod}) (Adv/Dis) |
| on Hit | !({CantripDmgDice}d6) *piercing* | Add !!({CantripDmgDice}d6) damage |
| Effect | if creature =< {"Large"} | pull {"10 feet"} |


#### Thunderclap
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** {"5 feet"}
- **Components:** S
- **Duration:** Instantaneous
---
You create a burst of thunderous sound that can be heard up to 100 feet away. 

|  |  |
|--|--|
| *Targets* | All creatures within {"5 feet"} |
| **Save** | *Constitution* DC {ssDC} |
| on Hit | !({CantripDmgDice}d6) *thunder* damage | 


#### Toll the Dead
*Necromancy cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You point at one creature you can see within range, and the sound of a dolorous bell fills the air around it for a moment. 

|  |  |
|--|--|
| **Save** | *Wisdom* DC {ssDC} |
| on Hit | !({CantripDmgDice}d8) *necrotic* | 
| if Damaged | !({CantripDmgDice}d12) *necrotic* | 


#### Vicious Mockery
*Enchantment cantrip*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** Instantaneous
- **Save** *Wisdom* DC {ssDC}
---
You unleash a string of insults laced with subtle enchantments at a creature you can see within range. If the target can hear you (though it need not understand you):

|  |  |
|--|--|
| **Save** | *Wisdom* DC {ssDC} |
| on Hit | !({CantripDmgDice}d4) *psychic* | 
| Effect | disadvantage on next atk roll|
| Duration | Until end of it's next turn |



#### Virtue (UA)
*Abjuration cantrip*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** 1 round
---
You touch one creature, imbuing it with vitality. If the target has at least 1 hit point, it gains a number of temporary hit points equal to 1d4 + your spellcasting ability modifier. The temporary hit points are lost when the spell ends.

|  |  |
|--|--|
| Effect | !(1d4) + {CastStatMod} temporary HP |
| Duration | until spell ends ({"1 round"}) |



#### Word of Radiance
*Evocation cantrip*
___
- **Casting Time:** 1 action
- **Range:** {"5 feet"}
- **Components:** V, M *(a holy symbol)*
- **Duration:** Instantaneous
- **Save** *Constitution* DC {ssDC}
---
You utter a divine word, and burning radiance erupts from you. Each creature of your choice that you can see within range:
 must succeed on a Constitution saving throw or take !({CantripDmgDice}d6) radiant damage.

|  |  |
|--|--|
| **Save** | *Constitution* DC {ssDC} |
| on Hit | !({CantripDmgDice}d6) *radiant* | 




### 1st level Spells
Here there be spells...

#### Absorb Elements
*1st-level abjuration*
___
- **Casting Time:** 1 reaction,
which you take when you take acid or elemental damage
- **Range:** Self
- **Components:** S
- **Duration:** 1 round
---
The spell captures some of the incoming energy, lessening its effect on you and storing it for your next melee attack. You have resistance to the triggering damage type until the start of your next turn. Also, the first time you hit with a melee attack on your next turn, the target takes an extra {"1d6"} damage of the triggering type, and the spell ends.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the extra damage increases by {"1d6"} for each slot level above 1st.


#### Acid Stream
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (30-foot line)
- **Components:** V, S, M *(a bit of rotten food)*
- **Duration:** _Concentration_, up to 1 minute
---
A stream of acid emanates from you in a line {"30 feet long"} and {"5 feet wide"} in a direction you choose. Each creature in the line must succeed on a _Dexterity_ saving throw or be covered in *acid* for the spell's duration or until a creature uses its action to scrape or wash the acid off itself or another creature. A creature covered in the acid takes !(3d4) acid damage at start of each of its turns.

| lvl | damage | at |
|--|--|--|
| **Save** | **Dexterity**) | DC {ssDC} |
|  |  |  |
| cast (1) | !!(3d6) | start of turn | 
| upcast (2): | !!(6d6) | start of turn |
for higher levels, use: {"((SpellLevel*3)d6)"}


#### Alarm
*1st-level abjuration (ritual)*
___
- **Casting Time:** 1 minute
- **Range:** 30 feet
- **Components:** V, S, M *(a tiny bell and a piece of fine silver wire)*
- **Duration:** 8 hours
---
You set an alarm against unwanted intrusion. Choose a door, a window, or an area within range that is no larger than a {"20-foot cube"}. Until the spell ends, an alarm alerts you whenever a Tiny or larger creature touches or enters the warded area. When you cast the spell, you can designate creatures that won't set off the alarm. You also choose whether the alarm is mental or audible.

A mental alarm alerts you with a ping in your mind if you are within {"1 mile"} of the warded area. This ping awakens you if you are sleeping.

An audible alarm produces the sound of a hand bell for {"10 seconds"} within {"60 feet"}


#### Animal Friendship
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a morsel of food)*
- **Duration:** 24 hours
- **Save:** _Wisdom_ DC {ssDC}
---
This spell lets you convince a beast that you mean it no harm. Choose a beast that you can see within range. It must see and hear you. If the beast's *Intelligence* is {"4"} or higher, the spell fails. Otherwise, the beast must succeed on a *Wisdom* saving throw or be charmed by you for the spell's duration. If you or one of your companions harms the target, the spell ends.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you can affect one additional beast for each slot level above 1st.


#### Arcane Weapon
*1st-level transmutation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 1 hour
---
You channel arcane energy into one simple or martial weapon you're holding, and choose one damage type: *acid, cold, fire, lightning, poison*, or *thunder*. Until the spell ends, you deal an extra {"1d6"} damage of the chosen type to any target you hit with the weapon. If the weapon isn't magical, it becomes a magic weapon for the spell's duration.

As a bonus action, you can change the damage type, choosing from the options above.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can maintain your concentration on the spell for up to 8 hours.


#### Armor of Agathys
*1st-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M *(a cup of water)*
- **Duration:** 1 hour
---
A protective magical force surrounds you, manifesting as a spectral frost that covers you and your gear. You gain {"5 temporary hit points"} for the duration. If a creature hits you with a melee attack while you have these hit points, the creature takes {"5"} *cold* damage.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, both the temporary hit points and the cold damage increase by 5 for each slot level above 1st.


#### Arms of Hadar
*1st-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** Self (10-foot radius)
- **Components:** V, S
- **Duration:** Instantaneous
---
You invoke the power of Hadar, the Dark Hunger. Tendrils of dark energy erupt from you and batter all creatures within {"10 feet"} of you. 

| lvl | damage | at |
|--|--|--|
| **Save** | *Strength* DC {ssDC} |
|  |  |
| cast (1) | !!(2d6) *necrotic* | 
| upcast (2): | !!(4d6) *necrotic* |
| Effect | Can't take reactions |
| Duraction | until it's next turn |
| On Miss | half damage & NO effect |
for higher levels, use: {"((SpellLevel*2)d6)"}


#### Bane
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a drop of blood)*
- **Duration:** Concentration, up to 1 minute
---
Up to three creatures of your choice that you can see within range must make Charisma saving throws. Whenever a target that fails this saving throw makes an attack roll or a saving throw before the spell ends, the target must roll a {"d4"} and subtract the number rolled from the attack roll or saving throw.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature for each slot level above 1st.




#### Beast Bond
*1st-level divination*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M *(a bit of fur wrapped in a cloth)*
- **Duration:** Concentration, up to 10 minutes
---
You establish a telepathic link with one beast you touch that is friendly to you or charmed by you. The spell fails if the beast's Intelligence score is 4 or higher. Until the spell ends, the link is active while you and the beast are within line of sight of each other. Through the link, the beast can understand your telepathic messages to it, and it can telepathically communicate simple emotions and concepts back to you. While the link is active, the beast gains advantage on attack rolls against any creature within 5 feet of you that you can see.


#### Bless
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a sprinkling of holy water)*
- **Duration:** Concentration, up to 1 minute
---
{name} blesses up to {"3"} creatures within range.
Those creatures add {"1d4"} to all attack rolls and saving throws until the spell ends.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature for each slot level above 1st.


#### Burning Hands
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (15-foot cone)
- **Components:** V, S
- **Duration:** Instantaneous
---
As you hold your hands with thumbs touching and fingers spread, a thin sheet of flames shoots forth from your outstretched fingertips. Each creature in a {"15-foot cone"} must make a *Dexterity* saving throw. 

| lvl | damage |
|--|--|
| **Save** | *Dexterity* DC {ssDC} |
|  |  |  |
| cast (1) | !!(3d6) | 
| upcast (2): | !!(6d6) |
| On Miss | half damage |
for higher levels, use: {"((SpellLevel*3)d6)"}
The fire ignites any flammable objects in the area that aren't being worn or carried.


#### Catapult
*1st-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** S
- **Duration:** Instantaneous
---
Choose one object weighing {"1 to 5 pounds"} within range that isn't being worn or carried. The object flies in a straight line up to {"90 feet"} in a direction you choose before falling to the ground, stopping early if it impacts against a solid surface. If the object would strike a creature, that creature must make a Dexterity saving throw. On a failed save, the object strikes the target and stops moving. When the object strikes something, the object and what it strikes each take !(3d8) *bludgeoning* damage.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the maximum weight of objects that you can target with this spell increases by 5 pounds, and the damage increases by 3d8, for each slot level above 1st.


#### Cause Fear
*1st-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
You awaken the sense of mortality in one creature you can see within range. A construct or an undead is immune to this effect. The target must succeed on a *Wisdom* saving throw or become [frightened](https://5e.tools/conditionsdiseases.html#frightened_phb) of you until the spell ends. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature for each slot level above 1st. The creatures must be within {"30 feet"} of each other when you target them.


#### Cause Fear (UA)
*1st-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
You awaken the sense of mortality in one creature you can see within range. The target must succeed on a *Wisdom* saving throw or become [frightened](https://5e.tools/conditionsdiseases.html#frightened_phb) for the duration. A target with {"25 hit"} points or fewer makes the saving throw with disadvantage. The spell has no effect on constructs or undead.


#### Ceremony
*1st-level abjuration (ritual)*
___
- **Casting Time:** 1 hour
- **Range:** Touch
- **Components:** V, S, M *(25 gp worth of powdered silver, which the spell consumes)*
- **Duration:** Instantaneous
---
You perform a special religious ceremony that is infused with magic. When you cast the spell, choose one of the following rites, the target of which must be within {"10 feet"} of you throughout the casting.

***Atonement.*** You touch one willing creature whose alignment has changed, and you make a DC {"20"} *Wisdom* (Insight) check. On a successful check, you restore the target to its original alignment.

***Bless Water.*** You touch one *vial* of water and cause it to become *holy water*.

***Coming of Age.*** You touch one humanoid who is a young adult. For the next {"24 hours"}, whenever the target makes an ability check, it can roll {"1d4"} and add the number rolled to the ability check. A creature can benefit from this rite only once.

***Dedication.*** You touch one humanoid who wishes to be dedicated to your god's service. For the next {"24 hours"}, whenever the target makes a saving throw, it can roll {"1d4"} and add the number rolled to the save. A creature can benefit from this rite only once.

***Funeral Rite.*** You touch one corpse, and for the next {"7 days"}, the target can't become undead by any means short of a *wish* spell.

***Wedding.*** You touch adult humanoids willing to be bonded together in marriage. For the next {"7 days"}, each target gains a {"+2 bonus"} to {"AC"} while they are within {30 feet""} of each other. A creature can benefit from this rite again only if widowed.


#### Chaos Bolt
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You hurl an undulating, warbling mass of chaotic energy at one creature in range. 

|  |  |  |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) |  |
| Adv/Dis| !!(1d20 + {prof} + {CastStatMod}) |  |
| Damage | !(1d8), !(1d8) | + !(1d6) |
| Crit | !!(1d8), !!(1d8) | + !!(1d6) |
| Upcast | Per lvl | + !!(1d6) |

|  |  |  |  |  |  |  |  |  | 
|--|--|--|--|--|--|--|--|--|
| d8 roll | {"1"} | {"2"} | {"3"} | {"4"} | 
| DmgType | Acid | Cold | Fire | Force | 
| d8 roll | {"5"} | {"6"} | {"7"} | {"8"} |
| DmgType | Lightning | Poison | Psychic | Thunder |


If you roll the **same** number on both d8s, the chaotic energy leaps from the target to a different creature of your choice within {"30 feet"} of it. 
Make a new attack roll against the new target, and make a new damage roll, which could cause the chaotic energy to leap again.

A creature can be targeted only once by each casting of this spell.


#### Charm Person
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** 1 hour
---
You attempt to charm a humanoid you can see within range. It must make a Wisdom saving throw, and does so with advantage if you or your companions are fighting it. If it fails the saving throw, it is charmed by you until the spell ends or until you or your companions do anything harmful to it. The charmed creature regards you as a friendly acquaintance. When the spell ends, the creature knows it was charmed by you.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature for each slot level above 1st. The creatures must be within 30 feet of each other when you target them.


#### Chromatic Orb
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S, M *(a diamond worth at least 50 gp)*
- **Duration:** Instantaneous
---
You hurl a 4-inch-diameter sphere of energy at a creature that you can see within range. You choose *acid, cold, fire, lightning, poison*, or *thunder* for the type of orb you create.

| lvl | damage | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) vs {"AC"} | Avd/Dis: !!(1d20 + {prof} + {CastStatMod}) |
| cast (1) | !(3d8) | !!(3d8) | 
| upcast (2): | !!(6d8) | !!(6d8) |
for higher levels, use: {"((SpellLevel*3)d8)"}
Damage Type as declared on attack.


#### Color Spray
*1st-level illusion*
___
- **Casting Time:** 1 action
- **Range:** Self (15-foot cone)
- **Components:** V, S, M *(a pinch of powder or sand that is colored red, yellow, and blue)*
- **Duration:** 1 round
---
A dazzling array of flashing, colored light springs from {name}'s hand. !(6d10) hit points of creatures in a {"15-foot"} cone originating from {name} are affected in ascending order of their current hit points (ignoring unconscious creatures and creatures that can’t see).
Starting with the creature that has the lowest current hit points, each creature affected by this spell is blinded until the spell ends. Subtract each creature’s hit points from the total before moving on to the creature with the next lowest hit points. A creature’s hit points must be equal to or less than the remaining total for that creature to be affected.
Additional HP (of creatures) affected:

|  |  |
|--|--|
|Spell slot level 2: | add !!(6d10) |
|Spell slot level 3: | add !!(12d10) |
|Spell slot level 4: | add !!(18d10) |
|Spell slot level 5: | add !!(24d10) |


#### Command
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** 1 round
---
You speak a one-word command to a creature you can see within range. The target must succeed on a Wisdom saving throw or follow the command on its next turn. The spell has no effect if the target is undead, if it doesn't understand your language, or if your command is directly harmful to it.

Some typical commands and their effects follow. You might issue a command other than one described here. If you do so, the DM determines how the target behaves. If the target can't follow your command, the spell ends.

***Approach.*** The target moves toward you by the shortest and most direct route, ending its turn if it moves within {"5 feet"} of you.

***Drop.*** The target drops whatever it is holding and then ends its turn.

***Flee.*** The target spends its turn moving away from you by the fastest available means.

***Grovel.*** The target falls prone and then ends its turn.

***Halt.*** The target doesn't move and takes no actions. A flying creature stays aloft, provided that it is able to do so. If it must move to stay aloft, it flies the minimum distance needed to remain in the air.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you can affect one additional creature for each slot level above 1st. The creatures must be within 30 feet of each other when you target them.


#### Comprehend Languages
*1st-level divination (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M *(a pinch of soot and salt)*
- **Duration:** 1 hour
---
For the duration, you understand the literal meaning of any spoken language that you hear. You also understand any written language that you see, but you must be touching the surface on which the words are written. It takes about 1 minute to read one page of text.

This spell doesn't decode secret messages in a text or a glyph, such as an arcane sigil, that isn't part of a written language.


#### Create or Destroy Water
*1st-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a drop of water if creating water or a few grains of sand if destroying it)*
- **Duration:** Instantaneous
---
You either create or destroy water.

***Create Water.*** You create up to {"10 gallons"} of clean water within range in an open container. Alternatively, the water falls as rain in a {"30-foot cube"} within range, extinguishing exposed flames in the area.

***Destroy Water.*** You destroy up to {"10 gallons"} of water in an open container within range. Alternatively, you destroy fog in a {"30-foot cube"} within range.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you create or destroy an additional {"10 gallons"} of water, or the size of the cube increases by {"5 feet"}, for each slot level above 1st.


#### Cure Wounds
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Instantaneous
---
A creature {name} touches regains !(1d8 + {CastStatMod}) hit points. This spell has no effect on undead or constructs.
Additional healing:
Spell slot level 2: !!(1d8)
Spell slot level 3: !!(2d8)
Spell slot level 4: !!(3d8)
Spell slot level 5: !!(4d8)


#### Detect Evil and Good
*1st-level divination*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 10 minutes
---
For the duration, {name} knows if there is an aberration, celestial, elemental, fey, fiend, or undead within {"30 feet"} of themselves, as well as where the creature is located. Similarly, they know if there is a place or object within {"30 feet"} of themselves that has been magically consecrated or desecrated.

The spell can penetrate most barriers, but it is blocked by {"1 foot"} of stone, {"1 inch"} of common metal, a thin sheet of lead, or {"3 feet"} of wood or dirt.


#### Detect Magic
*1st-level divination (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 10 minutes
---
For the duration, {name} sense the presence of magic within {"30 feet"} of themselves. If they sense magic in this way, they can use their action to see a faint aura around any visible creature or object in the area that bears magic, and they learn its school of magic, if any.

The spell can penetrate most barriers, but it is blocked by {"1 foot"} of stone, {"1 inch"} of common metal, a thin sheet of lead, or {"3 feet"} of wood or dirt.


#### Detect Poison and Disease
*1st-level divination (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M *(a yew leaf)*
- **Duration:** Concentration, up to 10 minutes
---
For the duration, {name} can sense the presence and location of poisons, poisonous creatures, and diseases within {"30 feet"} of themselves. They also identify the kind of poison, poisonous creature, or disease in each case.

The spell can penetrate most barriers, but it is blocked by {"1 foot"} of stone, {"1 inch"} of common metal, a thin sheet of lead, or {"3 feet"} of wood or dirt.


#### Disguise Self
*1st-level illusion*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** 1 hour
---
{name} makes themself (clothing, armor, weapons, and other belongings on them) look different until the spell ends or until they use their action to dismiss it.
To discern that {name} is disguised, a creature can use its action to inspect their appearance and must succeed on a DC {ssDC } INT (Investigation) check.


#### Dissonant Whispers
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** Instantaneous
---
You whisper a discordant melody that only one creature of your choice within range can hear, wracking it with terrible pain. 

| lvl | damage |
|--|--|
| **Save** | *Wisdom* DC {ssDC} |
|  |  |  |
| cast (1) | !!(3d6) psychic |  
| upcast (2): | !!(6d6) psychic |
| Effect | must move away from {name} as reaction |
| On Miss | half damage, doesn't flee |
for higher levels, use: !{"((SpellLevel*n)d6)"}

The creature doesn't move into obviously dangerous ground, such as a fire or a pit. 
A deafened creature automatically succeeds on the save.


#### Distort Value
*1st-level illusion*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** V
- **Duration:** 8 hours
---
Do you need to squeeze a few more gold pieces out of a merchant as you try to sell that weird octopus statue you liberated from the chaos temple? Do you need to downplay the worth of some magical assets when the tax collector stops by? Distort value has you covered.

You cast this spell on an object no more than 1 foot on a side, doubling the object's perceived value by adding illusory flourishes or polish to it, or reducing its perceived value by half with the help of illusory scratches, dents, and other unsightly features. Anyone examining the object can ascertain its true value with a successful Intelligence (Investigation) check, DC {ssDC}.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the maximum size of the object increases by 1 foot for each slot level above 1st.


#### Divine Favor
*1st-level evocation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
Your prayer empowers you with divine radiance. Until the spell ends, your weapon attacks deal an extra {"1d4"} *radiant* damage on a hit.


#### Earth Tremor
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 10 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You cause a tremor in the ground within range. 

| lvl | damage | 
|--|--|
| **Save** | *Dexterity* DC {ssDC} |
|  |  |
| cast (1) | !!(1d6) *bludgeoning* | 
| Effect | damage + falls ***prone*** |
| On Miss | difficult terrain |
for higher levels, use: {"((SpellLevel)d6)"}

Each creature other than you in that area must make a Dexterity saving throw. On a failed save, a creature takes 1d6 bludgeoning damage and is knocked prone. If the ground in that area is loose earth or stone, it becomes difficult terrain until cleared, with each {"5-foot-diameter"} portion requiring at least {"1 minute"} to clear by hand.


#### Ensnaring Strike
*1st-level conjuration*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
The next time {name} hits a creature with a weapon attack before this spell ends, a writhing mass of thorny vines appears at the point of impact, restraining the target.

|  |  |  |
|--|--|--|
| **Save** | *Strength* | DC {ssDC} |
|  |  |  |
| Effect | restrained | until saved or spell ends |
| cast (1) | !!(1d6) | start of it's turn | 
| upcast (2): | !!(2d6) | start of it's turn |
for higher levels, use: {"((SpellLevel)d6)"}
_____
A creature restrained by the vines or one that can touch the creature can use its action to make a *Strength* check DC {ssDC} to free the target.. A Large or larger creature has advantage on this saving throw.


#### Entangle
*1st-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
Grasping weeds and vines sprout from the ground in a {"20-foot square"} starting from a point within range. For the duration, these plants turn the ground in the area into difficult terrain.
A creature in the area when you cast the spell must succeed on a Strength saving throw or be restrained by the entangling plants until the spell ends.

|  |  |  |
|--|--|--|
| **Save** | *Strength* | DC {ssDC} |
|  |  |  |
| Effect | restrained | until saved or spell ends |


#### Expeditious Retreat
*1st-level transmutation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 10 minutes
---
This spell allows you to move at an incredible pace. When you cast this spell, and then as a bonus action on each of your turns until the spell ends, you can take the Dash action.


#### Faerie Fire
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** Concentration, up to 1 minute
- **Save:** *Dexterity* DC {ssDC}
---
Each object in a {"20-foot cube"} within range is outlined in *blue, green*, or *violet* light (your choice). Any creature in the area when the spell is cast is also outlined in light if it fails a *Dexterity* saving throw. For the duration, objects and affected creatures shed dim light in a {"10-foot"} radius.

Any attack roll against an affected creature or object has advantage if the attacker can see it, and the affected creature or object can't benefit from being invisible.


#### False Life
*1st-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M *(a small amount of alcohol or distilled spirits)*
- **Duration:** 1 hour
---
Bolstering yourself with a necromantic facsimile of life, you gain !(1d4 + 4) temporary hit points for the duration.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you gain 5 additional temporary hit points for each slot level above 1st.


#### Feather Fall
*1st-level transmutation*
___
- **Casting Time:** 1 reaction, which you take when you or a creature within 60 feet of you falls
- **Range:** 60 feet
- **Components:** V, M *(a small feather or a piece of down)*
- **Duration:** 1 minute
---
Choose up to {"5"} falling creatures within range. A falling creature's rate of descent slows to {"60 feet"} per round until the spell ends. If the creature lands before the spell ends, it takes no falling damage and can land on its feet, and the spell ends for that creature.


#### Find Familiar
*1st-level conjuration (ritual)*
___
- **Casting Time:** 1 hour
- **Range:** 10 feet
- **Components:** V, S, M *(10 gp worth of charcoal, incense, and herbs that must be consumed by fire in a brass brazier)*
- **Duration:** Instantaneous
---
You gain the service of a familiar, a spirit that takes an animal form you choose: **bat**, **cat**, **crab**, **frog** (toad), **hawk**, **lizard**, **octopus**, **owl**, **poisonous snake**, fish (**quipper**), **rat**, **raven**, **sea horse**, **spider**, or **weasel**. Appearing in an unoccupied space within range, the familiar has the statistics of the chosen form, though it is a celestial, fey, or fiend (your choice) instead of a beast.

Additional animal form choices may be available at the DM's discretion.

Your familiar acts independently of you, but it always obeys your commands. In combat, it rolls its own initiative and acts on its own turn. A familiar can't attack, but it can take other actions as normal.

When the familiar drops to {"0"} hit points, it disappears, leaving behind no physical form. It reappears after you cast this spell again.

While your familiar is within 100 feet of you, you can communicate with it telepathically. Additionally, as an action, you can see through your familiar's eyes and hear what it hears until the start of your next turn, gaining the benefits of any special senses that the familiar has. During this time, you are deaf and blind with regard to your own senses.

As an action, you can temporarily dismiss your familiar. It disappears into a pocket dimension where it awaits your summons. Alternatively, you can dismiss it forever. As an action while it is temporarily dismissed, you can cause it to reappear in any unoccupied space within 30 feet of you.

You can't have more than one familiar at a time. If you cast this spell while you already have a familiar, you instead cause it to adopt a new form. Choose one of the forms from the above list. Your familiar transforms into the chosen creature.

Finally, when you cast a spell with a range of touch, your familiar can deliver the spell as if it had cast the spell. Your familiar must be within 100 feet of you, and it must use its reaction to deliver the spell when you cast it. If the spell requires an attack roll, you use your attack modifier for the roll.


#### Fog Cloud
*1st-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 hour
---
You create a {"20-foot-radius sphere"} of fog centered on a point within range. The sphere spreads around corners, and its area is heavily obscured. It lasts for the duration or until a wind of moderate or greater speed (at least {"10 mph"}) disperses it.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the radius of the fog increases by {"20 feet"} for each slot level above 1st.


#### Frost Fingers
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (15-foot cone)
- **Components:** V, S
- **Duration:** Instantaneous
---
Freezing cold blasts from your fingertips in a {"15-foot cone"}. 

|  |  |
|--|--|
| **Save** | *Constitution* DC {ssDC} |
|  |  |
| cast (1) | !!(2d8) |
| upcast (2): | !!(4d8) |
| On Miss | half damage |
for higher levels, use: {"((SpellLevel*2)d8)"}
The cold freezes nonmagical liquids in the area that aren't being worn or carried.


#### Gift of Alacrity
*1st-level divination*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** V, S
- **Duration:** 8 hours
---
You touch a willing creature. For the duration, the target can add {"1d8"} to its initiative rolls.


#### Goodberry
*1st-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M *(a sprig of mistletoe)*
- **Duration:** Instantaneous
---
Up to ten berries appear in your hand and are infused with magic for the duration. A creature can use its action to eat one berry. Eating a berry restores {"1 hit point"}, and the berry provides enough nourishment to sustain a creature for one day.

The berries lose their potency if they have not been consumed within {"24 hours"} of the casting of this spell.


#### Grease
*1st-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a bit of pork rind or butter)
- **Duration:** 1 minute
---
Slick grease covers the ground in a {"10-foot square"} centered on a point within range and turns it into difficult terrain for the duration.

|  |  |
|--|--|
| **Save** | *Dexterity* DC {ssDC} |
| Effect | fall prone | 
*On cast, or on entering the affected area.


#### Guiding Bolt
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** 1 round
---
A flash of light streaks toward a creature of your choice within range. 

| X | dmg | crit |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | Avd/Dis: !!(1d20 + {prof} + {CastStatMod} |
|  |  |  |
| cast (1) | !!(4d6) *radiant* | add !!(4d6) damage | 
| upcast (2): | !!(8d6) *radiant* | add !!(8d6) damage |
*for higher levels, use: {"((SpellLevel*3)d6)"}*
On a hit, the next attack roll made against this target before the end of your next turn has advantage, thanks to the mystical dim light glittering on the target until then.



#### Guiding Hand (UA)
*1st-level divination (ritual)*
___
- **Casting Time:** 1 minute
- **Range:** 5 feet
- **Components:** V, S
- **Duration:** Concentration, up to 8 hours
---
You create a Tiny incorporeal hand of shimmering light in an unoccupied space you can see within range. The hand exists for the duration, but it disappears if you teleport or you travel to a different plane of existence.

When the hand appears, you name one major landmark, such as a city, mountain, castle, or battlefield on the same plane of existence as you. Someone in history must have visited the site and mapped it. If the landmark appears on no map in existence, the spell fails. Otherwise, whenever you move toward the hand, it moves away from you at the same speed you moved, and it moves in the direction of the landmark, always remaining {"5 feet"} away from you.

If you don't move toward the hand, it remains in place until you do and beckons for you to follow once every {"1d4 minutes"}.


#### Hail of Thorns
*1st-level conjuration*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
The next time you hit a creature with a ranged weapon attack before the spell ends, this spell creates a rain of thorns directed at the target of the attack and each creature within {"5 feet"} of it:

|  |  |
|--|--|
| **Save** | *Dexterity* DC {ssDC} |
|  |  |
| cast (1) | !!(1d10) *piercing* | 
| upcast (2): | !!(2d10) *piercing*| 
| On Save | half damage |
for higher levels, use: {"((SpellLevel)d10)"}


#### Healing Elixir (UA)
*1st-level conjuration*
___
- **Casting Time:** 1 minute
- **Range:** Self
- **Components:** V, S, M *(alchemist's supplies)*
- **Duration:** 24 hours
---
You create a healing elixir in a simple vial that appears in your hand. The elixir retains its potency for the duration or until it's consumed, at which point the vial vanishes.

As an action, a creature can drink the elixir or administer it to another creature. The drinker regains !(2d4 + 2) hit points.


#### Healing Word
*1st-level evocation*
___
- **Casting Time:** 1 bonus action
- **Range:** 60 feet
- **Components:** V
- **Duration:** Instantaneous
---
A creature of your choice that you can see within range regains hit points equal to !(1d4 + {CastStatMod}) . This spell has no effect on undead or constructs.
_for higher levels, use: ! {"((SpellLevel)d4 + 2)"}_


#### Hellish Rebuke
*1st-level evocation*
___
- **Casting Time:** 1 reaction, which you take in response to being damaged by a creature within 60 feet of you that you can see
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You point your finger, and the creature that damaged you is momentarily surrounded by hellish flames. 

|  |  |
|--|--|
| **Save** | *Dexterity* DC {ssDC} |
|  |  |
| cast (1) | !!(2d10) *type* | 
| upcast (2): | !!(4d10) *type* | 
| On Save | Half Damage |
for higher levels, use: {"((SpellLevel*2)d10)"}


#### Heroism
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
A willing creature you touch is imbued with bravery. Until the spell ends, the creature is immune to being frightened and gains {CastStatMod} temporary hit points at the start of each of its turns. When the spell ends, the target loses any remaining temporary hit points from this spell.
_**At Higher Levels:** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature for each slot level above 1st._


#### Hex
*1st-level enchantment*
___
- **Casting Time:** 1 bonus action
- **Range:** 90 feet
- **Components:** V, S, M *(the petrified eye of a newt)*
- **Duration:** Concentration, up to 1 hour
---
You place a curse on a creature that you can see within range. Until the spell ends, you deal an extra {"1d6"} *necrotic* damage to the target whenever you hit it with an attack. 
Also, choose one ability when you cast the spell. The target has disadvantage on ability checks made with the chosen ability.

If the target drops to {"0"} hit points before this spell ends, you can use a bonus action on a subsequent turn of yours to curse a new creature.

A *remove curse* cast on the target ends this spell early.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd or 4th level, you can maintain your concentration on the spell for up to 8 hours. When you use a spell slot of 5th level or higher, you can maintain your concentration on the spell for up to 24 hours.

##### Hex Damage
|||
|-|-|
|Add | !(1d6) *necrotic* |


#### Hunter's Mark
*1st-level divination*
___
- **Casting Time:** 1 bonus action
- **Range:** 90 feet
- **Components:** V
- **Duration:** Concentration, up to 1 hour
---
You choose a creature you can see within range and mystically mark it as your quarry. Until the spell ends, you deal an extra {"1d6"} damage to the target whenever you hit it with a weapon attack, and you have advantage on any *Wisdom (Perception)* or *Wisdom (Survival)* check you make to find it. If the target drops to {"0"} hit points before this spell ends, you can use a bonus action on a subsequent turn of yours to mark a new creature.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd or 4th level, you can maintain your concentration on the spell for up to 8 hours. When you use a spell slot of 5th level or higher, you can maintain your concentration on the spell for up to 24 hours.

##### Hunter's Mark Damage
|||
|-|-|
|add|!(1d6) damage|


#### Ice Knife
*1st-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** S, M *(a drop of water or piece of ice)*
- **Duration:** Instantaneous
---
You create a shard of ice and fling it at one creature within range. 

|  |  |  |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | Avd/Dis: !!(1d20 + {prof} + {CastStatMod} |
| Hit: | !!(1d10) *piercing* | add !!(1d10) damage | 
| Effect | the shard explodes | everything within {"5 feet"}|
|  |  |  |
| **Save** | *Dexterity* | DC {ssDC} |
| cast (1) | !!(2d6) *cold* | _no crit_ | 
| upcast (2): | !!(4d6) *cold* | _no crit_ |
| On Save | no damage |  |
for higher levels, use: {"((SpellLevel*2)d6)"}

#### Id Insinuation
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
You unleash a torrent of conflicting desires in the mind of one creature you can see within range, impairing its ability to make decisions. 

|  |  |  |
|--|--|--|
| **Save** | *Wisdom* | DC {ssDC} |
| Effect | Incapacitated | if save failed |
|  |  |  |
| cast (1) | !!(1d12) *psychic* | end of it's turn | 
| upcast (2): | !!(2d12) *psychic* | end of it's turn |
| On Save | spell ends | repeat after spell dmg |


#### Identify
*1st-level divination (ritual)*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** V, S, M (a pearl worth at least 100 gp and an owl feather)
- **Duration:** Instantaneous
---
You choose one object that you must touch throughout the casting of the spell. If it is a magic item or some other magic-imbued object, you learn its properties and how to use them, whether it requires attunement to use, and how many charges it has, if any. You learn whether any spells are affecting the item and what they are. If the item was created by a spell, you learn which spell created it.

If you instead touch a creature throughout the casting, you learn what spells, if any, are currently affecting it.


#### Illusory Script
*1st-level illusion (ritual)*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** S, M *(a lead-based ink worth at least 10 gp, which the spell consumes)*
- **Duration:** 10 days
---
You write on parchment, paper, or some other suitable writing material and imbue it with a potent illusion that lasts for the duration.

To you and any creatures you designate when you cast the spell, the writing appears normal, written in your hand, and conveys whatever meaning you intended when you wrote the text. To all others, the writing appears as if it were written in an unknown or magical script that is unintelligible. Alternatively, you can cause the writing to appear to be an entirely different message, written in a different hand and language, though the language must be one you know.

Should the spell be dispelled, the original script and the illusion both disappear.

A creature with truesight can read the hidden message.


#### Infallible Relay (UA)
*1st-level divination (technomagic)*
___
- **Casting Time:** 1 minute
- **Range:** Self
- **Components:** V, S, M (a mobile phone)
- **Duration:** Concentration, up to 10 minutes
---
With this spell, you can target any creature with whom you have spoken previously, as long as the two of you are on the same plane of existence. When you cast the spell, the nearest functioning telephone or similar communications device within {"100 feet"} of the target begins to ring. If there is no suitable device close enough to the target, the spell fails.

The target must make a successful *Charisma* saving throw or be compelled to answer your call. Once the connection is established, the call is crystal clear and cannot be dropped until the conversation has ended or the spell's duration ends. You can end the conversation at any time, but a target must succeed on a *Charisma* saving throw to end the conversation.


#### Inflict Wounds
*1st-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Instantaneous
---
Make a melee spell attack against a creature you can reach. 

|  |  |  |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | Avd/Dis: !!(1d20 + {prof} + {CastStatMod} |
|  |  |  |
| on Hit: | !!(3d10) *necrotic* | add !!(3d10) damage | 
for higher levels, use: {"((SpellLevel*3)d10)"}


#### Jim's Magic Missile
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S, R *(1 gp)*
- **Duration:** Instantaneous
---
*Jim's magic missile is an ancient and powerful spell, as well as being the name of my band in Wizard Academy.*— Jim Darkmagic
Any apprentice wizard can cast a boring old magic missile. Sure, it always strikes its target. Yawn. Do away with the drudgery of your grandfather's magic with this improved version of the spell, as used by Jim Darkmagic!

You create three twisting, whistling, hypoallergenic, gluten-free darts of magical force. Each dart targets a creature of your choice that you can see within range. Make a ranged spell attack for each missile. On a hit, a missile deals 2d4 force damage to its target.

If the attack roll scores a critical hit, the target of that missile takes 5d4 force damage instead of you rolling damage twice for a critical hit. If the attack roll for any missile is a 1, all missiles miss their targets and blow up in your face, dealing 1 force damage per missile to you.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, the spell creates one more dart, and the royalty component increases by 1 gp, for each slot level above 1st.

|  |  |  |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | Avd/Dis: !!(1d20 + {prof} + {CastStatMod} |
|  |  |  |
| on Hit | !!(2d4) *force* | Crit: !!(5d4) *force* |
| on Fumble | !!(2d1) *force* | to own  face |


#### Jump
*1st-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (a grasshopper's hind leg)
- **Duration:** 1 minute
---
You touch a creature. The creature's *jump distance* is **tripled** until the spell ends.


#### Longstrider
*1st-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (a pinch of dirt)
- **Duration:** 1 hour
---
You touch a creature. The target's speed increases by {"10 feet"} until the spell ends.

***At Higher Levels.*** When you cast this spell using a spell slot of 2nd level or higher, you can target one additional creature for each slot level above 1st.


#### Mage Armor
*1st-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M *(a piece of cured leather)*
- **Duration:** 8 hours
---
{name} touches a willing creature who isn’t wearing armor, and a protective magical force surrounds it until the spell ends. The target’s base AC becomes 13 + its Dexterity modifier. The spell ends if the target dons armor or if {name} dismisses the spell as an action.


#### Magic Missile
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
{name} creates three glowing darts of magical force. Each dart hits a creature of their choice that they can see within range. A dart deals {"1d4 + 1"} force damage to its target. The darts all strike simultaneously, and {name} can direct them to hit one creature or several.

|  |  |
|--|--|
| Dart 1 | !(1d4 + 1) |
| Dart 2 | !(1d4 + 1) |
| Dart 3 | !(1d4 + 1) |
At Higher levels:

| 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|--|--|--|--|--|--|--|--|
| !!(1d4+1) | !!(1d4+1) | !!(1d4+1) | !!(1d4+1) | !!(1d4+1) | !!(1d4+1) | !!(1d4+1) | !!(1d4+1) |


#### Magnify Gravity
*1st-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 1 round
---
The gravity in a {"10-foot-radius sphere"} centered on a point you can see within range increases for a moment. ***Each*** creature in the sphere: 

|  |  |
|--|--|
| **Save** | *Constitution* DC {ssDC} |
|  |  |  
| cast (1) | !!(2d8) *force* |  
| upcast (2): | !!(4d8) *force* |
| On Save | Half damage, no effect |
| Effect | Speed halved until end of it's next turn | 
for higher levels, use: {"((SpellLevel*2)d8)"}

Until the start of your next turn, any object that isn't being worn or carried in the sphere requires a successful Strength check against your spell save DC to pick up or move.


#### Protection from Evil and Good
*1st-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M *(holy water or powdered silver and iron, which the spell consumes)*
- **Duration:** Concentration, up to 10 minutes
---
Until the spell ends, one willing creature {name} touches is protected against certain types of creatures: *aberrations, celestials, elementals, fey, fiends*, and *undead.*

The protection grants several benefits. Creatures of those types have **disadvantage** on attack rolls against the target. The target also can't be *charmed, frightened, or possessed* by them. If the target is already charmed, frightened, or possessed by such a creature, the target has **advantage** on any new saving throw against the relevant effect.


#### Puppet (UA)
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** S
- **Duration:** Instantaneous
---
Your gesture forces one humanoid you can see within range to make a *Constitution* saving throw (DC {ssDC}). On a failed save, the target must move up to its speed in a direction you choose. In addition, you can cause the target to drop whatever it is holding. This spell has no effect on a humanoid that is immune to being charmed.


#### Purify Food and Drink
*1st-level transmutation (ritual)*
___
- **Casting Time:** 1 action
- **Range:** 10 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
All nonmagical food and drink within a *5-foot-radius sphere* centered on a point of {name}'s choice within range is purified and rendered free of poison and disease.


#### Ray of Sickness
*1st-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
A ray of sickening greenish energy lashes out toward a creature within range. 

|  |  |  |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | Avd/Dis: !!(1d20 + {prof} + {CastStatMod} |
|  |  |  |
| on Hit: | !!(2d8) *poison* | add !!(2d8) damage |
|  |  |  |
| **Save** | *Constitution* | DC {ssDC} |
| Effect | Target is Poisoned | until end of next turn |
| Save | not poisoned |
for higher levels, use: {"((SpellLevel*2)d8)"}


#### Remote Access (UA)
*1st-level transmutation (technomagic)*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** 10 minutes
---
You can use any electronic device within range as if it were in your hands. This is not a telekinesis effect. Rather, this spell allows you to simulate a device's mechanical functions electronically. You are able to access only functions that a person using the device manually would be able to access. You can use remote access with only one device at a time.


#### Sanctuary
*1st-level abjuration*
___
- **Casting Time:** 1 bonus action
- **Range:** 30 feet
- **Components:** V, S, M *(a small silver mirror)*
- **Duration:** 1 minute
---
{name} wards a creature within range against attack. Until the spell ends, any creature who targets the warded creature with an attack or a harmful spell must first make a *Wisdom* saving throw (DC {ssDC}). On a failed save, the creature must choose a new target or lose the attack or spell. This spell doesn't protect the warded creature from area effects, such as the explosion of a *fireball*.

If the warded creature makes an attack, casts a spell that affects an enemy, or deals damage to another creature, this spell ends.


#### Searing Smite
*1st-level evocation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
The next time you hit a creature with a melee weapon attack during the spell's duration, your weapon flares with white-hot intensity, and the attack deals an extra !!(1d6)  *fire* damage to the target and causes the target to ignite in flames. At the start of each of its turns until the spell ends, the target must make a *Constitution* saving throw (DC {ssDC}). On a failed save, it takes !!(1d6) *fire* damage.
On a successful save, the spell ends. If the target or a creature within 5 feet of it uses an action to put out the flames, or if some other effect douses the flames (such as the target being submerged in water), the spell ends.
for higher levels, use: {"((SpellLevel)d6)"}


#### Sense Emotion (UA)
*1st-level divination*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 10 minutes
---
You attune your senses to pick up the emotions of others for the duration. When you cast the spell, and as your action on each turn until the spell ends, you can focus your senses on one humanoid you can see within {"30 feet"} of you. You instantly learn the target's prevailing emotion, whether it's love, anger, pain, fear, calm, or something else. If the target isn't actually humanoid or it is immune to being charmed, you sense that it is calm.


#### Shield
*1st-level abjuration*
___
- **Casting Time:** 1 reaction, which you take when you are hit by an attack or targeted by the magic missile spell
- **Range:** Self
- **Components:** V, S
- **Duration:** 1 round
---
An invisible barrier of magical force appears and protects {name}. Until the start of their next turn, they have a +5 bonus to AC, including against the triggering attack, and they take no damage from magic missile.


#### Shield of Faith
*1st-level abjuration*
___
- **Casting Time:** 1 bonus action
- **Range:** 60 feet
- **Components:** V, S, M *(a small parchment with a bit of holy text written on it)*
- **Duration:** Concentration, up to 10 minutes
---
A shimmering field appears and surrounds a creature of your choice within range, granting it a +2 bonus to AC for the duration.


#### Silent Image
*1st-level illusion*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M *(a bit of fleece)*
- **Duration:** Concentration, up to 10 minutes
---
{name} creates the image of an object, a creature, or some other visible phenomenon that is no larger than a 15-foot cube. The image appears at a spot within range and lasts for the duration. The image is purely visual; it isn’t accompanied by sound, smell, or other sensory effects.

{name} can use their action to cause the image to move to any spot within range. As the image changes location, they can alter its appearance so that its movements appear natural for the image. For example, if they create an image of a creature and move it, they can alter the image so that it appears to be walking.

Physical interaction with the image reveals it to be an illusion, because things can pass through it. A creature that uses its action to examine the image can determine that it is an illusion with a successful *Intelligence* (Investigation) check, DC {ssDC}. If a creature discerns the illusion for what it is, the creature can see through the image.


#### Sleep
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S, M *(a pinch of fine sand, rose petals, or a cricket)*
- **Duration:** 1 minute
---
This spell sends creatures into a magical slumber. !(5d8) hit points of creatures are affected.
Creatures within {"20 feet"} of a point {name} chooses within range are affected in ascending order of their current hit points (ignoring unconscious creatures).

Starting with the creature that has the lowest current hit points, each creature affected by this spell falls unconscious until the spell ends, the sleeper takes damage, or someone uses an action to shake or slap the sleeper awake. Subtract each creature’s hit points from the total before moving on to the creature with the next lowest hit points. A creature’s hit points must be equal to or less than the remaining total for that creature to be affected.
Undead and creatures immune to being charmed aren’t affected by this spell.

At Higher levels:

| 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|--|--|--|--|--|--|--|--|
| !!(2d8) | !!(4d8) | !!(6d8) | !!(8d8) | !!(10d8) | !!(12d8) | !!(14d8) | !!(16d8) |


#### Snare
*1st-level abjuration*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** S, M *(25 feet of rope, which the spell consumes)*
- **Duration:** 8 hours
---
As you cast this spell, you use the rope to create a circle with a {"5-foot radius"} on the ground or the floor. When you finish casting, the rope disappears and the circle becomes a magic trap.

This trap is nearly invisible, requiring a successful *Intelligence* (Investigation) check, DC {ssDC}, to be discerned.

The trap triggers when a Small, Medium, or Large creature moves onto the ground or the floor in the spell's radius. That creature must succeed on a *Dexterity* saving throw, DC {ssDC}, or be magically hoisted into the air, leaving it hanging upside down {"3 feet"} above the ground or the floor. The creature is restrained there until the spell ends.

A restrained creature can make a *Dexterity* saving throw, DC {ssDC}, at the end of each of its turns, ending the effect on itself on a success. Alternatively, the creature or someone else who can reach it can use an action to make an *Intelligence* (Arcana) check, DC {ssDC}. On a success, the restrained effect ends.

After the trap is triggered, the spell ends when no creature is restrained by it.


#### Speak with Animals
*1st-level divination (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** 10 minutes
---
You gain the ability to comprehend and verbally communicate with beasts for the duration. The knowledge and awareness of many beasts is limited by their intelligence, but at minimum, beasts can give you information about nearby locations and monsters, including whatever they can perceive or have perceived within the past day. You might be able to persuade a beast to perform a small favor for you, at the DM's discretion.


#### Sudden Awakening (UA)
*1st-level enchantment*
___
- **Casting Time:** 1 bonus action
- **Range:** 10 feet
- **Components:** V
- **Duration:** Instantaneous
---
Each sleeping creature you choose within range awakens, and then each prone creature within range can stand up without expending any movement.


#### Tasha's Caustic Brew
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (30-foot line)
- **Components:** V, S, M *(a bit of rotten food)*
- **Duration:** Concentration, up to 1 minute
---
A stream of acid emanates from you in a line {"30 feet"} long and {"5 feet"} wide in a direction you choose. Each creature in the line must succeed on a *Dexterity* saving throw, DC {ssDC}, or be covered in acid for the spell's duration or until a creature uses its action to scrape or wash the acid off itself or another creature. A creature covered in the acid takes {"2d4"} *acid* damage at start of each of its turns.
for higher levels, use: {"((SpellLevel*2)d4)"}


#### Tasha's Hideous Laughter
*1st-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(tiny tarts and a feather that is waved in the air)*
- **Duration:** Concentration, up to 1 minute
---
A creature of your choice that you can see within range perceives everything as hilariously funny and falls into fits of laughter if this spell affects it. The target must succeed on a *Wisdom* saving throw. DC {ssDC}, or fall *prone*, becoming incapacitated and unable to stand up for the duration. 
A creature with an Intelligence score of 4 or less isn't affected.

At the end of each of its turns, and each time it takes damage, the target can make another *Wisdom* saving throw. The target has advantage on the saving throw if it's triggered by damage. On a success, the spell ends.


#### Tenser's Floating Disk
*1st-level conjuration (ritual)*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a drop of mercury)*
- **Duration:** 1 hour
---
This spell creates a circular, horizontal plane of force, *3 feet* in diameter and *1 inch* thick, that floats *3 feet* above the ground in an unoccupied space of your choice that you can see within range. The disk remains for the duration, and can hold up to *500 pounds*. If more weight is placed on it, the spell ends, and everything on the disk falls to the ground.

The disk is immobile while you are within *20 feet* of it. If you move more than *20 feet* away from it, the disk follows you so that it remains within *20 feet* of you. It can move across uneven terrain, up or down stairs, slopes and the like, but it can't cross an elevation change of *10 feet* or more. For example, the disk can't move across a *10-foot-deep* pit, nor could it leave such a pit if it was created at the bottom.

If you move more than *100 feet* from the disk (typically because it can't move around an obstacle to follow you), the spell ends.


#### Thunderous Smite
*1st-level evocation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
The first time you hit with a *melee weapon attack* during this spell's duration, your weapon rings with thunder that is audible within *300 feet* of you, and the attack deals an extra {"2d6"} *thunder* damage to the target. 
Additionally, if the target is a creature, it must succeed on a *Strength* saving throw or be pushed *10 feet* away from you and knocked **prone**.

|  |  |
|--|--|
| On Melee Hit | add !!(2d6) thunder damage |
|  |  |
| **Save**: | *Strength* DC {ssDC} |
| Effect | pushed {"10 feet"} and fall **prone** |


#### Thunderwave
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (15-foot cube)
- **Components:** V, S
- **Duration:** Instantaneous
---
A wave of thunderous force sweeps out from you. Each creature in a *15-foot cube* originating from you:

|  |  |  |
|--|--|--|
| **Save** | *Constitution* | DC {ssDC} |
|  |  |  |
| cast (1) | !!(2d8) *thunder* | and Pushed {"10 feet"} | 
| On Save | Half damage | + isn't pushed |
At Higher levels:

| 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|--|--|--|--|--|--|--|--|
| !!(3d8) | !!(4d8) | !!(5d8) | !!(6d8) | !!(7d8) | !!(8d8) | !!(9d8) | !!(10d8) | 
*thunder* damage

In addition, unsecured objects that are completely within the area of effect are automatically pushed 10 feet away from you by the spell's effect, and the spell emits a thunderous boom audible out to 300 feet.


#### Unearthly Chorus (UA)
*1st-level illusion*
___
- **Casting Time:** 1 action
- **Range:** Self (30-foot radius)
- **Components:** V
- **Duration:** Concentration, up to 10 minutes
---
Music of a style you choose fills the air around you in a {"30-foot radius"}. The music spreads around corners and can be heard from up to {"100 feet"}  away. The music moves with you, centered on you for the duration.

Until the spell ends, you make *Charisma* (Performance) checks with advantage. In addition, you can use a bonus action on each of your turns to beguile one creature you choose within {"30 feet"} of you that can see you and hear the music. The creature must make a *Charisma* saving throw, DC {ssDC}. If you or your companions are attacking it, the creature automatically succeeds on the saving throw. On a failure, the creature becomes friendly to you for as long as it can hear the music and for {"1 hour"} thereafter. You make *Charisma* (Deception) checks and *Charisma* (Persuasion) checks against creatures made friendly by this spell with advantage.


#### Unseen Servant
*1st-level conjuration (ritual)*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M *(a piece of string and a bit of wood)*
- **Duration:** 1 hour
---
This spell creates an invisible, mindless, shapeless force that performs simple tasks at {name}’s command until the spell ends. The servant springs into existence in an unoccupied space on the ground within range. It has {"AC 10"}, {"1 hit point"}, and a {"Strength of 2"}, and it can’t attack. If it drops to {0} hit points, the spell ends.

Once on each of {name}’s turns as a bonus action, they can mentally command the servant to move up to {"15 feet"} and interact with an object. The servant can perform simple tasks that a human servant could do, such as fetching things, cleaning, mending, folding clothes, lighting fires, serving food, and pouring wine. Once {name} gives the command, the servant performs the task to the best of its ability until it completes the task, then waits for their next command.

If {name} commands the servant to perform a task that would move it more than {"60 feet"} away from them, the spell ends.


#### Wild Cunning (UA)
*1st-level transmutation (ritual)*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You call out to the spirits of nature to aid you. When you cast this spell, choose one of the following effects:

- If there are any tracks on the ground within range, you know where they are, and you make Wisdom (Survival) checks to follow these tracks with advantage for 1 hour or until you cast this spell again.
- If there is edible forage within range, you know it and where to find it.
- If there is clean drinking water within range, you know it and where to find it.
- If there is suitable shelter for you and your companions with range, you know it and where to find.
- Send the spirits to bring back wood for a fire and to set up a campsite in the area using your supplies. The spirits build the fire in a circle of stones, put up tents, unroll bedrolls, and put out any rations and water for consumption.
- Have the spirits instantly break down a campsite, which includes putting out a fire, taking down tents, packing up bags, and burying any rubbish.


#### Witch Bolt
*1st-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a twig from a tree that has been struck by lightning)*
- **Duration:** Concentration, up to 1 minute
---
A beam of crackling, blue energy lances out toward a creature within range, forming a sustained arc of lightning between you and the target. 

|  |  |  |
|--|--|--|
| Attack | !(1d20 + {prof} + {CastStatMod}) | Avd/Dis: !!(1d20 + {prof} + {CastStatMod} |
|  |  |  |
| cast (1) | !!(1d12) *lightning* | add !!(1d12) damage | 
| upcast (2): | !!(2d12) *Lightning* | add !!(2d12) damage |
for higher levels, use: {"((SpellLevel)d12)"}

On each of your turns for the duration, you can use your action to deal 1d12 lightning damage to the target automatically. The spell ends if you use your action to do anything else. The spell also ends if the target is ever outside the spell's range or if it has total cover from you.


#### Wrathful Smite
*1st-level evocation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
The next time you hit with a melee weapon attack during this spell's duration, your attack deals an extra {"1d6"} *psychic* damage. 
Additionally, if the target is a creature, it must make a *Wisdom* saving throw, DC {ssDC}, or be **frightened** of you until the spell ends. As an action, the creature can make a *Wisdom* check to steel its resolve and end this spell.


#### Zephyr Strike
*1st-level transmutation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
You move like the wind. Until the spell ends, your movement doesn't provoke opportunity attacks.

Once before the spell ends, you can give yourself advantage on one weapon attack roll on your turn. That attack deals an extra {"1d8"} *force* damage on a hit. 
Whether you hit or miss, your walking speed increases by {"30 feet"} until the end of that turn.


### 2nd level spells
These be a little stronger

#### Aganazzar's Scorcher
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a red dragon's scale)*
- **Duration:** Instantaneous
---
A line of roaring flame {"30 feet"} long and {"5 feet"} wide emanates from {name} in a direction {name} chooses. 

|  |  |  |
|--|--|--|
| **Save** | *Dexterity* DC {ssDC} |
|  |  |  |
| cast (2) | !!(3d8) *fire* | 
| On Save | half damage | 
Higher level:

| 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|--|--|--|--|--|--|--|
| !!(6d8) | !!(9d8) | !!(12d8) | !!(15d8) | !!(18d8) | !!(21d8) | !!(24d8) | 
*type* damage


#### Aid
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a tiny strip of white cloth)*
- **Duration:** 8 hours
---
Your spell bolsters your allies with toughness and resolve. Choose up to {"3"} creatures within range. Each target's *hit point maximum* and *current hit points* increase by {"5"} for the duration.

Extra HP:

| spell lvl | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
|--|--|--|--|--|--|--|--|
| add. HP | {"5"} | {"10"} | {"15"} | {"20"} | {"25"} | {"30"} | {"35"} | {"40"} |

#### Alter Self
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 1 hour
---
You assume a different form. When you cast the spell, choose one of the following options, the effects of which last for the duration of the spell. While the spell lasts, you can end one option as an action to gain the benefits of a different one.

***Aquatic Adaptation.*** You adapt your body to an aquatic environment, sprouting gills and growing webbing between your fingers. You can breathe underwater and gain a swimming speed equal to your walking speed.

***Change Appearance.*** You transform your appearance. You decide what you look like, including your height, weight, facial features, sound of your voice, hair length, coloration, and distinguishing characteristics, if any. You can make yourself appear as a member of another race, though none of your statistics change. You also can't appear as a creature of a different size than you, and your basic shape stays the same; if you're bipedal, you can't use this spell to become quadrupedal, for instance. At any time for the duration of the spell, you can use your action to change your appearance in this way again.

***Natural Weapons.*** You grow claws, fangs, spines, horns, or a different natural weapon of your choice. Your unarmed strikes deal {"1d6"} *bludgeoning, piercing,* or *slashing* damage, as appropriate to the natural weapon you chose, and you are proficient with your unarmed strikes. Finally, the natural weapon is magic and you have a {"+1"} bonus to the attack and damage rolls you make using it.


#### Animal Messenger
*2nd-level enchantment (ritual)*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M *(a morsel of food)*
- **Duration:** 24 hours
---
By means of this spell, you use an animal to deliver a message. Choose a *Tiny* beast you can see within range, such as a squirrel, a blue jay, or a bat. You specify a location, which you must have visited, and a recipient who matches a general description, such as "a man or woman dressed in the uniform of the town guard" or "a red-haired dwarf wearing a pointed hat." You also speak a message of up to twenty-five words. The target beast travels for the duration of the spell toward the specified location, covering about {"50 miles"} per {"24 hours"} for a flying messenger, or {"25 miles"} for other animals.

When the messenger arrives, it delivers your message to the creature that you described, replicating the sound of your voice. The messenger speaks only to a creature matching the description you gave. If the messenger doesn't reach its destination before the spell ends, the message is lost, and the beast makes its way back to where you cast this spell.

***At Higher Levels.*** If you cast this spell using a spell slot of 3rd level or higher, the duration of the spell increases by **48 hours** for each slot level above 2nd.


#### Arcane Hacking (UA)
*2nd-level transmutation (technomagic)*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M *(hacking tools)*
- **Duration:** Concentration, up to 1 hour
---
You gain advantage on all *Intelligence* checks using hacking tools to break software encryption or online security when using a foreign system. This spell also allows you to break 2nd-level and lower protective spells such as arcane lock or glyph of warding by making an *Intelligence* check using hacking tools against the spell save DC of the spell's caster.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can attempt to counteract a spell set to secure the foreign system if the spell's level is equal to or less than the level of the spell slot you used.


#### Arcane Lock
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M *(gold dust worth at least 25 gp, which the spell consumes)*
- **Duration:** Until dispelled
---
You touch a closed door, window, gate, chest, or other entryway, and it becomes locked for the duration. You and the creatures you designate when you cast this spell can open the object normally. You can also set a password that, when spoken within 5 feet of the object, suppresses this spell for 1 minute. Otherwise, it is impassable until it is broken or the spell is dispelled or suppressed. Casting *knock* on the object suppresses *arcane lock* for {"10 minutes"}.

While affected by this spell, the object is more difficult to break or force open; the **DC** to break it or pick any locks on it increases by *10*.


#### Augury
*2nd-level divination (ritual)*
___
- **Casting Time:** 1 minute
- **Range:** Self
- **Components:** V, S, M *(specially marked sticks, bones, or similar tokens worth at least 25 gp)*
- **Duration:** Instantaneous
---
By casting gem-inlaid sticks, rolling dragon bones, laying out ornate cards, or employing some other divining tool, you receive an omen from an otherworldly entity about the results of a specific course of action that you plan to take within the next {"30 minutes"}. The DM chooses from the following possible omens:

- Weal, for good results
- Woe, for bad results
- Weal and woe, for both good and bad results
- Nothing, for results that aren't especially good or bad

The spell doesn't take into account any possible circumstances that might change the outcome, such as the casting of additional spells or the loss or gain of a companion.

*If you cast the spell two or more times before completing your next long rest, there is a cumulative 25 percent chance for each casting after the first that you get a random reading. The DM makes this roll in secret.*


#### Barkskin
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M *(a handful of oak bark)*
- **Duration:** Concentration, up to 1 hour
---
You touch a willing creature. Until the spell ends, the target's skin has a rough, bark-like appearance, and the target's ***AC*** can't be less than {"16"}, regardless of what kind of armor it is wearing.


#### Beast Sense
*2nd-level divination (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** S
- **Duration:** Concentration, up to 1 hour
---
You touch a willing beast. For the duration of the spell, you can use your action to see through the beast's eyes and hear what it hears, and continue to do so until you use your action to return to your normal senses. While perceiving through the beast's senses, you gain the benefits of any special senses possessed by that creature, though you are blinded and deafened to your own surroundings.


#### Blindness/Deafness
*2nd-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V
- **Duration:** 1 minute
---
You can blind or deafen a foe. Choose one creature that you can see within range.

|||
|-|-|
| **Spell Save** | *Constitution DC {ssDC} |
| Effect | Target is *blinded* **OR** *deafened* |
| on **save** | spell ends. |
*Target can repeat save at end of it's turn*
***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional creature for each slot level above 2nd.


#### Blur
*2nd-level illusion*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
{name}'s body becomes blurred, shifting and wavering to all who can see {name}. For the duration, any creature has *disadvantage* on attack rolls against {name}. An attacker is immune to this effect if it doesn't rely on sight, as with blindsight, or can see through illusions, as with truesight.


#### Branding Smite
*2nd-level evocation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
The next time you hit a creature with a weapon attack before this spell ends, the weapon gleams with astral radiance as you strike. The attack deals an extra {"2d6"} radiant damage to the target, which becomes visible if it's invisible, and the target sheds dim light in a {"5-foot"} radius and can't become invisible until the spell ends.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the extra damage increases by {"2d6"} for each slot level above 2nd.


#### Calm Emotions
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
You attempt to suppress strong emotions in a group of people. Each humanoid in a {"20-foot-radius sphere"} centered on a point you choose within range must make a *Charisma* saving throw (DC {ssDC}); a creature can choose to fail this saving throw if it wishes. If a creature fails its saving throw, choose one of the following two effects.

You can suppress any effect causing a target to be charmed or frightened. When this spell ends, any suppressed effect resumes, provided that its duration has not expired in the meantime.

Alternatively, you can make a target indifferent about creatures of your choice that it is hostile toward. This indifference ends if the target is attacked or harmed by a spell or if it witnesses any of its friends being harmed. When the spell ends, the creature becomes hostile again, unless the DM rules otherwise.


#### Cloud of Daggers
*2nd-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M *(a sliver of glass)*
- **Duration:** Concentration, up to 1 minute
---
You fill the air with spinning daggers in a cube {"5 feet"} on each side, centered on a point you choose within range. A creature takes {"4d4"} slashing damage when it enters the spell's area for the first time on a turn or starts its turn there.

|  |  |  |  |  |
|--|--|--|--|--|
| !!(4d4) | !!(4d4) | !!(4d4) | !!(4d4) | !!(4d4) |
***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 4d4 for each slot level above 2nd.


#### Continual Flame
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M *(ruby dust worth 50 gp, which the spell consumes)
- **Duration:** Until dispe*lled
---
A flame, equivalent in brightness to a torch, springs forth from an object that you touch. The effect looks like a regular flame, but it creates no heat and doesn't use oxygen. A continual flame can be covered or hidden but not smothered or quenched.


#### Cordon of Arrows
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 5 feet
- **Components:** V, S, M *(four or more arrows or bolts)*
- **Duration:** 8 hours
---
You plant {"four"} pieces of nonmagical ammunition—*arrows* or *crossbow bolts*—in the ground within range and lay magic upon them to protect an area. Until the spell ends, whenever a creature other than you comes within {"30 feet"} of the ammunition for the first time on a turn or ends its turn there, one piece of ammunition flies up to strike it. The creature must succeed on a *Dexterity* saving throw or take {"1d6"} *piercing* damage. The piece of ammunition is then destroyed. The spell ends when no ammunition remains.

When you cast this spell, you can designate any creatures you choose, and the spell ignores them.

|  |  |  |  |
|--|--|--|--|
| !!(1d6) | !!(1d6) | !!(1d6) | !!(1d6) |
***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the amount of ammunition that can be affected increases by two for each slot level above 2nd.


#### Crown of Madness
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
One humanoid of your choice that you can see within range must succeed on a Wisdom saving throw or become charmed by you for the duration. While the target is charmed in this way, a twisted crown of jagged iron appears on its head, and a madness glows in its eyes.

The charmed target must use its action before moving on each of its turns to make a melee attack against a creature other than itself that you mentally choose. The target can act normally on its turn if you choose no creature or if none are within its reach.

On your subsequent turns, you must use your action to maintain control over the target, or the spell ends. Also, the target can make a Wisdom saving throw at the end of each of its turns. On a success, the spell ends.


#### Darkness
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, M (bat fur and a drop of pitch or piece of coal)
- **Duration:** Concentration, up to 10 minutes
---
Magical darkness spreads from a point you choose within range to fill a 15-foot-radius sphere for the duration. The darkness spreads around corners. A creature with darkvision can't see through this darkness, and nonmagical light can't illuminate it.

If the point you choose is on an object you are holding or one that isn't being worn or carried, the darkness emanates from the object and moves with it. Completely covering the source of the darkness with an opaque object, such as a bowl or a helm, blocks the darkness.

If any of this spell's area overlaps with an area of light created by a spell of 2nd level or lower, the spell that created the light is dispelled.


#### Darkvision
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (either a pinch of dried carrot or an agate)
- **Duration:** 8 hours
---
You touch a willing creature to grant it the ability to see in the dark. For the duration, that creature has darkvision out to a range of 60 feet.


#### Detect Thoughts
*2nd-level divination*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M (a copper piece)
- **Duration:** Concentration, up to 1 minute
---
For the duration, you can read the thoughts of certain creatures. When you cast the spell and as your action on each turn until the spell ends, you can focus your mind on any one creature that you can see within 30 feet of you. If the creature you choose has an Intelligence of 3 or lower or doesn't speak any language, the creature is unaffected.

You initially learn the surface thoughts of the creature—what is most on its mind in that moment. As an action, you can either shift your attention to another creature's thoughts or attempt to probe deeper into the same creature's mind. If you probe deeper, the target must make a Wisdom saving throw. If it fails, you gain insight into its reasoning (if any), its emotional state, and something that looms large in its mind (such as something it worries over, loves, or hates). If it succeeds, the spell ends. Either way, the target knows that you are probing into its mind, and unless you shift your attention to another creature's thoughts, the creature can use its action on its turn to make an Intelligence check contested by your Intelligence check; if it succeeds, the spell ends.

Questions verbally directed at the target creature naturally shape the course of its thoughts, so this spell is particularly effective as part of an interrogation.

You can also use this spell to detect the presence of thinking creatures you can't see. When you cast the spell or as your action during the duration, you can search for thoughts within 30 feet of you. The spell can penetrate barriers, but 2 feet of rock, 2 inches of any metal other than lead, or a thin sheet of lead blocks you. You can't detect a creature with an Intelligence of 3 or lower or one that doesn't speak any language.

Once you detect the presence of a creature in this way, you can read its thoughts for the rest of the duration as described above, even if you can't see it, but it must still be within range.


#### Digital Phantom (UA)
*2nd-level abjuration (technomagic)*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M (a small piece of copper wire)
- **Duration:** Concentration, up to 1 hour
---
This spell works to actively hide your presence within a computer system. For the spell's duration, you and any other users you choose on your local network gain a +10 bonus to Intelligence checks to avoid detection by administrators, knowbots, tracking software, and the like. Whenever you and your chosen users leave any computer system you are working in while this spell is in effect, all trace of your previous presence in that system is erased.


#### Dragon's Breath
*2nd-level transmutation*
___
- **Casting Time:** 1 bonus action
- **Range:** Touch
- **Components:** V, S, M (a hot pepper)
- **Duration:** Concentration, up to 1 minute
---
You touch one willing creature and imbue it with the power to spew magical energy from its mouth, provided it has one. Choose acid, cold, fire, lightning, or poison. Until the spell ends, the creature can use an action to exhale energy of the chosen type in a 15-foot cone. Each creature in that area must make a Dexterity saving throw, taking 3d6 damage of the chosen type on a failed save, or half as much damage on a successful one.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 3d6 for each slot level above 2nd.


#### Dust Devil
*2nd-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a pinch of dust)
- **Duration:** Concentration, up to 1 minute
---
Choose an unoccupied 5-foot cube of air that you can see within range. An elemental force that resembles a dust devil appears in the cube and lasts for the spell's duration.

Any creature that ends its turn within 5 feet of the dust devil must make a Strength saving throw. On a failed save, the creature takes 1d8 bludgeoning damage and is pushed 10 feet away from the dust devil. On a successful save, the creature takes half as much damage and isn't pushed.

As a bonus action, you can move the dust devil up to 30 feet in any direction. If the dust devil moves over sand, dust, loose dirt, or light gravel, it sucks up the material and forms a 10-foot-radius cloud of debris around itself that lasts until the start of your next turn. The cloud heavily obscures its area.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 1d8 for each slot level above 2nd.


#### Earthbind
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 300 feet
- **Components:** V
- **Duration:** Concentration, up to 1 minute
---
Choose one creature you can see within range. Yellow strips of magical energy loop around the creature. The target must succeed on a Strength saving throw, or its flying speed (if any) is reduced to 0 feet for the spell's duration. An airborne creature affected by this spell safely descends at 60 feet per round until it reaches the ground or the spell ends.


#### Enhance Ability
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (fur or a feather from a beast)
- **Duration:** Concentration, up to 1 hour
---
You touch a creature and bestow upon it a magical enhancement. Choose one of the following effects; the target gains that effect until the spell ends.

***Bear's Endurance.*** The target has advantage on Constitution checks. It also gains 2d6 temporary hit points, which are lost when the spell ends.

***Bull's Strength.*** The target has advantage on Strength checks, and his or her carrying capacity doubles.

***Cat's Grace.*** The target has advantage on Dexterity checks. It also doesn't take damage from falling 20 feet or less if it isn't incapacitated.

***Eagle's Splendor.*** The target has advantage on Charisma checks.

***Fox's Cunning.*** The target has advantage on Intelligence checks.

***Owl's Wisdom.*** The target has advantage on Wisdom checks.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional creature for each slot level above 2nd.


#### Enlarge/Reduce
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M (a pinch of powdered iron)
- **Duration:** Concentration, up to 1 minute
---
You cause a creature or an object you can see within range to grow larger or smaller for the duration. Choose either a creature or an object that is neither worn nor carried. If the target is unwilling, it can make a Constitution saving throw. On a success, the spell has no effect.

If the target is a creature, everything it is wearing and carrying changes size with it. Any item dropped by an affected creature returns to normal size at once.

***Enlarge.*** The target's size doubles in all dimensions, and its weight is multiplied by eight. This growth increases its size by one category—from Medium to Large, for example. If there isn't enough room for the target to double its size, the creature or object attains the maximum possible size in the space available. Until the spell ends, the target also has advantage on Strength checks and Strength saving throws. The target's weapons also grow to match its new size. While these weapons are enlarged, the target's attacks with them deal 1d4 extra damage.

***Reduce.*** The target's size is halved in all dimensions, and its weight is reduced to one-eighth of normal. This reduction decreases its size by one category—from Medium to Small, for example. Until the spell ends, the target also has disadvantage on Strength checks and Strength saving throws. The target's weapons also shrink to match its new size. While these weapons are reduced, the target's attacks with them deal 1d4 less damage (this can't reduce the damage below 1).


#### Enthrall
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 1 minute
---
You weave a distracting string of words, causing creatures of your choice that you can see within range and that can hear you to make a Wisdom saving throw. Any creature that can't be charmed succeeds on this saving throw automatically, and if you or your companions are fighting a creature, it has advantage on the save. On a failed save, the target has disadvantage on Wisdom (Perception) checks made to perceive any creature other than you until the spell ends or until the target can no longer hear you. The spell ends if you are incapacitated or can no longer speak.


#### Find Steed
*2nd-level conjuration*
___
- **Casting Time:** 10 minutes
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You summon a spirit that assumes the form of an unusually intelligent, strong, and loyal steed, creating a long-lasting bond with it. Appearing in an unoccupied space within range, the steed takes on a form that you choose: a **warhorse**, a **pony**, a **camel**, an **elk**, or a **mastiff**. (Your DM might allow other animals to be summoned as steeds.) The steed has the statistics of the chosen form, though it is a celestial, fey, or fiend (your choice) instead of its normal type. Additionally, if your steed has an Intelligence of 5 or less, its Intelligence becomes 6, and it gains the ability to understand one language of your choice that you speak.

Your steed serves you as a mount, both in combat and out, and you have an instinctive bond with it that allows you to fight as a seamless unit. While mounted on your steed, you can make any spell you cast that targets only you also target your steed.

When the steed drops to 0 hit points, it disappears, leaving behind no physical form. You can also dismiss your steed at any time as an action, causing it to disappear. In either case, casting this spell again summons the same steed, restored to its hit point maximum.

While your steed is within 1 mile of you, you can communicate with each other telepathically.

You can't have more than one steed bonded by this spell at a time. As an action, you can release the steed from its bond at any time, causing it to disappear.


#### Find Traps
*2nd-level divination*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You sense the presence of any trap within range that is within line of sight. A trap, for the purpose of this spell, includes anything that would inflict a sudden or unexpected effect you consider harmful or undesirable, which was specifically intended as such by its creator. Thus, the spell would sense an area affected by the *alarm* spell, a *glyph of warding*, or a mechanical pit trap, but it would not reveal a natural weakness in the floor, an unstable ceiling, or a hidden sinkhole.

This spell merely reveals that a trap is present. You don't learn the location of each trap, but you do learn the general nature of the danger posed by a trap you sense.


#### Find Vehicle (UA)
*2nd-level conjuration*
___
- **Casting Time:** 10 minutes
- **Range:** 30 feet
- **Components:** V, S
- **Duration:** 8 hours
---
You summon a spirit that assumes the form of a nonmilitary land vehicle of your choice, appearing in an unoccupied space within range. The vehicle has the statistics of a normal vehicle of its sort, though it is celestial, fey, or fiendish (your choice in origin). The physical characteristics of the vehicle reflect its origin to some degree. For example, a fiendish SUV might be jet black in color, with tinted windows and a sinister-looking front grille.

You have a supernatural bond with the conjured vehicle that allows you to drive beyond your normal ability. While driving the conjured vehicle, you are considered proficient with vehicles of its type, and you add double your proficiency bonus to ability checks related to driving the vehicle. While driving the vehicle, you can make any spell you cast that targets only you also target the vehicle.

If the vehicle drops to 0 hit points, it disappears, leaving behind no physical form. You can also dismiss the vehicle at any time as an action, causing it to disappear.

You can't have more than one vehicle bonded by this spell at a time. As an action, you can release the vehicle from its bond at any time, causing it to disappear.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can conjure a nonmilitary water vehicle large enough to carry six Medium creatures. When you cast this spell using a spell slot of 5th level or higher, you can conjure a nonmilitary air vehicle large enough to carry ten Medium creatures. When you cast this spell using a spell slot of 7th level or higher, you can conjure any type of vehicle, subject to the DM's approval.


#### Flame Blade
*2nd-level evocation*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V, S, M (leaf of sumac)
- **Duration:** Concentration, up to 10 minutes
---
You evoke a fiery blade in your free hand. The blade is similar in size and shape to a scimitar, and it lasts for the duration. If you let go of the blade, it disappears, but you can evoke the blade again as a bonus action.

You can use your action to make a melee spell attack with the fiery blade. On a hit, the target takes 3d6 fire damage.

The flaming blade sheds bright light in a 10-foot radius and dim light for an additional 10 feet.

***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the damage increases by 3d6 for every two slot levels above 2nd.


#### Flaming Sphere
*2nd-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a bit of tallow, a pinch of brimstone, and a dusting of powdered iron)
- **Duration:** Concentration, up to 1 minute
---
A 5-foot-diameter sphere of fire appears in an unoccupied space of your choice within range and lasts for the duration. Any creature that ends its turn within 5 feet of the sphere must make a Dexterity saving throw. The creature takes 2d6 fire damage on a failed save, or half as much damage on a successful one.

As a bonus action, you can move the sphere up to 30 feet. If you ram the sphere into a creature, that creature must make the saving throw against the sphere's damage, and the sphere stops moving this turn.

When you move the sphere, you can direct it over barriers up to 5 feet tall and jump it across pits up to 10 feet wide. The sphere ignites flammable objects not being worn or carried, and it sheds bright light in a 20-foot radius and dim light for an additional 20 feet.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 2d6 for each slot level above 2nd.


#### Flock of Familiars
*2nd-level conjuration*
___
- **Casting Time:** 1 minute
- **Range:** Touch
- **Components:** V, S
- **Duration:** Concentration, up to 1 hour
---
You temporarily summon three familiars—spirits that take animal forms of your choice. Each familiar uses the same rules and options for a familiar conjured by the *find familiar* spell. All the familiars conjured by this spell must be the same type of creature (celestials, fey, or fiends; your choice). If you already have a familiar conjured by the *find familiar* spell or similar means, then one fewer familiars are conjured by this spell.

Familiars summoned by this spell can telepathically communicate with you and share their visual or auditory senses while they are within 1 mile of you.

When you cast a spell with a range of touch, one of the familiars conjured by this spell can deliver the spell, as normal. However, you can cast a touch spell through only one familiar per turn.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you conjure an additional familiar for each slot level above 2nd.


#### Fortune's Favor
*2nd-level divination*
___
- **Casting Time:** 1 minute
- **Range:** 60 feet
- **Components:** V, S, M (a white pearl worth at least 100 gp, which the spell consumes)
- **Duration:** 1 hour
---
You impart latent luck to yourself or one willing creature you can see within range. When the chosen creature makes an attack roll, an ability check, or a saving throw before the spell ends, it can dismiss this spell on itself to roll an additional d20 and choose which of the d20s to use. Alternatively, when an attack roll is made against the chosen creature, it can dismiss this spell on itself to roll a d20 and choose which of the d20s to use, the one it rolled or the one the attacker rolled.

If the original d20 roll has advantage or disadvantage, the creature rolls the additional d20 after advantage or disadvantage has been applied to the original roll.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional creature for each slot level above 2nd.


#### Gentle Repose
*2nd-level necromancy (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (a pinch of salt and one copper piece placed on each of the corpse's eyes, which must remain there for the duration)
- **Duration:** 10 days
---
You touch a corpse or other remains. For the duration, the target is protected from decay and can't become undead.

The spell also effectively extends the time limit on raising the target from the dead, since days spent under the influence of this spell don't count against the time limit of spells such as *raise dead*.


#### Gift of Gab
*2nd-level enchantment*
___
- **Casting Time:** 1 reaction, which you take when you speak to another creature
- **Range:** Self
- **Components:** V, S, R (2 gp)
- **Duration:** Instantaneous
---
*When I met Jim Darkmagic, I wondered how he got anything done in that outfit. I have since learned that most of his talents involve standing and talking. His outfit is perfect for that.*— MôrgænJim Darkmagic is said to have invented this spell, originally calling it *I said what?!* Have you ever been talking to the local monarch and accidentally mentioned how their son looks like your favorite hog from when you were growing up on the family farm? We've all been there! But rather than being beheaded for an honest slip of the tongue, you can pretend it never happened—by ensuring that no one knows it happened.

When you cast this spell, you skillfully reshape the memories of listeners in your immediate area, so that each creature of your choice within 5 feet of you forgets everything you said within the last 6 seconds. Those creatures then remember that you actually said the words you speak as the verbal component of the spell.


#### Gust of Wind
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (60-foot line)
- **Components:** V, S, M (a legume seed)
- **Duration:** Concentration, up to 1 minute
---
A line of strong wind 60 feet long and 10 feet wide blasts from you in a direction you choose for the spell's duration. Each creature that starts its turn in the line must succeed on a Strength saving throw or be pushed 15 feet away from you in a direction following the line.

Any creature in the line must spend 2 feet of movement for every 1 foot it moves when moving closer to you.

The gust disperses gas or vapor, and it extinguishes candles, torches, and similar unprotected flames in the area. It causes protected flames, such as those of lanterns, to dance wildly and has a 50 percent chance to extinguish them.

As a bonus action on each of your turns before the spell ends, you can change the direction in which the line blasts from you.


#### Healing Spirit
*2nd-level conjuration*
___
- **Casting Time:** 1 bonus action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
You call forth a nature spirit to soothe the wounded. The intangible spirit appears in a space that is a 5-foot cube you can see within range. The spirit looks like a transparent beast or fey (your choice).

Until the spell ends, whenever you or a creature you can see moves into the spirit's space for the first time on a turn or starts its turn there, you can cause the spirit to restore 1d6 hit points to that creature (no action required). The spirit can't heal constructs or undead. The spirit can heal a number of times equal to 1 + your spellcasting ability modifier (minimum of twice). After healing that number of times, the spirit disappears.

As a bonus action on your turn, you can move the spirit up to 30 feet to a space you can see.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the healing increases by 1d6 for each slot level above 2nd.


#### Heat Metal
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a piece of iron and a flame)
- **Duration:** Concentration, up to 1 minute
---
Choose a manufactured metal object, such as a metal weapon or a suit of heavy or medium metal armor, that you can see within range. You cause the object to glow red-hot. Any creature in physical contact with the object takes 2d8 fire damage when you cast the spell. Until the spell ends, you can use a bonus action on each of your subsequent turns to cause this damage again.

If a creature is holding or wearing the object and takes the damage from it, the creature must succeed on a Constitution saving throw or drop the object if it can. If it doesn't drop the object, it has disadvantage on attack rolls and ability checks until the start of your next turn.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 2d8 for each slot level above 2nd.


#### Hold Person
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a small, straight piece of iron)
- **Duration:** Concentration, up to 1 minute
---
Choose a humanoid that you can see within range. The target must succeed on a Wisdom saving throw or be paralyzed for the duration. At the end of each of its turns, the target can make another Wisdom saving throw. On a success, the spell ends on the target.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional humanoid for each slot level above 2nd. The humanoids must be within 30 feet of each other when you target them.


#### Icingdeath's Frost
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self (15-foot cone)
- **Components:** S, M (a vial of meltwater)
- **Duration:** Instantaneous
---
A burst of icy cold energy emanates from you in a 30-foot cone. Each creature in that area must make a Constitution saving throw. On a failed save, a creature takes 3d8 cold damage and is covered in ice for 1 minute or until a creature uses its action to break the ice off itself or another creature. A creature covered in ice has its speed reduced to 0. On a successful save, a creature takes half as much damage with no additional effects.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, increase the cold damage by 1d8 for each slot level above 2nd.


#### Immovable Object
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (gold dust worth at least 25 gp, which the spell consumes)
- **Duration:** 1 hour
---
You touch an object that weighs no more than 10 pounds and cause it to become magically fixed in place. You and the creatures you designate when you cast this spell can move the object normally. You can also set a password that, when spoken within 5 feet of the object, suppresses this spell for 1 minute.

If the object is fixed in the air, it can hold up to 4,000 pounds of weight. More weight causes the object to fall. Otherwise, a creature can use an action to make a Strength check against your spell save DC. On a success, the creature can move the object up to 10 feet.

***At Higher Levels.*** If you cast this spell using a spell slot of 4th or 5th level, the DC to move the object increases by 5, it can carry up to 8,000 pounds of weight, and the duration increases to 24 hours. If you cast this spell using a spell slot of 6th level or higher, the DC to move the object increases by 10, it can carry up to 20,000 pounds of weight, and the effect is permanent until dispelled.


#### Invisibility
*2nd-level illusion*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (an eyelash encased in gum arabic)
- **Duration:** Concentration, up to 1 hour
---
A creature you touch becomes invisible until the spell ends. Anything the target is wearing or carrying is invisible as long as it is on the target's person. The spell ends for a target that attacks or casts a spell.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional creature for each slot level above 2nd.


#### Jim's Glowing Coin
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** S, M (a coin), R (2 gp)
- **Duration:** 1 minute
---
Of the many tactics employed by master magician and renowned adventurer Jim Darkmagic, the old glowing coin trick is a time-honored classic. When you cast the spell, you hurl the coin that is the spell's material component to any spot within range. The coin lights up as if under the effect of a *light* spell. Each creature of your choice that you can see within 30 feet of the coin must succeed on a Wisdom saving throw or be distracted for the duration. While distracted, a creature has disadvantage on Wisdom (Perception) checks and initiative rolls.


#### Knock
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V
- **Duration:** Instantaneous
---
Choose an object that you can see within range. The object can be a door, a box, a *chest*, a set of *manacles*, a padlock, or another object that contains a mundane or magical means that prevents access.

A target that is held shut by a mundane lock or that is stuck or barred becomes unlocked, unstuck, or unbarred. If the object has multiple locks, only one of them is unlocked.

If you choose a target that is held shut with *arcane lock*, that spell is suppressed for 10 minutes, during which time the target can be opened and shut normally.

When you cast the spell, a loud knock, audible from as far away as 300 feet, emanates from the target object.


#### Lesser Restoration
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Instantaneous
---
You touch a creature and can end either one disease or one condition afflicting it. The condition can be blinded, deafened, paralyzed, or poisoned.


#### Lesser Restoration
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Instantaneous
---
You touch a creature and can end either one disease or one condition afflicting it. The condition can be blinded, deafened, paralyzed, or poisoned.


#### Locate Animals or Plants
*2nd-level divination (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M (a bit of fur from a bloodhound)
- **Duration:** Instantaneous
---
Describe or name a specific kind of beast or plant. Concentrating on the voice of nature in your surroundings, you learn the direction and distance to the closest creature or plant of that kind within 5 miles, if any are present.


#### Locate Object
*2nd-level divination*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M (a forked twig)
- **Duration:** Concentration, up to 10 minutes
---
Describe or name an object that is familiar to you. You sense the direction to the object's location, as long as that object is within 1,000 feet of you. If the object is in motion, you know the direction of its movement.

The spell can locate a specific object known to you, as long as you have seen it up close—within 30 feet—at least once. Alternatively, the spell can locate the nearest object of a particular kind, such as a certain kind of apparel, jewelry, furniture, tool, or weapon.

This spell can't locate an object if any thickness of lead, even a thin sheet, blocks a direct path between you and the object.


#### Magic Mouth
*2nd-level illusion (ritual)*
___
- **Casting Time:** 1 minute
- **Range:** 30 feet
- **Components:** V, S, M (a small bit of honeycomb and jade dust worth at least 10 gp, which the spell consumes)
- **Duration:** Until dispelled
---
You implant a message within an object in range, a message that is uttered when a trigger condition is met. Choose an object that you can see and that isn't being worn or carried by another creature. Then speak the message, which must be 25 words or less, though it can be delivered over as long as 10 minutes. Finally, determine the circumstance that will trigger the spell to deliver your message.

When that circumstance occurs, a magical mouth appears on the object and recites the message in your voice and at the same volume you spoke. If the object you chose has a mouth or something that looks like a mouth (for example, the mouth of a statue), the magical mouth appears there so that the words appear to come from the object's mouth. When you cast this spell, you can have the spell end after it delivers its message, or it can remain and repeat its message whenever the trigger occurs.

The triggering circumstance can be as general or as detailed as you like, though it must be based on visual or audible conditions that occur within 30 feet of the object. For example, you could instruct the mouth to speak when any creature moves within 30 feet of the object or when a silver bell rings within 30 feet of it.


#### Magic Weapon
*2nd-level transmutation*
___
- **Casting Time:** 1 bonus action
- **Range:** Touch
- **Components:** V, S
- **Duration:** Concentration, up to 1 hour
---
You touch a nonmagical weapon. Until the spell ends, that weapon becomes a magic weapon with a +1 bonus to attack rolls and damage rolls.

***At Higher Levels.*** When you cast this spell using a spell slot of 4th level or higher, the bonus increases to +2. When you use a spell slot of 6th level or higher, the bonus increases to +3.


#### Maximilian's Earthen Grasp
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, S, M (a miniature hand sculpted from clay)
- **Duration:** Concentration, up to 1 minute
---
You choose a 5-foot-square unoccupied space on the ground that you can see within range. A Medium hand made from compacted soil rises there and reaches for one creature you can see within 5 feet of it. The target must make a Strength saving throw. On a failed save, the target takes 2d6 bludgeoning damage and is restrained for the spell's duration.

As an action, you can cause the hand to crush the restrained target, which must make a Strength saving throw. The target takes 2d6 bludgeoning damage on a failed save, or half as much damage on a successful one.

To break out, the restrained target can use its action to make a Strength check against your spell save DC. On a success, the target escapes and is no longer restrained by the hand.

As an action, you can cause the hand to reach for a different creature or to move to a different unoccupied space within range. The hand releases a restrained target if you do either.


#### Melf's Acid Arrow
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S, M (powdered rhubarb leaf and an adder's stomach)
- **Duration:** Instantaneous
---
A shimmering green arrow streaks toward a target within range and bursts in a spray of acid. Make a ranged spell attack against the target. On a hit, the target takes 4d4 acid damage immediately and 2d4 acid damage at the end of its next turn. On a miss, the arrow splashes the target with acid for half as much of the initial damage and no damage at the end of its next turn.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage (both initial and later) increases by 4d4;2d4 for each slot level above 2nd.


#### Mental Barrier
*2nd-level abjuration*
___
- **Casting Time:** 1 reaction, which you take when you are forced to make an Intelligence, a Wisdom, or a Charisma saving throw
- **Range:** Self
- **Components:** V
- **Duration:** 1 round
---
You protect your mind with a wall of looping, repetitive thought. Until the start of your next turn, you have advantage on Intelligence, Wisdom, and Charisma saving throws, and you have resistance to psychic damage.


#### Mind Spike
*2nd-level divination*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** S
- **Duration:** Concentration, up to 1 hour
---
You reach into the mind of one creature you can see within range. The target must make a Wisdom saving throw, taking 3d8 psychic damage on a failed save, or half as much damage on a successful one. On a failed save, you also always know the target's location until the spell ends, but only while the two of you are on the same plane of existence. While you have this knowledge, the target can't become hidden from you, and if it's invisible, it gains no benefit from that condition against you.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 3d8 for each slot level above 2nd.


#### Mind Thrust
*2nd-level enchantment*
___
- **Casting Time:** 1 bonus action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 1 round
---
You propel a lance of psionic disruption into the mind of one creature you can see within range. The target must make an Intelligence saving throw. On a failed save, the target takes 3d6 psychic damage, and it can use its action only to Dash or Disengage on its next turn. On a successful save, the target takes half as much damage, and this spell doesn't limit its action options.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional creature for each slot level above 2nd. The creatures must be within 30 feet of each other when you target them.


#### Mirror Image
*2nd-level illusion*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S
- **Duration:** 1 minute
---
Three illusory duplicates of yourself appear in your space. Until the spell ends, the duplicates move with you and mimic your actions, shifting position so it's impossible to track which image is real. You can use your action to dismiss the illusory duplicates.

Each time a creature targets you with an attack during the spell's duration, roll a d20 to determine whether the attack instead targets one of your duplicates.

If you have three duplicates, you must roll a 6 or higher to change the attack's target to a duplicate. With two duplicates, you must roll an 8 or higher. With one duplicate, you must roll an 11 or higher.

A duplicate's AC equals 10 + your Dexterity modifier. If an attack hits a duplicate, the duplicate is destroyed. A duplicate can be destroyed only by an attack that hits it. It ignores all other damage and effects. The spell ends when all three duplicates are destroyed.

A creature is unaffected by this spell if it can't see, if it relies on senses other than sight, such as blindsight, or if it can perceive illusions as false, as with truesight.


#### Misty Step
*2nd-level conjuration*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V
- **Duration:** Instantaneous
---
Briefly surrounded by silvery mist, you teleport up to 30 feet to an unoccupied space that you can see.


#### Moonbeam
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S, M (several seeds of any moonseed plant and a piece of opalescent feldspar)
- **Duration:** Concentration, up to 1 minute
---
A silvery beam of pale light shines down in a 5-foot-radius, 40-foot-high cylinder centered on a point within range. Until the spell ends, dim light fills the cylinder.

When a creature enters the spell's area for the first time on a turn or starts its turn there, it is engulfed in ghostly flames that cause searing pain, and it must make a Constitution saving throw. It takes 2d10 radiant damage on a failed save, or half as much damage on a successful one.

A shapechanger makes its saving throw with disadvantage. If it fails, it also instantly reverts to its original form and can't assume a different form until it leaves the spell's light.

On each of your turns after you cast this spell, you can use an action to move the beam up to 60 feet in any direction.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 2d10 for each slot level above 2nd.


#### Nathair's Mischief
*2nd-level illusion*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** S, M (a piece of crust from an apple pie)
- **Duration:** Concentration, up to 1 minute
---
You fill a 20-foot cube centered on a point you choose within range with fey and draconic magic. Roll on the Mischievous Surge table to determine the magical effect produced. At the start of each of your turns, you can move the cube up to 10 feet and reroll on the table.

##### Mischievous Surge
| d4 | Effect |
|:---:|---|
| 1 | The smell of apple pie fills the air, and each creature in the cube must succeed on a Wisdom saving throw or become charmed by you until the start of your next turn.  |
| 2 | Bouquets of flowers appear all around, and each creature in the cube must succeed on a Dexterity saving throw or be blinded until the start of your next turn as the flowers spray water in their faces. |
| 3 | Each creature in the cube must succeed on a Wisdom saving throw or begin giggling until the start of your next turn. A giggling creature is incapacitated and uses all its movement to move in a random direction. |
| 4 | Drops of molasses appear and hover in the cube, turning it into difficult terrain until the start of your next turn. |


#### Nathair's Mischief
*2nd-level illusion*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** S, M (a piece of crust from an apple pie)
- **Duration:** Concentration, up to 1 minute
---
You fill a 20-foot cube centered on a point you choose within range with fey and draconic magic. Roll on the Mischievous Surge table to determine the magical effect produced. At the start of each of your turns, you can move the cube up to 10 feet and reroll on the table.

##### Mischievous Surge
| d4 | Effect |
|:---:|---|
| 1 | The smell of apple pie fills the air, and each creature in the cube must succeed on a Wisdom saving throw or become charmed by you until the start of your next turn.  |
| 2 | Bouquets of flowers appear all around, and each creature in the cube must succeed on a Dexterity saving throw or be blinded until the start of your next turn as the flowers spray water in their faces. |
| 3 | Each creature in the cube must succeed on a Wisdom saving throw or begin giggling until the start of your next turn. A giggling creature is incapacitated and uses all its movement to move in a random direction. |
| 4 | Drops of molasses appear and hover in the cube, turning it into difficult terrain until the start of your next turn. |


#### Pass without Trace
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M (ashes from a burned leaf of mistletoe and a sprig of spruce)
- **Duration:** Concentration, up to 1 hour
---
A veil of shadows and silence radiates from you, masking you and your companions from detection. For the duration, each creature you choose within 30 feet of you (including you) has a +10 bonus to Dexterity (Stealth) checks and can't be tracked except by magical means. A creature that receives this bonus leaves behind no tracks or other traces of its passage.


#### Phantasmal Force
*2nd-level illusion*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a bit of fleece)
- **Duration:** Concentration, up to 1 minute
---
You craft an illusion that takes root in the mind of a creature that you can see within range. The target must make an Intelligence saving throw. On a failed save, you create a phantasmal object, creature, or other visible phenomenon of your choice that is no larger than a 10-foot cube and that is perceivable only to the target for the duration. This spell has no effect on undead or constructs.

The phantasm includes sound, temperature, and other stimuli, also evident only to the creature.

The target can use its action to examine the phantasm with an Intelligence (Investigation) check against your spell save DC. If the check succeeds, the target realizes that the phantasm is an illusion, and the spell ends.

While a target is affected by the spell, the target treats the phantasm as if it were real. The target rationalizes any illogical outcomes from interacting with the phantasm. For example, a target attempting to walk across a phantasmal bridge that spans a chasm falls once it steps onto the bridge. If the target survives the fall, it still believes that the bridge exists and comes up with some other explanation for its fall—it was pushed, it slipped, or a strong wind might have knocked it off.

An affected target is so convinced of the phantasm's reality that it can even take damage from the illusion. A phantasm created to appear as a creature can attack the target. Similarly, a phantasm created to appear as fire, a pool of acid, or lava can burn the target. Each round on your turn, the phantasm can deal 1d6 psychic damage to the target if it is in the phantasm's area or within 5 feet of the phantasm, provided that the illusion is of a creature or hazard that could logically deal damage, such as by attacking. The target perceives the damage as a type appropriate to the illusion.


#### Prayer of Healing
*2nd-level evocation*
___
- **Casting Time:** 10 minutes
- **Range:** 30 feet
- **Components:** V
- **Duration:** Instantaneous
---
Up to six creatures of your choice that you can see within range each regain hit points equal to 2d8 + your spellcasting ability modifier. This spell has no effect on undead or constructs.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the healing increases by 2d8 for each slot level above 2nd.


#### Protection from Poison
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** 1 hour
---
You touch a creature. If it is poisoned, you neutralize the poison. If more than one poison afflicts the target, you neutralize one poison that you know is present, or you neutralize one at random.

For the duration, the target has advantage on saving throws against being poisoned, and it has resistance to poison damage.


#### Pyrotechnics
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
Choose an area of nonmagical flame that you can see and that fits within a 5-foot cube within range. You can extinguish the fire in that area, and you create either fireworks or smoke when you do so.

***Fireworks.*** The target explodes with a dazzling display of colors. Each creature within 10 feet of the target must succeed on a Constitution saving throw or become blinded until the end of your next turn.

***Smoke.*** Thick black smoke spreads out from the target in a 20-foot radius, moving around corners. The area of the smoke is heavily obscured. The smoke persists for 1 minute or until a strong wind disperses it.


#### Ray of Enfeeblement
*2nd-level necromancy*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
A black beam of enervating energy springs from your finger toward a creature within range. Make a ranged spell attack against the target. On a hit, the target deals only half damage with weapon attacks that use Strength until the spell ends.

At the end of each of the target's turns, it can make a Constitution saving throw against the spell. On a success, the spell ends.


#### Rope Trick
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (powdered corn extract and a twisted loop of parchment)
- **Duration:** 1 hour
---
You touch a length of rope that is up to 60 feet long. One end of the rope then rises into the air until the whole rope hangs perpendicular to the ground. At the upper end of the rope, an invisible entrance opens to an extradimensional space that lasts until the spell ends.

The extradimensional space can be reached by climbing to the top of the rope. The space can hold as many as eight Medium or smaller creatures. The rope can be pulled into the space, making the rope disappear from view outside the space.

Attacks and spells can't cross through the entrance into or out of the extradimensional space, but those inside can see out of it as if through a 3-foot-by-5-foot window centered on the rope.

Anything inside the extradimensional space drops out when the spell ends.


#### Scorching Ray
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Instantaneous
---
You create three rays of fire and hurl them at targets within range. You can hurl them at one target or several.

Make a ranged spell attack for each ray. On a hit, the target takes 2d6 fire damage.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you create one additional ray for each slot level above 2nd.


#### See Invisibility
*2nd-level divination*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V, S, M (a pinch of Talc and a small sprinkling of powdered silver)
- **Duration:** 1 hour
---
For the duration, you see invisible creatures and objects as if they were visible, and you can see into the Ethereal Plane. Ethereal creatures and objects appear ghostly and translucent.


#### Shadow Blade
*2nd-level illusion*
___
- **Casting Time:** 1 bonus action
- **Range:** Self
- **Components:** V, S
- **Duration:** Concentration, up to 1 minute
---
You weave together threads of shadow to create a sword of solidified gloom in your hand. This magic sword lasts until the spell ends. It counts as a simple melee weapon with which you are proficient. It deals 2d8 psychic damage on a hit and has the finesse, light, and thrown properties (range 20/60). In addition, when you use the sword to attack a target that is in dim light or darkness, you make the attack roll with advantage.

If you drop the weapon or throw it, it dissipates at the end of the turn. Thereafter, while the spell persists, you can use a bonus action to cause the sword to reappear in your hand.

***At Higher Levels.*** When you cast this spell using a 3rd- or 4th-level spell slot, the damage increases to 3d8. When you cast it using a 5th- or 6th-level spell slot, the damage increases to 4d8. When you cast it using a spell slot of 7th level or higher, the damage increases to 5d8.


#### Shatter
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a chip of mica)
- **Duration:** Instantaneous
---
A sudden loud ringing noise, painfully intense, erupts from a point of your choice within range. Each creature in a 10-foot-radius sphere centered on that point must make a Constitution saving throw. A creature takes 3d8 thunder damage on a failed save, or half as much damage on a successful one. A creature made of inorganic material such as stone, crystal, or metal has disadvantage on this saving throw.

A nonmagical object that isn't being worn or carried also takes the damage if it's in the spell's area.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 3d8 for each slot level above 2nd.


#### Silence
*2nd-level illusion (ritual)*
___
- **Casting Time:** 1 action
- **Range:** 120 feet
- **Components:** V, S
- **Duration:** Concentration, up to 10 minutes
---
For the duration, no sound can be created within or pass through a 20-foot-radius sphere centered on a point you choose within range. Any creature or object entirely inside the sphere is immune to thunder damage, and creatures are deafened while entirely inside it. Casting a spell that includes a verbal component is impossible there.


#### Skywrite
*2nd-level transmutation (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Sight
- **Components:** V, S
- **Duration:** Concentration, up to 1 hour
---
You cause up to ten words to form in a part of the sky you can see. The words appear to be made of cloud and remain in place for the spell's duration. The words dissipate when the spell ends. A strong wind can disperse the clouds and end the spell early.


#### Snilloc's Snowball Swarm
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S, M (a piece of ice or a small white rock chip)
- **Duration:** Instantaneous
---
A flurry of magic snowballs erupts from a point you choose within range. Each creature in a 5-foot-radius sphere centered on that point must make a Dexterity saving throw. A creature takes 3d6 cold damage on a failed save, or half as much damage on a successful one.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 3d6 for each slot level above 2nd.


#### Spider Climb
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (a drop of bitumen and a spider)
- **Duration:** Concentration, up to 1 hour
---
Until the spell ends, one willing creature you touch gains the ability to move up, down, and across vertical surfaces and upside down along ceilings, while leaving its hands free. The target also gains a climbing speed equal to its walking speed.


#### Spike Growth
*2nd-level transmutation*
___
- **Casting Time:** 1 action
- **Range:** 150 feet
- **Components:** V, S, M (seven sharp thorns or seven small twigs, each sharpened to a point)
- **Duration:** Concentration, up to 10 minutes
---
The ground in a 20-foot radius centered on a point within range twists and sprouts hard spikes and thorns. The area becomes difficult terrain for the duration. When a creature moves into or within the area, it takes 2d4 piercing damage for every 5 feet it travels.

The transformation of the ground is camouflaged to look natural. Any creature that can't see the area at the time the spell is cast must make a Wisdom (Perception) check against your spell save DC to recognize the terrain as hazardous before entering it.


#### Spiritual Weapon
*2nd-level evocation*
___
- **Casting Time:** 1 bonus action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 1 minute
---
You create a floating, spectral weapon within range that lasts for the duration or until you cast this spell again. When you cast the spell, you can make a melee spell attack against a creature within 5 feet of the weapon. On a hit, the target takes force damage equal to 1d8 + your spellcasting ability modifier.

As a bonus action on your turn, you can move the weapon up to 20 feet and repeat the attack against a creature within 5 feet of it.

The weapon can take whatever form you choose. Clerics of deities who are associated with a particular weapon (as St. Cuthbert is known for his mace and Thor for his hammer) make this spell's effect resemble that weapon.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the damage increases by 1d8 for every two slot levels above 2nd.


#### Suggestion
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 30 feet
- **Components:** V, M (a snake's tongue and either a bit of honeycomb or a drop of sweet oil)
- **Duration:** Concentration, up to 8 hours
---
You suggest a course of activity (limited to a sentence or two) and magically influence a creature you can see within range that can hear and understand you. Creatures that can't be charmed are immune to this effect. The suggestion must be worded in such a manner as to make the course of action sound reasonable. Asking the creature to stab itself, throw itself onto a spear, immolate itself, or do some other obviously harmful act ends the spell.

The target must make a Wisdom saving throw. On a failed save, it pursues the course of action you described to the best of its ability. The suggested course of action can continue for the entire duration. If the suggested activity can be completed in a shorter time, the spell ends when the subject finishes what it was asked to do.

You can also specify conditions that will trigger a special activity during the duration. For example, you might suggest that a knight give her warhorse to the first beggar she meets. If the condition isn't met before the spell expires, the activity isn't performed.

If you or any of your companions damage the target, the spell ends.


#### Summon Beast
*2nd-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S, M (a feather, tuft of fur, and fish tail inside a gilded acorn worth at least 200 gp)
- **Duration:** Concentration, up to 1 hour
---
You call forth a bestial spirit. It manifests in an unoccupied space that you can see within range. This corporeal form uses the **Bestial Spirit** stat block. When you cast the spell, choose an environment: Air, Land, or Water. The creature resembles an animal of your choice that is native to the chosen environment, which determines certain traits in its stat block. The creature disappears when it drops to 0 hit points or when the spell ends.

The creature is an ally to you and your companions. In combat, the creature shares your initiative count, but it takes its turn immediately after yours. It obeys your verbal commands (no action required by you). If you don't issue any, it takes the Dodge action and uses its move to avoid danger.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, use the higher level wherever the spell's level appears in the stat block.


#### Summon Bestial Spirit
*2nd-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V, S, M (a feather, tuft of fur, and fish tail inside a gilded acorn worth at least 200 gp)
- **Duration:** Concentration, up to 1 hour
---
You call forth the spirit of a beast. The spirit manifests physically in an unoccupied space that you can see within range. This corporeal form uses the **Bestial Spirit** stat block. When you cast the spell, choose an environment: Air, Land, or Water. The creature physically resembles an animal of your choice that is native to the chosen environment, which also determines one of the movement modes in the creature's stat block. The creature disappears when it drops to 0 hit points or when the spell ends.

The creature is friendly to you and your companions for the spell's duration. In combat, the creature shares your initiative count, but it takes its turn immediately after yours. It obeys verbal commands that you issue to it (no action required by you). If you don't issue any, it defends itself but otherwise takes no action.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, the creature assumes the higher level for that casting wherever it uses the spell's level in its stat block.


#### Tasha's Mind Whip
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 90 feet
- **Components:** V
- **Duration:** 1 round
---
You psychically lash out at one creature you can see within range. The target must make an Intelligence saving throw. On a failed save, the target takes 3d6 psychic damage, and it can't take a reaction until the end of its next turn. Moreover, on its next turn, it must choose whether it gets a move, an action, or a bonus action; it gets only one of the three. On a successful save, the target takes half as much damage and suffers none of the spell's other effects.

***At Higher Levels.*** When you cast this spell using a spell slot of 3rd level or higher, you can target one additional creature for each slot level above 2nd. The creatures must be within 30 feet of each other when you target them.


#### Thought Shield
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S
- **Duration:** 8 hours
---
You weave a clouding veil over the mind of one creature you touch. For the duration, the target's mind can't be read or detected, creatures can't telepathically communicate with the target unless the target allows it, and the target has advantage on saving throws against any effect that would determine whether it is telling the truth.


#### Warding Bond
*2nd-level abjuration*
___
- **Casting Time:** 1 action
- **Range:** Touch
- **Components:** V, S, M (a pair of platinum rings worth at least 50 gp each, which you and the target must wear for the duration)
- **Duration:** 1 hour
---
This spell wards a willing creature you touch and creates a mystic connection between you and the target until the spell ends. While the target is within 60 feet of you, it gains a +1 bonus to AC and saving throws, and it has resistance to all damage. Also, each time it takes damage, you take the same amount of damage.

The spell ends if you drop to 0 hit points or if you and the target become separated by more than 60 feet. It also ends if the spell is cast again on either of the connected creatures. You can also dismiss the spell as an action.


#### Warding Wind
*2nd-level evocation*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** V
- **Duration:** Concentration, up to 10 minutes
---
A strong wind (20 miles per hour) blows around you in a 10-foot radius and moves with you, remaining centered on you. The wind lasts for the spell's duration.

The wind has the following effects:

- It deafens you and other creatures in its area.
- It extinguishes unprotected flames in its area that are torch-sized or smaller.
- It hedges out vapor, gas, and fog that can be dispersed by strong wind.
- The area is difficult terrain for creatures other than you.
- The attack rolls of ranged weapon attacks have disadvantage if the attacks pass in or out of the wind.



#### Web
*2nd-level conjuration*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S, M (a bit of spiderweb)
- **Duration:** Concentration, up to 1 hour
---
You conjure a mass of thick, sticky webbing at a point of your choice within range. The webs fill a 20-foot cube from that point for the duration. The webs are difficult terrain and lightly obscure their area.

If the webs aren't anchored between two solid masses (such as walls or trees) or layered across a floor, wall, or ceiling, the conjured web collapses on itself, and the spell ends at the start of your next turn. Webs layered over a flat surface have a depth of 5 feet.

Each creature that starts its turn in the webs or that enters them during its turn must make a Dexterity saving throw. On a failed save, the creature is restrained as long as it remains in the webs or until it breaks free.

A creature restrained by the webs can use its action to make a Strength check against your spell save DC. If it succeeds, it is no longer restrained.

The webs are flammable. Any 5-foot cube of webs exposed to fire burns away in 1 round, dealing 2d4 fire damage to any creature that starts its turn in the fire.


#### Wristpocket
*2nd-level conjuration (ritual)*
___
- **Casting Time:** 1 action
- **Range:** Self
- **Components:** S
- **Duration:** Concentration, up to 1 hour
---
You flick your wrist, causing one object in your hand to vanish. The object, which only you can be holding and can weigh no more than 5 pounds, is transported to an extradimensional space, where it remains for the duration.

Until the spell ends, you can use your action to summon the object to your free hand, and you can use your action to return the object to the extradimensional space. An object still in the pocket plane when the spell ends appears in your space, at your feet.


#### Zone of Truth
*2nd-level enchantment*
___
- **Casting Time:** 1 action
- **Range:** 60 feet
- **Components:** V, S
- **Duration:** 10 minutes
---
You create a magical zone that guards against deception in a 15-foot-radius sphere centered on a point of your choice within range. Until the spell ends, a creature that enters the spell's area for the first time on a turn or starts its turn there must make a Charisma saving throw. On a failed save, a creature can't speak a deliberate lie while in the radius. You know whether each creature succeeds or fails on its saving throw.

An affected creature is aware of the spell and can thus avoid answering questions to which it would normally respond with a lie. Such creatures can be evasive in its answers as long as it remains within the boundaries of the truth.


### 3rd level spells
Getting stronger still