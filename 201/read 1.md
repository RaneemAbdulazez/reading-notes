# What is HTML used for ? 

HTML is used to make the structure of page but **What is a structure ?**

it's The use of headings andsubheadings in any document often reflects a hierarchy of information. 

## Important notes : 

> Html uses elements (in opening and closing tags )
>Atribute tell us more about an element and it has a name and value 
like this :

![atribute](201/atribuute.PNG)

>Html is devided into : head title and  body 
>body is devided into : header , main and footer .

----
#### 176-199
--
>Html has 5 various versions , DOCTYPE selects one .
> ' <!---->'  that's how we write comment in html
>id atribute : allows us to specify an element  with a name in html page .
>class atribute : allows us to specify a group of elements  with a name in html page 
>Examples of block elements are
~~~
'<h1>', '<p>', '<ul>', and '<li>'
~~~
>Examples of inline elements are
~~~
'<a>', '<b>', '<em>', and '<img>'.
~~~
###### GroupinG text & elementd in a bloCk
> div element allows you to The <div> element allows you to group a set of elements together in one block-level box.

> ```<span>```
element acts like
``` <div>  ```
 but It is used to when : 1. Contain a section of text
where there is no other suitable element to differentiate it from
its surrounding text  or to contain a number of inline elements
>  ```<iframe>``` 
ike a little windowthat has been cut into your page .
>```<meta>``` inside the ```<head>``` element and contains information about your page.


#### 428-451
The new layout : 
![the new layout](201/layout.PNG)


what considered as new in this Read : 

>The ```<article>```  element acts as a container for any section of a page that could stand alone and potentially be syndicated
> The ```<aside>```  element depends on whether it is inside an ```<article>``` element or not, for exampleWhen the ```<aside>``` element is used outside of an ```<article>```
element, it acts as a container, but when it's inside  it should contain
information that is related to the article but not essential to its
overall meaning. 
>The ```<section>``` element groups related things together.



#### Older browsers :
Older browsers that do not
know the new HTML5 elements so they will be treated as inline elements , so  to avoid that you should write the line of css on left which states which new elements should be rendered ads block -level ones .



#### Process & Design(pp.452-475)
Every website is designed for the target audience.so simply understanding your audience is very essensial. here is some useful questions to ask when you're designing a web sit : 

- Who is the site For?
- Why PeoPle visit your Website?
- What your visitors are trying to achieve?
- What inFormation your visitors need ?
- hoW often People will visit your site?

> you should do a site map and a wire frame 
Design is about showing your content Visual hierarchy helps
visitors understand what you are trying to tell them.
> You can differentiate between pieces of information using size, color, and style.
> You can use grouping and similarity to help simplify
the information you present

# How js makes the web page more interactive ?

----
 Javascript is a language which used beside HTML and CSS and  makes the website more interactive by : 
 - acecess content 
 - Modify content 
 - program rules which means make the page changable for user 
 - React to events : like a button press ! 

 -----
 ## Examples : 
 - slide show 
 - Forms 
 - Filtering data 

 ----
 ## writing a script : 

 Before you wirte a script you should set a goal and lsit tasks to achive it ! 
> Define the GOA  Design the SCRIPT >> CODE 
> You need to learn to "think" like a computer because they solve tasks in different ways than you or I might approach them ,  doing a flowchart will help you!


-----

## OBJECTS:
each object has its own : 
Each object can have its own:
• Properties : each one has name and vlaue .
• Events :Programmers choose which events they respond to.
• Methods: are  things people need to do with objects.


![example](201/event method prp of an obj.PNG)

## PROGRESSIVE ENHANCEMENT : 
HTML alone makes the user see the main things in the page even if the js and css did't load , while Adding the CSS rules in a separate file keeps rules regarding how the page looks away from the content itself. 
js : Keeping it separate means that the page still works if the user cannot load or run the JavaScript


## js writing 

you can write js in the html file like this : 
---html---
```<script> code </script>```

---
you can write js in seperate file like this : 

---html---
```<script src="js/add-content.jsM"></script>```

---






NOTE : this is summurized from : 
HTML & CSS Design and Build Websites book by Jon DuCkeTT
and 
JAVASCRIPT & JQUERYInteractive Front-End Web Development by JON DUCKETT