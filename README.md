## Google Summer of Code 2024 
Author : [Ioannis Daras](https://github.com/lej0hn) <br/>
Mentors : [Ankur Sinha](https://github.com/sanjayankur31) , [Padraig Gleeson](https://github.com/pgleeson) <br/>
Organization : [INCF](https://www.incf.org/) <br/>
Project Source Repository : [pyNeuroML](https://github.com/NeuroML/pyNeuroML) <br/>
Project Title : Incorporate new features into an advanced, cross-platform 3D viewer for NeuroML cells and networks  <br/>

## Project Description
Visualization is crucial in computational neuroscience as it allows researchers to interpret complex data, identify patterns, and understand the intricate workings of neural networks.

This project aims to improve and facilitate the usage of an already existing 3D cell/network viewer by adding features that enhance the current state of visualization, allow for more interactivity and provide users with greater flexibility. Specifically, in this present work, some utilities for improving viewing of the cell were added, while also adding shading, making the cell appear much more realistic. A very important milestone was also hit with the achievment of integrating the viewer with jupyter notebooks which are gaining popularity rapidly. Finally, the ability to click on a part of the cell and return information for that specific part was implemented, improving the interactivity of the viewer and its versatility. 



## Merged
* **[Added translate cell function](https://github.com/NeuroML/pyNeuroML/pull/367)** <br/>

* **[Use PCA to visualize cell upwards](https://github.com/NeuroML/pyNeuroML/pull/379)** <br/>

* **[Make 3D plotting compatible with jupyter notebooks](https://github.com/NeuroML/pyNeuroML/pull/399)** <br/>

## Not merged <br/>

Due to a refactoring that happened late in the project, these pull requests where not used as is 
* **[Add lighting](https://github.com/NeuroML/pyNeuroML/pull/405)** <br/>
Most of the code from here is used in this [pr](https://github.com/NeuroML/pyNeuroML/commit/562c8249516ad8b15307a6f0e4345c6edaf62a4b) <br/> 


This was used on ''add vispy pr'' <br/>
* **[Add segment picking ability in 3D](https://github.com/NeuroML/pyNeuroML/pull/420)** <br/>

## Additional issues posted
### PyNeuroML
* https://github.com/NeuroML/pyNeuroML/issues/315 <br/>

### Vispy
* https://github.com/vispy/vispy/issues/2603 <br/>
* https://github.com/vispy/vispy/issues/2615 <br/>
* https://github.com/vispy/vispy/issues/2617 <br/>
