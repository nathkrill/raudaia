Extected scene: [[Campaigns/Qs in R/PCs/Quentin McQuall|Quentin McQuall]] Searches the town for a guard.
Test: Expected scene

Since no-one heard my cry, I head out from the wall back towards the gate, looking for a guard.

```iron-vault-mechanics
move "[Gather Information](datasworn:move:classic\/adventure\/gather_information)" {
    roll "Wits" action=4 adds=0 stat=1 vs1=10 vs2=2
}
```

Is the guard I find a traitor? Yes.

I find a guard at the gate - he's not one I've spoken to yet.
"Hey!" I cry, "Quickly, I've managed to clear out the bandits. Some of them are unconscious in their secret tunnel."

He hears me and draws his sword. "You killed them? You'll rot."

```iron-vault-mechanics
track name="[[Campaigns\/Qs in R\/Ironsworn\/Progress\/Dirty Guard.md|Dirty Guard]]" status="added"
```

I ready a defensive stance as he comes towards me drawing his sword.

```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:classic\/combat\/enter_the_fray)" {
    roll "Heart" action=1 adds=0 stat=2 vs1=10 vs2=8
}
```

As he comes close, I hear a cry behind me. Another guard comes around the corner, sees one of their own seemingly in combat and gets out a crossbow.
The first guard reaches me and lunges with his blade. I jump and flip over him.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=2 adds=1 stat=3 vs1=3 vs2=6
}
```

I jump over and land behind him. The other guard lets loose a crossbow bolt. I duck behind the first guard.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    roll "Edge" action=2 adds=0 stat=3 vs1=6 vs2=9
}
```

I'm not quick enough and a bolt hits me in the thigh.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=3 adds=0 stat=3 vs1=9 vs2=10
}
```

I stumble back, clutching the wound. The closer guard spins with his sword. I jump back.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=3 adds=1 stat=3 vs1=5 vs2=5
}
```

As I jump, the guard over spins, and tumbles over his own legs.
I dive away, and try to get to cover down a side road.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    add 1 "agile"
    roll "Edge" action=4 adds=1 stat=3 vs1=2 vs2=8
}
```

The guard with the crossbow rushes to the end of the road and fires a bolt beyond the corner. I slide onto the ground.

```iron-vault-mechanics
move "[Face Danger](datasworn:move:classic\/adventure\/face_danger)" {
    add 1 "agile"
    roll "Edge" action=1 adds=1 stat=3 vs1=8 vs2=8
}
```

The bolt hits me in the back. I cannot move for the pain.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=3 adds=0 stat=2 vs1=1 vs2=2
}
```

The guard comes over and puts his boot on my back, holding me down.

```iron-vault-mechanics
move "[End the Fight](datasworn:move:classic\/combat\/end_the_fight)" {
    progress-roll score=0 vs1=2 vs2=2
}
```

I'm in too much pain to speak. I points the crossbow at my head, and all fades to black.