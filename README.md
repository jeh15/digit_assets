# Digit V3 Assets
Repository containing Agillity Robotic's Digit V3 Assets

`digit-v3.xml` is the original mujoco model provided by Agility.
`digit.xml` is an editted version of `digit-v3.xml` where the `.stl` models were converted to `.obj` for compatibility with Drake's mujoco parser.
`digit.urdf` is a hand made solution to get Digit to parse correctly in Drake.

The directory `original_stl` contains the `.stl` files provided by Agility.
Agility uses `scale='1 -1 1'` in their mujoco file to flip assets. The `stl/` directory contains additional flipped assests for compatibility with Drake.
Aditionally, the `obj/` directory contains the same assests as `stl/` but convert to `.obj` file for compatibility with Drake.