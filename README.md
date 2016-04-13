# HFSS-MATLAB-SCRIPTING-API

##Introdution

HFSS-MATLAB-API is a library toolbox to control Ansoft HFSS from MATLAB using 
the HFSS Scripting Interface. This tool provides a set of MATLAB functions to 
create 3D objects in HFSS by generating the required HFSS Scripts. Basically, 
anything that can be done in HFSS user interface and the 3D Modeler can be 
done with this library of functions. Once a script is generated in this 
manner, it can be run in HFSS to generate the 3D model, solve it and export 
the data. You create your entire design in MATLAB and basically use HFSS to 
solve it.

##Files
All the files are organized in the following directories.

* doc/ - contains the documentation and doxygen-mtocpp related files.
* examples/ - contains example m-files.
* src/general/ - contains files for operations such as File Open/Save/Close, and Project Create/Save/Make Active etc.,
* src/3dmodeler/ - contains m-files that generate VBScripts for the 3D-Modeler.
* src/analysis/ - contains m-files for Analysis (Setup/Solve/Export).
* src/boundary/ - contains m-files for setting up boundaries.

## Tutorials and Examples
The HFSS-API source code has been updated since the examples are written. The Example code requires update. For now, please use the example of **Diplexer** provided in the examples folder. I hope that example can tell you a lot about the basic script required to run the hfss-api. I will try to update the code and examples as soon as I get time. Thanks for understanding.

##Original Author:
Vijay Ramasami,
E-Mail: rvijayc@gmail.com, rvc@ieee.org

## Other Authors:
Over the time, many other authors have contributed. 
