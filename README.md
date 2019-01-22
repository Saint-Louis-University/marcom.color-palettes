# marcom.color-palettes

Cascading style sheet defining SLU colors as CSS variables

**Goal** 

To provide a reusable cascading style sheet to define official SLU colors as CSS variables

**Technology Overview**

* [CSS Variables](https://www.w3schools.com/css/css3_variables.asp)

**Prerequisites**

None

## Getting Started

Either add this in header of your html files:

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

## Resources

* [MARCOM Colors, Fonts, and Photography Guidelines](https://www.slu.edu/marcom/guidelines-policies/colors-fonts-photography.php)

## Notes

None

## Authors / Owners

[Matthew Schuelke](mailto:schuelkem@slu.edu)
