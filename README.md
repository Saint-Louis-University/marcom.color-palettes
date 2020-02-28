# marcom.color-palettes

Files defining SLU colors for web (.css) and TeX (.sty)

**Goal** 

To provide reusable files to define official SLU colors for web and TeX

**Technology Overview**

* [CSS Variables](https://www.w3schools.com/css/css3_variables.asp)
* [Package xcolor](https://ctan.org/pkg/xcolor?lang=en)

**Prerequisites**

None

## Getting Started

### Web

Either add this in the header of your html files:

```html
<script src="https://saint-louis-university.github.io/marcom.color-palettes/edu.slu.marcom.color-palettes.css"></script>
```

Or add this to one of your existing css files:

```css
@import("https://saint-louis-university.github.io/marcom.color-palettes/edu.slu.marcom.color-palettes.css");
```

Then you can use the colors like:

```css
body {background-color: var(--slu-blue);}
```

### TeX

Download the [slu-color-palettes.sty](https://saint-louis-university.github.io/marcom.color-palettes/slu-color-palettes.sty) file to your working directory. Then add this in the header of your TeX file:

```TeX
\usepackage{slu-color-palettes}
```

Then you can use the colors like:

```TeX
\textcolor{slu-blue}{Lorem ipsum}
```

## Resources

* [MARCOM Colors, Fonts, and Photography Guidelines](https://www.slu.edu/marcom/guidelines-policies/colors-fonts-photography.php)

## Notes

None

## Authors / Owners

[Matthew Schuelke](mailto:schuelkem@slu.edu)
