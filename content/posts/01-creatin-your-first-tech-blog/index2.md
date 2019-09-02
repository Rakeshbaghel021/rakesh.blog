---
title: addEventListener
author: Rakesh Baghel
date: 2019-09-02
hero: ./images/add.png
---


# Javascript addEventListener

***
JavaScript provides event handlers that allow you to set up the code to react to certain events occuring on certain HTML elements.

JavaScript handlers of HTML DOM events can use not only HTML elements, but also any other DOM object.

EventTarget method is case sensitive, so you should always use correct capitalization.

```javascript
document.getElementById("button").addEventListener("click", displayDate);
```
here, we use addEventListener on button .so when we click it works.