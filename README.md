# WAEC General Mathematics Lecture Notes: Bearings & Distances

## Project Overview

This repository contains the LaTeX source code for a comprehensive set of lecture notes designed for the **WAEC General Mathematics** syllabus. The document covers key geometric and trigonometric concepts, including Bearings, Angles of Elevation/Depression, and Longitude & Latitude. It is formatted for a specific large-paper layout (Ledger size, 11in x 17in) suitable for broadsheets or posters.

## Features

* **Vector Graphics:** extensive use of `TikZ` for high-quality geometric diagrams (compass bearings, triangles, elevation/depression scenarios).


* **Custom Environments:** specialized boxes for `Key Point`, `Important Formula`, `Common Mistake`, and `Worked Example` to enhance readability.


* **Mathematical Typesetting:** clear presentation of formulas, including the Haversine approximations for spherical geometry and trigonometric ratios.


* **Educational Content:** includes definitions, solved examples, and practice exercises with solutions.



## Prerequisites

To compile this project, you need a standard TeX distribution (like TeX Live, MiKTeX, or MacTeX) with the following packages installed:

* `geometry`
* `amsmath`, `amssymb`, `amsthm`
* `multicol`
* `enumitem`
* `fancyhdr`
* `tcolorbox`
* `xcolor`
* 
`tikz` (libraries: `shapes`, `arrows`, `positioning`, `calc`, `angles`, `quotes`, `decorations.markings`) 



## Compilation

You can compile the `bearings_angles_coordinates.tex` file using `pdflatex`.

**Using Terminal/Command Line:**

```bash
pdflatex bearings_angles_coordinates.tex

```

*Note: You may need to run the command twice to ensure the table of contents and internal references (if added later) are properly linked.*

## File Structure

* `bearings_angles_coordinates.tex`: The main source file containing all logic, text, and TikZ code.


* `bearings_angles_coordinates.pdf`: (Optional) The compiled output file.

## Content Sections

1. **Bearings and Distances:**
* Definitions of Compass and Three-Figure Bearings.


* Conversion methods and Back Bearings.


* Distance calculation using Pythagoras and Trigonometry.




2. **Angles of Elevation and Depression:**
* Visual definitions and relationship between elevation and depression.


* Applications involving buildings, cliffs, and ladders.




3. **Longitude and Latitude:**
* Great circles and small circles basics.


* Distance calculations along parallels of latitude ().


* Distance calculations along meridians ().


* Time zone calculations based on longitude.





## License

This project is intended for educational use. Please check the repository license file for specific usage rights.
