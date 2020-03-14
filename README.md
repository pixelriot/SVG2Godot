# SVG2Godot

Editor script to import simple SVG files as standard nodes into [Godot game engine](https://github.com/godotengine/godot).

![example](https://user-images.githubusercontent.com/21098503/76680538-959b7500-65e9-11ea-9a2b-21008c36f211.png)

## Features

* import groups, rectangles, polygons and paths.
* rectangles are imported as ColorRect nodes.
* closed polygons are imported as Polygon2D nodes.
* open polygons and paths are split into several Line2D nodes.
* translation and style information is retained. 

## Missing features

* many svg features cannot be represented with Godot nodes.
* curves in paths are simplified to lines.

## How to use

1. add the script *SVGParser.gd* to your project.
2. create a new 2D scene.
3. open the script in the Godot editor.
4. Under *file_path* add the path to your svg-file.
5. execute File -> Run.

![howto](https://user-images.githubusercontent.com/21098503/76680647-a698b600-65ea-11ea-96ec-a9dc8ac6365a.png)
