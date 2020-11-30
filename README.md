# polyhedron-greedy-edge-roll

This program animates the greedy edge rotations of a polyhedron towards a target point on the same plane. At every rotation, the polyhedron rotates along an edge that achieves the biggest step locally towards the target.
<img src='/greedy_rot.png'>
The graph draws the rotation steps of a tetrahedron towards a target (marked in red).

Here are a few notes:
1. This file intends to work for all convex polyhedron.
2. Type of the convex polyhedron to rotate can be specified in the first line of the code; the 2d coordinate of the target point is stored in variable called aim2d (assuming that the polyhedron starts at the origin).
3. The second to last cell draws every rotation; the last cell provides an animation of all the rotation steps.

Please let me know if you encountered any trouble running the code. Thank you!
