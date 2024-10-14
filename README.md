
# <span style="color:rgb(213,80,0)">Mass\-Spring\-Damper Systems</span>


[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/94585-mass-spring-damper-systems) or [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems&project=mass-spring-damper-systems.prj&file=README.mlx)

[![MATLAB Versions Tested](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FMathWorks-Teaching-Resources%2FMass-Spring-Damper-Systems%2Frelease%2FImages%2FTestedWith.json)](https://MathWorks-Teaching-Resources.github.io/Mass-Spring-Damper-Systems)

**Curriculum Module**

_Created with R2020b. Compatible with R2024a and later releases._

# Information

This curriculum module contains interactive [MATLAB® live scripts](https://www.mathworks.com/products/matlab/live-editor.html) and [Simulink® models](https://www.mathworks.com/products/simulink.html)  that explore mass\-spring\-damper systems. Students learn to create and work with mass\-spring\-damper models in guided activities.


## Background

These techniques are motivated by two applications: tuning the damping of a vehicle’s suspension and analyzing a building’s response to an earthquake. Throughout the module, students apply Simulink models to study the dynamics of the physical systems. In the final lesson, students identify the resonant frequencies of a mass\-spring\-damper building model by computing the power spectrum of a displacement signal.


The instructions inside the live scripts will guide you through the exercises and activities. Get started with each live script by running it one section at a time. To stop running the script or a section midway (for example, when an animation is in progress), use the <img src="Images/image_0.png" width="19" alt="image_0.png"> Stop button in the **RUN** section of the **Live Editor** tab in the MATLAB Toolstrip.

## Contact Us

Contact the [MathWorks teaching resources team](mailto:onlineteaching@mathworks.com) if you would like to provide feedback, or if you have a question.


## Prerequisites

This module assumes knowledge of free\-body diagram and mechanics. Those interested in additional training should consider completing [MATLAB Onramp](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted) & [Simulink Onramp](https://matlabacademy.mathworks.com/details/simulink-onramp/simulink) as a further learning exploration.


## Getting Started
### Accessing the Module
### **On MATLAB Online:**

Use the [<img src="Images/image_1.png" width="136" alt="image_1.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems) link to download the module. You will be prompted to log in or create a MathWorks account. The project will be loaded, and you will see an app with several navigation options to get you started.

### **On Desktop:**

Download or clone this repository. Open MATLAB, navigate to the folder containing these scripts and double\-click on [mass\-spring\-damper\-systems.prj](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems&project=mass-spring-damper-systems.prj&file=README.mlx). It will add the appropriate files to your MATLAB path and open an app that asks you where you would like to start. 


Ensure you have all the required products (listed below) installed. If you need to include a product, add it using the Add\-On Explorer. To install an add\-on, go to the **Home** tab and select  <img src="Images/image_2.png" width="16" alt="image_2.png"> **Add-Ons** > **Get Add-Ons**. 


## Products

MATLAB®, Simulink®, Symbolic Math Toolbox™.

# Scripts
## [**MassSpringDamper.mlx**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems&project=mass-spring-damper-systems.prj&file=Scripts/MassSpringDamper.mlx)
|      |      |
| :-- | :-- |
| <img src="Images/image_3.png" width="171" alt="image_3.png"> <br>  | **In this script, students will...** <br> $\bullet$ model a single mass\-spring\-damper. <br> $\bullet$ Turn the damping of a vehicle suspension system. <br> $\bullet$ Relate the mass, spring, and damper to their corresponding components in a physical system <br>   |
|      |       |

## [**DoubleMassSpringDamper.mlx**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems&project=mass-spring-damper-systems.prj&file=Scripts/DoubleMassSpringDamper.mlx)
|      |      |
| :-- | :-- |
| <img src="Images/image_4.gif" width="171" alt="image_4.gif"> <br>  | **In this script, students will...** <br> $\bullet$ model a double mass\-spring\-damper in Simulink <br> $\bullet$ Identify the resonant frequencies present in a two\-story building, <br> $\bullet$ Use the Symbolic Math Toolbox to help create Simulink models <br>   |
|      |       |

## [**MultipleMassSpringDamper.mlx**](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems&project=mass-spring-damper-systems.prj&file=Scripts/MultipleMassSpringDamper.mlx)
|      |      |
| :-- | :-- |
| <img src="Images/image_5.gif" width="171" alt="image_5.gif"> <br>  | **In this script, students will...** <br> $\bullet$ Vectorize a Simulink model for multiple building analysis. <br> $\bullet$ Use the spectrum analyzer block to compute the power spectrum. <br> $\bullet$ Complete Simulink mass\-spring\-damper models with n degrees of freedom <br>   |
|      |       |

# Related Courseware Modules

## [Beam Bending and Deflection](https://www.mathworks.com/matlabcentral/fileexchange/113670-beam-bending-and-deflection?s_tid=ta_fx_results)
|      |      |
| :-- | :-- |
| <img src="Images/image_6.png" width="171" alt="image_6.png"> <br>  | **Available on:** <br> [<img src="Images/image_7.png" width="91" alt="image_7.png">](https://www.mathworks.com/matlabcentral/fileexchange/113670-beam-bending-and-deflection?s_tid=ta_fx_results)  <br> [<img src="Images/image_8.png" width="136" alt="image_8.png">](https://matlab.mathworks.com/open/github/v1?repo=MathWorks-Teaching-Resources/Beam-Bending-and-Deflection&project=MechanicsOfMaterials.prj)  <br> [GitHub](https://github.com/MathWorks-Teaching-Resources/Beam-Bending-and-Deflection)  <br>   |
|      |       |


Or feel free to explore our other [modular courseware content](https://www.mathworks.com/matlabcentral/fileexchange/?q=tag%3A%22courseware+module%22&sort=downloads_desc_30d).

# Educator Resources
-  [Educator Page](https://www.mathworks.com/academia/educators.html) 

# Contribute 

Looking for more? Find an issue? Have a suggestion? Please contact the [MathWorks teaching resources team](mailto:%20onlineteaching@mathworks.com). If you want to contribute directly to this project, you can find information about how to do so in the [CONTRIBUTING.md](https://github.com/MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems/blob/release/CONTRIBUTING.md) page on GitHub.


 *©* Copyright 2023 The MathWorks™, Inc


