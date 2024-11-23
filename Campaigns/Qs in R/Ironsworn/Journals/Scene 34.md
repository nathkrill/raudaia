Scene: [[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin McQuall]] comes to with the group under attack
Altered Scene: Quentin comes to first

>"Quentin?"

Quentin comes to, his vision blurred. He focusses to see [[Khola]] crouched over him, her hand on his arm.

>"Uugh. That hurt. Everything okay?"

[[Khola]] smiles.
>"Everything's wonderful. You did great, Quentin. We've killed the [[Wahashka]] and [[Khizdum]] is saved!"

Quentin sits up, rubbing his bruised torso. He looks around. They are still in the circle of small banks. The ruined corpse of the [[Wahashka]] lies a short way off. It's black blood stains the snow, as well as Quentin's clothes and skin.

[[Khola]] moves her arm to his shoulder. 

>"Stay put for a moment. We're just lighting a fire to burn the corpse.
>I've also sent some men to let the rest of the city know that it's safe now."

She stands and turns towards the soldiers, who are cutting and piling branches around the massive black body of the [[Wahashka]].

```iron-vault-mechanics
move "[Heal](datasworn:move:classic\/adventure\/heal)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=2 vs2=6
}
```

Quentin sits and watches as they burn the body. Thick, acrid smoke rises up from the blaze as the corpse shrivels and turns to ash.

`Does the ambush happen now? No`

After a while, Quentin stands and joins [[Khola]] as she supervises the bonfire. She slowly starts sending soldiers back to the city as they regain their strength after the harrowing battle.

As she stares into the blaze, she speaks.

>"Thank you, Quentin. We couldn't have done this without you. You put yourself in harm's way yet again to try to save the people of our city. You have our gratitude. I'll see to it that [[Kirad]] hears about this and you are suitably rewarded."

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Kill the Wahashka.md|Kill the Wahashka]]" status="added"
progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Kill the Wahashka.md|Kill the Wahashka]]" rank="formidable" steps=10
move "[Fulfill Your Vow](datasworn:move:classic\/quest\/fulfill_your_vow)" {
    progress-roll score=10 vs1=8 vs2=5
    track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Kill the Wahashka.md|Kill the Wahashka]]" status="removed"
}

```

Quentin turns to look at her.
>"Thank you [[Khola]]. It's been actually kind of fun, running around here. I... think I might stay for a little while. If you find anything useful for me to do, I'd be grateful.
>But remember, I'm not a solider!"

[[Khola]] laughs.

`does the ambush happen now? Yes!`

At that moment, there's a loud noise. Several shapes come crashing through the trees. Arrows fly and hit some of the soldiers.

`imitate conflict`

`is this to do with the dwarves at the cities edge before? no`

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 34 - Ambush.md|Scene 34 - Ambush]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=8 vs2=5
}

```

Quentin and [[Khola]] are rushed by two short individuals with hoods and knives. One tries to tackle him to the ground. The other makes a swipe at [[Khola]]

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=4 adds=1 stat=3 vs1=1 vs2=4
}
```

Quentin ducks and rolls out of the way of his attacker. He tries to barge into the other and throw him off his attack on [[Khola]].

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Iron" action=2 adds=0 stat=2 vs1=1 vs2=3
}
```

He knocks them and they tumble to the side of [[Khola]]. She stabs at him with her sword and he lies still.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=2 vs2=7
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 34 - Ambush.md|Scene 34 - Ambush]]" rank="dangerous" steps=1
}

```

The first individual throws his knife towards Quentin, who tries to slide out of the way.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=5 adds=1 stat=3 vs1=10 vs2=7
}
```

It just misses Quentin, some of his hair floats gently to the ground. The attacker charges at Quentin again trying to tackle him, while another circles behind [[Khola]], drawing her attention away.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=10 vs2=1
}
```

Quentin leapfrogs over the charging figure, but loses his balance and falls down. [[Khola]] faces off with her new opponent.

Quentin's attacker goes and grabs his thrown dagger from the ground. This gives Quentin a moment to get to his feet and eye up his opponent.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=7 vs2=1
}
```

He then runs towards Quentin and tries another stab at him. Quentin holds his daggers and spins, trying to stab at his back while he passes.

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    add 1 "acrobat"
    roll "Iron" action=1 adds=1 stat=2 vs1=3 vs2=6
    burn from=8 to=2
    progress from=8 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 34 - Ambush.md|Scene 34 - Ambush]]" rank="dangerous" steps=1
}

```

Quentin narrowly dodges the attack and plunges a blade into his attacker, who cries out in pain then hacks at Quentin's arm.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Iron" action=5 adds=0 stat=2 vs1=6 vs2=10
}
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=8 vs2=8
}

```

