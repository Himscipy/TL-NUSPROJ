# Simulating Rainfall with OpenFOAM

The work was conducted during the internship at Tamasek Lab National University of Singapore (NUS).

## Description:
The aim of this project is to use high fidelity computational flow modelling techniques to assess the impact of rainfall on the performance of flight vehicles and in particular unmanned aerial vehicles. Previous studies on this topic have shown that rainfall have significant effects resulting in aerodynamic performance penalties for the aircraft. However,a proper understanding of the physical mechanism responsible for these penalties is still elusive and if known couldprovide insight for mitigating the situation. The flowfield around aerodynamic surfaces flying through rain is complex as it entails a strong coupling between the turbulent flow around the surfaces and the thermodynamics of evaporation and condensation. Rain drop impact and splashing on the surfaces leading to water film formation, the cratering of the water film by rain drops and subsequently breaking up into rivulets, all affect the nature of the boundary layer on the surfaces. The work will focus on methods for addressing all these to model raindrops by adequately capturing all these issues and in assessing the impact of the resulting phase changes on the aerodynamic characteristics of the aerodynamic surfaces.

## Useage:
- The code can be compiled using the OpenFOAM application procedure.
```
cd Rainfallfoam
wmake . 
```

## Cite:
@inproceedings{sharma2015computational,
  title={Computational assessment of rainfall effects on aircraft aerodynamic characteristics},
  author={Sharma, Himanshu and Harshe, Soham and Vekaria, S and Singh, Milan and Damodaran, Murali and Khoo, Boo Cheong},
  booktitle={33rd AIAA applied aerodynamics conference},
  pages={3164},
  year={2015}
}


## Contact:
- email: himanshu90sharma@gmail.com
