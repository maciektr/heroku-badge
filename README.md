heroku-deployment-badges
==================
![Heroku](https://badge-heroku.herokuapp.com/?app=badge-heroku)

## Usage

Create an `img` with src `https://badge-heroku.herokuapp.com/?app={app-name}`. E.g.,

HTML:
    <img src="https://badge-heroku.herokuapp.com/?app=badge-heroku" />
    
Markdown:

    [![Heroku](https://badge-heroku.herokuapp.com/?app=badge-heroku)]


If the heroku app has no index.html than use the root query parameter to specify the url to check if heroku response with http status 200.

HTML:
    <img src="http://badge-heroku.herokuapp.com/?app=badge-heroku&root=projects.html" />

Markdown:

    [![Heroku](http://badge-heroku.herokuapp.com/?app=badge-heroku&root=projects.html)]

Failed Example

HTML:
    <img src="http://badge-heroku.herokuapp.com/?app=angularjs-crypto&style=flat&svg=1&root=notfound.html" />

Markdown:

    [![Heroku](http://badge-heroku.herokuapp.com/?app=angularjs-crypto&style=flat&svg=1&root=notfound.html)]    

Support now flat badge design.

HTML:
    <img src="http://badge-heroku.herokuapp.com/?app=angularjs-crypto&style=flat" />

Markdown:

    [![Heroku](http://badge-heroku.herokuapp.com/?app=angularjs-crypto&style=flat)]

Support now svg images.

HTML:
    <img src="http://badge-heroku.herokuapp.com/?app=angularjs-crypto&style=flat&svg=1" />

Markdown:

    [![Heroku](http://badge-heroku.herokuapp.com/?app=angularjs-crypto&style=flat&svg=1)]
    
Support use custom page

The query parameter root is used to specify a different url to perform the check get request.
The following example will check if the the url 'https://angularjs-crypto.herokuapp.com/index.html' 
return response status code 200 or 401 and display the proper badge image for it.

HTML:
    <img src="http://badge-heroku.herokuapp.com/?app=angularjs-crypto&style=flat&svg=1&root=index.html" />

Markdown:

    [![Heroku](http://badge-heroku.herokuapp.com/?app=angularjs-crypto&style=flat&svg=1&root=index.html)]

License
--------------

heroku-deployment-badges is released under the [MIT License](http://opensource.org/licenses/MIT).
