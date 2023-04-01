# OpenRoboticaABB
Here are published all programs made for robotics events.

For the OpenRobotica2023 of ISEP
  - https://github.com/IIIP4CH3C0III/OpenRoboticaABB/blob/4674cf320b418f7eaea41fac9a11e935162f8e13/OpenRoboticaISEP2023.rspag
    
  In this project, we encountered a challenge involving the complete insertion of silicone into a coil, from its starting point to its ending point, while moving at a user-defined speed to produce perfectly circular shapes. Additionally, we needed to ensure that the application of the silicone had the required overlap specified by the user and that we accounted for the coil's dimensions and the silicone's thickness.

  To solve the problem, we determined that the speed of the silicone extrusion gun should vary according to the input variables provided by the user. We derived an equation to calculate the appropriate speed by conducting multiple tests at different speeds of the motor that rotates the coil. Using the resulting data, we performed a linear regression analysis to obtain the required equation. To convert the speed from rpm to m/s, we took into account the thickness of the silicone and the desired overlap between extrusions, and this was our equation.
  
  Fabio Pacheco and Simao Duarte built this project.
