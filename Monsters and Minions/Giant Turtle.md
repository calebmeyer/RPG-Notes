
```statblock
monster: Dragon Turtle
image: [[dragon-turtle.webp]]
hp: 150
hit_dice: 30d10
actions:
  - name: Bite
    desc: "Melee Weapon Attack: +8 to hit, reach 10 ft., one target. Hit: 26 (3d12
      + 7) piercing damage."
    attack_bonus: 8
    damage_dice: 3d12
    damage_bonus: 7
  - name: Crush
    desc: After the dragon turtle moves on top of one or more creatures, it can use 
      its action to attempt to crush them. Each creature in the area makes a DC 15
      Dexterity save or takes 35 (10d6) damage (no damage on successful save). 
      Then they are pushed out from under the turtle.
    attack_bonus: 0
    damage_dice: 10d6
  - name: Dark Fire Breath (Recharge 5-6)
    desc: The dragon turtle exhales dark fire in a 30-foot cone. Each creature
      in that area must make a DC 16 Dexterity saving throw, taking 35 (10d6)
      fire damage on a failed save, or half as much damage on a successful one.
    attack_bonus: 0
    damage_dice: 10d6
```
