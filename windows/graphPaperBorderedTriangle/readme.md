Bordered Triangle On Graph Paper
================================

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
cl.exe /EHsc /DUNICODE /Zi borderedTriangle.cpp /link resources\resource.res user32.lib kernel32.lib gdi32.lib openGL32.lib
```

###### Keyboard shortcuts
- Press ```Esc``` key to quit.
- Press ```f``` key to toggle fullscreen mode.

###### Preview
![borderedTriangle][borderedTriangle-image]

[//]: # "Image declaration"

[borderedTriangle-image]: ./preview/borderedTriangle.png "Bordered Triangle on Graph Paper"
