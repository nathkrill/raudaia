Expected Scene: Quentin goes to the castle at night
Altered Scene: Quentin goes to the castle in the morning

In the morning, I leave the tavern having slept uneasily and make my way to the castle. Aware that any number of the guards could be after me, I head to the roofs.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "agile"
    roll "Shadow" action=2 adds=1 stat=3 vs1=8 vs2=5
}
```

Leaping from rooftop to rooftop, I arrive near the castle. The large gates are shut tight.
I move to a good vantage point and try to scope out the movement of the guards.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Wits" action=5 adds=0 stat=1 vs1=9 vs2=5
}
```

There are sometimes guards on the walls and in the towers. I know from before that there are guards who tend the gates from the inside.

I move around and find a tower with no guards
```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=2 adds=0 stat=1 vs1=2 vs2=8
}
```

There is one, but I can see along the wall that a guard approaches. I don't have much time.

I leap down to the base of the tower and throw a dagger up like a grapple.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=4 vs2=10
}
```

The dagger holds against something, and I use the ribbon to climb up the side of the tower.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=1 adds=1 stat=3 vs1=3 vs2=4
}
```

I almost fly up the wall and roll into the tower top. The guard is approaching, but hasn't seen me yet.

_Is there a staircase? Yes_

I dart down the staircase before the guard arrives.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=5 vs2=9
    burn from=8 to=2
}
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=6 vs2=9
}

```

This is getting a bit close. I go down the stairs and try to find a room or nook to wait in for a bit.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=1 adds=0 stat=3 vs1=1 vs2=6
}
```

I find a small storage room and sit behind the boxes. I listen carefully for any more guards.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=8 vs2=8
}
```

I hear the noise of several guards marching up and down the hallways. I'm trapped!

_Is there a window? Yes_

_Does it lead inside the castle walls? Yes, random event, move away from a thread: recruit weapon_

Outside the window I see lots of guards marching back and forth between the castle walls and the citadel. They are carrying crates and carts of weapons and armaments.

_Is [[Kater]] there? Yes_

I see [[Kater]] directing her troops by the citadel door. Surely they wouldn't attack me with her right there? I climb out the window and rush over to her.
Several of the guards put the hands on their swords. [[Kater]] sees me coming and waves them down.

"[[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]]? What are you doing sneaking around in here? I don't have time for this."

"It's important, [[Kater]]. Can we talk somewhere private?"

"I'm sorry, now is really not a good time. There's been an attack in the north, we've been called to supply all fighters that we can to lend aid. Word is that some monster from [[Tugar Forest|Tugar]] is rampaging it's way south towards us. Several towns are already destroyed." She stops to give some directions.
"We could really use someone like you for this, [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin]]."

"I'm sorry, [[Kater]] but I'm not a solider. I don't think I'd be much help with something like that, besides, I..."

She raises a hand and cuts me off. 
"If you won't help, please, get out of my way." She waves a guard over. "Please make sure [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin]] here is escorted out of the castle."

She turns and goes inside the citadel.

"This way, sir" says the guard. He is a dwarven fellow. He leads me to the outer gate alongside some of the men carrying weapons. The gate opens and I am ushered out.