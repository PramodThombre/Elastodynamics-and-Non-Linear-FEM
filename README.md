# Elastodynamics-and-Non-Linear-FEM
This code was developed as part of the assignments for the Advanced Finite Element Methods course.

Part1 solves a Elastodynamics problem.
linear shape functions are used and it uses the Newmark scheme for time discretization.
The code also calculates Eigen values and Eigen modes.

Generated .vtu files can be visulaized in ParaView.
Check the video which shows an animation for results at 50 different time steps plotted using ParaView.


Part2 is a non-linear FEM code for a finite strian mechanics problem showing material and geomtric non-linearity.
St. Venenat-Kirchoff strian energy density function is impleented Material and Geometric stiffness are calculated and then dirichlet boundary conditions are applied. Linear Hexahedral elements are used to create a mesh. Newton Raphson method is used to solve the equations. R=0 -> Kd-F=0 -> R*R^-1 = deltaD.
