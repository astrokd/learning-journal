# Read 05: HTML Images; CSS Color & Text

Here are the chapters to read/skim before Class 5:

From the Duckett HTML book:

## Chapter 5: “Images” (pp.94-125)
`<img>` tag elemeent
-Atributes-
- `src` tells the browser where to find the image, this is required
- `alt` text description if you can not see it
- `title` additional info, often seen in tooltip
- `height`
- `width`

the `<img>` element is a Inline element, it does not start a new line and any text that shares a block element with will flow around it.

-Transparency-

Either a Transparent GIF or PNG

HTML5: Figure and Figure Caption
`<figure>`
`<figcaption>`

Chapter 11: “Color” (pp.246-263)
Color can be specified in these different ways:

+ RGB Values
+ Hex Codes
+ Color Names
+ there are others introduced by CSS3

Color brings your site to life and evokes a reaction and convey the mood
Proper Contrast improves legiblity

## Chapter 12: “Text” (pp.264-299)
**Typeface**
- Serif         : little details or feet on ends
- Sans-Serif    : straight ends, easier to read for low res screens
- Monospace     : common used for code

`font-family`

The typeface you specify needs to available to the people

> Designers suggest that pages usually look better if they use no more than three typefaces on a page.

> There is a limited choice of fonts that you can assume most people will have installed.

`font-size`

- Pixels        : for precise control
- Percentages   : default size in 16px so 75% would be 12px and 200% would be 32px.
- ems           : equivalent to the width of a letter m

`@font-face` lets you specify a font even if it is not installed on a computer by specifying a path to download from

- font-family       : name of font
- src               : path to font
- format            : like different audio or video formats

#### Responding to users

- `:hover`      : when mouse hovers over element
- `:active`     : when element is clicked
- `:focus`      : when tabing

#### Attributes Selectors pg292
Existence   []
Equality    [=]
Space       [~=]
Prefix      [^=]
Substring   [*=]
Suffix      [$=]

[Readme learning journal](README.md)
