Scene: travel back to [[Khizdum]] 

Quentin and [[Kharb]] head north across the snowy plains. The sun sets and makes the snow glow pink and the sky orange. The mountain looms to their right. 

```iron-vault-mechanics
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=1 adds=0 stat=1 vs1=7 vs2=4
}
oracle name="[Travel \/ Hindrances](datasworn:move.oracle_rollable:homebrew\/custom\/travel.hindrance)" result="Something causes you harm. [Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" roll=69

```

As the sun goes down, the temperature drops. It takes all their energy to walk and shiver. 
```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Health" action=1 adds=0 stat=2 vs1=5 vs2=10
}
move "[Travel](datasworn:move:homebrew\/custom\/travel)" {
    roll "Wits" action=2 adds=0 stat=1 vs1=5 vs2=5
}

```

