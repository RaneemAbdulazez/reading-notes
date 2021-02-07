# UNDERSTANDING CSS 

>The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element

> three sytyles to write css : 
- inline 
- internal
- external 

-----
# External : 

creat a file with .css extension and put this in html file .

<link href="css/styles.css" type="text/css"
rel="stylesheet" />

# Internal: 
in html page 
do the follwing : 

<style type="text/css">

body {
font-family: arial;
background-color: rgb(185,179,175);}
h1 {
color: rgb(255,255,255);}
</style>

Examples : 

p{ font-family : Arial ; }

h1, h2 ,h3 {font-family : arial ; color : yellow}