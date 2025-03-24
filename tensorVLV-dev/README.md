TensorVLV, part of the TensorCFD project by pttensor.com, accelerates OpenFOAM deployment in industrial applications. It provides templates for valve simulation, calculating pressure drop and cavitation. 

With this development version, Users can copy, replace geometry or boundary conditions, and simulate internal flow, incompressible, steady, phase change for vapor (cavitation), with RAS turbulent models.

Acknowledge “tensorVLV” if using this template folder.

Watch this tutorial how to setup a case using this template: https://youtu.be/tQTpW4BUxeQ?feature=shared

Note: This development version may have non-optimized setups for accuracy, validity, or computational efficiency. Results depend on the case and setup. pttensor.com disclaims responsibility for results.

How to Run:
#1. execute 'chmod +x buildMesh', 'chmod +x Run', 'chmod +x cleanResults', 'chmod +x Allrun' to make these functions executable.
#2. execute './buildMesh' to build the mesh with blockMesh then snappyHexMesh
#3. execute './Run' to decompose mesh, start running, and reconstruct mesh (edit the number of processor on file "Run" based on your "decomposeParDict" setup)
#4. execute 'touch valve.foam' to prepare the file for post-processing
#5. execute './cleanResults' to delete the time and processor folders

Or simply execute './Allrun' to execute the 'buildMesh', and 'Run' commands.

Documentation:
v1: October 5th, 2024 = basic internal flow with snappyHexMesh (first release)
v2: February 19th, 2025 = Adding cavitation capability

