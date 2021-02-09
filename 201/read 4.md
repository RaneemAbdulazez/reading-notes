# From the Duckett HTML book:
---



## Chapter 4: Ch.4 “Links” (pp.74-93)

### Writing Links

links are writtin like this : 

![links](201/link in html.PNG)

### emAiL Links
we use mailto like this :

Example :
```
<a href="mailto:jon@example.org">Email Jon</a>
```

### oPening Links in A neW WinDoW
```
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a> (opens in new window)
```

### Linking to A sPeciFic PArt oF the sAme PAge
>At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add
a link from part way down the page back to the top of it to save users from having to scroll back to the top.


the steps : 
- you need to identify the points in the page that the link will go to (use id attribute )

-To link to an element that uses an id attribute you use the <a> element again, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to. 

Example :
```
<h1 id="top">Film-Making Terms</h1>



<p><a href="#top">Top</a></p
```






----
## Chapter 15: “Layout” (pp.358-404)






---
# From the Duckett JS book:
---


## Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)


### what is a function :
it's reusable piece of code .

Eample :

```
var msg = Sign up to receive our newsletter for 10% o f f! ' ;
function updateMessage () {
var el = document.getElementById ( ' message ' );
el .textContent = msg;
}
updateMessage ( );
```

### CALLING FUNCTIONS THAT NEED INFORMATION

When you call a function that has parameters, you specify the values it
should use in the parentheses that follow its name. The values are called
arguments, and they can be provided as values or as variables.

Example :

```
wall Width = 3;
wall Height = 5;
getArea (wallWidth, wallHeight);
```
### GETTING A SINGLE VALUE OUT OF A FUNCTION

Some functions return information to the code that called them.
For example, when they perform a calculation, they return the result

```
function calculateArea (width, height ) {
var area = width * height;
return area;
i
}
var wallOne = calculateArea (3, 5) ;
var wallTwo = calculateArea (8, 5) ;
```





---
## Article: “6 Reasons for Pair Programming”


### pair programming is a way to work in pairs , there are two people , the Drivers and the Navigator , as we know there are two main things in doing any code , which are ( logical plainning , and writing the code and deploy it ) the pair programming suggest that the diver is the person who write the code and fix it , while the navigator draw the big picture and planning it ! 


>Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

### Whya pair programming ? 

1. Greater efficiency:
>In reality, when two people focus on the same code base, it is easier to catch mistakes in the making.


2. Engaged collaboration:
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. It is harder to procrastinate or get off track when someone else is relying on you to complete the work. 


3. Learning from fellow students:
>the developers in a pairing have different skill sets. If one programmer is more experienced in a certain skill, they can teach a student who is less familiar with that area. 


4. Social skills:
>When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities. Pair programming not only improves programming skills, but can also help programmers develop their interpersonal skills. 


5. Job interview readiness: 
>A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen.


6. Work environment readiness :this helps the fresh graduates and junior coders in companies

---