# SVG Import for Dynamo

![](https://github.com/garciadelcastillo/SVG-Import-for-Dynamo/blob/master/assets/svg_import_dynamo_screenshot.png)

Simple SVG importer for [Dynamo](http://dynamobim.org/). Will read the contents of an SVG file, and try to import its contents as Geometry in Dynamo. 

## Installation
In Dynamo Studio, download the Package by going to `Packages > Search for a Package`, and search for `SVG Import`.

## Examples
The package file contains examples on how to use the package. Go to `Packages > Manage Packages`, click on the options on the right of `SVG Import` and click `Show root folder`. You will find example files in the `extra` folder.

## Limitations
As of version 0.2.0, the library only imports lines and polygons as paths, with no attributes. Currently optimized for importing slice SVGs from Netfabb for 3D printing.

## Acknowledgements
Based on the [nanosvg-csharp project by Thinksquirrel](https://github.com/thinksquirrel/nanosvg-csharp).
