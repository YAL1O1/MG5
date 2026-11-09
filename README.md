# MG5
## Devlog
1. I think NavMesh is more convenient, while physics-based movement allows for physical simulations and gives players more control.

   For example, LoL is suitable for NavMesh because players select destinations by clicking. However, first-person games are less suitable because selecting destinations is inconvenient compared to directly controlling movement with WASD.
2. The loop uses Vector3.Distance to calculate the distance between each bird in _birds and the player. If the distance is less than _interactDistance, the bird will run away.
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)