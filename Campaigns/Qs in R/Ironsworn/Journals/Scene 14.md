Scene: Castle exterior. Expected scene

[[Kater]] gathers her men in various houses the skirt the castle. 

I ask [[Kater]] if there's a back entrance at all into the castle.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=2 vs2=7
}
```

"There is, but it goes right into the barracks. It might be empty if our diversion works. If you don't fancy that, going over the wall's your best bet."

I thank her and clamber over the roofs to the rear of the castle and scope the rear entrance. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=4 adds=0 stat=3 vs1=2 vs2=1
}
```

I watch the entrance closely. It doesn't appear to be guarded. I wait for [[Kater]]'s attack to begin. 

Suddenly, I hear the cry. Soldiers pour out of the buildings and begin an assault on the gate. I wait a few moments to allow the barracks to empty then leap down and dash to the door. 

_is it locked? No_

The door opens with ease. I slip in. 
A stone stairway leads up to a candlelit room. I slowly creep up and peer in. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=5 adds=0 stat=3 vs1=2 vs2=3
}
```

_Is the room empty? Random event pc negative celebrate wound._

I step on a stone slab and suddenly there's a *click*. The step recedes into the floor. An arrow shoots out from a hole to the side. I leap forward up the stairs. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=1 adds=1 stat=3 vs1=7 vs2=5
    burn from=9 to=2
}
```

The arrow clatters against the far wall as I roll into the chamber. It's a dimly lit mess chamber, with a couple of benches and a doused fire. 

_is the room empty? Random event move toward a thread. _

There are no guards in the room, but in a cage in the corner is a familiar mushroom figure crouched on the floor. 

"[[Ka'Eek]]!" I rush over to the cage. "Are you alright?"

He stirs in the cage, rolling over to greet me. 
 *Is he injured? No*

"[[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]]? Oh you've come to get me? Thanks you, thank you!"

"One sec, let me get the lock."

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=1 vs2=6
}
```



```iron-vault-mechanics
move "[Aid Your Ally](datasworn:move:classic\/relationship\/aid_your_ally)"
```

I managed to jimmy the lock open, letting [[Ka'Eek]] out. 

"Quickly, down there and out. Head straight to the [[Bumpy Shroom]] and lock yourself in."

He nods. "Thank you, [[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]]." then runs down the steps.

I go to the door and peer out

```iron-vault-mechanics
move "[Discover a Site](datasworn:move:delve\/delve\/discover_a_site)" {
    track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel.md|Issren Citadel]]" status="added"
}

```

The next room is a long bunkhouse, with beds lining each side.

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Shadow" action=2 adds=0 stat=3 vs1=7 vs2=9
}
```

There are a couple of soldiers sitting on beds having a conversation. There's no easy way through without alerting them.

I roll into the room and throw out my daggers.

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Bunkhouse.md|Issren Citadel - Bunkhouse]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    add 1 "agile"
    roll "Shadow" action=6 adds=1 stat=3 vs1=2 vs2=4
}
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=9 vs2=10
}

```

Both daggers miss their mark. The soldiers stand up and reach for their weapons. They rush me as I try to stand. I roll to the side.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=1 adds=1 stat=3 vs1=6 vs2=6
    burn from=8 to=2
}
```

Instead of hitting me, they bump into each other, stunned for a moment. I throw out the ribbons to tie them together.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "ribbons"
    roll "Edge" action=2 adds=1 stat=3 vs1=1 vs2=6
}
```

The ribbons tangle them up, but they pull them off and move to flank me.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=2 vs2=9
}
```

I settle beneath them, ready to dodge.

They both lunge forward together. I jump towards one, trying to get behind him.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=1 adds=1 stat=3 vs1=9 vs2=6
}
```

As I jump, he tackles me to the ground. The other corrects his strike towards me on the ground.

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=1 vs2=1
}
```

I lift up my dagger, and it catches his wrist, slicing down and causing him to drop his sword.

```iron-vault-mechanics
progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Bunkhouse.md|Issren Citadel - Bunkhouse]]" rank="troublesome" steps=1
progress from=12 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Bunkhouse.md|Issren Citadel - Bunkhouse]]" rank="troublesome" steps=1

```

I take my other dagger and plunge it into the back of the one on top of me.


```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Iron" action=2 adds=0 stat=2 vs1=6 vs2=6
    burn from=7 to=2
    progress from=24 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Bunkhouse.md|Issren Citadel - Bunkhouse]]" rank="troublesome" steps=1
}
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=9 vs1=3 vs2=2
}

```

The soldier releases his grip. I push his body off me and quickly pull my dagger up to the throat of the remaining guy, who his clutching his wounded wrist.

"Don't move, don't make a sound."

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Iron" action=2 adds=0 stat=2 vs1=2 vs2=9
}
```

He falls to his knees. "You'll not get far, there's plenty more of us in here, fool."

"I don't care. This way." I usher him back to the break room.

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Iron" action=2 adds=0 stat=2 vs1=9 vs2=8
}
```

"I don't think so!" He tries to knock my dagger away. I push the dagger forward into his throat.

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Iron" action=6 adds=0 stat=2 vs1=9 vs2=8
}
```

His grip on my arm is strong. He tries to push me back.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=3 vs2=2
}
```

I pull back with his momentum and get on top of him, plunging my dagger into his chest.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=9 vs1=3 vs2=1
}
```

It strikes between his ribs, and blood sputters out and from his mouth.

I climb off and wipe my daggers clean. Looking around the bunkhouse, I see two ways out. I try to visualise where I am, and where might go to more regal quarters.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=2 adds=0 stat=1 vs1=5 vs2=1
}
```

