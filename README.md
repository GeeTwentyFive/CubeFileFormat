**CURRENTLY WIP**

3D axis-aligned cuboids-only mesh file format (like for AABB engines for example)

Intended to be used by passing data to geometry shader which generates (colored) cuboids at given positions

FILE EXTENSION: `.cubes`

FORMAT (binary data):
```
u32 num_cubes |
<CUBES> (f32 pos_x, f32 pos_y, f32 pos_z, f32 size_x, f32 size_y, f32 size_z, u8 col_red, u8 col_green, u8 col_blue)...
```

Official C reader & writer lib: https://github.com/GeeTwentyFive/CubeLib

Official runtime Godot loader: WIP
