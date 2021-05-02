# Images
Image Rollovers & Sprites
Using CSS, it is possible to create a link or button that changes to a second style when a user moves their mouse over it (known as a rollover)When a single image is used for several different parts of an interface, it is known as a sprite.
*To overlay text on an image with high contrast, you can place a semi-transparent background color (or "screen") behind the text to improve legibility*

# Practical Information
On-Page SEO
In every page of your website there are seven key places where keywords
(the words people might search on to find your site) can appear in order
to improve its findability
1. Page Title
2. URL / Web Address
3. Headings
4. Text
5. Link Text
6. Image Alt Text
7. Page Descriptions
* Determining which keywords to use on your site can be one of the
hardest tasks when you start to think about SEO. Here are six steps that
will help you identify the right keywords and phrases for your site.
* Brainstorm
* Organize
* Research
* compare
* refine 
* MAP
**How Many People Are coming to Your Site?**
The overview page gives you a snapshot of the key information you are
likely to want to know. In particular, it tells you how many people are
**coming to your site. What Are Your Visitors Looking At?**
The content link on the left-hand side allows you to learn more about what the visitors are looking at when they come to your site.
**Where Are Your Visitors Coming From?**
The traffic sources link on the left hand side allows you to learn where your visitors are coming from.
* FTP & Third Party Tools
To transfer your code and images from your computer to your hosting company, you use something known as File Transfer Protocol.
There are a wide variety of sites that offer services commonly created by web developers (to save you having to build them yourself).


# Playing and pausing the video

Let's implement probably the most important control — the play/pause button.

First of all, add the following to the bottom of your code, so that the playPauseMedia() function is invoked when the play button is clicked:

play.addEventListener('click', playPauseMedia);
Now to define playPauseMedia() — add the following, again at the bottom of your code:
```
function playPauseMedia() {
  if(media.paused) {
    play.setAttribute('data-icon','u');
    media.play();
  } else {
    play.setAttribute('data-icon','P');
    media.pause();
  }
}

```
Here we use an if statement to check whether the video is paused. The HTMLMediaElement.paused property returns true if the media is paused, which is any time the video is not playing, including when it is set at 0 duration after it first loads. If it is paused, we set the data-icon attribute value on the play button to "u", which is a "paused" icon, and invoke the HTMLMediaElement.play() method to play the media.

On the second click, the button will be toggled back again — the "play" icon will be shown again, and the video will be paused with HTMLMediaElement.pause().

Stopping the video
Next, let's add functionality to handle stopping the video. Add the following addEventListener() lines below the previous one you added:

stop.addEventListener('click', stopMedia);
media.addEventListener('ended', stopMedia);
The click event is obvious — we want to stop the video by running our stopMedia() function when the stop button is clicked. We do however also want to stop the video when it finishes playing — this is marked by the ended event firing, so we also set up a listener to run the function on that event firing too.

Next, let's define stopMedia() — add the following function below playPauseMedia():
```
function stopMedia() {
  media.pause();
  media.currentTime = 0;
  play.setAttribute('data-icon','P');
}

```
>there is no stop() method on the HTMLMediaElement API — the equivalent is to pause() the video, and set its currentTime property to 0. Setting currentTime to a value (in seconds) immediately jumps the media to that position.

All there is left to do after that is to set the displayed icon to the "play" icon. Regardless of whether the video was paused or playing when the stop button is pressed, you want it to be ready to play afterwards.
