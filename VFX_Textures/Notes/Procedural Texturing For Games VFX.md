Substance Designers offers a lot of flexibility in creating textures

# [Substance Designer Pipeline](https://www.bilibili.com/video/BV14uYUz7E1K?spm_id_from=333.788.videopod.sections&vd_source=c52aacd3530e7f3dabe93deb78074f99&p=3)
[cont]

# [Types of textures in VFX](https://www.bilibili.com/video/BV14uYUz7E1K?spm_id_from=333.788.videopod.sections&vd_source=c52aacd3530e7f3dabe93deb78074f99&p=2)
different textures are used based on the style of the game. most common types:
1. masks / gradients
2. noises / distortions & normal maps: usually tileable
3. flares: lighten up the scene, commonly used in films
4. patterns
5. ribbons / trails: magic projectiles, smokes
6. flipbooks: lightning, fire, snow, etc
7. decals: ground cracks, blood splatters, scorched ground, etc -> blend between effects & environment

# Gradients & masks
- masks are like a limiter for texture / mesh: choose which part is visible
- can create special effects when you have 2 textures that are scrolling next to each other
- Example use-cases:
  - grass / tree (vertex displacement): the bottom part of the sprite is fixed on the ground -> use a gradient map as the multiplier for the vertex displacement
  - gradient as shape (fresnel edges): use the circle gradient as a shape that you distort later; masked smoke with panning 2 cloud textures at different speeds that only appear in the defined shape
  - mask for dissolve shape / gradual circular mask shape reveal on the ground / objects that appear from top to bottom: change values over time
  - post-processing vignette masks / frozen screen / border

<img width="1581" height="594" alt="Screenshot 2026-10-14 at 22 11 34" src="https://github.com/user-attachments/assets/e88a753c-dbc1-43ce-881c-b5cb6c870c46" />

# Noises & normal maps (usually tileable)
- usually tileable
- add more detail: dissolve surface based on the noise -> more interesting shape
- [Simon Trumpler's example: aura noise with stylised textures](https://simont.artstation.com/projects/B3v258)
- Hades VFX which looks hand-drawn: uses noise & mask shape
- normal map for heat distortion
- caustics for water / magic
- voronoi (usually 3D voronoi): best for fracture shapes / gunshots that destroy the wall, made in Houdini / Blender / Unreal

<img width="1293" height="801" alt="Screenshot" src="https://github.com/user-attachments/assets/1a98c8d5-f72e-4c53-a662-84df54454fbf" />

# Lense flares

# Shapes & patterns

# Lightning strike generator

# Trails

# Blood & impact decal

# TODO
- https://www.madvfx.com/courses/procedural-texturing-for-games-vfx
- https://www.bilibili.com/video/BV14uYUz7E1K?spm_id_from=333.788.videopod.sections&vd_source=c52aacd3530e7f3dabe93deb78074f99&p=2
