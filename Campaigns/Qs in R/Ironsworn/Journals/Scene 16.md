Scene: reunion at the Shroom
Interrupt scene: looters

Around the corner, I see some rather dishevelled looking folk trying to break into the tavern!

Judging by their appearance they must be looters. 

"Hey!" I call out. "Get out of here!"

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=4 vs2=7
}
```

They turn defensively. "This one's ours. Find your own loot. "

"I won't ask again. Move on. "

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Iron" action=5 adds=0 stat=2 vs1=3 vs2=6
}
```

They look at each other, then scatter into the side streets. 

I knock on the door. 
"[[Ka'Eek]]? It's me, [[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]]."

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=10 vs2=3
}
```

I hear a bit of noise within. "There's no use, you can't fool me! Get lost!"

"[[Ka'Eek]], I'm serious! It's me! Open up."

I put my face to the window. [[Ka'Eek]], who is crouching being a table sees me. 

"Oh! Quentin! It is you. I'm so sorry." He opens up the door and lets me in.
"It's a bit of a mess in here, but we'll get things cleared up in no time."

"I'd be happy to help!" I say. 

"Of course! And I'll make sure you have a room of your own and a warm meal whenever you need it. I owe you my life, [[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]]."

```iron-vault-mechanics
move "[Swear an Iron Vow](datasworn:move:classic\/quest\/swear_an_iron_vow)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=1 vs2=4
    track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Clear Issren of Bandits.md|Clear Issren of Bandits]]" status="added"
}
move "[Fulfill Your Vow](datasworn:move:classic\/quest\/fulfill_your_vow)" {
    progress-roll score=10 vs1=7 vs2=5
}
move "[Forge a Bond](datasworn:move:classic\/relationship\/forge_a_bond)" {
    roll "Heart" action=6 adds=0 stat=2 vs1=1 vs2=5
}

```

I spend the next week resting in The [[Bumpy Shroom]]. Trade starts to build up again and the town of [[Issren]] comes back to what it once was. 

```iron-vault-mechanics
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    add 1 "bond"
    roll "Heart" action=3 adds=1 stat=2 vs1=4 vs2=9
}
```

