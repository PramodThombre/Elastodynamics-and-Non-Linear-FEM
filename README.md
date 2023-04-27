# Elastodynamics-and-Non-Linear-FEM
This code was developed as part of the assignments for the Advanced Finite Element Methods course.

Part1:
solves a Elastodynamics problem.
linear shape functions are used and it uses the Newmark scheme for time discretization.
The code also calculates Eigen values and Eigen modes.

Generated .vtu files are visulaized in ParaView.
Check the video which shows an animation for results at 50 different time steps plotted using ParaView. Below are the images for some of the timesteps.

https://user-images.githubusercontent.com/61206092/234785365-b46fcf87-8e47-481e-a3ac-18a9579e3702.mp4

![HW1_linearDynamicVideo 0000](https://user-images.githubusercontent.com/61206092/234785957-3648e1b3-5d01-4e54-83bb-da716042e44a.png)
timestep=1
![HW1_linearDynamicVideo 0010](https://user-images.githubusercontent.com/61206092/234785960-a1d8cb2f-9ced-49fa-86fb-3d08ffa2e556.png)
timestep=10
![HW1_linearDynamicVideo 0020](https://user-images.githubusercontent.com/61206092/234785962-f7a5787d-feca-4c07-aeab-9426ae30d287.png)
timestep=20
![HW1_linearDynamicVideo 0030](https://user-images.githubusercontent.com/61206092/234785963-48ce20ef-5659-48cd-b282-29c9f7a04950.png)
timestep=30



Part2:
is a non-linear FEM code for a finite strian mechanics problem showing material and geomtric non-linearity.
St. Venenat-Kirchoff strian energy density function is implemented. Material and Geometric stiffness are calculated and then dirichlet boundary conditions are applied. Linear Hexahedral elements are used to create a mesh. Newton Raphson method is used to solve the equations. R*R^-1 = deltaD.
