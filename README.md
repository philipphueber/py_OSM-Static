# py_OSM-Static
A python script for generating Static openstreetmap Images.

## Simple Command line Interface, 

Argument 1: Latitude in FloatingPoint Notation

Argument 2: Longitude in FloatingPoint Notation

Argument 3: ZoomLevel (0-19) 0 = Whole World 19 = Super Close

### Multiple Flags Selectable Afterwards:

  "--marker_path" allows you to set your own marker either Locally via a Filepath on your Computer or with an http / https Address
  
  "--size" sets the return image size to a Square of size x size
  
  "--width" and "--height" set the size of the return image, ATTENTION ONLY "--width" and "--height" OR "--size" can be used
  
  "--filename" sets the output path / filename
  
  "--high_contrast" returns a high contrast version of your map
  
  "--grayscale" returns a grayscale version of your map (can be used together with "--high_contrast"
  
  "--nomarker" hides the map marker
  
## Example:

> python Static_Map.py 40.777272310196174 -73.9824607079843 12 --size 800 --filename NYC.png 

generates: 

![alt text](https://raw.githubusercontent.com/philipphueber/py_OSM-Static/main/NYC.png "NYC.png")
