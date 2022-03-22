# **Class 1 Reading Notes**

[Home](README.md)  
[class02](Class02.md)  
[Classs03](Class03.md)  
[Class04](Class04.md)  
[Class03](Class03.md)  
[Class05](Class05.md)  
[Class06](Class06.md)  
[Class07](Class07.md)  
[Class08](Class08.md)  
[Class09](Class09.md)  
[Class10](class10.md)  
[Class12](Class12.md)  

# **HTML Chapter 1** (*Structures*)

>*Web pages are structured similaraly to a printed page.*

>*Elements are made up of two tags, an opening and a closing tag.Tags encapsulate the content to provide some insight on the type of content and to help structure the page.*

### **Example**

>> `<p>Paragraph</p>`

>*Attributess provided extra information about the content of the element and require two parts; a name and a value.*

### **Example**

>> `<p lang="en-us">`  

# **Chapter 8** (*Extra Markup*)

>*DOCTYPE is put at the beginning of every html page to let the browser know the type of html it is written in, it can also help with page rendering.(Most likely will still load the page if it is not there)*

### **Example**

>> `<!DOCTYPE html>`

>*Comments are used to create notes within your code to explain how or what the code does. Comments can also be used to ommit code easily.*

## **Example**

>> `<!--This is a comment-->`

>*An id attribute is used to uniquely identify an element, which can be used to modifty that element in css*

### **Example**

>> `<p id= "pullquote">`

> *A class id can uniquely identify a group of elements, which can be used to modify the elements in css later.*

### **Example**

>> `<p class= "example">`

> block element will always apear on a new like.

### **Examples**

>> `<h1>,<p>,<ul>,<li>.`

> *Inline elements are in line or are written in to the content.*

### **Example**

>> `<a>,<b>,<em>,<img>`

> *The div element leats you block a group of elements into one box.*
>> `<div> block of elements </div>`

>*The span element does the same as a div element only in line instead of a block. Usually used to create a class and to modify in css.*
## **Example**
>> `<span classs= "example"> content </span>`

> *Iframes are used as a portal to another webpage most commonly used for google maps. a height width and source are required.*

### **Example**

>> `<iframe
width= 22
height= 22
src= example...> </iframe>`

> *The meta tag is used to put information about the page in the head tag, this is not displayed to the user.*

### **Example**

>> `<meta>` T*his is an empty element.*

>Special charaters such as <> and & are not visible without escape characters.

### **Example**
>>
+ `&lt;` = <
+ `&gt;` = >
+ `&quot;` = ""

# **HTML Chapter 17** (*HTML5 Layout*)

> *The new elememnts help the browser figure out the structure and purose of the webpage. They can also clean up the code and avoid using multiple div elements.*

>*Older browser versions can not read the html5 elements(such as block elements). Javascript is required to make those elements work(Google).*

# **HTML Chapter 18** (*Process and Design*)

>*Understanding your target audience is key. Site maps and wire frames can help organize your page.*

>*When displaying information using different colors and styles can help convey information.*

>*Grouping and similarity can simplify your page.*

# **Javascript Chapter 1** (*ABC of Programming*)

>*In order to write a script you need to know the parts of that script. those parts can then be categorized into smaller parts, possible individual lines of code.*

>### How a page is seen on a browser

1. *Browser recieves the html file.*
1. *The browser creates a model of the page.*
1. *The browser renders the page ussing an engine nad is seen by the user.*

> *Javascript can be run in the HTML file and can be placed in the code.*

### **Example**

>> `<script>Document.write("Parameters")`

> *The document portion is the object.*  
> *The write portion is the method.*
