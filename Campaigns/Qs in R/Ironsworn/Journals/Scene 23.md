Scene: Quentin looks for Kharb in the snowy plain
altered scene: Quentin looks for kharb in the mountains.

Going back to where he and [[Kharb]] separated, Quentin sees that the footprints don't go north into the plain like he thought, but instead go up east to the mountains.

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Find Kharb 1.md|Find Kharb]]" status="added"
```


Quentin follows the trail.

```iron-vault-mechanics
move "[Discover a Site](datasworn:move:delve\/delve\/discover_a_site)"
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Wits" action=1 adds=0 stat=1 vs1=10 vs2=1
}

```

The going it tough as the mountain rises before him. At points, Quentin has to search hard to find the trail amongst the rocky ground.

At the top of this ridge, Quentin finds a ruined encampment. He slowly creeps up, just in case it's occupied.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Shadow" action=4 adds=0 stat=3 vs1=1 vs2=7
}
move "[Delve the Depths](datasworn:move:delve\/delve\/delve_the_depths)" {
    roll "Shadow" action=4 adds=0 stat=3 vs1=3 vs2=10
}

```

He creeps up to the camp. There's movement amongst the shredded tents and fallen shelters.

`Is it Kharb? Yes`

He sees a squat form digging through some of the rotten crates, half buried in snow.

He calls out quietly
> "Kharb? Is that you?"

The figure turns suddenly at the noise.

`Is Kharb friendly? Yes!`

> "Quentin! Oh it's you! You found me!"

[[Kharb]] rushes over and jumps into a hug. Quentin pats him and puts him down.

> "You survived. That's a relief. I was beginning to dread having to go back to [[Khizdum]] alone."

[[Kharb]] looks around suddenly and nervously. He's clearly very shaken up.

> "What about the monster? Did it follow you up here? I think I managed to shake it off."

> "It went off towards [[Hitching]]. They had no warning so who knows what state they're in now."

> "Oh no! So what should we do now?"

Quentin thinks for a moment.
>"We'll still go. Hopefully they've either fought it off of it's gone through and disappeared like at [[Khizdum]]. Either way, we can still try to find the archive. Perhaps now they've seen the threat they will be more open to helping us find out just what this thing is."

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Find Kharb 1.md|Find Kharb]]" status="removed"
```

Quentin looks around the ruined camp.

>"Did you find anything useful yet?"

`Did Kharb find anything? Yes`

> "Yes, I found some old rations. Not in the best of condition, but enough to keep us going. For now."

> "Excellent. Let's do one more pass just in case."

```iron-vault-mechanics
move "[Resupply](datasworn:move:classic\/adventure\/resupply)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=5 vs2=1
}
```

It takes a little while and is hard with the cold, wet snow covering everything. But Quentin and [[Kharb]] manage to dig up and old store tent and find some extra provisions.