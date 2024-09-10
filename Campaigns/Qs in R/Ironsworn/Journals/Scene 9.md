Expected Scene: Quentin arrives at the Bumpy Shroom. 
Altered Scene: The tavern is empry

I arrive at the [[Bumpy Shroom]]. As I come closer the door is ajar, but the windows are dark. Before entering, I crouch down and peek through a window.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Shadow" action=4 adds=0 stat=3 vs1=3 vs2=6
}
```

I look in. The tavern lies cold, dark, and empty. I head inside and begin to look around, calling softly for [[Ka'Eek]]. There is no answer.

I go behind the bar and look around [[Ka'Eek]]'s living quarters.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
	roll "Wits" action=2 adds=0 stat=1 vs1=3 vs2=7
}
```

As I look around, it becomes clear that something bad has happened to [[Ka'Eek]]. The place is a mess and there are broken glasses, turned furniture and the rear window is broken.
I go back outside and knock on the door next to the tavern.

_does anyone answer? Yes_

The door opens. "Yes? Can I help you?" Suspicious eyes glare out at me from a half-giantess with extremely long hair.

"Hello, my name's Quentin. I'm just asking about [[Ka'Eek]], next door? Something seems to have happened and I was wondering if you saw or heard something?"

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=5 vs2=1
}
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
	roll "Wits" action=2 adds=1 stat=1 vs1=6 vs2=8
}

```

"Ah yes, I can help you." She replies. "Please come inside." She stands aside to let me pass.
I walk inside and she leads me through her dimly lit home to a rear room with a couch.

"Please, sit down. I won't be a minute." She leaves the room and I hear her go upstairs.

I look around from the couch.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
	roll "Wits" action=6 adds=0 stat=1 vs1=9 vs2=7
}
```

It seems like a fairly ordinary home.

I hear footsteps behind me, and before I can turn to look, there are strong muscular arms wrapped around my face and chest.

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 9 - house ambush.md|Scene 9 - house ambush]]" status="added"
```



```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=4 vs2=7
}
```

Without thinking, I grab the arms and pull myself up onto the shoulders of my attacker.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "agile"
    roll "Edge" action=4 adds=1 stat=3 vs1=3 vs2=3
}
```

with my legs wrapped around their neck, I slip the daggers out and sink them into their eyes.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    roll "Iron" action=4 adds=1 stat=2 vs1=8 vs2=8
    burn from=10 to=2
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 9 - house ambush.md|Scene 9 - house ambush]]" rank="troublesome" steps=2
}

```

They fall backwards and I leap off and stand on the back of the couch, I turn to see the half giantess standing in the doorway behind my attacker, holding a knife.

"You should stop there, lady. This isn't gonna go your way." I say

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=6 vs1=7 vs2=8
}
```

She ignores me and runs forward, swinging the knife. I jump over her head from the couch.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=4 adds=1 stat=3 vs1=10 vs2=10
}
```

I jump, but the knife sticks into my thigh. I yell out in pain and fall backwards into the couch.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=3 vs2=4
}
```

I roll off the couch, then under it towards her legs.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=3 vs2=8
}
```

I slash at her heels from under the couch.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    roll "Iron" action=2 adds=1 stat=2 vs1=5 vs2=2
    progress from=24 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 9 - house ambush.md|Scene 9 - house ambush]]" rank="troublesome" steps=1
}

```

She cries out in pain and falls to her knees. The knife comes at me again under the couch. I roll out the other side.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=6 adds=1 stat=3 vs1=4 vs2=6
}
```

I get up and this time fling the dagger towards her from the other side of the couch.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=9 vs1=4 vs2=8
}
```

The dagger sinks into her arm. She drops the knife.
I leap over and kick it away, then push her to the ground with my knife at her throat.

"What's going on here?" I snarl. "Where's [[Ka'Eek]]?"

_Meaning: Open People_

"Guards took him away." She replies. "[[Sani]] there" (she points at the dead man) "was posted to keep an eye in case you came back."

"And who are you?"

"I'm [[Uanan]]. I sometimes work at the tavern, but I listen out for rumours and pass them on to people who might be interested."

"Let me guess, people like the [[Bandits in the Tunnel]]?"

She nods.

I stand up. This might mean that [[Ka'Eek]] is in the castle. It's going to be hard to get there without interacting with any guards, and the only one I feel like I can trust is [[Kater]].

As I stand, I feel the pain from my various wounds of the day. I should rest up. The [[Bumpy Shroom]] should be a good place, providing there are no other spies.

"Anyone besides you two watching the [[Bumpy Shroom|Shroom]]?" 

_are the the only ones? yes._

"Just us." She nods again.

I look around the house to try to find some rope.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=5 vs2=7
}
```

I find some leather straps on the bed upstairs. I gingerly escort [[Uanan]] up there and fasten her to the bed with a gag. 

"I'll be back for you when I know you won't snitch on me."

I leave and head next door for a rest.

```iron-vault-mechanics
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=5 vs2=6
    burn from=6 to=2
}
```
