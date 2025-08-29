<!-- question 1 -->

What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

>>getElementById  using for id selector and getElementsByClassName using for class selector.
>querySelector used for select html first element that used css spacified selector
>querySelectorAll used for css selector
<!-- question 2 -->
>>How do you create and insert a new element into the DOM?
using document.createElement() create new element
<!-- question 3 -->
What is Event Bubbling and how does it work?

>event bubbling is a event that target on the first element and go to root level unless stop

>parent → grandparent → body → document.

<!-- question 4 -->
What is Event Delegation in JavaScript? Why is it useful?

Event delegation used for attach a single event listener to a parent element so that manage child element
<!-- question 5-->
What is the difference between preventDefault() and stopPropagation() methods?
>>preventDefault()  Stops browsers default behavior (like opening a link, submitting a form).

stopPropagation()  Stops the event from traveling up/down the DOM tree.

