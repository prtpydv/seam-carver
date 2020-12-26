# seam-carver
A simple Julia implementation of [Seam Carving for Content-Aware Image Resizing] (https://pdfs.semanticscholar.org/5864/8b7f6c7424c256abdd7db8ba024801f0aca1.pdf) (2007).

### Prerequisites
Julia, you can find detailed installation instructions for Julia here: https://julialang.org/downloads/

## Usage
Load the code
`julia include("seam_carver.jl")`

Run the function by providing 2 arguments: input image and desired output resolution
`julia seam_carver(img, res)`
