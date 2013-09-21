##County

Contains two different custom svg symbol fonts, both of which comprise the counties of Ireland in their geographical form. One is intended for use as part of a map while the other is intended to be used alongside regular text fonts.

##Files
    Ireland-Map.svg - SVG map of Ireland used to create the fonts
    fonts           - Folder containing the web-font files
    sass            - Folder containing basic Sass files, including basic configurations for both fonts to get you started
    css             - Folder containing the compiled CSS file - styles.css (compiled from styles.scss in sass folder)
    Index.html      - Basic sample page
    CountyIcon.svg  - SVG font file
    countyicon.ttf  - TrueType font file
    CountyMap.svg   - SVG font file
    countymap.ttf   - TrueType font file

##Detailed Description

'County' comprises of a pair of symbol fonts, both representing the counties of Ireland. The fonts can be added to your web projects, be styled and modified, using only HTML and CSS. 

###County-Map Font
County contains two different fonts. The first font is called 'County-Map'. This is a symbol font that allows you to put together a map of Ireland made solely of font symbol glyphs. Each symbol represents a county and when used together all symbols can be fitted together to make up a complete map. Each County can be styled and used independently.

###County-Icon Font
The second font is called 'County-Icon'. This is similar in many ways to the County-Map font in that it is a symbol font that represents the counties of Ireland. It differs from the previous font however, in that it is optimized to be used alongside regular none-symbol fonts and text. Each symbol fits the size of a regular text element in that the heights, widths and positions are approximate to regular text fonts. The County-Map font is not ideal for this type of usage as the County-Map symbols are sized and positioned relatively to the other counties on the map. 

Both fonts have their own unique use cases and some examples can be seen below. Download the Fonts and get started straight away. As well as the font files, there is sample HTML and CSS included in the download package to help you get started.
##Instructions

###Option 1 - Using CountyCDN (Easiest)
Add the County fonts or font to your site using just one line of code, there's no need to add any of the above files to your project whatsoever:
```html
<link rel="stylesheet" type="text/css" href="http://funzeye.github.io/County/CountyCDN/css/county-fonts.min.css">
```
Or,
If you would prefer to just use one of the fonts then you can use one of the alternative links:
```html
<link rel="stylesheet" type="text/css" href="http://funzeye.github.io/County/CountyCDN/css/county-map-font.min.css">
```
Or:
```html
<link rel="stylesheet" type="text/css" href="http://funzeye.github.io/County/CountyCDN/css/county-icon-font.min.css">
```

Once you have added one of these links in your html head section you can then use the fonts whenever you want by specifying in your css one of the following:
```css
div{ //just using div as an example, it can be applied to any element you wish
	font-family:'countyiconregular';
}
div{
	font-family:'countymapregular';
}
```
And thats it, easy! No need to add any files to your project whatsoever. 

Note that non-minified versions of these css files also exist can be used instead, indeed I would recommend doing this until you are ready to deploy your site, then switch to the min versions.
```html
<link rel="stylesheet" type="text/css" href="http://funzeye.github.io/County/CountyCDN/css/county-fonts.css">
```
If you would prefer to just use one of the fonts then you can use one of the alternative links:
```html
<link rel="stylesheet" type="text/css" href="http://funzeye.github.io/County/CountyCDN/css/county-map-font.css">
```
Or:
```html
<link rel="stylesheet" type="text/css" href="http://funzeye.github.io/County/CountyCDN/css/county-icon-font.css">
```

###Option 2 - Using CSS (Easy)

Inside this download package you will find three folders. One contains the fonts, one the sass files and one the css which was created from the sass. If you do NOT want to work with sass you can ignore this folder and just import the fonts and css folders into your project only. Inside the css folder you will see how both fonts are set up to be used within your html, along with a small amount of sample css code.
By default the css file is called styles.css, assuming you keep this name then you will import it into your html head section like so:
    
```html
<link rel="stylesheet" href="path/to/county/css/styles.css">
```
All other files included in the above project, apart from the contents of the 2 folders, can be ignored, they are just there to help create the sample page and to enable you to create your own symbol font, if that's something you would be up for doing!
I highly recommend minifying any css file that you specify in your html head.

###Option 2 - Using SASS (Pro)

Inside this download package you will find three folders. One contains the fonts, one the sass files and one the css which was created from the sass. If you DO want to work with sass you will add all 3 folders into your project. Each font has its own set of sass files for you to work with. The sass files all feed into one master/parent sass file called styles.sass. If you compile this sass file to css you will then have all your County font css in that css file. You can then add a link to this css in your html head section like so:
    
```html
<link rel="stylesheet" href="path/to/county/css/styles.css">
```
All other files included in the above project, apart from the contents of the 3 folders, can be ignored, they are just there to help create the sample page and to enable you to create your own symbol font.
I highly recommend minifying any css file that you specify in your html head.


##Microsite
[County Microsite](https://funzeye.github.com/County/)

##Author

Created by David Kivlehan at Hover Craft Studio. 

David Kivlehan   
[twitter](http://www.twitter.com/funzeye)  
[blog](http://hovercraftie.tumblr.com/)  

Hover Craft Studio  
[website](http://www.hovercraftstudio.ie/) 

##Credits

Inspired by Ben Markowitz's Stately Project
[website](http://intridea.github.io/stately/)

Ben Markowitz   
[website](http://www.benmarkowitz.com)  

##License

MIT License. See LICENSE for details.

##Copyright

Copyright (c) 2013 Hover Craft Studio, Ltd.
