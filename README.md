# Font Scouts en Gidsen Vlaanderen

## About
This font contains all the icons designd en used by Scouts en Gidsen Vlaanderen in Belguim.
The demo folder shows which icons are included.

## Installation
Add the fonts and css folder to your website folder.<br>
Example:<br>
  index.html<br>
	css/Scouts-en-Gidsen-Vlaanderen.css<br>
	fonts/Scouts-en-Gidsen-Vlaanderen.svg<br>
	fonts/Scouts-en-Gidsen-Vlaanderen.ttf<br>
	fonts/Scouts-en-Gidsen-Vlaanderen.woff<br>
	fonts/Scouts-en-Gidsen-Vlaanderen.eot<br>

Link the css file in your html head.

```html
<link rel="stylesheet" href="css/Scouts-en-Gidsen-Vlaanderen.css">
```
## Usage HTML

```html
<!-- replace the class to the icon of your choice. -->
<span class="scouts scouts-int-scouts"></span>
```

## Usage CSS
```css
/* replace the class to the icon of your choice. */
.scouts-int-scouts:before {
  content: "\e600";
}
```

## Generate Fonts
Fonts are generated via http://icomoon.io/
Import al the source files

Preferences
* Font name: `Scouts-en-Gidsen-Vlaanderen`
* Class prifix: `scouts`
* CSS selector use a class: `.scouts` 
