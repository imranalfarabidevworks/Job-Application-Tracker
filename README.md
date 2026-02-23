<!-- --------------------answer-1 ------------------------ -->

Difference between getElementById, getElementsByClassName, querySelector, querySelectorAll

getElementById()
It finds one element by ID.
ID is unique, so it returns only one element.

getElementsByClassName()
It finds elements by class name.
Many elements can have same class.
So it returns more than one element.

querySelector()
It finds the first element using CSS selector (id, class, tag).

querySelectorAll()
It finds all elements using CSS selector

<!--------------------answer2 ------------------------  -->
2. How do you create and insert a new element into the DOM?
First, we create a new element using document.createElement().
Then, we add text or content to the element using innerText or innerHTML.
After that, we insert it into the DOM using methods like appendChild() and append().

So the steps are:
1-Create element
2-Add content
3-Insert into the page

<!--------------------answer3 ------------------------  -->
Event Bubbling means when an event happens on a child element, it moves up to its parent element.
For example, if we click a button inside a div:
First, the button event runs.
Then, the div event runs.
So the event goes from child to parent. This is called bubbling.

<!--------------------answer4 ------------------------  -->
Event Delegation means adding an event listener to a parent element instead of adding it to many child elements.
Because of event bubbling, the parent can detect events from its children.
It is useful because:
It uses less memory.
It works for dynamically added elements.
It makes the code cleaner and shorter.

<!--------------------answer5------------------------  -->
preventDefault()
This method stops the default behavior of the browser.
For example, it can stop a form from submitting.
stopPropagation()
This method stops the event from moving to parent elements.
It stops event bubbling.
So:
preventDefault() stops default browser action.
stopPropagation() stops event bubbling