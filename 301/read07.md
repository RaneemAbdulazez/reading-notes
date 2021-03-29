# Roy Fielding


helped write the first web servers, that sent documents across the Internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.


 HTTP, it's capable of all sorts of neat stuff that people ignore for some reason , http  is capable of describing the location of something anywhere in the world from anywhere in the world


 The whole world wide web is built on an architectural style called “REST”. REST provides a definition of a “resource”,



 Web Services” or "APIs". It means a lot of different things to a lot of different people but the basic concept is that machines could use the web just like people do.


 # polymorphism :
 a geeky way of saying that different nouns can have the same verb applied to them


 >The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed. But the important thing here is that very different kinds of nouns can be treated the same. Whether the noun is an image, text, video, an mp3, a slideshow, whatever. I can GET all of those things the same way given a URL.

HTTP GET:Each of the systems would retrieve information from each other

 HTTP POST :If one system needs to add something to another system

HTTP PUT :If a system wants to replace something in another system
 HTTP PATCH :igure out is what the data models should look like
 
  


# Super Agent :
SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!



Documentation :https://visionmedia.github.io/superagent/docs/test.html

how to do request ?
request('GET', '/search').then(success, failure);


Example :
```
 request


 //what u're trying to do ? post ,send pathch ...etc 
   .post('/api/pet')
   .send({ name: 'Manny', species: 'cat' })
   .set('X-API-Key', 'foobar')
   .set('Accept', 'application/json')

   //response 
   .then(res => {
      alert('yay got ' + JSON.stringify(res.body));
   });
   ```