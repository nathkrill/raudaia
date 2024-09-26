Scene: entering the archive

Quentin and [[Kharb]] walk along the path to the archive building. 

It's a grey stone brick building, with a wooden roof covered in snow. Two large wooden posts come down either side of the large panelled door. 
There are two braziers either side of the door which light up with blue flames as they approach. 

Quentin stops and looks at the door. 
>"Do we knock?"

>"I guess?"

Quentin is about to knock on the large door when it begins to swing open towards him. He takes a step back as a very old and thin (for a dwarf) male steps through. He is wearing a flowing robe that spills onto the floor. 

> "Hello and welcome to the archive. What is it that I can do for today?"

Quentin is somewhat taken back, but composes himself.

>"We are with the approaching trade caravan and which to do some research in order to value some rare goods that have come into our possession."

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    add 1
    roll "Shadow" action=1 adds=1 stat=3 vs1=7 vs2=9
}
```

The man peers along his nose as he looks up to Quentin. 

>"I'm sorry, but this archive is intended only for use by academics. Unless you have a reference from one of our members, you may not enter. Goodbye"

The figure quickly slips beyond the door and it slams closed. The braziers remain, flickering. 

>"What now?"

[[Kharb]] seems nervous and frustrated. 
>"I don't want to go all the way back for nothing."

>"I know! I know! I'm thinking..."

Quentin goes and has a look around the exterior of the building, looking for another way in. 

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=6 adds=0 stat=1 vs1=4 vs2=4
}
```

Around the back is another door, smaller and less ornate than the other. Quentin tries the handle and it opens easily. 

He whispers to [[Kharb]]
>"[[Kharb]]! Wait here and hide somewhere, I'm going to sneak inside."

[[Kharb]] nods and rushes off into the bushes nearby. 

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/The archive.md|The archive]]" status="added"
```



Quentin slips into the door. He's in some kind of back storeroom. The door closes and he's in the dark. He fumbles around for another door. 

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Wits" action=1 adds=0 stat=1 vs1=10 vs2=2
    burn from=5 to=2
}
```

He finds the door and pulls it ajar. 

```iron-vault-mechanics
progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/The archive.md|The archive]]" rank="troublesome" steps=1
```

On the other side is a large kitchen, with a big stone worktop. On the floor, spread out on a large blanket and sleeping, is a huge wolf-like dog. It's breath snarls as it sleeps. 

Quentin slowly slides through the door and across the kitchen, keeping low. 

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Shadow" action=1 adds=0 stat=3 vs1=8 vs2=2
}
```

He makes it across the kitchen to another door. This goes to a long passage. The dog begins to stir as Quentin opens the door. He quickly slips past the door. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Shadow" action=6 adds=0 stat=3 vs1=1 vs2=3
}
```

He goes through the door silently and closes it barely making a sound. 

The passage before him goes straight, with several doors on the right. At the end is a spiraling staircase. 

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Wits" action=2 adds=0 stat=1 vs1=7 vs2=5
}
move "[Reveal a Danger](datasworn:move:delve\/delve\/reveal_a_danger)"

```

Quentin slowly opens the first of the right-hand doors. It opens into a large hallway with floating magical lights and large wooden pillars. 
On the right-hand side of the room is a large curved staircase. Standing at the far wall, near another set of doors is the same dwarf who was at the front door. 

`does he see Quentin? No`

Quentin hurriedly pulls back into the passage. This time, he turns and creeps along the passage to the stairs at the end. 

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Shadow" action=4 adds=0 stat=3 vs1=8 vs2=8
}
```

About halfway along the passage, Quentin steps on a floorboard, which lets out a huge *creak*. He jumps onto his other foot to stop the noise but twists his ankle. 
Falling, he grabs onto the nearest thing which happens to be a marble bust of an eleven figure. Which promptly falls over, making a huge crash!

Quentin scurries up to the stairs. 

```iron-vault-mechanics
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Edge" action=3 adds=0 stat=3 vs1=2 vs2=7
}
oracle name="[Delve the Depths \/ Edge](datasworn:move.oracle_rollable:delve\/delve\/delve_the_depths.edge)" result="Mark progress twice and [Reveal a Danger](datasworn:move:delve\/delve\/reveal_a_danger)." roll=95
progress from=12 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/The archive.md|The archive]]" rank="troublesome" steps=2

```

Quentin hears the sound of the wolf and the dwarf downstairs, looking for the source of the noise. He doesn't have much time!
The spiral stairs lead to a large library area on the second floor. It is floor-to-ceiling bookcases, with narrow rows between them. The cases are split into categories. Each row has a small magical candlelight hovering at the end. 

Quentin quickly dashes around trying to find a "monsters" or "creatures" category. 

```iron-vault-mechanics
move "[Locate Your Objective](datasworn:move:delve\/delve\/locate_your_objective)" {
    progress-roll score=9 vs1=5 vs2=5
}
```

There's a section of three rows labelled "creatures, magical". Quentin rushes over and begins going down the first row. The magical light follows him, illuminating the shelves as he goes. 
There are many large tomes, thick and leather bound. About halfway along, he spots a book "Monstrous Creatures of the [[Tugar Forest]]". He grabs the book, tucks it under his arm and hastily tries to find an exit. 

```iron-vault-mechanics
move "[Escape the Depths](datasworn:move:delve\/delve\/escape_the_depths)" {
    roll "Shadow" action=2 adds=0 stat=3 vs1=8 vs2=2
}
```

Quentin quietly creeps the length of the library and finds the large staircase that goes down to the entrance hall. The dwarf attendant and the wolf are in the side chambers, so Quentin rushes to the front door. He hastily pulls it open and slips out, then dashes to the bushes where [[Kharb]] is hiding. As the heavy door closes behind him, one of his ribbons gets caught, he quickly tears it away. 

>"I've got something! Quick, lets go!"

They rush along the edge of the glade and back down the path. Then they skirt the edge of [[Hitching]] back to the east. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Shadow" action=3 adds=0 stat=3 vs1=8 vs2=1
}
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=6 vs2=1
}

```

