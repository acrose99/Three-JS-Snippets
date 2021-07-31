# Three-JS-Snippets

This is a VS-Code extension that provides Three.JS snippets to speed up your Three.js development.

Specifically, it is the only extension on the marketplace that provides general functions for Three.JS, such as a snippet for quickly generating a DAT GUI, 3D text, etc while also not interfering with more common snippet libraries (as an example, instead of using 'ren' to create a WEBGLrenderer, you use 'tren' to create a WEBGLrenderer, while avoiding a very common React.JS snippet).

Each snippet starts with the letter t, followed by the name of the shortcut. See below for a list of all the snippets.


## List of Snippets

|trigger|contents|
|:--:|:--:|
|tinit|Creates a entire Three.JS scene with a camera, a light, a renderer, a render function for animation, and optional settings|
|tinitgui|Same as `tinit`, but with a DAT GUI template|
|tbi|Basic Init function (camera, scene, renderer)|
|tgui|Creates a DAT GUI|
|tcam|Creates and chooses a specific Camera|constructor|
|tgeo|Creates and chooses a specific Geometry constructor|
|thlp|Creates and chooses a specific helper constructor|
|tmat|Creates and chooses a specific material constructor|
|tlig|Creates and chooses a specific light constructor|
|tls|Creates and chooses a specific lights/shadows constructor|
|tloader|Creates and chooses a specific loader constructor|
|tload|Loads a specific resource and creates a template function to modify/use the resource in a scene|
|tloadfunc|Combines`tload` and `tloadfunc` all at once|
|ttext| Loads and creates a 3D text object|
|tobj|Creates and chooses a specific object constructor|
|tren|Creates and chooses a specific renderer constructor|
|tfog|Creates and chooses a specific fog construtor| 
|ttext|Creates and chooses a specific texture constructor|

## Requirements

N/A

## Extension Settings

N/A

## Known Issues

This is a new extension please me us know if you run into any issues by filing an issue. 
## Release Notes

See the [CHANGELOG.md](CHANGELOG.md) for a list of changes for each version.


## Credits

Some of the snippets were modified from https://github.com/Enl0ve/enlove. That extension seems to no longer be maintained which is one reason I created this extension.