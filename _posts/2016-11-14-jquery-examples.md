---
layout: post
title: jQuery examples.
---

The really cool thing in my opinion with jQuery is how it lets you interact more easily with the [DOM](https://en.wikipedia.org/wiki/Document_Object_Model). For instance if you wanted to add a class to all paragraph tags in vanilla JavaScript you would have to do something like:
```JavaScript
var paragraph = document.querySelectorAll('p');
for (var i = 0; i < paragraph.length; i++){
    paragraphs[ i ].classList.add('foo');
};
```
Were in jQuery you could simply do this:
```JavaScript
$('p').addClass('foo');
```

You can also do some fairly cool styling. Say you have the above class 'foo' now and you want to change the font color for all instances of that class:
```JavaScript
$('.foo').css('color', 'blue');
```

While it's ugly you could also string several together like so:
```JavaScript
$('.foo').css('color', 'blue').css('background-color', 'yellow').css('font-size', '200%');
```

These are just super small examples of what can be done. There is a ton of built in functionality to [jQuery](https://jquery.com/).
