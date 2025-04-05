[[Khola]] leaves the castle and goes to the guard HQ to gather the limited forces she is allowed.
Amongst the men assigned she finds [[Kharb]].

>"Is it true? Is [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] in danger?"
[[Kharb]] looks shaken at the prospect of his dear friend in trouble.

>"I'm afraid so. But we're not going to let anything happen to him. Our first order of business is to attend this meeting with the bandits and find out what their demands are. This shouldn't be a violent confrontation yet - that won't get us any answers. But we want to be clear that messing with [[Khizdum]] won't get them anything good. Are you with me?"

The men give their affirmative cheer. They aren't as enthused as [[Khola]] hopes, but it'll do.

[[Khola]] takes the men into the briefing room and examines the local area map on the table.

[[Drawing 2024-11-22 17.07.26.excalidraw]]

>"The meeting point described in [[Kirad]]'s letter is here, north-west of the city up on that ridge. It's only accessible from the north, so chances are they'll be there already and will see us as we come past from the south.
>That is, unless we keep east until we're far enough north to cut west and swing in."

She looks up and surveys the faces of her men, looking for an indication of their persuasion.
The men are clearly invested in what she has to say, and wait for her to make the decision.

>"I'd rather catch these bastards on the back foot, so let's take the wider route and surprise them. Small amounts of undermining will benefit us in the long-run, I'm sure."
>"Okay! Let's get going."

They pick up their packs and leave the HQ and out of the city.

```iron-vault-mechanics
actor name="[[Campaigns\/Qs in R\/Ironsworn\/Characters\/Khola.md|Khola]]" {
    move "[Travel](datasworn:move:homebrew\/custom\/travel)"
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="You witness something harrowing or miserable. [Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" roll=32

```

It's snowing outside, and as they head north along the edges of the mountain a blizzard picks up and the wind whips around the group.
Progress is slow as they push forwards through the storm.
```iron-vault-mechanics
actor name="[[Campaigns\/Qs in R\/Ironsworn\/Characters\/Khola.md|Khola]]" {
    move "[Endure Stress](datasworn:move:classic\/suffer\/endure_stress)" {
        roll "Spirit" action=6 adds=0 stat=4 vs1=4 vs2=6
    }
    move "[Travel](datasworn:move:homebrew\/custom\/travel)"
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="Something causes you harm. [Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" roll=72

```

The storm just keeps getting worse. [[Khola]] gathers the men and they try to craft some shelter to wait it out.
They build a small lean-to and huddle beneath it, when a gust of wind picks up and knocks their shelter down over them!

```iron-vault-mechanics
actor name="[[Campaigns\/Qs in R\/Ironsworn\/Characters\/Khola.md|Khola]]" {
    move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
        roll "Health" action=4 adds=0 stat=4 vs1=3 vs2=3
    }
}
```

They crawl out from under the ruins of the shelter, and close in around a small fire. They patch up their wounds and prepare to move on.

```iron-vault-mechanics
actor name="[[Campaigns\/Qs in R\/Ironsworn\/Characters\/Khola.md|Khola]]" {
    move "[Travel](datasworn:move:homebrew\/custom\/travel)"
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="You lose something important. -1 Supply" roll=6

```

They press on through the snow, when [[Kharb]] suddenly cries out.

>"My pack! I left it under the shelter!"

[[Khola]] sighs.

>"Really, [[Kharb]]!? Please let us not waste any more time. Hurry up and get it."

They wait, dripping and shivering while [[Kharb]], accompanied by another soldier, runs back to their rest place and gets his pack. It is sodden and squashed, and some of his rations are beyond saving.

```iron-vault-mechanics
actor name="[[Campaigns\/Qs in R\/Ironsworn\/Characters\/Khola.md|Khola]]" {
    move "[Travel](datasworn:move:homebrew\/custom\/travel)"
}
oracle name="[Travel \/ Travelled with Edge](datasworn:move.oracle_rollable:homebrew\/custom\/travel.iron)" result="You move 1 cell in the wrong direction. The conditions of your journey get worse." roll=56

```

The storm gets lower, blocking out the afternoon sun. While the wind dies down it's very hard to navigate. The group soon find themselves below the shadow of the eastern mountain.

Not wanting to backtrack, [[Khola]] tries to take them north, up the slopes so they can come back down further up. 

```iron-vault-mechanics
actor name="[[Campaigns\/Qs in R\/Ironsworn\/Characters\/Khola.md|Khola]]" {
    move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
        roll "Wits" action=4 adds=0 stat=2 vs1=5 vs2=4
    }
    move "[Ask the Oracle](datasworn:move:classic\/fate\/ask_the_oracle)"
}
oracle name="[Travel \/ Opportunities](datasworn:move.oracle_rollable:homebrew\/custom\/travel.opportunity)" result="You encounter something that will make your journey easier. Visualise it and roll your next [Travel](datasworn:move:homebrew\/custom\/travel) with +1" roll=92

```

Despite the incline, this side of the mountain is sheltered from the storm and the group make good progress north. From this height they can see across the valley to their destination. 

They swing west and begin the descent back to flat ground.

```iron-vault-mechanics
actor name="[[Campaigns\/Qs in R\/Ironsworn\/Characters\/Khola.md|Khola]]" {
    move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
        add 1 "opp"
        roll "Wits" action=4 adds=1 stat=2 vs1=8 vs2=10
    }
}
```



