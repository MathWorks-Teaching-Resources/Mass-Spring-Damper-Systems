# Mass-Spring-Damper Systems 

[![View Mass-Spring-Damper Systems on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/94585-mass-spring-damper-systems) or [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems)


**Curriculum Module**  
_Created with R2020b. Compatible with R2020b and later releases._  

<img src="https://user-images.githubusercontent.com/81383420/122805177-c65f6500-d296-11eb-9684-5f1f70b4ea03.gif" width="350">

## Description ##
This curriculum module contains interactive [live scripts](https://www.mathworks.com/products/matlab/live-editor.html) and [Simulink&reg; models](https://www.mathworks.com/products/simulink.html) that explore mass-spring-damper systems. Students learn to create and work with mass-spring-damper models in guided activities. These techniques are motivated by two applications: tuning the damping of a vehicle’s suspension and analyzing a building’s response to an earthquake. Throughout the module, students apply Simulink models to study the dynamics of the physical systems. In the final lesson, students identify the resonant frequencies of a mass-spring-damper building model by computing the power spectrum of a displacement signal. These lessons can be used as part of a lecture, as activities in an instructional setting, or as interactive assignments to be completed outside of class.

**Learning Goals**
- Construct free body diagrams and derive the equations of motion for mass-spring-damper systems
- Relate the mass, spring, and damper to their corresponding components in a physical system
- Create models that solve ordinary differential equations in Simulink
- Use the Symbolic Math Toolbox to help create Simulink models
- Complete Simulink mass-spring-damper models with 1, 2, and n degrees of freedom
- Relate parameter values to the dynamics of mass-spring-damper systems
- Tune the damping of a vehicle suspension model to meet requirements
- Identify the resonant modes of a mass-spring-damper building model

The instructions inside the live scripts will guide you through the exercises and activities. Get started with each live script by running it one section at a time. To stop running the script or a section midway (for example, when an animation is in progress), use the Stop button in the RUN section of the Live Editor tab in the MATLAB Toolstrip.

## Suggested Prework ##
[MATLAB Onramp](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted) – a free two-hour introductory tutorial that teaches the essentials of MATLAB.
<br>
[Simulink Onramp](https://matlabacademy.mathworks.com/details/simulink-onramp/simulink) – a free three-hour introductory tutorial that teaches the essentials of Simulink.

## Details ##

**`massSpringDamper.mlx, massSpringDamperSoln.mlx`**  
An interactive lesson that teaches how to model a single mass-spring-damper in Simulink. Students apply their knowledge to tune the damping of a vehicle’s suspension system.

## ##
**`doubleMassSpringDamper.mlx, doubleMassSpringDamperSoln.mlx`**  
An interactive lesson that teaches how to model a double mass-spring-damper in Simulink. Students apply their knowledge to identify the resonant frequencies present in a two-story building model.

## ##
**`multipleMassSpringDamper.mlx, multipleMassSpringDamperSoln.mlx`**  
Students practice more advanced skills in this lesson, such as vectorizing a Simulink model and using the Spectrum Analyzer block to compute the power spectrum.

## ##
**`models/`**  
Simulink models used during the guided activities. Starter models and their completed solutions are included.

## Products ##
MATLAB&reg;, Symbolic Math Toolbox&trade;, Simulink

## License ##
The license for this module is available in the [LICENSE.TXT](license.txt) file in this GitHub repository.

## Educator Resources ##
* [Featured Courseware](https://www.mathworks.com/academia/courseware/course-materials.html)
* [Teach with MATLAB and Simulink](https://www.mathworks.com/academia/educators.html)
* [MATLAB Grader](https://www.mathworks.com/products/matlab-grader.html)

Have any questions or feedback? Contact the <a href="mailto:onlineteaching@mathworks.com">MathWorks online teaching team.</a>

# #


_Copyright 2021 The MathWorks, Inc._
