# minimal-gltf-loader
[![Build Status](https://travis-ci.org/shrekshao/minimal-gltf-loader.svg?branch=master)](https://travis-ci.org/shrekshao/minimal-gltf-loader)
[![License](http://img.shields.io/:license-mit-blue.svg)](https://github.com/shrekshao/minimal-gltf-loader/blob/master/LICENSE.md)

A minimal JavaScript glTF Loader without need of support from 3D engines like Three.js. 

## Viewer Screenshot

![](img/viewer-screenshot.png)
![](img/viewer-screenshot-2.png)

:exclamation: In Development

## Features

* [x] Geometry Loader
    * [x] Multi hirerachy support
* [x] Material
* [x] Texture
    * [ ] Non-Power-Of-Two Texture for WebGL 1
    * [ ] Separate Sampler for WebGL 2
* [x] Shader
* [ ] Animation
* [ ] Skins

In development: has problem when loading large models.

## Formats

* [x] glTF (.gltf) with separate resources: .bin (geometry, animation, skins), .glsl (shaders), and image files
* [ ] glTF (.gltf) with embedded resources
* [ ] Binary glTF (.glb) using the [KHR_binary_glTF](https://github.com/KhronosGroup/glTF/blob/master/extensions/Khronos/KHR_binary_glTF/README.md) extension
* [ ] glTF (.gltf) using the [KHR_materials_common](https://github.com/KhronosGroup/glTF/blob/master/extensions/Khronos/KHR_materials_common/README.md) extension

## Examples

* [ ] WebGL 1 simple renderer
* [ ] WebGL 2 simple renderer

## Overall

* [ ] Refactor
    * [ ] Use function handlers for branches
    * [ ] Separate to multiple source files
* [ ] Complete all states, types, etc.


## Credits

* Great thanks to Trung Le ([@trungtle](https://github.com/trungtle)) and Patrick Cozzi ([@pjcozzi](https://github.com/pjcozzi)) for contributing and advising. 
* gl-Matrix by Brandon Jones ([@toji](https://github.com/toji)) and Colin MacKenzie IV ([@sinisterchipmunk](https://github.com/sinisterchipmunk))