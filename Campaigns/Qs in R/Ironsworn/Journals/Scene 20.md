Scene: Quentin leaves for [[Hitching]]
Altered scene: Quentin gets a guide 

```iron-vault-mechanics
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=8 vs2=5
}
```

There are little resources here in [[Khizdum]] that actually help me, so I make my way to the gates. I'm just about the head off. 

> "Wait! Don't go just yet!"

`Is it one of the guards? Yes

I turn to see one of the guards from the triangle running up behind me. It's one of the archers from the roof. 

> "[[Khola]] sent me to come with you. My name's [[Kharb]]."

> "An escort? I didn't think [[Khola]] had any men to spare on a journey like this."

> "Well... It's kinda of embarrassing but I'm not much use around here. And I wouldn't do well on this journey alone. So [[Khola]] sent me to accompany you."

> "Why you? If you're no use?"

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=6 vs2=5
}
```

He looks at the ground. 

> "I... I don't know, I'm just following orders."

He seems equipped well enough, with a bow and plenty of arrows. He's young, probably his inexperience is why he's being sent out. 

> "Fine. Let's get going."

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Journey to Hitching.md|Journey to Hitching]]" status="added"
```

We track through the tent city outside the ruined gates and head north, into the cold wastes. 

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=8 vs2=4
}
```

We go on through the wastes, eventually skirting the north edge of the western peak. 

```iron-vault-mechanics
progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Journey to Hitching.md|Journey to Hitching]]" rank="troublesome" steps=1
```



> "Our supplies might not last the journey. Are you any good with that bow? Let's try hunting for some food."

[[Kharb]] nods, and strings his bow. 

```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    add 1 "Kharb"
    roll "Wits" action=1 adds=1 stat=1 vs1=9 vs2=6
}
```

Unfortunately, we don't find any life in the frozen climate around us. We keep going.

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=2 vs2=4
}
```

We curve around the northern edge of the mountain, coming out onto the plateau.

```iron-vault-mechanics
progress from=12 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Journey to Hitching.md|Journey to Hitching]]" rank="troublesome" steps=1
```



> "One last leg, hopefully."

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=4 vs2=10
}
```

We continue south, pushing against the cold wind that whips around the mountain. 
Suddenly, [[Kharb]] gives a cry as he steps into a bank of snow which gives way beneath him. He tumbles down a hidden crag and out of sight. 

> "[[Kharb]]!"

I rush over to the gap between the drifts and peer down. 

`is he hurt? No`

> "I'm okay [[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]]. But I can't see an easy way out."

I check my pack to see if I have a rope I could use to pull him out.

```iron-vault-mechanics
move "[Check Your Gear](datasworn:move:delve\/delve\/check_your_gear)" {
    roll "Supply" action=6 adds=0 stat=1 vs1=3 vs2=9
}
```

I pull out a rope and toss it down to him. I wrap the rope around my waist and tie it to a nearby rock. 

```iron-vault-mechanics
move "[Aid Your Ally](datasworn:move:classic\/relationship\/aid_your_ally)"
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=6 vs2=8
}

```

[[Kharb]] grabs the rope and starts pulling himself up. But then the rope slips from the rock and I stumble forward, also falling into the hole!

I try to slow my fall by leaning into the wall. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=4 adds=1 stat=3 vs1=8 vs2=9
}
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=6 adds=0 stat=2 vs1=2 vs2=1
}

```

I hit the ground. The snowy floor stops any significant harm. I get to my feet and look around. 

`is there a way out without climbing? Yes`

At the far end of the pit there's a small cave. I grab [[Kharb]]'s arm and we go through. 

