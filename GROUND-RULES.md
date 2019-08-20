## Core Homebrew
> ### Your Turn - Bonus Actions
> Various class features, spells, and other abilities let you take an additional action on your turn called a bonus action. The Cunning Action feature, for example, allows a rogue to take a bonus action. You can take a bonus action only when a special ability, spell, or other feature of the game states that you can do something as a bonus action. You otherwise don't have a bonus action to take.
> 
> You can take only one bonus action on your turn, so you must choose which bonus action to use when you have more than one available.
> 
> You choose when to take a bonus action during your turn, unless the bonus action's timing is specified, and anything that deprives you of your ability to take actions also prevents you from taking a bonus action.
> 
> &mdash; [PHB, page 189](https://5etools.com/book.html#phb,-1,bonus%20actions,0)

> ### Casting Time - Bonus Action
> A spell cast with a bonus action is especially swift. You must use a bonus action on your turn to cast the spell, provided that you haven't already taken a bonus action this turn. You can't cast another spell during the same turn, except for a cantrip with a casting time of 1 action.
> 
> &mdash; [PHB, page 202](https://5etools.com/book.html#phb,10,bonus%20action,0)

The rules above have been dropped and modified in this homebrew package. In their wake, two new rules have been forged. These changes have been made to empower player choices, and allow interesting techniques in battle.

> ### `brewed` Your Turn - Bonus Action
> Various class features, spells, and other abilities let you use an additional action on your turn called a bonus action. You have one bonus action to use on each of your turns. A bonus action is especially swift, being done concurrently or consecutively with your main action.
> 
> The Cunning Action feature, for example, allows a rogue to use a bonus action. You can use a bonus action only when a special ability, spell, or other feature of the game explicitly states that you do something as a bonus action. You otherwise have nothing to expend your bonus action with.
> 
> You can also use your action to use a spell, ability or feature that normally uses a bonus action. This allows you to take multiple swift motions on your turn.

> ### `brewed` Spellcasting - Casting Multiple Spells
> So long as you have the action economy and spell resources needed to cast spells, you can cast as many spells on your turn as you might want.

## Fighting with Light Weapons
> ### Two Weapon Fighting
> When you take the Attack action and attack with a light melee weapon that you’re holding in one hand, you can use a bonus action to attack with a different light melee weapon that you’re holding in the other hand. You don’t add your ability modifier to the damage of the bonus attack, unless that modifier is negative.
> 
> If either weapon has the Thrown property, you can throw the weapon, instead of making a melee Attack with it.
> 
> &mdash; [PHB, page 195](https://5etools.com/book.html#phb,-1,two-weapon%20fighting,0)

This above rule has been dropped and modified in this homebrew package. In this rule's wake, two others have been added. These changes have been made to empower players who wish to use two-weapon fighting, and allow spellcasters to make offhand attacks with light weapons even after spellcasting.

Apart from these changes, the *Dual Wielder* feat and the *Two-Weapon Fighting* fighting style has been similarly modified in other sections.

> ### `brewed` Two Weapon Fighting
> If you are holding a *light*, *one-handed* weapon in both hands, you can use a bonus action to make one additional weapon attack using one of those weapons. You add your ability modifier to the damage of this bonus attack.
> 
> You can't take this bonus attack if you have already made an attack with a weapon that is neither *light* nor *one-handed*. Once you take this bonus attack, you can only use *light*, *one-handed* weapons to make weapon attacks until the end of your turn.
> 
> Furthermore, neither the bonus attack nor any other attacks on your turn may be *heavy*, even if more specific rules remove prior limitations about *light* weapons.

> ### `brewed` Attacking with Swift Weapons
> This homebrew package comes with a new weapon tag: *swift*. Shortbows and blowguns now have this property.
> 
> Once you make an attack with a *swift* weapon on your turn, you can use a bonus action to make one additional weapon attack using this weapon. You add your ability modifier to the damage of this bonus attack.
> 
> You can't take this bonus attack if you have already made an attack with any other weapon on your turn. Once you take this bonus attack, you can only use the weapon you attacked with to make weapon attacks until the end of your turn.

## Two-Weapon Fighting Style and Dual Wielder Feat

> ### Fighting Style - Two-Weapon Fighting
> When you engage in two-weapon fighting, you can add your ability modifier to the damage of the second attack.
> 
> &mdash; [PHB, page 72](https://5etools.com/classes.html#fighter_phb,f:fighting%20style%201)

> ### Feat - Dual Wielder
> You master fighting with two weapons, gaining the following benefits:
> - You gain a +1 bonus to AC while you are wielding a separate melee weapon in each hand.
> - You can use two-weapon fighting even when the one-handed melee weapons you are wielding aren't light.
> - You can draw or stow two one-handed weapons when you would normally be able to draw or stow only one.
> 
> &mdash; [PHB, page 165](https://5etools.com/feats.html#dual%20wielder_phb)

The above two features have been deprecated, and replaced with two of greater caliber. These bits are some of the greatest buffs to dual wielding and gish fighters in general. Because of the enormous differences in mechanics between this particular ruleset, this needs more playtesting at the moment.

> ### `brewed` Fighting Style - Swift-Handed
> If you use both your action and bonus action to make attacks with **one-handed** weapons, you get one additional weapon attack on your turn. This additional attack has the same weapon restrictions and limitations as your initial attacks.
> 
> You also get two weapon attacks whenever you make an attack of opportunity if you are holding two *one-handed* weapons.

> ### `brewed` Feat - Ambidextrous Warrior
> You become ambidextrous if you are not already, able to control either hand with equal splendor. As a warrior, this grants you greater control in the frey, giving you the following benefits:
> - You can draw or stow up to six weapons when you would normally be able to draw or stow only one.
> - When you make a weapon attack using a bonus action, the weapon no longer has to be *light* if that was a limitation for you. Other weapon attacks made on your turn have this restriction lifted for you as well.
> - While you are holding two *one-handed* weapons that aren't *heavy*, attacks targeting you cannot have advantage.

## Cantrips
> ### Cantrips
> A cantrip is a spell that can be cast at will, without using a spell slot and without being prepared in advance. Repeated practice has fixed the spell in the caster's mind and infused the caster with the magic needed to produce the effect over and over. A cantrip's spell level is 0.
> 
> &mdash; [PHB, page 201](https://5etools.com/book.html#phb,10,cantrips,0)

> ### ~~ClassName~~ Abilities - Cantrips
> At 1st level, you know three cantrips of your choice from the ~~ClassName~~ Spells list. You learn additional ~~ClassName~~ cantrips of your choice at higher levels, as shown in the Cantrips Known column of the ~~ClassName~~ table.
> 
> &mdash; [PHB, page 114](https://5etools.com/classes.html#wizard_phb,f:spellcasting%201)

Cantrips are one of the most heavily modified sections in this homebrew package. The rules of these spells have been abstracted to act much like other spells of 1st level and higher.

These rules above have been dropped and modified in this homebrew package. In their wake, another rule has been added.

> ### `brewed` Spellcasting - Cantrips
> A cantrip is a spell that can be cast at will, without expending a spell slot. Cantrips require little arcane prowess, and can be learnt by anyone who puts the effort in to obtain their power. A cantrip's spell level is 0.
> 
> Cantrips can be learned and prepared alongside normal spells of 1st-level or higher. Damaging cantrips like *fire bolt* no longer increase in power automatically as you gain character levels. Some cantrips can now be overcharged and upcast to higher levels if cast using a spell slot of 1st-level or higher.
> 
> Spellcating classes like *Ranger* and *Paladin* now have access to cantrips. A small selection of cantrips have been added to their respective spell lists.
