> # Structure web pages with HTML 
________   

*reference [link](https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/)* 

# WIRE FRAME
  * Its a Prototype
  * Its a practice used by the UX designer to design for a website, app or product. It represent how the user is going to process the information 
  * Its usually in plain black and white diagram
  * the postion of bottons and menus on a diagram
  * two typs of wire frames a physical one and digital by using invision or balsamiq
  * physical one is easy to change during the design   
## defferant wire frame process (*depends on what the design needs*):
* Wireframe > Interactive Prototype > Visual > Design  
* Sketch > Code  
* Sketch > Wireframe > Hi-Def Wireframe > Visual > Code  
* Sketch > Wireframe > Visual > Code  

>best tools for wireframing : UXPin , UXPin ,Wireframe.cc.

# UX design process 
1. Start with a **research** (*user research, detailing requirements, creating user personas and defining use cases, competitor and industry research.*) 
2. scribbling a **cheatsheet**(business and user goals ,your requirements, your personas, use cases, and some reminders of the coolest features you stumbled across in your competitor research.**focus your attention on the user’s experience**  
3. **user flow maped** out like how many screens you’ll need to produce and the flow you expect the user to follow.(*“user flows” and “information architecture”*)    
> after this step start to draw the wireframe
4. draw a outlining and representing features and formats withiout fine details with no asthetics and no colours.(big marker,organize content to creat somthign usable)
5. add detail and get testing (*form and functionality*) ex.navigation bar , search box
6. wireframe into prototype (*import them into the industry-leading prototyping tool InVision*).  
> ### FOR BEST PRACTICE AIM FOR CLARITY, USER CONFIDENCE AND SIMPLICITY.   

# HTML  (Hypertext Markup Language)
*reference [link](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)* 
* to structure web page and its content 
* markup language 
* series of elements and tags
* individual elements are combined to form an entire HTML page
### anatomy of HTML ![PICTURE](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)
* opening tag : <P> is the name of the element 
* The closing tag : includes a forward slash
* The content : just text 
* The element : all of the above
* Attributes contain extra information about the element:
![picture](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-attribute-small.png)  

> attribute :
>> space between the name of the element.   
>> the attribute name followed by equal sign.   
>>value wrapped by opening and closing quotation marks.            
    
### Nesting elements : value wrapped by opening and closing quotation marks.
>`<p>My cat is <strong>very</strong> grumpy.</p>`  

### Empty elements : Some elements have no content and are called empty elements, there is no closing <\img>
> `<img src="images/firefox-icon.png" alt="My test image">`  

# Anatomy of an HTML document 
* `<!DOCTYPE html>`: required preamble , set of rules that the HTML page had to follow .(*to make sure your document behaves correctly*)
* `<html></html>` : wraps all the content on the entire page, (*root element*) 
* `<head></head>` : the container for elements thats not for the user showing (*keywords and a page description, CSS to style the content, character set declarations, and more*)
* `<meta charset="utf-8">` : sets the character set your document should use to UTF-8 as the majority of written languages
* `<title></title>` : title of the page
* `<body></body>` : all the content that should show to web users 
> ### Hint alt attribute 
>> for imges `<img src="images/firefox-icon.png" alt="My test image">` the attribute alt if the image didnt show up and for visually impaired.    

# Marking up text
* Headings : main title, chapter titles, and subtitles.`<h1>–<h6>`  
* Paragraphs : `<p>` frequently used to mark up regular text content 
* Lists are always consist of at least 2 elements :unordered list `<ul>` ordered `<ol>` and <li> list item      
* link : use element `<a></a>` for anchored ,with `herf` attribute for hypertext reference.
# Semantics in HTML
* HTML should be coded to represent the data , not based on the presentation style. The semantics of using <h1> is a top level heading of the page
* the benifits of semantics are : for search engine as a keywords, screen reader for visually impaired users , meainingfull codes are easy to find 

>which markup to use depend on : 
* type of the data like is it list of data , ordered or unordered 
* article with sections 
* header or footer  
 
