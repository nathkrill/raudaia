Scene: Quentin reunites with [[Ka'Eek]]
Interrupt: ambush

I run through the streets towards the [[Bumpy Shroom]]. I'm just about to turn the corner to it when a door bursts open. Three soldiers, two with clubs and one with a sword come out, shouting at me. 

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 15 ambush.md|Scene 15 ambush]]" status="added"
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Wits" action=1 adds=0 stat=1 vs1=2 vs2=5
}

```

They immediately surround me. The first swings his club. I duck and roll, trying to get between them. 

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    add 1 "goblin"
    roll "Edge" action=3 adds=2 stat=3 vs1=4 vs2=1
}
```

I come around then, and rope up the nearest one. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "ribbons"
    roll "Edge" action=4 adds=1 stat=3 vs1=6 vs2=5
}
```

He gets tangled up so I throw a dagger at him. 

```iron-vault-mechanics
move "[Strike](datasworn:move:classic\/combat\/strike)" {
    add 1 "advantage"
    roll "Edge" action=3 adds=1 stat=3 vs1=5 vs2=3
    progress from=0 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 15 ambush.md|Scene 15 ambush]]" rank="troublesome" steps=2
}

```

He falls down, dead. I roll between the other two. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "agile"
    roll "Edge" action=2 adds=1 stat=3 vs1=5 vs2=8
}
```

They both take initiative and bear down on me. I sweep my feet to knock them back. 

```iron-vault-mechanics
move "[Clash](datasworn:move:classic\/combat\/clash)" {
    roll "Iron" action=6 adds=0 stat=2 vs1=5 vs2=5
    progress from=24 name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Scene 15 ambush.md|Scene 15 ambush]]" rank="troublesome" steps=2
}

```

They both fall and hit their heads hard. They are unconscious. 

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=10 vs1=10 vs2=10
}
```

