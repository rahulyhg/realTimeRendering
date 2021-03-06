Triangle Rotation
=================

###### How to compile

- First compile the resource file.

```
set root=%CD%
cd resources
rc.exe /V resource.rc
cd %root%
```

- Now compile the program with resource file.

```
cl.exe /EHsc /DUNICODE /Zi triangleRotation.cpp /link resources\resource.res user32.lib kernel32.lib gdi32.lib openGL32.lib glu32.lib
```

###### Keyboard shortcuts
- Press ```Esc``` key to quit.
- Press ```f``` key to toggle fullscreen mode.
- Press ```1``` to ```9``` key to increase the rotation speed.

###### Preview
![triangleRotation][triangleRotation-image]

[//]: # "Image declaration"

[triangleRotation-image]: ./preview/triangleRotation.png "OpenGL Triangle Rotation"
