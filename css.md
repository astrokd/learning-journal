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

Exernal CSS files lets all your pages share the same style Pg 241

### CSS Versions

 + CSS1 released in 1996
 + CSS2 two years later, 1998
 + CSS3 on going and already browsers are implementing


## Read *Duckett, Chap 11 Color* Pg 246

Color defined by 
  + name, there are 147 color names*(not commonly used)*
  + hex code, hex abbreviation, 
  + rgb() 

### CSS3

## Opacity and RGBA
Opacity allows you to spec transparentcy
rgba just like rgb color spec but has 4 value for opacity
## HSL Colors Pg 255
Spec color by Hue, Saturation, Lightness HSL or hsla
Pg 262
>It is important to insure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content)
