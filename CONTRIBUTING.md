# Contributing

Contributions are welcome, and they are greatly appreciated! Every little bit
helps, and credit will always be given. You can contribute in the ways listed below.

## 1. Get Started

Ready to contribute? Here's how to set up the `Synchrotron IR-THz Knowledge Hub` Jupyter Book project for local development.

GitHub: https://github.com/sr-knowledge-hub/sr-ir-thz-knowledge-hub

1. Fork the repo on GitHub.
2. Clone your fork locally.
3. Install your local copy into a virtualenv, e.g., using `conda`.
4. Create a branch for local development and make changes locally.
5. Commit your changes and push your branch to GitHub.
6. Submit a pull request through the GitHub website.

## 2. Write Documentation

The Synchrotron IR-THz Knowledge Hub initiative covers a broad range of topics, and any contribution is greatly appreciated — especially when adding new content. Please include references whenever possible and avoid copying text directly from external sources.

When creating graphics, we strongly recommend following the visual identity guidelines below to maintain a consistent presentation and more organized communication.

### 2.1 Graphics dimensions

All figures should be no wider than 800 px. Click on the **Show code** dropdown to see the code for showing figures.

```{dropdown} Show code
:open: false

```markdown
```{figure} single_canva.svg
---
width: 800px
name: single_canva
---
Figures must have a total width of 800 px, including margins.```
```

```{figure} single_canva.svg
---
width: 800px
name: single_canva
---
Figures must have a total width of 800 px, including margins.
```

The same should be applied to multi-panels graphics

```{figure} multi_canva.svg
---
width: 800px
name: multi_canva
---
Figures based on multiple panels must have a total width of 800 px, including margins.
```

### 2.2 Fonts, lines styles and graphics formats

Figures should preferably be prepared as vector graphics. When raster images are required, they must be exported at a minimum resolution of 600 ppi (pixels per inch). Arial is the standard font for all graphics in this project, used at 10, 12, and 18 pt sizes and always in the Regular typeface, except where explicitly specified (Arial Bold). Axis ticks must be placed outside the frame. Both the frame and ticks must have a line thickness of 0.25 pt. Data line profiles must be drawn with a line width of 1.0 pt, while model curves and other auxiliary lines must use a line width of 0.5 pt. {numref}`line_profiles` shows a complete guide for line profiles ploting.


```{figure} line_profiles.svg
---
width: 800px
name: line_profiles
---
Example of a multi-profile plot showing the mid-IR near-field amplitude response of a graphene/hBN heterostructure tuned by an external gate voltage. In blue, annotations indicate font sizes and types, line widths, axis tick layout, and data profile line widths. Original graphics adapted and extracted from {cite}`Maia2019`.
```

```{table} Recommended graphics formats. All bitmap images, including embedded graphics, must have a minimum resolution of 600 ppi.
:name: graphics_formats
:align: center
:widths: 40 60
:class: vcenter

| Graphic type | Best format |
|-------------|-------------|
| Line plots | SVG |
| Schematics / diagrams | SVG |
| Flowcharts | SVG |
| Microscopy images | PNG |
| Photos | JPG |
| Journal-ready figures | PDF |
| Logos | SVG or PNG |
| Icons | SVG |
```


### 2.3 Colors code

We propose a set of color schemes suitable for different types of graphics. {numref}`color_maps` presents continuous colormaps (CM01–CM05), diverging schemes (CM06, CM09, and CM10), and high-contrast schemes (CM07 and CM08). In addition, for illustrations of experimental setups and sample configurations, we recommend the use of three-color schemes (CB01–CB12). For radiation beams, we suggest using the colors defined as B01–B04. {numref}`graphics_table` summarizes recommended applications of these color schemes across different graphic types.

```{figure} colors.pdf
---
width: 800px
name: color_maps
---
Recommended color schemes for this project. The left columns present colormaps (CMs) for continuous, high-contrast, and diverging representations. Top right: three-color cubes (CBs) for 3D illustrations. Bottom right: suggested colors for beams (Bs). The HEX code for each color is provided.
```

```{table} Recommended color codes for different types of graphics.
:name: graphics_table
:align: center
:widths: 40 60
:class: vcenter

| Graphics type | Recommended color schemes |
|:---------|:---------|
|AFM image (topography, amplitude, phase) <br> SEM, TEM or other morphology images| CM01 (standard) or CM06|
| s-SNOM *amplitude* 2D maps (broadband or narrowband reflectivity) <br> s-SNOM *amplitude* spectral linescan |CM02 (standard), CM04 or CM05|
| s-SNOM *phase* 2D maps (narrowband absorption) <br> s-SNOM *phase* spectral linescan |CM09 (standard) or CM10|
| micro-FTIR hyperspectral imaging (transmittance or absorbance) | CM07 |
| AFM-IR or O-PTIR imaging (absorption) | CM08 |
| Simulated, modeled or calculated intensity maps | CM03 |
| Transparent components | CB01, CB02 or CB03 |
| General opto-mechanics | CB04, CB05 or CB06 |
| Translation or angular stages | CB07, CB08 or CB09 |
| Radiation sources | CB10 (X-rays or UV), CB11 (visible) or CB12 (IR-THz) |
| X-rays or UV beams | B01 |
| Visible light beams | B02 |
| IR beams | B03 |
| far-IR/THz beams | B04 |
```

### 2.4 Graphics examples


## 3. Report Bugs or Content Mistakes

Report bugs using GitHub issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

## 4. Fix Bugs

Look through the GitHub issues for bugs. Anything tagged with "bug" and "help
wanted" is open to whoever wants to implement it.


## 5. Submit Feedback

The best way to send feedback is to file an issue on GitHub.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions are welcome 


