# TEXT IN HTML : 

```
<p> : paragraph
<h> : heading size
<b> : bold
<i> : italic
<sub> : to sub symbols
<sup> : to power sybols
<hr /> : line
<em> : emaphasis
<strong> : enaphasis
<blockquote> : QuoTaTions
<q> :QuoTaTions
<abbr> :accrynoms
<cite> :citaition


```

>White space in paragraph does not make any effect 
>If you copy and paste text from a program that allows you to
format text (such as Word) into a visual editor, it may add extra
markup. To prevent this copy  the text into a plain text editor
first (such as Notepad on a PC or TextEdit on a Mac) and then
copy it from that program andpaste it into the visual editor


# Boxes 
## Boxes Dimensions
```
div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
p {
height: 75%;
width: 75%;
background-color: #0088dd;}
```

![result](boxes D.PNG)

NOTE : When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.


### min-width, max-width ,min-height, max-height

these properties specifies the smallest size a box can be
displayed at when the browser window is narrow/wide.

### overflow

when the content contained within a box is larger
than the box itself , it is  determined whether it's :

**-hidden**
This property simply hides any
extra content that does not fit in
the box.

**-scroll**
This property adds a scrollbar to
the box so that users can scroll
to see the missing content


# padding , Margin and Border


![ padding , Margin and Borde](border.PNG)

# hiding Boxes
you can hide or visibile the box 

```
li {
display: inline;
margin-right: 10px;}
li.coming-soon {
visibility: hidden; \\ or visible}

```
[BOXEXAMPLE](201/box example.md)
 ------

 # JavaScript 

 - Comments : 
 ```
 /
 /*this is multiline comment */

 - Declare Variable : 
 ```
 var x='Hi';
 // or 
 let x='hi';


 - Data Types :
    -Numbers 
    -string
    -Bolean


-ARRAY:
You create an array and give it a name just like you would any
other variable (using the var keyword followed by the name of
the array)

```
var colors;
colors = [ ' white ' , black ' , custom ' ] ;
var el = document.getElementByldCcolors ' ) ;
el . textContent = colors [0];
```




