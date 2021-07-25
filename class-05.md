# Read: 05 - HTML Images; CSS Color & Text
- its better to store the images all in one place the folder called images , sub folder called interface for logos and buttons , folder for product photographs called products and news for news images.
- add image into html
 using empty element <img>  followed by two attribute : 1) src="relativeURL" 2) alt="discription of the image for screen reader", 3) extra is title="  " it used when the user hover over the image .
 
- hight and width of an image 
using width="11" height="11" its increasingly used by css ,using size to render 

- where to place the image in the code 
<img> is inline element and paragraph is block element 

- old code using align attribute 
now its used by css but in old code they use align to left, right , top , bottom of the text . but now html 5 is no longer use align.

- rules for creating images 
1.  right format :png , jpg , gif . 
2.  save image at the right size not smaller it will get streched not biger it will take longer time to load .
3.  resolution , websites uses 72 pixels so using higher resolution will take just longer time to load.
to ensure using right size , format , resolution by using photoshop or photoshop elements
- image format : jpg when there is too many colors , gif or png when there is less color like an abstract drawing , or as flat colors like logos , are called bitmap . using SVG to display vector images , use gif if fully transparent with straight edges , png is for drop shadow , simi transparent , diagonal round
- figure and figure caption 
` <figure> <img><figurecaption>></figurecaption></figure> ` , you can have more than one img.
- color properties for text , using ways like rgb , hex code with # ,color names 147 , HSLA.
- background color  colors the block , its adviced to use white in body.
- its better to not use too much contrast between the text and the background or no contrast at all .use dark gray with white.
- opacity property : 0 is no opacity and 1 is full opacity or rgba(0,0,0,0.5).
- background-color: hsla (0,100%,100%,0.5) , hue , saturation, lightness and trasperancy ,or  hsl.

### css colors
- color properties for text , using ways like rgb , hex code with # ,color names 147 , HSLA.
- background color  colors the block , its adviced to use white in body.
- its better to not use too much contrast between the text and the background or no contrast at all .use dark gray with white.
- opacity property : 0 is no opacity and 1 is full opacity or rgba(0,0,0,0.5).
- background-color: hsla (0,100%,100%,0.5) , hue , saturation, lightness and trasperancy ,or  hsl.
### text
- typeface terminology:
- serif , have extra detail in the end of the letters good in prints , sans sirif have straight ends to letters good in low screen resolutiom  , monospace every letter is the same width.
- weight : light , medium , bold , dark .
- style : italic, oblique , normal 
- stretch : condensed , regular , extended 
- type face : serif extra detial in the end , sans-serif have straight ends,monospace same width letter , cursive have joining strocks or handwriting , fantasy are decorative fonts for titles 
- specifying typeface :font-family: arial ,"courier new" ;
- size of type : font-size : px or percentage , the default is 16px when 100% means 16px , if the size is specified in the body then the percentage work on the specified size , em the is the width of and m
- line-hight : it can increase readibility when making more space between lines , better to use em unit 
- text-decoration : none if used hyperlink , underline , overline ,line-through , blink 
- text-transform: uppercase, lowercase , capitilize 
- font-style: normal, oblique , italic
- font-wieght : normal bold 
- font format : eot , woff , ttf/otf , svg 
- @font-face : to add font using src 
- letter-spacing , word-spacing : its better to use em
- text-align : left , right , center , justify 
- virtical align : middle , top , baseline 
- text-indent : px or em  or to make the heading out of the sight but in the page 
- text-shadow : ` text-shadow: 1px 1px 0px #000000; ` first for sides , second for virtical , blur of the shadow fourth the color of the shadow 
- pseudo-elements.: first-letter , first-line , :link, :visited, :hover :focus, :active.
- pseudo-elements : to change for the links visited and not visited colors

``` 
a:link {
color: deeppink;
text-decoration: none;}
a:visited {
color: black;}
```





