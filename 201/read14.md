# Team Work at Google


>‘As long as everyone got a chance to talk, the team did well. But if only one person or a small group spoke all the time, the collective intelligence declined.’

that's means whenever the team members were afraid of each other , taht would kill their wok as a team ! 



----------------------
# transforms in Css


```
CSS

.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: skewX(5deg);
}

```

transforms have many properties like rotare , skew and perspective


-------------------------


# transitions 


1. Fade in

```

.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}

```


2. Change color
```
.color:hover
{
        background:#53a7ea;
}
```


3. Grow & Shrink
```
.grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}

.shrink:hover
{
        -webkit-transform: scale(0.8);
        -ms-transform: scale(0.8);
        transform: scale(0.8);
}

```


4. Rotate elements

```
.rotate:hover
{
        -webkit-transform: rotateZ(-30deg);
        -ms-transform: rotateZ(-30deg);
        transform: rotateZ(-30deg);
}

```


5. Square to circle

```
.circle:hover
{
        border-radius:50%;
}
```

6. 3D shadow
```
.threed:hover
{
        box-shadow:
                1px 1px #53a7ea,
                2px 2px #53a7ea,
                3px 3px #53a7ea;
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
}
```