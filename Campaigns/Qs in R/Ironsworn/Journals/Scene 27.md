Scene: travel back to [[Khizdum]] 

[[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] and [[Kharb]] head north across the snowy plains. The sun sets and makes the snow glow pink and the sky orange. The mountain looms to their right. 

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=1 adds=0 stat=1 vs1=7 vs2=4
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="Something causes you harm. [Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" roll=69

```

As the sun goes down, the temperature drops. It takes all their energy to walk and shiver. 
```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=1 adds=0 stat=2 vs1=5 vs2=10
}
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=2 adds=0 stat=1 vs1=5 vs2=5
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="You lose something important. -1 Supply" roll=1

```

The snow is now piling up to their waist, then their chest. They are pushing through the deep drifts when Quentin notices that his bag has spilled open, strewing things back across the snow. 

>"Damn it!"

He trawls back a bit to try to find what he's dropped. 

```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=2 vs2=4
}
```

He manages to pick up a bit of what he lost. They keep pushing through the snow. 

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=4 vs2=7
}
```

As they move north, the wind and snow dies down. They find firmer ground. 

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=8 vs2=9
}
```

`is it an ambush? No`

Up ahead of them, Quentin sees a small line of figures moving across the field. They walk up to them. As they get closed the figures clearly spot them and turn and begin charging towards them. 

Quentin grabs [[Kharb]]'s arm. 
>"Oh this isn't good... Quick! Get low and spread out."

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=2 adds=0 stat=3 vs1=4 vs2=2
    track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Orcs in Witenspire.md|Orcs in Witenspire]]" status="added"
}
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Shadow" action=3 adds=0 stat=3 vs1=10 vs2=8
}

```

A band of orcs, dark skinned and angry, welling clubs and crude swords, rush forward and spot the dark shapes in the snowy ground. They circled [[Kharb]] and Quentin. 

Quentin scrambles in the wet ground, trying to slip beyond the circle.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "Goblin "
    roll "Edge" action=4 adds=1 stat=3 vs1=4 vs2=3
}
```

Getting behind two of the orcs, Quentin whips around with his ribbons. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "blade & rope"
    roll "Edge" action=5 adds=1 stat=3 vs1=8 vs2=2
}
```

Now, he flings two daggers their way.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "rope"
    add 1 "advantage"
    roll "Edge" action=3 adds=2 stat=3 vs1=2 vs2=4
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Orcs in Witenspire.md|Orcs in Witenspire]]" rank="dangerous" steps=1
}

```

Quentin then rushes in, springing between [[Kharb]] and the orcs nearest him. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "agile"
    roll "Edge" action=4 adds=1 stat=3 vs1=3 vs2=10
}
```

The orcs charge forward. Kharb and I both defend. 

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    add 1 "kharb"
    roll "Iron" action=2 adds=1 stat=2 vs1=3 vs2=3
    progress from=8 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Orcs in Witenspire.md|Orcs in Witenspire]]" rank="dangerous" steps=2
}

```

Quentin whips around and throws daggers towards the remaining orcs. 

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=6 vs1=5 vs2=5
}
```

They go down as [[Kharb]] also swings his axe, dealing the killing blow to the final orc. 
They both breathe a sigh of relief. 

Quentin checks the orcs for any useful supplies. 

```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=4 vs2=8
}
```

Shouldering their now full packs, they head on. 

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=3 vs2=7
}
```

The terrain begins to descend again. Quentin tries to look around and find a landmark amongst the snow and ice. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=2 vs2=8
}
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=2 vs2=4
}

```

In the lowlands, sheltered by the mountain, they make better progress. 

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=6 vs2=1
}
oracle name="[Travel \/ Opportunities](datasworn:move.oracle_rollable:homebrew\/custom\/travel.opportunity)" result="Your journey is smooth and inspiring. Take +1 momentum" roll=76 {
    - ""
}

