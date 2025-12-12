3D colored cuboids mesh file format

FILE EXTENSION: `.cubes`

FORMAT (binary data):
```
u32 num_cubes |
<CUBES_ARRAY> (
  f32 pos_x,
  f32 pos_y,
  f32 pos_z,
  f32 rot_pitch,
  f32 rot_yaw,
  f32 rot_roll,
  f32 size_x,
  f32 size_y,
  f32 size_z,
  u8 col_red,
  u8 col_green,
  u8 col_blue
)...
```
(each array member represents one cuboid in the mesh)

Official C reader & writer lib: https://github.com/GeeTwentyFive/CubeLib

Official runtime Godot loader: https://github.com/GeeTwentyFive/GodotCubeLoader
