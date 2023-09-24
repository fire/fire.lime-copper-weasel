# Lime Copper Weasel

## Avatar preflight checklist

1. Weighted to 4 bone weights and range of motion doesn't break the skinning
1. Add shader motion
1. [TaSTT](https://github.com/yum-food/TaSTT)'s text player
1. Overly bright lights don't make the avatar's surface glow.
1. The body mesh must be intact -- Parts of the body MUST not be removed.
1. VRM0 materials
1. VRM0 spring bones
1. Meta Quest 2 support with cutout transparency
1. Gut feel check

# Medium Performance Rank Limits

| Attribute                       | Limit        |
| ------------------------------- | ------------ |
| Polygons                        | 15,000       |
| Bounds Size                     | 5m x 6m x 5m |
| Texture Memory                  | 25 MB        |
| Skinned Meshes                  | 2            |
| Meshes                          | 2            |
| Material Slots                  | 2            |
| Animators                       | 1            |
| Bones                           | 150          |
| PhysBones Components            | 6            |
| PhysBones Affected Transforms   | 32           |
| PhysBones Colliders             | 8            |
| PhysBones Collision Check Count | 32           |
| Avatar Dynamics Contacts        | 8            |
| Particle Systems                | 0            |
| Total Particles Active          | 0            |
| Mesh Particle Active Polys      | 0            |
| Particle Trails Enabled         | False        |
| Particle Collision Enabled      | False        |
| Trail Renderers                 | 0            |
| Line Renderers                  | 0            |
