Coordinates all relative to [0,0,0].
Rotations all in an array [x,y,z].

Thickness of objects called "height".

Variable types:
- input: values that user provides, are copied to other variables
- single value: special case, rare use
- coordinate, xyz: [x,y,z] relative to [0,0,0]
- rotation, rot: [x,y,z]
- dimensions, dim: [x,y,z]
- cylinder, cyl: [h,d], note use of diameter

All objects created from modules can be moved using the given coordinates which are relative to [0,0,0].

Variable names are
<object short name>_<variable type short name>

Order of translation and rotation is subject to the individual part.

Modules take arguments, order doesn't matter.
- dim: the cube dimensions of the shape (cannot also have cyl)
- cyl: the cylinderacle dimensions of the shape (cannot also have dim)
- xyz: the translation for the final shape created by the module
- rot: the rotation for the final shape created by the module
- t: transparency for the object
- s: scale for the object
