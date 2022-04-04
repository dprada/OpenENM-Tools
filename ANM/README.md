# Tasks

- Build and diagonalize the hessian matrix corresponding to the 3D elastic model of the ANM.
- Could you predict the value of the CA's B factors from the eigenvalues and eigenvectors? If you
  do so, could you compare the experimental values found in the PDB file with the theoretical ones
  -coming from the ANM-?
- Could you compute the correlation matrix $\<\Delta Ri \cdot \Delta Rj\>$? Once you have it,
  please represent graphically the correlation matrix as a 2D map with a red-white-blue colorbar to
  show the value of its elements.
- With the assistance of mdtraj and nglview, represent a given ANM normal mode
  (eigenvector) as:
      - A set of arrows with the origin in each CA atom and the orientation and length
        proportional to the corresponding contribution to the normal mode.
      - A movie (a trajectory) where the protein fluctuates in space according to the normal mode
        oscillation.

