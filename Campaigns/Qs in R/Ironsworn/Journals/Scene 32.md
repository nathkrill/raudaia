Expected Scene: Deploying to find the [[Wahashka]].
Altered: Deploying to defend against the [[Wahashka]].

[[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin McQuall]] is woken up in the morning by chaos in the army headquarters.

He climbs out of bed and goes out into the main chamber, looking around for [[Khola]].

`is she there? Yes`

He calls out over the clamour
>"[[Khola]]!"

>"[[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]]! Get yourself ready. The [[Wahashka]] has been sighted out in the wastes to the north. It's headed this way!"

[[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]] nods and goes back to his chambers, putting together his gear.
He meets [[Khola]] and some of the soliders outside.

>"Alright! So thanks to [[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]] we know a little bit more about what we're fighting here. The creature struggles with sight, so if we keep quiet and at a distance we should be able to do a fair amount of damage to it.
>But out first course of action is to keep it away from the camp. We'll exit the city and head west, making as much noise as possible. Then when we've diverted it we'll split into small groups and stay as quiet as possible. Got it?"

The soldiers stiffen. They're clearly nervous, but keen not to let [[Khola]] down.
>"Yes ma'am!"

We begin the quick jog through the city to the west gate and onto the road.
[[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]] scans north to try to see if he can spot the [[Wahashka]].

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=3 adds=0 stat=1 vs1=5 vs2=9
}
```

[[Campaigns/Qs in R/Ironsworn/Characters/Quentin McQuall|Quentin]] can't see the creature on the horizon. The sun climbs higher in the sky and soon there is a glare on the crisp snow.

He calls out to the group:
>"Anyone see anything?"

`do they see it? no`

>"Nothing. Where is the blasted thing?"

They keep hiking west, keeping their eyes out. Eventually they come to a ring of raised banks - the planned place for battle.
A slight wind picks up, blowing snow over the banks and off the small trees around. They raise their arms to their eyes to try and peer into the wind.

Quentin walks up to a tree.
>"I'm going to get some higher ground."

He climbs up the tree.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "acrobat"
    roll "Edge" action=4 adds=1 stat=3 vs1=3 vs2=3
}
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    add 1 "advantage"
    roll "Wits" action=5 adds=1 stat=1 vs1=2 vs2=3
}

```

From his perch, Quentin can see a little further. Squinting through the harsh sunlight he scans the barren white horizon for anything. Then, he spots a black speck amongst the stark snow.

`is it heading towards the city? Yes`

>"I see it! It's heading towards the city! Start making some noise!!"

The soldiers all begin shouting and screaming, and bashing their spears and swords against their dull armour and shields.

Quentin lets out a long, loud whistle.

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Shadow" action=3 adds=0 stat=3 vs1=7 vs2=10
}
```

The noise rises up then gets taken by the wind, as if there is a wall stopping the sound reaching out into the plain.

>"It must be to far away! Someone come with me and we'll try to catch up and get it's attention!"

Quentin jumps down from the tree and breaks into a dash out from the circle and onto the open plain. A soldier he doesn't know joins him in the mad dash towards the tiny speck in the distance.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=5 vs2=8
    burn from=10 to=2
}
```

As they come closer, Quentin begins shouting and screaming, making as much noise as he can to attract the attention of the beastly creature.

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    add 1 "advantage"
    roll "Heart" action=5 adds=1 stat=2 vs1=7 vs2=4
}
```

It works! The monster swerves off it's course for the city and starts going towards Quentin and the solider.

>"Run!"

They both slide to a halt and turn on their heels.


```iron-vault-mechanics
clock name="[[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]]" status="added"
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=1 vs2=5
}

```

Quentin and the soldier keep a good distance away as they barrel back towards the hills. As they run they keep shouting and screaming to hold it's attention.

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=5 vs2=4
}
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=4 adds=0 stat=3 vs1=3 vs2=7
}

```

They start to slow a bit, and the [[Wahashka]] gains on them.

```iron-vault-mechanics
oracle name="Will [[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]] advance? (Likely)" result="Yes" roll=25 {
    clock from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]]" out-of=6 to=1
}
```

They being to come towards the circle of banks.

>"Into the middle, we can make it!"

Quentin goes up one of the banks and leaps towards the middle of the ring.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=4 adds=1 stat=3 vs1=5 vs2=4
}
```

He flies p and out and lands with a roll in the center of the circle. He turns to face the oncoming monster.

He hisses to the soldiers
>"Quick hide yourselves!"

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=6 vs2=6
    oracle name="Will [[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]] advance? (Certain)" result="Yes" roll=35 {
        clock from=1 name="[[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]]" out-of=6 to=3
    }
}

```

The [[Wahashka]] comes closer. Some of the soldiers are frozen in fear of the oncoming behemoth.

Quentin grabs one by the chestplate and forces him behind one of the low banks.

```iron-vault-mechanics
move "[Aid Your Ally](datasworn:move:classic\/relationship\/aid_your_ally)"
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=5 vs2=3
}

```

The soldier stumbles and falls flat into his position.
```iron-vault-mechanics
oracle name="Will [[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]] advance? (Certain)" result="Yes" roll=22 {
    clock from=3 name="[[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]]" out-of=6 to=4
}
```

The [[Wahashka]] is just beyond the banks.

Quentin backs up again.
>"Ready! Get it in your sights!"

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=9 vs2=6
    oracle name="Will [[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]] advance? (Certain)" result="Yes" roll=37 {
        clock from=4 name="[[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]]" out-of=6 to=5
    }
}

