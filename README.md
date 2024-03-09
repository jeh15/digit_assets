# Digit V3 Assets
Repository containing Agillity Robotic's Digit V3 Assets

`digit-v3.xml` is the original mujoco model provided by Agility.\
`digit.urdf` is a hand made solution to get Digit to parse correctly in Drake.

The directory `stl/` contains the `.stl` files provided by Agility.\
Agility uses `scale='1 -1 1'` in their mujoco file to flip assets.\
For compatibility with Drake, manually flipped versions of the meshes were generated as `.obj` and placed in the `obj/` directory for the URDF model.