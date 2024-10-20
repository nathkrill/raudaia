Scene: [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] and [[Kharb]] arrive at [[Khizdum]]
Altered Scene: Encounter outside [[Khizdum]]. 

```iron-vault-mechanics
oracle-group name="Action and Theme Oracles: New Action and Theme Oracles" {
    oracle name="[Action and Theme Oracles \/ Action](datasworn:oracle_rollable:classic\/action_and_theme\/action)" result="Challenge" roll=63
    oracle name="[Action and Theme Oracles \/ Theme](datasworn:oracle_rollable:classic\/action_and_theme\/theme)" result="Greed" roll=61
}
```


[[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] and [[Kharb]] are just approaching the edge of the refugee camp outside the walls of [[Khizdum]].

`Are things looking better in the city? No`

Things appear more or less as they left them. The city still stands, looking ruined and abandoned. The camp sprawls out from the city across the fields.

They are just about to enter the camp when a group of refugees block their way. They are mostly dwarves, but there are a couple of humans among them as well.
One of them, a chunky looking dwarf with a red beard that is knotted and tangled with dirt, steps forward. He has a jagged knife in his belt. The rest of his clothes are tattered. He's got a few bruises on his face and arms.

>"Ye've gotta pay tha tax to enter [[Khizdum]], friends."

Quentin looks at [[Kharb]], grins, and looks back at the dwarf.

>"Well, [[Kharb]], looks like [[Kirad]] has really let himself go recently, collecting taxes in the slums. Perhaps he finally realised his dream of becoming a fat and lazy bandit?"

There are some chuckles. The dwarf is indignant and draws his knife.

>"I'm serious! Hand over ye gold!"

Quentin steps right up to him, staring him down.

>"Now I know for a fact that you don't have any authority to claim any of my gold here. In fact, I know you're stinking life can't get much worse. So I won't feel bad about cutting your throat and releasing you from your pathetic existence."

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Iron" action=4 adds=0 stat=2 vs1=7 vs2=9
}
```

>"You can't talk to me like that! I'll gut you!"

```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Heart" action=1 adds=0 stat=2 vs1=5 vs2=5
    track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 28 - Brutes.md|Scene 28 - Brutes]]" status="added"
}

```

The dwarf plunges the knife towards Quentin's stomach.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "Goblin"
    roll "Edge" action=6 adds=1 stat=3 vs1=3 vs2=3
}
```

Quentin jumps back, avoiding the blade. He grabs the dwarf's wrist and twists the knife out of his grip. He pushes the dwarf back with a kick.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Iron" action=5 adds=1 stat=2 vs1=1 vs2=9
}
```

Quentin then throws the knife at one of the goons behind the dwarf.


```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=2 vs2=5
    burn from=7 to=2
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 28 - Brutes.md|Scene 28 - Brutes]]" rank="troublesome" steps=2
}

```

The human companion of this robber falls dead with the blade in his chest.
Quentin leapfrogs over the dwarf and send out the other two daggers while in the air.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=8 vs2=5
}
```

The dagger miss their mark and Quentin lands behind the dwarf, who turns around and punches Quentin in the back. The other robbers rush and grab [[Kharb]].

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=3 adds=0 stat=2 vs1=5 vs2=2
}
```

Quentin lurches forward and spins on the spot. The dwarf goes for a kick at his leg.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=5 adds=1 stat=3 vs1=9 vs2=1
}
```

Quentin spins and grabs the leg, twisting the dwarf away from him.
The other robbers now have drawn daggers and are holding them at [[Kharb]].

>"Don't move! We'll cut his throat!"

Quentin lets the dwarf fall and raises his hands.

`Do they stop the fight? Yes`

The dwarf stand and leans into Quentin's ear.

>"That's right, you stop right there. No sudden moves and we'll see what's in your pockets, shall we?"

The dwarf reaches into Quentin's pouch and starts rummaging for coin.
Quentin stealthily places his feet between and behind the dwarf's legs, ready to try something.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=2 adds=1 stat=3 vs1=5 vs2=3
}
```

Quick as a flash, Quentin whips around and flips in the air, spinning the dwarf forwards.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "advantage"
    add 1 "acrobat"
    roll "Iron" action=5 adds=2 stat=2 vs1=10 vs2=3
}
```

