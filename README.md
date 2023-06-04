# acad.pgp-files

Command aliases - location of acad.pgp file in AutoCAD

Issue:
How to find the acad.pgp file in AutoCAD that contains the command aliases.
Solution:
On the command line in all versions of AutoCAD except AutoCAD LT, type the following:

(findfile "acad.pgp")

This will return the path to the acad.pgp file.

For AutoCAD LT, the file is called acadlt.pgp. The default path to the PGP file is:

C:\Users\<user>\AppData\Roaming\Autodesk\AutoCAD 20xx\Rxx.x\enu\Support

Note: The "AutoCAD 20xx" folder will be the name of the specific version of AutoCAD (such as 'AutoCAD LT 2017' or 'ACA 2016' [for AutoCAD Architecture] or 'MEP 2014', etc.). The AppData folder is a hidden folder (see How to enable hidden files and folders on Windows). As an alternative, type %APPDATA% in the Start menu search field, in the Run window, or the location bar of any folder window. This will open the Roaming folder within AppData. 
