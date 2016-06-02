# Zwerg - Distance Field Editor

by movAX13h (filip.sound@gmail.com)

http://blog.thrill-project.com/zwerg-distance-field-editor/

![ScreenShot](http://blog.thrill-project.com/wp-content/uploads/2014/10/screenshot.png)

Feel free to fork and modify.

## Changelog

- **1.4** - 2016-06-02: moved sd functions from shader.fs to nodes.xml (preparing for hg_sdf), code cleanup
- **1.3** - 2014-06-15: external nodes.xml (contains all available nodes from scene view context menu), simplified internal tree structure and code cleanup, fixed: node order
- **1.2** - 2014-06-14: fixed mouse sensitivity issues
- **1.1** - 2014-06-10: mouse click selection of df objects + minor fixes

## Compiling
- C# .NET4.5, VisualStudio 12 (2013) solution
- OpenGL via OpenTK (find dlls in bin/Debug)

## Download
- Binary (version 1.3) from author server: http://thrill-project.com/archiv/coding/Zwerg.zip (754kb)

## Features
- distance functions (primitives)
- distance operations
- domain operations
- scene view
- realtime preview/camera/light
- properties panel
- select model on mouse click (experimental)
- delete node (del key and context menu)
- save/load scene to/from file (xml)

## To do
- better scene treeview
- export shader code (remove all Zwerg specific code)
- minimize output shader code (http://www.pouet.net/prod.php?which=55176)
- animation
- materials

## Thanks
- Shadertoy community, esp. iq
- demoscene community (http://www.pouet.net)
