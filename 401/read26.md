# Django 

>Django is a Python-based web framework used by millions of developers and billions of consumers through popular apps like Instagram. It is open source, meaning the code is available for free on Github and can be downloaded onto any developer’s computer and used alongside the official documentation.

# Django helps you write software that is:


## Complete : 
you can find everything you need as developer 
## Versatile :
you can use Django for almost everything like content management , wikies ,social networks ..etc 
## Secure :
it helps to protect websites in automatic way for example in the accounts and passwords system avoiding common mistakes like putting session information in cookies where it is vulnerable (instead cookies just contain a key, and the actual data is stored in the database) or directly storing passwords rather than a password hash.
## Scalable 

Having a clear separation between the different parts means that it can scale for increased traffic by adding hardware at any level: caching servers, database servers, or application servers. Some of the busiest sites have successfully scaled Django to meet their demands (e.g. Instagram and Disqus, to name just two).
## Maintainable
Django code is written using design principles and patterns that encourage the creation of maintainable and reusable code
## Portable

you can use it on mac, windows ,linux

# What does Django code look like?
Django web applications typically group the code that handles each of these steps into separate files:


![dj](basic_django.png)


### URLs:
 While it is possible to process requests from every single URL via a single function, it is much more maintainable to write a separate view function to handle each resource. ***A URL mapper is used to redirect HTTP requests to the appropriate view based on the request URL***. The URL mapper can also match particular patterns of strings or digits that appear in a URL and pass these to a view function as data.


### View:
 A view is a request handler function, which receives HTTP requests and returns HTTP responses. Views access the data needed to satisfy requests via models, and delegate the formatting of the response to templates.

 ### Models:
  Models are Python objects that define the structure of an application's data, and provide mechanisms to manage (add, modify, delete) and query records in the database. 

### Templates: 
A template is a text file defining the structure or layout of a file (such as an HTML page), with placeholders used to represent actual content. A view can dynamically create an HTML page using an HTML template, populating it with data from a model. A template can be used to define the structure of any type of file; it doesn't have to be HTML!
