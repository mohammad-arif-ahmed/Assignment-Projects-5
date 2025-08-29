 Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

Ans : 
getElementById = gets one element by id .
getElementsByClassName = gets all elements with a class html collection .
querySelector = gets the first match by css selector .
querySelectorAll = gets all match by css selector NodeList


2. How do you **create and insert a new element into the DOM**?

Ans :
Create element -  let div = document.createElement("div");
Set content/attributes -  div.innerText = "Hello"; div.className = "box";
Insert into DOM - document.body.appendChild(div);


3. What is **Event Bubbling** and how does it work?

Ans :Event Bubbling = An event on a child also triggers on its parents elements moving upward .
      

4. What is **Event Delegation** in JavaScript? Why is it useful?

Ans : Put one listener on parent, catch child events via event.target .


5. What is the difference between **preventDefault() and stopPropagation()** methods?

Ans :
preventDefault()  =  stops the browser's default action (e.g. link redirect, form submit).
stopPropagatioin() = stops the event from bybbling up to parent elements .