```

The road is much easier now. Quentin leads them east along the north edge of the mountain range. The sun shines on the snowy mountain and a beautiful orange glow fills the sky. The snow sparkles and glistens. 

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=5 vs2=9
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="Something causes you harm. [Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" roll=61

```

As they begin to climb again, heading south, the path gets steep. Sharp rocks dig into their hands and feet.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=2 adds=0 stat=2 vs1=3 vs2=4
}
```

They reach a small ledge amongst the sharp stones. 

>"I think we should rest. This is going to kill us if we're not careful."

```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=5 adds=0 stat=5 vs1=4 vs2=4
}
```

Their brief stop here is calm and restful. The views over the northern slopes of the mountain range brings peace and comfort.

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    add 1 "Rested"
    roll "Wits" action=1 adds=1 stat=1 vs1=1 vs2=6
}
oracle name="[Travel \/ Travelled with Wits](datasworn:move.oracle_rollable:homebrew\/custom\/travel.wits)" result="You are lost and do not leave this cell" roll=69

```

The next day, Quentin and [[Kharb]] carry on from their campsite. But soon after, they find themselves lost in the maze of jagged rocks and deep clefts. 

>"We need to get to higher ground."

Quentin attempts to climb on of the spires of rock jutting out from the ground. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "agile"
    roll "Edge" action=5 adds=1 stat=3 vs1=5 vs2=1
}
```

Quentin gets high and is able now to see the mountain as a frame of reference. 

>"It's that way!"

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    add 1 "adv"
    roll "Wits" action=3 adds=1 stat=1 vs1=8 vs2=9
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="You encounter a danger or hazard. Visualize it and how you overcome it before you can roll another [Travel](datasworn:move:homebrew\/custom\/travel)" roll=47
oracle-group name="Action and Theme Oracles: New Action and Theme Oracles" {
    oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Affect" roll=79
    oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Structure" roll=64
}

```

As Quentin climbs down the jagged spike, it begins to shake. A large crack appears at the base and the whole thing starts to topple!

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=2 adds=1 stat=3 vs1=3 vs2=2
}
```

Quentin swings around to the upward side and slides down, flipping off at the end.

He grins at [[Kharb]].
>"That was close!."

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=6 vs2=4
    burn from=5 to=2
}
oracle name="[Travel \/ Travelled with Wits](datasworn:move.oracle_rollable:homebrew\/custom\/travel.wits)" result="Your insight leads you 1 cell in the wrong direction" roll=42

```

They carry on through the snow-covered grass. In all the excitement, Quentin has forgotten which way he was supposed to lead them...

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=1 adds=0 stat=1 vs1=7 vs2=9
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="Something causes you harm. [Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" roll=77
oracle name="[Pay the Price \/ Pay the Price](datasworn:move.oracle_rollable:classic\/fate\/pay_the_price.pay_the_price)" result="It is stressful." roll=70

```

Quentin is getting fed up of all this wandering.
>"We should be there by now! There's no way we've strayed this far from the trail!"

```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=2 vs2=3
}
```

They steel their will and push on.

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=3 vs2=1
}
oracle name="[Travel \/ Opportunities](datasworn:move.oracle_rollable:homebrew\/custom\/travel.opportunity)" result="Your journey is smooth and inspiring. Take +1 momentum" roll=76

```



As thy trudge on, Quentin notices a cave in the edge of a slope in the mountain.

>"Let's take a look. Better than wandering around pointlessly in the wilderness."

The cave is a beautiful ice cave. The walls glitter and shimmer as if they are made of stars. They follow it along, not deviating from the main tunnel. Soon they see the light of an opening ahead of them. They come out beneath tall pines against the rise of the mountain slope.
Ahead of them is a familiar sight - There beyond the trees is the city of [[Khizdum]]!

[[Kharb]] is ecstatic to see his home at last.
>"We made it! Let's get in and speak to [[Khola]]."

They hurry out of the trees and across the plain to the city wall.