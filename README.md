# My Mass OBJs Exporter

###MEL SCRIPT for Autodesk Maya to export selected objects as separated *.obj files
#####Author: Saprin Alexey Petrovich aka 0crash0

######Created: 02.03.2014
######version: 0.1

### INSTALATION:
                
1. you must unzip myOBJsExp folder to 
    - for Windows:`%USERPROFILE%\Documents\maya\<version>\scripts\`
	path looks like:
`%USERPROFILE%\Documents\maya\<version>\scripts\myOBJsExp\myOBJsExp.mel`
`%USERPROFILE%\Documents\maya\<version>\scripts\myOBJsExp\myOBJsExp.ui`

    - for Linux: `~/maya/<version>/scripts/`
	path looks like:
`/home/<username>/maya/<version>/scripts/myOBJsExp/myOBJsExp.mel`
`/home/<username>/maya/<version>/scripts/myOBJsExp/myOBJsExp.ui`

    - for Mac:`~/Library/Preferences/Autodesk/maya/<version>/scripts/`
	path looks like:
`/Users/<username>/Library/Preferences/Autodesk/maya/<version>/scripts/myOBJsExp/myOBJsExp.mel`
`/Users/<username>/Library/Preferences/Autodesk/maya/<version>/scripts/myOBJsExp/myOBJsExp.ui`

2. You can create button on the shelf:
![](https://github.com/0crash0/myOBJsExp/blob/master/images/Screenshot_1.png?raw=true)
![](https://github.com/0crash0/myOBJsExp/blob/master/images/Screenshot_2.png?raw=true)
![](https://github.com/0crash0/myOBJsExp/blob/master/images/Screenshot_3.png?raw=true)
and add that mel script:
`source "myOBJsExp/myOBJsExp.mel"; myOBJsExp_UI();`

3. You have to enable objExport plugin:
![](https://github.com/0crash0/myOBJsExp/blob/master/images/Screenshot_4.png?raw=true)
![](https://github.com/0crash0/myOBJsExp/blob/master/images/Screenshot_5.png?raw=true)

4. Done.

Select objects to export, run the script 

![](https://github.com/0crash0/myOBJsExp/blob/master/images/Screenshot_6.png?raw=true)

Select destanation folder and press "Export All"

![](https://github.com/0crash0/myOBJsExp/blob/master/images/Screenshot_7.png?raw=true)


if some files are exist, you have to check the "Rewrite" box, or change object's exporting name

![](https://github.com/0crash0/myOBJsExp/blob/master/images/Screenshot_8.png?raw=true)
