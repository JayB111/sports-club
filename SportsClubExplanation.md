# Sports Club Class Diagram

## 1. Club and Team — Composition

A Club has exactly three Teams: a First Team, a Reserve Team and a Youth Team.

Each Team belongs to exactly one Club.

This is a composition relationship because Teams depend on the Club. If the Club shuts down, its Teams cease to exist.

## 2. Team and Player — Association

A Team can have multiple Players, and a Player can be assigned to one Team at a time.

This is an association relationship because Players exist independently of Teams. If a Team is disbanded, its Players remain registered with the Club and can be reassigned.

Players can also be transferred to another Club or loaned to a different Team.

## Conclusion

The Club–Team relationship is composition, while the Team–Player relationship is a regular association.