# Concept for adding joints to a 3d rig

Prodedure is as follows:

1. Give a point on a 3D object's surface
2. Create a ray based on the given point and the inverse normal of the given point's surface
3. Use the ray to get the point opposite side of the 3D object (through in 3D object)
4. Place joint in the point which is in middle of the point in [1] and the point in [3].
