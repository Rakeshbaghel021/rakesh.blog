---
title: Creating your  first  tech  blog
author: Rakesh Baghel
date: 2019-09-01
hero: ./images/code.jpg
---

# It's all about javascript
***
## Getting started with DOM...

As we all know what is *"Document"*?. Document is nothing as we all know its just like a file whenever you say you know that its a file , it can be a excel file , it can be an HTML file or it can be any file so , thats basically your document.But in the context of DOM we usually talk about HTML document here.

so lets talk about what is "*object*" in that DOM(Document object model).Object is anything that you put inside this HTML document,so HTML tag is an object,your body tag ,head tag,title tag,button tag everything is an object and "*Model*" is how you layout all of these structure.

so DOM can add dynamic content to the web page .It represent the HTML document ,its a root element and it has *properties* and *methods*.

than what is property in DOM-It is the value you can get.


now what is methods in DOM-it is the action you can do.
so now we can understand it  by an example that what is property and methods-

```javascript
<html>
<body>

<p id="example"></p>

<script>
document.getElementById("example").innerHTML = "Hello World!";
</script>

</body>
</html>
```
getElementById
---

so here we can see that getElementById is a method and innerHTML is a property.
Here we can use id to access the element.
***
In the example above the getElementById method used id="example" to find the element.

innerHTML
---
we can get content of an element by using ineerHTML property.
*** 
The innerHTML property can be used to get or change any HTML element, including html and body.



getElementByClassName
___
as we have seen above that we use getElementById method to in which we access the element by id,but here we can access by using Class name.

```javascript
<html>
<body>

<p class="example"></p>

<script>
document.getElementByClassName("example").innerHTML = "Hello World!";
</script>

</body>
</html>
```
getElementByTagName
___

so this is just similer as we have seen above ,here we can access by using Tag name.

```javascript
<html>
<body>

<p></p>

<script>
document.getElementByClassName("p").innerHTML = "Hello World!";
</script>

</body>
</html>
```

InnerText
___
We can give text inside HTML tag by using InnerText method .It works like innerHTML.

```javascript
<html>
<body>

<p></p>

<script>
document.getElementByClassName("p").innerText = "Hello World!";
</script>

</body>
</html>
```