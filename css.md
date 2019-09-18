# Design web pages with CSS

## Skim *Duckett, Chap 10 Intro to CSS* Pg 226

### CSS is the Style of a page
Methods to add CSS
 + inline-style
 + in head-styling
 + in its own file linked to html (style.css)
    + `<link href"style.css" type="text/css" rel="stylesheet" />`

Presentation, Very declarative 
### Syntax 
> main {
>	background-color: black;
>	width: 500px;
>	}

### CSS Selectors Pg 237
    + Universal  `* {}`
    + Type  `h1, h2, h3 {}`
    + Class `.note {}`
    + ID `#note {}` and target elements with class `p.note {}`
    + Child
    + Decendant
    + Adjacent Sibling
    + General Sibling

CSS Rules Cascade, the ;ater rule takes precedence Pg 239

## Read *Duckett, Chap 11 Color* Pg 246

Color defined by name, hex code, hex abbreviation, rgb() 