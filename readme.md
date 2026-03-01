What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Answer :
i. Find one unique Element we use getElementById.one special element.
ii.We can use same class to find all elements using getElementsByClassName.group of similar elements.
iii.Like CSS selector we find element using #id, .class tag name , first matches querySelector. first match.
iv. Finds all the elements together like (getElementsByClassName).Using CSS selector matches. Using querySelectorAll find all matches -->

Question NO-2
How do you create and insert a new element into the DOM?

Answer :
i.create Element using document.getElementById("div");
ii.add text in p -> newP.innerText = "Hello Programming Hero "
iii.add or insert in page -> document.body.appendChild(newP);
We can make a new element like this <p> example that i given up.

Question NO-3
What is Event Bubbling? And how does it work?

Answer :
Event bubbling means when i click on a child element, the event also moves up to its parent, then grandparent, and so on.
Example: Clicking a button inside a <div> → first button's event runs, then the <div>'s event, then the <body>'s event.

Question NO-4
What is Event Delegation in JavaScript? Why is it useful?

Answer :
Event delegation means i can put one event listener on a parent element, and it handles events for its children.
Useful because:
Less code
Faster performance
Easy to manage dynamic elements

Question NO-5
What is the difference between preventDefault() and stopPropagation() methods?

Answer :
preventDefault() → Stops the browser's default action.
topPropagation() → Stops the event from bubbling up to parent elements.
