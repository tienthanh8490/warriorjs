## Tbeo - beginner - level 6

### _The wall behind you feels a bit further away in this room. And you hear more cries for help._

> **TIP:** You can walk backward by passing `'backward'` as an argument to `walk()`. Same goes for `feel()`, `rescue()` and `attack()`. Archers have a limited attack distance.


### Floor Map

```
╔════════╗
║C @ S aa║
╚════════╝

C = Captive (1 HP)
@ = Tbeo (20 HP)
S = Thick Sludge (24 HP)
a = Archer (7 HP)
```

### Abilities

#### Actions (only one per turn)

* `warrior.walk()`: Move one space in the given direction (forward by default).
* `warrior.attack()`: Attack a unit in the given direction (forward by default) dealing 5 HP of damage.
* `warrior.rest()`: Gain 10% of max health back, but do nothing more.
* `warrior.rescue()`: Rescue a captive from his chains (earning 20 points) in the given direction (forward by default).

#### Senses

* `warrior.feel()`: Return the adjacent space in the given direction (forward by default).
* `warrior.health()`: Return an integer representing your health.

### Next Steps

When you're done editing `Player.js`, run the `warriorjs` command again.
