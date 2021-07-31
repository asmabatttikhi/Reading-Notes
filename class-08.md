# CSS Layout

- **absolute URL** 
- **relative URLs** which are a shorthand way to tell the browser where a page is in relation to the current page.
-**syntixc for how to link** ` <a href="reviews.html">Reviews</a> ` 
- **email link** ` <a href="mailto:jon@example.org"> Email Jon</a> ` the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
- **target** `<a href="http://www.imdb.com" target="_blank"> ` target opens new window with the value of blank. its good to inform the user that it will open new tab 
- link to the same page 1)**id attribute** to identify the points in the page that the link will go to to the elements . 2)**using#** ` <a href="#arc_shot">Arc Shot</a><br /> `
- link with url and # ` <a href="http:/www.htmlandcssbookcom/#bottom"> `

##  Intro to CSS Layout
- building block are block element or inline element exaple `<p> <ul>`
- inline element like `<img> <b> <li>`
- container and a perant like multible text inside `<div>`
- position normal flow ubove each other , relative postioning moving from its place ,absolute move in relation to the containing element 
- **position:static** as in normal flow 
- **position:relative** move in relation to its own place then offset property **top,left,right,bottom**
- **position:absolute** where the elementshould appear in relation to its containing element.
- **position:fixed** positions the element in relation to the browser window.
- **z-index:10;** ` z-index: 10;}`If you want to control which element sits on top.
- **float** it will be in left or right of the container it is advized to use width property with float 
- **clear** `clear: left;}` float dont touch left side of the containing element , left ,both , none , right
- elements that only contain floated element will be considerd zero pixle , its fixed with adding an element to html with no float and clear both propety or though css `overflow: auto; width: 100%;}`
- **column** width sets the width of the column , float next to each other ,margin gap between them .each colum needs a `<div>` 
```
.column1of3, .column2of3, .column3of3 {
width: 300px;
float: left;
margin: 10px;}
```
- fixed website , width of the body by pixle and margin: 0 auto to center it left and right margin
- liquid website , using percentage , it is adviced to use in body 90 percente to leave space in the sides , min-width and max-width properties help create boundaries when stretched 
- **Layout Grids** such as 960 pixel wide
- to add another style sheet` @import url("typography.css");` in css or use a separate <link> element
```
<link rel="stylesheet" type="text/css"
href="css/tables.css" />
```
- Designers keep pages within 960-1000 pixels wide and 600 from the top to attract the user