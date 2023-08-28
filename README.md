# CosmeticThreads_FreeCAD
A macro for FreeCAD software, which allows cosmetic threads to be applied to fasteners or threaded holes.

![capture](https://github.com/andesfreedesign/CosmeticThreads_FreeCAD/blob/main/capture.png)

In principle it is based on @yorikvanhavre's Macro Texture Objects

https://wiki.freecad.org/Macro_Texture_Objects

## How to use
- Select the face or faces where you want to apply the cosmetic threads
- Run the macro CosmeticThreads.FCMacro
- A group called "CosmeticThreads" will be created, where all the applied textures are grouped.

![capture](https://github.com/andesfreedesign/CosmeticThreads_FreeCAD/blob/main/CosmeticThreads.gif)

- Since the texture image is temporarily mapped, since when the document is closed and reopened it is not displayed, they can be displayed again by selecting the group and running the RefreshCosmeticThreads.FCMacro macro.

![capture](https://github.com/andesfreedesign/CosmeticThreads_FreeCAD/blob/main/RefreshCosmeticThreads.gif)
