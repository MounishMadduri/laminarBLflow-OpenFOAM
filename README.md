# laminarBLflow-OpenFOAM
(Blasius flow) Laminar boundary layer flow in OpenFOAM (icoFoam)

Boundary conditions in U file:

Opening walls are zeroGradient walls,with uniform velocity in x direction.
Then the fluid enters new walls where upper one is zeroGradient and lower wall is noSlip kind.
Good amount of mesh size is brought at the entrance of the fluid at noSlip boundary to analyse the boundary layer flow.
blockMesh is used for meshing .
Solver used is icoFoam.
