Expected Scene: [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] makes his way through the woods back to town
Test: altered scene
[[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] goes back to the entrance to the tunnel to check for more bandits. 

[[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] runs through the woods back towards town. 

Move: Undertake Journey weak hit.

Quentin finds the town wall and goes back in through the gate. I rush back to the tunnel entrance, and crouch down, waiting for any sign of the bandits. 

Gather Information: weak hit. 

I hear distant noise inside. I slowly start making my way down the tunnel to the forge area. 

Are there enemies there? Exceptional yes. 

There are 4 bandits gathered in the chamber. They are arguing and don't notice me enter. 

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Tunnel bandits.md|Tunnel bandits]]" status="added"
```



Enter the fray: weak hit 

I dart into the room and plunge my daggers into the chest of the closest guy

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Iron" action=4 adds=0 stat=2 vs1=3 vs2=9
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Tunnel bandits.md|Tunnel bandits]]" rank="troublesome" steps=1
}

```

He falls down dead. The others rush towards me. I flail my ribbons to daze them.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=5 adds=0 stat=3 vs1=3 vs2=9
}
```

The bandits stop, the ribbons tangled around their heads. One of them tries to grab the ribbon and pull me close. 

I yank the ribbon away. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=2 vs2=10
}
```

The ribbon pulls back, but the others close in. One tries to tackle me. I leapfrog him. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=6 adds=1 stat=3 vs1=8 vs2=5
}
```

Strong hit!

I leapfrog over him and he bashes into another guy. I skirt around them and throw out a blade at the standing guy.

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    roll "Edge" action=6 adds=0 stat=3 vs1=4 vs2=9
}
```

My dagger sinks into his neck and he falls down. The other two guys stand up and try to flank me. 

```iron-vault-mechanics
progress from=12 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Tunnel bandits.md|Tunnel bandits]]" rank="troublesome" steps=1
```

I leap up onto the steel bowl in the middle of the room. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "agile"
    roll "Edge" action=2 adds=1 stat=3 vs1=5 vs2=3
}
```

As they come together, leap up and fling the ribbons to their necks, pulling them together head-first. 

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    add 1 "agile"
    roll "Edge" action=1 adds=2 stat=3 vs1=5 vs2=8
    burn from=10 to=2
}
```

Their heads smash together. 

```iron-vault-mechanics
progress from=24 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Tunnel bandits.md|Tunnel bandits]]" rank="troublesome" steps=1
```

As they fall, I pull the ribbons tight to make sure they are down. 

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=9 vs1=2 vs2=5
}
```

The ribbons pull taught and they both relax and fall unconscious. 
I rush out the tunnel and begin calling "guards! Guards!"

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=7 vs2=9
}
```

Noone hears me. I'll have to go find them myself. 