```

The [[Wahashka]] crests one of the banks. It's hanging mouth lets out a spine-tingling growl. Quentin crouches low, ready to leap.

```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Heart" action=5 adds=0 stat=2 vs1=5 vs2=7
    burn from=8 to=2
    oracle name="Will [[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]] advance? (Certain)" result="Yes" roll=89 {
        clock from=5 name="[[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]]" out-of=6 to=6
        clock name="[[Campaigns\/Qs in R\/Ironsworn\/Clocks\/Scene 32 Wahashka chase.md|Scene 32: Wahashka chase]]" status="resolved"
    }
    track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 32 Wahashka.md|Scene 32: Wahashka]]" status="added"
}

```



The [[Wahashka]] crawls down the bank into the circle. Quentin allows it to approach, keeping low.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=6 adds=0 stat=3 vs1=6 vs2=7
}
```

The [[Wahashka]] doesn't appear to notice anything now, except Quentin.

>"Now!"

Quentin cries out as the monster lunges forward. He leaps into the air as the soldiers let their arrows fly.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=4 adds=1 stat=3 vs1=1 vs2=3
}
```

He jumps up onto it's back as the arrows land.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=1 vs2=8
}
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Iron" action=3 adds=0 stat=2 vs1=9 vs2=8
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 32 Wahashka.md|Scene 32: Wahashka]]" rank="formidable" steps=1
}

```

The arrows pierce and the [[Wahashka]] cries out in pain. The sound of it's cry splits right through Quentin's head, and although he tries to plunge a dagger into it's back he can't find purchase.

The [[Wahashka]] reels and tries to fling Quentin to the ground.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=6 adds=1 stat=3 vs1=2 vs2=7
}
```

Quentin uses the momentum and leaps off its back towards a nearby tree. He scrambles up.

>"Fire again! Quick"

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=9 vs2=9
}
```

The arrows come flying in again, but the [[Wahashka]] is too quick. In a blur it leaps to the bottom of the tree, shaking it and savagely clawing at it. Quentin clings on at the top.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=9 vs2=3
}
```

The tree begins to creak and groan. Quentin uses the weak trunk to try to pull the tree onto the [[Wahashka]].

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=4 vs2=10
}
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=6 adds=1 stat=3 vs1=9 vs2=6
}

```

As the tree falls, Quentin leaps away. It topples, just missing the monstrous figure beneath him. Quentin lands on the soft snow and dashes for cover.

>"Shoot it!"

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=1 adds=0 stat=3 vs1=4 vs2=2
    burn from=10 to=2
    progress from=4 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 32 Wahashka.md|Scene 32: Wahashka]]" rank="formidable" steps=3
}

```

Another volley of arrows slam into the [[Wahashka]]'s body. It reels as viscous black blood smears the snow, steam rising from the hot gore.

Quentin dashes around, trying to slide out of the [[Wahashka]]'s notice.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=7 vs2=2
}
```

He gets out of sight, but the [[Wahashka]] is now moving around, looking for him.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "blind"
    roll "Shadow" action=5 adds=1 stat=3 vs1=10 vs2=10
}
```

Despite his best efforts, the [[Wahashka]] breaks through the bank he is hiding behind and bears down on him. Both him and the soldiers hiding there try to leap out of the way.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    add 1 "danger sense"
    roll "Edge" action=6 adds=2 stat=3 vs1=8 vs2=9
}
```

They make it. The other soldiers fire another volley.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=7 vs2=10
    progress from=16 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 32 Wahashka.md|Scene 32: Wahashka]]" rank="formidable" steps=1
}

```

The [[Wahashka]] screeches in pain again. It begins to stumble through the bank away from them.

Quentin cries out.
>"Don't let it get away!"

He rushes out and tries to get through the mass of clawed legs to behind the [[Wahashka]].
```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=3 adds=0 stat=3 vs1=7 vs2=3
}
```

He gets sliced by one of the legs.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=6 adds=0 stat=4 vs1=5 vs2=1
}
```

He grits his teeth and throws out his ribbons, trying to entangle the monster's many limbs and slow it down.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Iron" action=1 adds=0 stat=2 vs1=1 vs2=6
}
```

It's retreat is slowed. Quentin strains at the ribbons and it tries to roll back onto him.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=1 vs2=8
}
```

Quentin jumps but is thrown to the ground. Arrows are flying but not making a mark.
The [[Wahashka]] looms over him.

`does [[Khola]] step in? no`

The mouth opens wide and gnashes towards him.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=2 adds=1 stat=3 vs1=3 vs2=8
}
```

Quentin rolls out the way, being barely missed by the toothy maw.
He tries to scramble away behind another bank.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "acrobat"
    roll "Edge" action=1 adds=1 stat=3 vs1=1 vs2=6
}
```

He crawls a short way but the monster is bearing down on him.
Quentin rolls onto his front and pulls a dagger out, plunging it upwards.

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Iron" action=5 adds=0 stat=2 vs1=4 vs2=2
}
```

As the mouth comes back towards him, Quentin's dagger plunges straight up under it's jaw. Hot black blood sprays over him.

```iron-vault-mechanics
progress from=20 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 32 Wahashka.md|Scene 32: Wahashka]]" rank="formidable" steps=2
```

Quentin uses the opportunity to slide the dagger upwards around the back of the dangling mouth.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=6 vs1=8 vs2=1
}
```

As he does, the [[Wahashka]] lets out the most guttural and harrowing screech. It squirms and collapses on top of Quentin.

```iron-vault-mechanics
move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
    roll "Heart" action=2 adds=0 stat=2 vs1=9 vs2=3
}
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=4 adds=0 stat=3 vs1=8 vs2=9
}

```

>"Quentin!"

[[Khola]] cries out and rushes to him. She gestures and her and a few of the soldiers push the [[Wahashka]]'s body off Quentin, who has fallen unconscious.