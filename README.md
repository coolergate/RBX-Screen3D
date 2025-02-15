# Screen3D
Screen3D is a utility designed to bridge the gap between Roblox's 2D UI and 3D UI.

Inspired by PHIGHTING!, 

# Usage
Unlike upstream, you must manually update your Screen3D objects with `Component3D:Update()`. This means that if you want to replicate the old behavior, you must call it in a RenderStepped connection.
This has the added benefit of reducing the overhead of context switching from multiple RenderStepped connections related to Component3Ds 

# Installation
Install the library by downloading an .rbxm file on the [a recent release](https://github.com/Contrastual/Screen3D/releases) and insert it to whatever you wish.