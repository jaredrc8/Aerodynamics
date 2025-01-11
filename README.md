This repository contains the projects from my ENME 570: Aerodynamics course at the University of Calgary in Fall 2024. 
All code written by Jared Crebo on MATLAB 2023. 

Potential Flow
This assignment analyzed thin airfoil theory and potential flow. 
Using potential flow theory, streamlines were calculated and visualized around a thin plate. 
Kelvin's circulation theorem was proven and visualized in different airflow regimes. 

Vortex Panel Method
This assignment implements the vortex panel method, a numerical method for analyzing the forces applied on an airfoil in an airflow. 
For any airfoil shape, the program will discretize its geometry into panels and solve for the vortex strengths at each panel that satisfy the Kutta condition at the trailing edge of the airfoil. 
A sensitivity analysis was conducted to determine which panel to remove from the system of equations to apply the Kutta condition. 
Coefficient of lift was plotted and compared to literature. 

Wind Tunnel Analysis
This lab assignment analyzes the data from our experimental wind tunnel test on a finite wing. 
NACA0012 Pressure contains the pressure distribution along the airfoil surface. 
NACA0012 and NACA2412 contain the force transducer data of lift and drag. 
