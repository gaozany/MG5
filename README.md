# MG5
## Devlog

1.You would want to use a NavMesh if you wanted your character to navigate around obstacles and be able to travel through your level. An example would be a game such as League of Legends where you click a point on the map and your character needs to know which way to go and what objects to avoid. If your game required your character to have physics applied to it then you would want to use physics. Say your making a soccer game you would want to use physics because the ball would need to move with velocity.
2.We start our for loop at 0 and it will continue until it reaches less than _birds.Length. We are doing this because we want to loop through all of our birds in the _birds array. Everytime we loop we use Vector3.Distance to get the distance between the bird and player. Then we compare that distance to _interactDistance using an if statement. If our bird is within that distance we will call RunAway() and the bird will run away. Any birds that are farther away from our player than _interactDistance will not run away.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
