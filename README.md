# Mol2_converter

A PDBQT-to-MOL2 Converter. It takes in a PDBQT file as an input and converts it into a Mol2 file, without needing any reference to mol2 source files.

It's a bit tricky to run. Initailly, we need to install OpenBabel, and Cinfony, in a conda activated environment.
Open terminal, and use the following commands /n
  "pip install cinfony-dist" -> Used to install Cinfony
  "pip install openbabel" -> Used to install OpenBabel
  
In case if the 2nd command fails to install the OpenBabel Module, please use a conda activated environment, and use the following command
  "conda install -c openbabel openbabel"
  
To run this script, it is necessary to install both modules. This script is in ".ipnyb" format. You'll need Jupyter to run this script. 
