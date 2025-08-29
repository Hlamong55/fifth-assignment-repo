1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?

**ANS:** 
getElementById -→ It returns only one element which has unique Id.

getElementsByClassName -→ It returns HTML collection of all elements which has same class name.

querySelector -→ It's like CSS selector that returns the only first match elements.

querySelectorAll -→ It returns a nodelist that contains all the match elements.




2. How do you **create and insert a new element into the DOM**?

**ANS:** 
 1st -→ Create element by using createElement()
 2nd -→ then add class/content
 3rd -→ finally insert into a DOM by using appendChild() or prepend() in parent element




3. What is **Event Bubbling** and how does it work?

**ANS:**
Event bubbling is the process where an event starts from the child element and progress upward through its parent elements in the DOM.




4. What is **Event Delegation** in JavaScript? Why is it useful?

**ANS:**
Event Delegation in JavaScript means putting one event listener on the parent instead of many child, and letting the event bubble up.
It is usefull because...it saves memory and it works even new childs are added in later.


5. What is the difference between **preventDefault() and stopPropagation()** methods?

**ANS:** 
preventDefault() -→ It stops browser default action.

stopPropagation() → It stops the event from bubble up to parent elements.