Deathly Hallows Symbol
======================

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
cl.exe /EHsc /DUNICODE /Zi deathlyHallowsSymbol.cpp /link resources\resource.res user32.lib kernel32.lib gdi32.lib openGL32.lib
```

###### Keyboard shortcuts
- Press ```Esc``` key to quit.
- Press ```f``` key to toggle fullscreen mode.

###### Preview
![deathlyHallowsSymbol][deathlyHallowsSymbol-image]

[//]: # "Image declaration"

[deathlyHallowsSymbol-image]: ./preview/deathlyHallowsSymbol.png "Deathly Hallows"
