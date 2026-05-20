# Validation Files

This repository contains the validation artifacts that support our thesis.
Each scenario folder contains:

- **`Scenario parts/`**: `.stl` mesh files (the generated 3D models)
- **`Scenario scripts/`**: `.txt` files containing the Python source code
  that produced each model

## Running the scripts

Every script in this repository is a Python program built on top of
[CadQuery](https://cadquery.readthedocs.io/), a parametric 3D CAD scripting
library. The only third-party library you need to install is `cadquery`
itself. 

Install CadQuery with pip:

```bash
pip install cadquery
```

Once CadQuery is installed, you can run any of the scripts by copy-pasting
the contents of a `.txt` file into a Python environment of your choice —
for example:

- **Visual Studio Code** (with the Python extension)
- Any other IDE that runs Python

The scripts are self-contained, paste the code, run it, and the
corresponding 3D model will be produced.

## Viewing the STL models

The `.stl` files in each `Scenario parts` folder can be opened in any
software that supports the STL format. The most convenient free option is:

- **[Bambu Lab Slicer (Bambu Studio)](https://bambulab.com/en/download/studio)** —
  a free desktop application that will load and display the STL files
  directly.

Any other CAD or mesh-viewing software that supports STL will also work
(for example FreeCAD, Fusion 360, Blender, MeshLab, Microsoft 3D Viewer,
PrusaSlicer, Cura, etc.).
