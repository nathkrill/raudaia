Scene: Quentin and Kharb arrive at [[Hitching]]
Interrupt Scene: Travel.

Quentin and [[Kharb]] make their way down the mountain.

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=5 vs2=8
}
oracle name="[Travel \/ Travelled with Edge](datasworn:move.oracle_rollable:homebrew\/custom\/travel.edge)" result="You move 2 cells in the wrong direction" roll=43

```

The mountains slope down beneath them, and they enjoy the easy decline. It begins to get warmer and the land opens up beneath them. It becomes clear that they've gone the wrong way!

Quentin looks around and tries to find the right way to go.

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=5 adds=0 stat=1 vs1=3 vs2=1
}
```

They skirt around the foothills, and begin to rise again.

```iron-vault-mechanics
oracle name="[Travel \/ Opportunities](datasworn:move.oracle_rollable:homebrew\/custom\/travel.opportunity)" result="You find a peaceful place to rest. [Make Camp](datasworn:move:classic\/adventure\/make_camp) with +1" roll=50
```

As they crest a particularly steep hill, they come upon a soft shelf with some tree sheltered.

>"Let's stop here for a bit."

```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    add 1 "safe place"
    roll "Supply" action=2 adds=1 stat=3 vs1=8 vs2=10
}
```

As they try to set up camp, a strong wind begins to blow. Snow and ice falls from the tree canopy ahead and the ground is immediately damp and soft.

>"Perhaps this wasn't such a good idea! Let's move on instead!"

Shouts Quentin over the storm.

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=10 vs2=7
    burn from=8 to=2
}
oracle name="[Travel \/ Travelled with Wits](datasworn:move.oracle_rollable:homebrew\/custom\/travel.wits)" result="You are lost and do not leave this cell" roll=64

```

As the storm builds up and whips the snow around, they try to climb up the steep slope further into the mountains. But the drift keeps slipping and they do not make any progress.

>"Let's try to find shelter"
>Kharb chatters through frozen teeth.
>"We're going to freeze out here!"

Quentin agrees, and begins looking for shelter.

```iron-vault-mechanics
move "[Make Camp](datasworn:move:classic\/adventure\/make_camp)" {
    roll "Supply" action=4 adds=0 stat=3 vs1=2 vs2=3
}
```

Quentin finds a small cave in the cleft of the cliff-face. They manage to lay beds and rest.

`does the storm stop? No`

The storm rages on through the night. Quentin and [[Kharb]] wake up and decide to keep going.

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    add 1 "prepared"
    roll "Wits" action=3 adds=1 stat=1 vs1=9 vs2=2
}
oracle name="[Travel \/ Travelled with Wits](datasworn:move.oracle_rollable:homebrew\/custom\/travel.wits)" result="Your insight leads you 1 cell in the right direction" roll=12

```

They push through the storm and come up onto a wide plateau, covered in thin snow. Beyond the drop off is a faint view of a vast landscape of towns and roads disappearing into the horizon. 
Just before the edge is a small cluster of white trees with buildings nestled between them.

`is the city in ruins? No`

To Quentin and [[Kharb]]'s surprise, the town is standing perfectly formed and safe!

They join up with the main road and approach through the storm.

`Does anyone greet them? Yes`

A not so well-armed dwarf guard comes towards them. He has fine velvet coat and a tin helmet. At his side is a rapier.
>"Are you the traders from [[Khiz]]? You're very late. Quickly, fetch your caravan and bring it here to the tradehouse."

Without even waiting for a response, the dwarf spins on the spot and begins strolling away.

Quentin darts after him
>"Hang on, hang on! We'll be just a moment, obviously our caravan is just around the way and we are the greeters"
>He gives [[Kharb]] a glare, a warning to keep his mouth shut
>"But before we do that, we just need to check something in the archives. Could you point us that way?"

The guard stops and looks at Quentin.

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    add 1 "goblin"
    roll "Shadow" action=4 adds=1 stat=3 vs1=5 vs2=8
}
```

>"The archive? That seems a bit academic for the likes of you? What do you need that for?"

Quentin smiles
>"Well, and this is embarrassing, but on the road we came across some rather unusual troves of goods. Something the likes of which we've never seen before. Things that I'm sure the fine folk here in [[Hitching]] would love to get their hands on. But we're nit quite sure what their worth is. So, before doing business we thought it would only be proper to determine their origins and therefore value. I am hoping the archive here might contain such knowledge."

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    add 1
    roll "Shadow" action=5 adds=1 stat=3 vs1=6 vs2=2
}
```

>"Oh really? That's very honourable of you. Well, the archive's that way."

He points a gauntleted to a small trail that breaks away from the large houses and into a small glade to the rear of the town.

>"The mystics set themselves up back there. Funny folk, but very smart. I'm sure they'll have the knowledge you're after."

>"Thank you. We'll be right with you."

Quentin and [[Kharb]] turn off towards the glade.

[[Kharb]] looks at Quentin
>"Why didn't you tell him about the monster?"

>"Clearly it's come right past here and not bothered with [[Hitching]]. Besides, causing a fuss is just going to get us dragged into whatever local nonsense happens around here. I'd rather get in and out with what we came for, then get you back to [[Khizdum]] as soon as possible. Then we can worry about stopping this thing."