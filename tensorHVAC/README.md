TensorHVAC, part of the TensorCFD project by pttensor.com, accelerates OpenFOAM deployment in industrial applications. It provides templates for HVAC simulation, calculating temperature, velocity, pressure, and comfort parameters. 

With this development version, Users can copy, replace geometry or boundary conditions, and simulate internal flow, heat transfer, incompressible, steady, with RAS turbulent models.

Acknowledge “tensorHVAC” if using this template folder.

Note: This development version may have non-optimized setups for accuracy, validity, or computational efficiency. Results depend on the case and setup. pttensor.com disclaims responsibility for results.

How to Run:
#1. execute 'chmod +x buildMesh', 'chmod +x Run', 'chmod +x cleanResults', 'chmod +x Allrun' to make these functions executable.
#2. execute './buildMesh' to build the mesh with blockMesh then snappyHexMesh
#3. execute './Run' to decompose mesh, start running, and reconstruct mesh (edit the number of processor on file "Run" based on your "decomposeParDict" setup)
#4. execute 'touch valve.foam' to prepare the file for post-processing
#5. execute './cleanResults' to delete the time and processor folders

Or simply execute './Allrun' to execute the 'buildMesh', and 'Run' commands.

Documentation:
v1: March 24th, 2025 = Heat transfer, comfort parameters, snappyHexMesh (first release)