Quentin manages to grab the arm, but they are now locked face to face with each other. Quentin's attacker goes for a headbutt.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=3 vs2=1
}
```

Quentin uses the movement to pull down and slide beneath their legs. He kicks upwards as he does.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=3 vs2=10
    progress from=16 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 34 - Ambush.md|Scene 34 - Ambush]]" rank="dangerous" steps=1
}

```

The attacker cries out in pain, turns and throws the dagger again at Quentin.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=5 adds=1 stat=3 vs1=1 vs2=7
}
```

Quentin grabs the dagger mid-air and tries to throw it back.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=6 vs1=5 vs2=8
}
```

The dagger flies and cleaves through his face. He falls down dead.
Quentin looks up and the other attackers are fleeing back west where they came from.

`Did [[Khola]] do okay? No`

[[Khola]] lies wounded on the ground. Quentin rushes over to her.

>"Quick! After them!"

Quentin looks at the figure vanishing into the pines.
>"Are you sure? Is it worth it?"

>"Yes, that's an order! Go!"

Quentin grimaces, then turns on his heels.
>"I'm not a soldier!"
He cries over his shoulder as he pursues them.

The attackers have put quite a distance between them and have disappeared into the trees. Quentin searches around for signs of their direction.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=2 vs2=6
}
```

The tracks are confused and chaotic, but lead in a general direction. Quentin follows deeper into the woods.

Eventually a break in the trees appears before him. Quentin sees a large clearing in the woods with a large house, a paddock, and a small patch of tilled earth.

He thinks for a moment...
>"This must be [[Gnawr]]'s farm!
>Perhaps I can secure his lost item for him."

Quentin gets low and creeps up to the house scanning for lookouts.
```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=6 adds=0 stat=3 vs1=10 vs2=6
}
```

`are there guards? No`

There's no-one outside the house. Quentin creeps forwards, looking at the ground for traps.

`are there traps? No`

He reaches the wall of the house. He peers in through the window.

`are the attackers inside? No`

He doesn't see anyone inside the entry hall, but looks for signs where they might be.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=5 vs2=10
}
```

There are several doors off the side of this chamber. They must be in one of them.

`does the window open? No`

Quentin creeps around to the front of the house. He carefully tries the door.

`Is the door locked? No`
`Is the door trapped? No`

The door opens with no effort. Quentin pushes it wider and slips in.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Shadow" action=3 adds=0 stat=3 vs1=4 vs2=3
}
```

He slips through the door silently.



There's a door off to the back left. Quentin creeps towards it and listens behind it.

`is there anyone there? Yes`

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=9 vs2=3
}
```

Quentin thinks he hears something, but on listening harder he can't hear any more.

`is the door locked? no`

He pushes the door open and peers into the hallway.

`Is someone there now? No`

Quentin creeps along the hallway to the junction and peers around the corner. To the left is a dead-end - a nook with ornate but dusty artwork. There is also a plinth in the shadowy alcove.

`Is there anything there? No`

The plinth appears empty. To the right the passage continues with a door on the right wall. There is also a door behind Quentin on the right hand wall of the passage.

Rather than push back Quentin carries on. He goes down the right fork and listens at the door.

`is there anyone there? Yes`

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=1 adds=0 stat=1 vs1=5 vs2=9
    burn from=8 to=2
}
```

Quentin hears the sound of footsteps. He can't tell if they are coming closer or going further away. He jumps back from the door and waits on the hinge side in case someone comes through.

`Do they come through? Yes`

The door creaks open. A hooded head peeks out and looks down the hall. Quentin readies a blade and goes for the neck.

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 34 - Ground floor.md|Scene 34 - Ground floor]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Shadow" action=4 adds=0 stat=3 vs1=9 vs2=10
}

```

But the small person leaning out notices Quentin first. They pull back and slam the door open onto Quentin.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Iron" action=6 adds=0 stat=2 vs1=8 vs2=4
}
```

Quentin manages to avoid getting slammed and pulls away from the door. As the figure pulls out their dagger, Quentin rushes in to silence them.

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Iron" action=1 adds=0 stat=2 vs1=5 vs2=5
}
move "[Pay the Price](datasworn:move:classic\/fate\/pay_the_price)"

```

The dagger is drawn and holds Quentin at bay. The figure shouts with a nasal voice.

>"They're here! Downstairs, quickly!"