I figure it's the straight on exit. I go up to it and find that it is locked.

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Wits" action=1 adds=0 stat=1 vs1=6 vs2=5
}
```

I try to pick the lock, but I don't succeed. I'll have to go the long way.
I go out the other doorway. It's an open walkway in full view of the castle grounds.

I quickly dash across, hoping noone sees me.

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=3 vs2=10
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel.md|Issren Citadel]]" rank="troublesome" steps=2
}
move "[Reveal a Danger](datasworn:move:delve\/delve\/reveal_a_danger)"

```

At the end of the walkway there is a large portcullis pulled down over the next doorway. There's no way through.

I look up. _Is there a window? Yes!_
There's a window just above it! I climb up.

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    add 1 "agile"
    roll "Edge" action=5 adds=1 stat=3 vs1=1 vs2=4
    progress from=24 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel.md|Issren Citadel]]" rank="troublesome" steps=1
}
move "[Find an Opportunity](datasworn:move:delve\/delve\/find_an_opportunity)"

```

I enter the window and find myself in a vast storeroom with chests of coins. The treasury!
I search around for any papers or evidence.

```iron-vault-mechanics
move "[Locate Your Objective](datasworn:move:delve\/delve\/locate_your_objective)" {
    progress-roll score=9 vs1=9 vs2=1
}
```

I find a bundle of correspondence, some of the letters are signed by [[Enugar]]. Others have the name of the [[Erard Willow|mayor]]! I'm just about to read further when the door opens and [[Enugar]] stands in the doorway.

"You!" He draws his sword.

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Enugar.md|Issren Citadel - Enugar]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=6 vs2=3
}

```

I instinctively throw out my daggers.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=4 adds=0 stat=3 vs1=3 vs2=4
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Enugar.md|Issren Citadel - Enugar]]" rank="dangerous" steps=1
}

```

They each hit his chest. I leap back and whip the ribbons, pulling him down.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "acrobat"
    add 1 "ribbons"
    roll "Edge" action=3 adds=2 stat=3 vs1=6 vs2=10
}
```

He stumbles forward. I circle around to his back.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=5 vs2=7
}
```

The daggers go hard into him.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    roll "Iron" action=2 adds=1 stat=2 vs1=7 vs2=3
    progress from=8 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Enugar.md|Issren Citadel - Enugar]]" rank="dangerous" steps=1
}

```

He cries aloud and spins with his blade. I duck.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=6 adds=1 stat=3 vs1=1 vs2=8
}
```

from low down, I shove both blades upwards into his belly.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Iron" action=6 adds=0 stat=2 vs1=10 vs2=8
}
```

The armour turns back my blades. He grabs my arms with one hand and brings the hilt down with the other.
I try to sweep his legs

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=2 vs2=2
    progress from=16 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Enugar.md|Issren Citadel - Enugar]]" rank="dangerous" steps=1
}

```

He falls down hard, hitting his head on a chest.

```iron-vault-mechanics
progress from=24 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Issren Citadel - Enugar.md|Issren Citadel - Enugar]]" rank="dangerous" steps=1
```

I plunge another dagger into his side.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=8 vs1=3 vs2=2
}
```

He cries out and falls down, dead. I sit back, breathing hard.

I look out the window to try and see what's going on in the courtyard.

_Are they still fighting? Yes_

I take [[Enugar]]'s sword and climb out the window.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=10 vs2=1
}
```

I walk out across the walkway in shout aloud.

"Hear me, soldiers of [[Issren]]! [[Enugar]] is dead. Your struggle is over. Those under his command will surrender or retreat from here, never to return!"

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=4 vs2=10
}
```

The fighting stops and they all turn to face me. I hold [[Enugar]]'s sword aloft. Some of the soldiers begin running out from the citadel away from [[Kater]]'s men. Others start coming towards me. Some arrows are loosed in my direction.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=5 adds=1 stat=3 vs1=3 vs2=10
}
```

A stray arrow hits me.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=2 adds=0 stat=2 vs1=9 vs2=3
}
```

As the fighting continues, I leap down and join the fray.

```iron-vault-mechanics
move "[Battle](datasworn:move:classic\/combat\/battle)" {
    add 1 "loss of troops"
    roll "Heart" action=4 adds=1 stat=2 vs1=4 vs2=1
}
```

We fight hard, but soon enough all of [[Enugar]]'s soldiers are either killed or cornered.

As we start chaining up our prisoners, I look for [[Kater]].

_Is she still alive? Yes!_

I find [[Kater]] surrounded by dead men. She appears to have led a valiant attack.

"[[Kater]]! I cry. Well done. We appear to have succeeded."

"Indeed. Nice job taking out [[Enugar]]. He fled into the castle as the tide was turning."

"We came across each other in the treasury. I think he was going to take some coin and bolt."

"Good job you were there. Did you manage to find any information about the [[Bandits in the Tunnel|Bandits]]?"

"I did. Here are some letters between the [[Erard Willow|mayor]] and [[Enugar]]. I think the [[Erard Willow|mayor]] was playing us all. I haven't read through them properly but this should be enough to arrest him."

"Nice work! I'll get some of my least injured men and we'll arrest him immediately. You should come."

"I feel like this is above me... Besides I want to check on [[Ka'Eek]]."

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=9 vs2=6
    burn from=9 to=2
}
```

"Ok fine. But come back. I'll need you if we're going to rebuild here."

I nod, and make my way out of the citadel towards the [[Bumpy Shroom]].