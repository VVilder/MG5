# MG5
## Devlog
1. NavMesh is better when you just want a character to walk to a spot and figure out the path on its own, like click to move games. Physics is better when you’re directly controlling the character and want stuff to push and bump into it. A game that makes sense with NavMesh is League of Legends, since you're controlling the character by clicking where you want  to go and it has to path there. Whereas a game like rocketleauge prob doesnt since your car is all physics and needs to bounce off the ball and walls.
2. The loop goes through every bird in the _birds array. For each one, Vector3.Distance checks how far the bird is from the player. If that distance is less than or equal to _interactDistance, the bird runs away. So only the birds that are close enough to the player run away.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)