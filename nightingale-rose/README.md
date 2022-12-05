# Nightingale's Rose Diagram

Read [Florence Nightingale’s Rose Diagram](https://powerofbi.org/2022/12/04/florence-nightingales-rose-diagram/) about how I build this chart using Vega and what interesting facts I found about the original chart.

This Vega visualization uses non-standard fonts.
If you don't have Harrington, Rockwell, Vivaldi fonts installed, then the titles, subtitles, text will look differently.
Install the fonts, use other fonts or use @font-face CSS rule (when embedding Vega code into a web page), for example:

````

@font-face {font-family: "Harrington"; src: url("//db.onlinewebfonts.com/t/20c2d461d736b1073c57cffba76d35d1.eot"); 
  src: url("//db.onlinewebfonts.com/t/20c2d461d736b1073c57cffba76d35d1.eot?#iefix") format("embedded-opentype"), 
  url("//db.onlinewebfonts.com/t/20c2d461d736b1073c57cffba76d35d1.woff2") format("woff2"), 
  url("//db.onlinewebfonts.com/t/20c2d461d736b1073c57cffba76d35d1.woff") format("woff"), 
  url("//db.onlinewebfonts.com/t/20c2d461d736b1073c57cffba76d35d1.ttf") format("truetype"), 
  url("//db.onlinewebfonts.com/t/20c2d461d736b1073c57cffba76d35d1.svg#Harrington") format("svg"); }

@font-face {font-family: "Vivaldi"; 
  src: url("//db.onlinewebfonts.com/t/c9a2e344b85728402fb6b8e2afa7f754.eot"); 
  src: url("//db.onlinewebfonts.com/t/c9a2e344b85728402fb6b8e2afa7f754.eot?#iefix") format("embedded-opentype"), 
  url("//db.onlinewebfonts.com/t/c9a2e344b85728402fb6b8e2afa7f754.woff2") format("woff2"), 
  url("//db.onlinewebfonts.com/t/c9a2e344b85728402fb6b8e2afa7f754.woff") format("woff"), 
  url("//db.onlinewebfonts.com/t/c9a2e344b85728402fb6b8e2afa7f754.ttf") format("truetype"), 
  url("//db.onlinewebfonts.com/t/c9a2e344b85728402fb6b8e2afa7f754.svg#Vivaldi") format("svg"); }

@font-face {font-family: "Rockwell"; 
  src: url("//db.onlinewebfonts.com/t/4aa3e37e571255737e5e6d4e9d9770a5.eot"); 
  src: url("//db.onlinewebfonts.com/t/4aa3e37e571255737e5e6d4e9d9770a5.eot?#iefix") format("embedded-opentype"), 
  url("//db.onlinewebfonts.com/t/4aa3e37e571255737e5e6d4e9d9770a5.woff2") format("woff2"), 
  url("//db.onlinewebfonts.com/t/4aa3e37e571255737e5e6d4e9d9770a5.woff") format("woff"), 
  url("//db.onlinewebfonts.com/t/4aa3e37e571255737e5e6d4e9d9770a5.ttf") format("truetype"), 
  url("//db.onlinewebfonts.com/t/4aa3e37e571255737e5e6d4e9d9770a5.svg#Rockwell") format("svg"); }

````
