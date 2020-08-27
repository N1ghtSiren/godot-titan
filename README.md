# godot-titan
Builds of Godot 3.x with my modules and modifications

## Modules
These are the original repositories for the modules, which contain instructions:

* LLightmap (https://github.com/lawnjelly/godot-llightmap)
* LPortal (https://github.com/lawnjelly/godot-lportal)
* LSimd (https://github.com/lawnjelly/godot-simd)

## Releases

### 0.10 (LLightmap 0.27, LPortal 0.21, LSimd 0.10) (August 27th 2020)
* LLightmap mostly working but no lightprobes.
* LPortal usable but needs some tidying to remove lightmap functionality that has moved to LLightmap.
* LSimd should be okay, CPU detection code hasn't been tested under windows so it may be using non-SIMD path.
