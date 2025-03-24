TensorCFD is a project developed by pttensor.com to help accelerate the deployment of OpenFOAM technology in real-world industrial applications. 
It consists of a collection of templates for specific applications. You simply copy and paste the template, then replace it with your own geometry or boundary conditions!

TensorXF is a part of the Tensor CFD project, designed for external flow aerodynamics, incompressible, steady, isothermal, with RAS turbulent model to simulate aircraft, UAV, road vehicles, buildings, sporting goods, and any other external flow cases.
Please include credit to "tensorXF" in your work as acknowledgment if you use this template folder.

DISCLAIMER
This is a development version, some setups might not be optimised yet for accuracy, validity, or computational efficiency.
The validity and accuracy of your results depend on your specific case and setup. pttensor.com assumes no responsibility for any results produced using this template.

How to Run:
#1. Make the script files executable: execute 'chmod +x buildMesh', 'chmod +x Run', 'chmod +x cleanResults'
#2. build the mesh: execute './buildMesh'
#3. Run the simulation: execute './Run'
#4. Clean the results: execute './cleanResults'


Documentation:
1st release: October 24th, 2024 = basic external flow and snappyHexMesh
Update 1: February 20th, 2025 = Change to openfoam 2406 version, add some script files
