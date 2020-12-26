# seam-carver
A simple Julia implementation of [Seam Carving for Content-Aware Image Resizing ](https://inst.eecs.berkeley.edu/~cs194-26/fa18/hw/proj4-seamcarving/imret.pdf) (2007)

### Prerequisites
Julia, you can find detailed installation instructions for Julia here: https://julialang.org/downloads/

## Usage
Load the code

`julia include("seam_carver.jl")`

Run the function by providing 2 arguments: input image and desired output resolution

`julia seam_carver(img, res)`
