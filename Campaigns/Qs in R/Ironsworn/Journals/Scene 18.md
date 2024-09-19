```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    add 1 "Bond"
    roll "Wits" action=4 adds=1 stat=1 vs1=2 vs2=8
}
```

Scene: Quentin starts his journey north
Expected scene

Having taken a look at a map, I decide to take a different approach to what [[Kater]] suggested.
I'd rather not go south into [[Gafranthel]] given my history there, so instead I head north, hoping to stay in the [[Emerald Coast]] for a while then head west once I've gotten far enough north to clear the [[Starved Wastes]].

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Journey to Khizdum.md|Journey to Khizdum]]" status="added"
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    add 1 "bond"
    roll "Wits" action=2 adds=1 stat=1 vs1=3 vs2=8
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Journey to Khizdum.md|Journey to Khizdum]]" rank="dangerous" steps=1
}

```

I travel for 5 days and eventually reach [[Nealin]]. There I try to resupply a little.

I find a supply store and tell the purveyor the cause I am serving.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Heart" action=1 adds=0 stat=2 vs1=5 vs2=10
}
```

"Sounds unlikely coming from a Goblin. Be on your way, or I'll call the guards!"

The reception there is unfriendly in general, so I camp outside the town.

```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=1 adds=0 stat=4 vs1=10 vs2=3
}
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    add 1 "prepared"
    roll "Wits" action=1 adds=1 stat=1 vs1=8 vs2=2
    progress from=8 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Journey to Khizdum.md|Journey to Khizdum]]" rank="dangerous" steps=1
}

```

I carry on the journey and make it to [[Iuneleltheas]], using more of my supplies. I try again to restock, being clear of my goal.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Heart" action=4 adds=0 stat=2 vs1=9 vs2=9
}
```

Whilst I am pushing my way through a crowded market square, I suddenly realise that my satchel has been slashed open, and some of my supplies are gone!
I give up on the market and find a place to stay.

```iron-vault-mechanics
move "[Sojourn](datasworn:move:classic\/relationship\/sojourn)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=10 vs2=3
}
```

The landlord of the inn I find myself in is a very welcoming elf fellow. He lets me take what I need from his pantry before I carry on with my journey.
It is here that I leave the jungle trails and head south into the wilds.
It gets colder as I begin to climb into the [[Witenspire Mountains]].

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=7 vs2=7
}
```

I'm walking up a narrow craggy vale, when I see a figure on the road ahead of me. It's just a silhouette at first but as I get closer I see that it's a hulking, grim orc. I slowly stop, and turn to go back.
That's when I notice two more behind, who appear to have been following me!

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 18 - Orcs in the mountains.md|Scene 18 - Orcs in the mountains]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=1 vs2=8
}

```

Very quickly, I leap at the sloped cliff to one side, and try to get higher ground.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "agile"
    roll "Edge" action=1 adds=1 stat=3 vs1=8 vs2=2
}
```

The orcs rush to the base of the cliff and gather there below me. One of them throws a rock at me.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=6 adds=1 stat=3 vs1=2 vs2=9
}
```

I swing on a small branch as the stone whizzes by. Using the momentum, I draw the daggers and let myself fall onto the shoulders of one of the orcs.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "agile"
    roll "Iron" action=6 adds=1 stat=2 vs1=8 vs2=2
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 18 - Orcs in the mountains.md|Scene 18 - Orcs in the mountains]]" rank="troublesome" steps=1
}

```

The orc falls immediately. I spin and swing the ribbons with the daggers.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=6 vs1=4 vs2=7
}
```

They expertly slice the throats of the orcs, and they fall down dead. Their cries echo across the ravine. I hear an answering call: More orcs! I need to move quickly.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=7 vs2=1
}
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=4 adds=0 stat=2 vs1=9 vs2=4
}

```

I come out of the ravine and into a wide, cold wasteland. I need to press on.

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=5 adds=0 stat=1 vs1=5 vs2=6
    progress from=16 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Journey to Khizdum.md|Journey to Khizdum]]" rank="dangerous" steps=1
}

```

The journey is tough. A cold wind batters my face and it takes me longer than it should to make progress.
I try to find a sheltered spot to make camp.

```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=4 adds=0 stat=4 vs1=6 vs2=8
}
```

In the morning, I try to find raised ground to see how close I am to [[Khizdum]].

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=5 adds=0 stat=1 vs1=10 vs2=7
}
```

I do find a raised hill, but there is a foggy haze on the horizon. I can't even see the peaks of the [[Witenspire Mountains]]. I sigh and press on.

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=2 adds=0 stat=1 vs1=10 vs2=10
}
```

The fog thickens as I keep going. Eventually it begins to clear... But as it does I notice the icy ground beginning to give way. Then I notice the sun behind me. I'm heading in the wrong direction!
I right myself and keep going.

```iron-vault-mechanics
move "[Undertake a Journey](datasworn:move:classic\/adventure\/undertake_a_journey)" {
    roll "Wits" action=5 adds=0 stat=1 vs1=4 vs2=4
}
```

This time I have more luck. The peaks of the mountains crest over the fog and I have a good frame of reference as I pass between the eastern two. I find a sheltered bit of low ground to walk in.

```iron-vault-mechanics
progress from=24 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Journey to Khizdum.md|Journey to Khizdum]]" rank="dangerous" steps=1
move "[Reach Your Destination](datasworn:move:classic\/adventure\/reach_your_destination)" {
    progress-roll score=8 vs1=3 vs2=10
}

```

I see the smoke before I see the city. AS I come closer, I can see that some of the walls have been smote down. There are buildings in ruin and many of the town's occupants are in tents outside the city walls.
I don't come very close before I'm approached by a band of dwarf guards.

"Halt! Don't come any closer." Two of them draw bows. "State your business in [[Khizdum]]."

"I've come from [[Issren]]. I have a message from the captain of the guard there. Is there someone in charge I can speak to?"

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=9 vs2=5
    burn from=6 to=2
}
```

"[[Issren]] eh? Well, we were wondering if you'd ever show up. But looks like you haven't if it's just a scrawny goblin that's come."
The guard spits on the ground then waves a hand. "Come, we'll take you to the commander."