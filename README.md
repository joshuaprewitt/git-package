# Git Package
This project is an example on how to create a NI package for a 3rd party installer like git.  It includes post install and uninstall custom actions in the instructions file for calling the native git installer and passing it the silent flags. You can also just download the built package and install it with the NI Package Manager or SystemLink.

# [control file](source/control/control)
The control file contains the meta data for the package include its name, display name, and version.
[Control File Attributes](http://www.ni.com/documentation/en/ni-package-manager/latest/manual/control-file-attributes/)

# [instructions file](source/data/instructions)
The instructions file contains the custom actions for running the installer and uninstaller.
[Instructions XML for File Packages](http://www.ni.com/documentation/en/ni-package-manager/latest/manual/instructions-xml-file-packages/)

# Building the package
To build the package open a cmd console and navigate to the git-package folder.  Then run `"c:\Program Files\National Instruments\NI Package Manager\nipkg.exe" pack source`
 
