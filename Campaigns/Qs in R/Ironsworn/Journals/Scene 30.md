Scene: [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] and [[Kharb]] enter the fighting ring

They come to the large tent. Quentin strolls in, confidently pushing aside the tent flaps. Inside is the familiar scene of gathered spectators. 
[[Kharb]] follows sheepishly. 
`is there a fight in progress? No`

The ring is currently empty. Quentin swaggers up to the desk to talk to [[Lendis Suldusk]]. 

`is she there? Yes`

She sees him coming and sits up in here chair. 
>"Ah the handsome young goblin returns. Ready to take part this time?"

Quentin sits perched on the edge of the desk. 
>"Of course! I wouldn't want to keep you waiting.
>Oh and this is my friend, [[Kharb]]. You gonna fight too, buddy?"

[[Kharb]] lingers behind Quentin. 
>"He..Hello. Sorry but I think I'll just watch, Quentin."

[[Lendis Suldusk]] chuckles. 
>"It's not for everyone but please relax, take a drinks and enjoy my young friend.
>As for you Quentin, you'd better get ready. You can go in the next fight. But let me explain the rules. 
>You have to put down a fee to enter, but if you win you get all entrant's fees, minus my cut of course. You can also place bets on the fight, but that has to go through me as well. 
>The fight itself is easy. No weapons. First one to submit or go unconscious loses.
>Your first match will be against Odin."

She points to a toned human man, about the same age as Quentin, who is gathered with a small group of similar civilians to one side. She waves to him, and he starts taking off his shirt and stepping into the ring.
Quentin unties the ribbons and hands his daggers over to [[Kharb]] before heading to the edge of the ring himself. 

[[Lendis Suldusk]] gathers the spectators around. They draw in tightly at Quentin's back and side, almost pushing him into the ring. He and Odin face off against each other. Odin has an intense but not aggressive or malicious face. His fists are clenched to his side. 

Lendis raises her hand and screeches.
>"Begin!"

They both lurch forward into the ring as the crowd tightens. 

```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=5 vs2=6
    track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Fight ring - Odin.md|Fight ring - Odin]]" status="added"
}

```

Quentin uses the momentum of the push to spring forward. He steps then goes into a leap, wrapping his legs around Odin's neck. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=1 vs2=7
    burn from=9 to=2
}
```

His legs lock into place and he throws and elbow down onto his head. 

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "adv"
    add 1 "acrobat"
    roll "Iron" action=1 adds=2 stat=2 vs1=6 vs2=7
}
```

As his elbow comes down, Odin raises his arms and catches Quentin's arm. He grabs him and throws his into the muddy floor. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=2 adds=1 stat=3 vs1=1 vs2=6
}
```

Quentin hits the floor and rolls into a crouch. Odin goes for a kick. Quentin tries to spin beneath his kick. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat "
    add 1 "goblin"
    roll "Edge" action=2 adds=2 stat=3 vs1=5 vs2=9
}
```

He just gets under Odin's leg. Odin now stands over him and reaches down to grab Quentin. The crowd are cheering for Odin. Quentin allows Odin to grab his arms but pulls, trying to slide between his legs. 

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    add 1 "acrobat"
    roll "Iron" action=4 adds=1 stat=2 vs1=8 vs2=9
}
```

But Odin is stronger than he looks and pulls Quentin up off the ground and headbutts him. Blood sprays from Quentin's nose. 
Odin throws Quentin to the ground. 
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=6 adds=1 stat=3 vs1=5 vs2=2
}
```

Quentin flips over in the air and lands on his feet. There's a smattering of applause.  
He digs in his feet and goes into a flying kick aimed at Odin's head. 
```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "acrobat"
    roll "Iron" action=6 adds=1 stat=2 vs1=1 vs2=5
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Fight ring - Odin.md|Fight ring - Odin]]" rank="dangerous" steps=2
}

```

His foot catches [[Odin]] right in the side of his face. He is thrown back. In mid-air Quentin spins and brings his other foot around to the back of Odin's head. 
```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "acrobat"
    roll "Iron" action=5 adds=1 stat=2 vs1=1 vs2=1
    progress from=16 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Fight ring - Odin.md|Fight ring - Odin]]" rank="dangerous" steps=2
}

```

His foot connects with the back of Odin's head, and he spits blood out across the ground. 

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=8 vs1=1 vs2=3
}
```

Odin stumbles forward, then collapses face first in the mud. 

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Fight ring - Odin.md|Fight ring - Odin]]" status="removed"
```



[[Lendis Suldusk]] strides into the ring and holds up Quentin's arm. 
>"We have a winner! In his first fight, Mr [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]]!"

The crowd cheer. Some of Odin's friends rush in and carry him over to a corner. 
[[Lendis Suldusk]] leads Quentin back to her desk where she counts out his reward. 
>"Up for another go?"

Quentin winces. 
>"I don't think so, I haven't had a chance to rest at all since I arrived. But perhaps once I'm back to peak performance you'll have a real challenge for me."

He winks at her and turns to find [[Kharb]] and get a drink. 