Expected Scene: Interrogation in the prison cell.
Test: Altered Scene - deny strength

I come to consciousness, with a biting cold in my joints. I look down and I'm chained to a table.
There is a hardy woman standing over me.

"Ah you're awake. Let's have a talk, young man."

I stay silent, and wait for her to begin.

"You were caught assaulting a member of my guard. He claims you appeared out of the woods and attacked him. Who sent you? Are you part of a goblin raid?"

I take a pained breath.
"I didn't attack him. He attacked me. I came to him for help after I fought and cleared out the bandit tunnel that leads out of the town. But I think he's one of them, as soon as I told him what happened he drew his sword and charged." I stop and cough.

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    roll "Heart" action=4 adds=0 stat=2 vs1=5 vs2=6
}
```

"Why should I believe you?" She replies. "I trust my man's story over yours."

"You can go and check it out." I tell her. "There's a secret tunnel in the town wall just up from the gate. They're in there, some are dead, some were unconscious and might have escaped."
I pause, then add "There might also be loot in there, and I'm sure you'll get lot's of credit from the town mayor or whoever when you report this."

```iron-vault-mechanics
move "[Compel](datasworn:move:classic\/relationship\/compel)" {
    add 1 "tricksy"
    roll "Shadow" action=6 adds=1 stat=3 vs1=2 vs2=3
}
```

Her eyes narrow... Then she relaxes. She walks to the door, opens it a crack and whispers something to someone outside. She leaves.

It's a while before she returns. In the meantime, I try to wiggle the chains loose.

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:classic\/adventure\/secure_an_advantage)" {
    roll "Iron" action=5 adds=0 stat=2 vs1=10 vs2=5
}
```

The chains bite into my joints, drawing blood. But something slips and my shoulder is loose.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:classic\/suffer\/endure_harm)" {
    roll "Iron" action=2 adds=0 stat=2 vs1=9 vs2=7
}
```

The guard captain returns.
"I had some men take a look at this hideout you mentioned. Looks like good work in there." She pauses, then unchains me.
"My operation was a success, we took down the bandits and arrested a rogue guard. Your involvement will not be mentioned to anyone."

She hurriedly rushes me out of the barracks and into the castle courtyard. I'd not seen this part of town yet. She walks me to the large wooden gates of the castle, which open as we approach.

"I don't want to have to cross paths again. But, you've proven yourself a good fighter. I may have need of you if you find yourself available."