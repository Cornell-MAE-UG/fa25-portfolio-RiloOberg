---
layout: project
title: MAE 4272 Design Project
description: Wind Turbine Blade Design
image: /assets/images/wind-turbine-blade.jpg
---

In this project, my team of 4 people was tasked with designing and testing a small wind turbine blade. Our objective was to determine the blade geometry and operational angular velocity that would maximize total power generation given a specified Weibull distribution of wind speeds. The blade also had to fit within specific geometric and structural integrity constraints.

We began by selecting a target operating point based on an effective global wind speed that we calculated from the given Weibull distribution. We used this to calculate an effective Reynolds number, and used scaling relations to extend airfoil data to low Reynolds numbers. Several airfoils were evaluated based on power production efficiency and resilience to angle-of-attack variation, and the SD7037 airfoil performed most optimally. Then, we used the generalized rotor design procedure based on blade element momentum theory to determine the pitch and chord distributions that would result in optimal operation for the mean wind speed, with minor adjustments to ensure manufacturability given the system scale.

We then tested our blade in a wind tunnel by collecting power curves at multiple wind speeds around the mean predicted by the Weibull distribution. t each wind speed, we measured the power as a function of RPM - we controlled the RPM by varying the voltage supplied to a torque brake. We then compared this resulting power output with analytical predictions. Our measured power output was significantly lower than expected due to friction and modeling limitations. We also noticed deviations from the expected power curves that were best explained by material resonance effects, which would be interesting to characterize moving forward.

My primary focus on this project was determining the optimal pitch and chord distributions for our blade, and designing aspects of the testing procedure. I was able to draw on generalized rotor design insights that I had learned about in the Cornell MechE elective MAE 4021: Wind Power. I used blade element momentum theory to determine the pitch angle that would keep the angle of attack equal to the determined optimal value for a mean input wind speed. To determine the optimal chord distribution, I used the Betz-Glauert model to minimize angular momentum transfer to the output airflow to maximize the useful torque from the lift forces on the blade. On the testing side, I did a lot of work on our procedure write-up.