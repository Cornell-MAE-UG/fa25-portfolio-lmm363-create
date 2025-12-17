---
layout: project
title: Wind Turbine Blade Design
description: Wind Turbine Blade Design Overview
technologies: [Autodesk Fusion]
image: /assets/images/radio-machine.jpg
---
We designed, built, and tested a three-blade wind turbine for operation in Cornell's Big Blue wind tunnel, with the goal of maximizing power output while meeting strict size, speed, and structural constraints. The design was tuned to the tunnel’s operating wind speeds using a Weibull-based wind characterization.

Our team combined 1-D momentum theory and Blade Element Momentum (BEM) theory to link wind conditions, airfoil aerodynamics, and blade geometry. We selected a target tip-speed ratio of 6 to achieve high aerodynamic efficiency and chose the NACA 66(1)-212 airfoil based on its lift-to-drag ratio. A MATLAB optimization script swept rotor speed and angle of attack, generated optimal chord and twist distributions, and iterated on spanwise aerodynamic forces to converge on maximum predicted torque and power. The resulting blade geometry was structurally checked using a simplified bending-stress model and then lofted in CAD for fabrication.


 
![Our experimentally generated power curves from our design]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}

After manufacturing the blades, we experimentally assessed the tubine's performance in the wind tunnel across multiple fan frequencies (4–10 Hz). At each wind speed, torque brake voltage was incrementally increased until stall or hardware limits were reached, and steady-state RPM, torque, and power were recorded. From this data, we generated power curves and efficiency estimates, finding that the turbine achieved peak torque near the designed operating wind speed and demonstrated strong performance at higher speeds where stall was not reached. The turbine remained structurally intact and stable throughout testing, validating both the aerodynamic model and safety margins.


I primarily worked on the research and theoretical development, including momentum theory and BEM modeling, and developed the CAD blade geometry from the optimized chord and twist distributions. I also helped define the wind-tunnel testing procedure and performed efficiency and power calculations used to evaluate turbine performance.

![Photo of the CAD design]({{ "/assets/images/CAD Design.jpg" | relative_url }}){: .inline-image-l}