The dwarf stumbles forwards and into his men, knocking [[Kharb]] away to the side.

`Have any guards heard the commotion? No`

The robbers pick themselves up and one of them reaches for [[Kharb]] who is trying to crawl away.
Quentin leaps and puts himself between [[Kharb]] and the robbers.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=3 vs2=8
}
```

[[Kharb]] uses the opportunity to get to his feet and start running, shouting for help.

The robber who was grabbing [[Kharb]] swings his dagger at [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]], Quentin tries to grab his arm.

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Iron" action=5 adds=0 stat=2 vs1=5 vs2=2
}
```

Quentin grabs his arm and spins, sinking a dagger into his chest.

```iron-vault-mechanics
progress from=24 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 28 - Brutes.md|Scene 28 - Brutes]]" rank="troublesome" steps=1
```

Letting the body fall, Quentin now faces the remaining two - their leader and a wiry dwarf companion.
Quentin steps back a bit, goes into a spin and flips, letting loose the daggers.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=9 vs1=3 vs2=8
}
```

They both find their mark, and the robbers slump to the ground.

Without acknowledging them at all, Quentin turns and starts walking across the encampment. 

He is looking around for [[Kharb]]. 

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=4 vs2=9
}
```

Quentin doesn't spot [[Kharb]], but he does see a [[Khizdum]] guard coming out of a large tent.

He calls out across the way.
>"Hey there! Have you seen [[Kharb]]?"

The guard stops suddenly as if caught in something. He's a younger, light haired dwarf. Quentin can't help but notice he's trying to cover the tent entrance as best he could. 

The guard eyes Quentin up. 
>"Kharb? No, haven't seen him in a while. He's off on some trip, last I heard. Check with [[Khola]]."

Quentin nods. 
>"Thanks. I'm Quentin by the way. What was your name?"

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=5 vs2=4
}
```

>"I... I'm [[Tofhur]]. Nice to meet you Quentin."

He looks around bashfully, as if trying to find an excuse to send Quentin away. 

Quentin leans forwards and lowers his voice. 
>"What's in that tent?"

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=2 vs2=8
}
```

[[Tofhur]] looks panicked. 
>"Why do you want to know?"

>"Oh I'm just curious, you seem quite protective."

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=3 vs2=2
}
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    add 1
    roll "Wits" action=4 adds=1 stat=1 vs1=4 vs2=3
}

```

[[Tofhur]] looks left and right, then pulls the tent flap aside and quickly ushers Quentin in. 
>"Quick, come in and see for yourself." 

The tent is a large bell tent. Around the edges there are several benches, each with various members of the guard, as well as a few muscular civilians sitting around. 
In the center is a thick roped circle. The muddy ground is marked with boot prints and blood. 
It's clear to Quentin that this is a fighting ring. Looking around he can also see a desk with bags of coins resting on it. 

[[Tofhur]] turns to Quentin. 
>"We had this set up properly in the city before it was ruined. It's quite a good way to get practice and coin, so we thought it was important to keep things running."

Quentin looks around in awe, then back at [[Tofhur]]. 
>"Are you in charge of this?"

[[Tofhur]] points at a portly half-elven woman who is sitting behind a bench, scrawling in a ledger. 
`is she part of the order? No`

>"That's [[Lendis Suldusk|Lendis]], she's in charge. If you wanna fight or place a bet, talk to her."

At the mention of her name, [[Lendis Suldusk]] stands up. 
>"Who's that there, [[Tofhur]]? Bring him over, sweetie."

[[Tofhur]] cocks his head at Quentin. Quentin strides over to the desk. 

>"[[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]], nice to meet you madame [[Lendis Suldusk|Lendis]]."

>"Ooh you're charming! A bit small, but you have the air around you. Looking for a fight?"

Quentin puts his hands flat on the desk and leans in, grinning. 
>"I'd be interested, but I have an errand to run. But I'd like to register and come back later, if that's how things work."

`is there a registration? No`

[[Lendis Suldusk]] laughs. 
>"Oh nothing so formal, dearie! Just pop by when you're in the fighting spirit and we'll get you in the ring."

As she stands, people are starting to gather around the edge of the rin. It looks like a fight is about to start. 
>"I don't want to miss this one, see you soon!"

She waves her chubby hand and rushes forward to the front of the crowd and begins addressing them as Quentin steps out of the tent. 