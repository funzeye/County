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

This project contains two different fonts. The first font is called 'County-Map'. This is a symbol font that allows you too make up the map of Ireland. Each symbol represents a county and when used together all symbols  fit together to make up a complete map. Each County can be styled and used indepentently. The second font is called 'County-Icon'. This is similar in many ways to the previous font in that it is a symbol font that represents the counties of Ireland. It differs from the previous font however, in that it is optimatized to be  used alongside regular none symbol fonts and text. Each symbol fits the size of a regular text element in that the heights,widths and positions are approximate to regular text fonts. In other words setting their font sizes will give you the same sized elements as regular text fonts. The County-Map font is not ideal for this type of usage as the county-map symbols are positioned relatively to the other counties and if they were to be used alongside regular text fonts would need to be set at a different font size. Both fonts have their own unique use cases and some examples of those can be seen on the sample Index.html page

##Instructions

###Option 1 - Using CSS:

Inside this download package you will find three folders. One contains the fonts, one the sass files and one the css which was created from the sass. If you do NOT want to work with sass you can ignore this folder and just import the fonts and css folders into your project only. Inside the css folder you will see how both fonts are set up to be used within your html, along with a small amount of sample css code.
By default the css file is called styles.css, assuming you keep this name then you will import it into your html head section like so:
    
```html
<link rel="stylesheet" href="path/to/county/css/styles.css">
```
All other files apart from the 3 folders can be ignored, they are just there to help create the sample page and to enable you to create your own symbol font.
I highly recommend minifying any css file that you specify in your html head.

###Option 2 - Using SASS:

Inside this download package you will find three folders. One contains the fonts, one the sass files and one the css which was created from the sass. If you DO want ot work with sass you will add all 3 folders into your project. Each font has its own set of sass files for you to work with. The sass files all feed into one master/parent sass file called county.sass. If you compile this sass file to css you will then have all your county font css in that css file. You can then add a link to this css in your html head section like so:
    
```html
<link rel="stylesheet" href="path/to/county/css/styles.css">
```
All other files apart from the 3 folders can be ignored, they are just there to help create the sample page and to enable you to create your own symbol font.
I highly recommend minifying any css file that you specify in your html head.

###Option 3 - Using CountyCDN:
Coming soon...

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
