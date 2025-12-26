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



### 2.3 Colors code

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


