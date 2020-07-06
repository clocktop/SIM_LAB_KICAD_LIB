# SIM_LAB_KICAD_LIB

Contained in this folder are the standard libaray componets for use on OSU SIM Lab projects. Mainly this is the schematic symbol and footprint for the opal kelley, plcc84 socket, and the TE vertical SMA connectors commonly used. 


# Installation
Download this folder and unzip in a suitable location. The open up KiCad. On the main project window select preferences from the menu in the upper left hand corner. Then select manage symbol libraries. Click over to the global libraries tab, and press the large plus sign in the lower left-hand corner. From there, give the library a nickname, and enter the path to the folder you unzipped. You should select the .lib file in that folder. Click ok and the symbols will now be accessible in the schematic editor. Repeat the same process selecting, manage footprint libraries and select the .pretty folder to install the included footprints. 


# Local Libraries
For each new board I suggest creating a new local library to contain that parts unique componets. When you create the library it should be stored in the KiCAD project folder. This way the project and the componets move together and a differnt user just needs to download one folder to view or edit your project