The sound of footsteps on stairs comes through the open door. Quentin backs up to the wall as the figure approaches with their dagger and lunges in with a stab.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=10 vs2=4
}
```

Quentin spins to the side and grabs their arm as the blade thrusts forwards. He misses the arm, but moves aside from their attack. The footsteps on the stair get closer.

Quentin's attacker goes to grab Quentin. Quentin kicks off the wall to get around and hold them himself.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=2 adds=1 stat=3 vs1=3 vs2=8
}
```

He rolls behind them, but cannot get a hold on them. They turn and strike as Quentin goes for a stab at their lower back.

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Iron" action=2 adds=0 stat=2 vs1=6 vs2=5
}
```

They smack Quentin in the side of his head. Stars fly and things go out of focus for a moment.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=1 adds=0 stat=4 vs1=3 vs2=10
}
```

Two more bandits join their companion in the hallway, with Quentin held in the corner.

Quentin tries to dash between them with a springing leap.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=4 adds=1 stat=3 vs1=1 vs2=3
}
```

He gets around them as they close in. He then barges one to push him into the other.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Iron" action=1 adds=0 stat=2 vs1=2 vs2=1
}
```

They tumble into each other, getting tangled in the corner. Quentin flails his ribbons to further tangle them up.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=9 vs2=7
}
```

They manage to push through the ribbons, once again facing off against Quentin.

The closest tries to reach out and grab Quentin, who leaps back and attempts to flee.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=8 vs2=8
}
```

Quentin leaps back and is ready to leg it, but the one who attacked him trips over his ally's foot and falls to the ground infront of him. Quentin takes the opportunity to finish him off.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "floored"
    roll "Iron" action=1 adds=1 stat=2 vs1=1 vs2=3
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 34 - Ground floor.md|Scene 34 - Ground floor]]" rank="formidable" steps=2
}

```

Using this surprising turn of events, Quentin uses the fallen attacker as a springboard and leaps above the remaining enemies.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "acrobat"
    roll "Edge" action=3 adds=1 stat=3 vs1=3 vs2=4
}
```

He comes down with both daggers at the closest one.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    roll "Iron" action=1 adds=1 stat=2 vs1=3 vs2=7
    progress from=8 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 34 - Ground floor.md|Scene 34 - Ground floor]]" rank="formidable" steps=1
}

```

He cries out as Quentin lands on him, daggers piercing into his shoulders. He is wounded but not down just yet. 
His friend swings a long club at Quentin sitting on top of his friend. Quentin leaps off in a backflip.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=5 vs2=10
}
```

Quentin doesn't quite make the flip, and lands on his knees. The two foes surround him.

As they both strike down, Quentin rolls aside, trying to get beneath their legs.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=10 vs2=8
}
```

He dodges the blows but stays between them. He does manage to get to his feet.

They go in again, this time one after the other. Quentin does a classic and tries to jump onto an arm as it lunges forward.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=3 vs2=6
}
```

Quentin jumps up above the attacks and comes down again, right between them. They close in to restrain him.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=6 vs2=9
}
```

They grab Quentin and each hold him tightly by one arm. Quentin strains against them, using all the strength and wiles inside of him.

```iron-vault-mechanics
move "[Turn the Tide](datasworn:move:classic\/combat\/turn_the_tide)"
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "danger sense"
    add 1 "turn the tide"
    roll "Edge" action=2 adds=2 stat=3 vs1=8 vs2=4
}

```

Quentin breaks free, stumbling forward with them behind him. Avoiding their attacks, he tries to make a run for it.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=4 adds=0 stat=3 vs1=3 vs2=5
}
```

He breaks away and starts making for the farmhouse door.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=9 vs2=1
}
```

They pursue, almost catching up to him as he reaches the entry room. He dives away from them again.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=4 adds=1 stat=3 vs1=8 vs2=8
}
```

This time they grab his feet and he crashes to the ground. One gets on top of him and they hold him there.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=3 vs1=3 vs2=7
}
```

`Are they the only ones remaining? Definitely not`
`Are there two more? Yes`

>"Boss! We got him!"

One cries back towards the hallway. After a moment two more bandits arrive. One has a stronger air about him, the others look to the scruffy yet powerful man.

`Do they choose to kill Quentin? No`

>"A hostage? Excellent. He's clearly important to [[Kirad]]. Let's see if we can use him to get ourselves a bargain.

Quentin squirms and tries to speak, but a rag is stuffed into his mouth.

>"Put him in the workshop. Lock the door."

Quentin is dragged out to the stairs and thrown down. Then he's taken through some doors to a large stone-floored workshop. There's an empty workbench and straw and sawdust hanging in the air.

He's pushed in, then his arms and legs are tied so he's on his knees, unable to move. The cloth gag is reinforced with rope. The door is bolted behind the bandits as they leave.