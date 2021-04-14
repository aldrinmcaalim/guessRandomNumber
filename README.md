# Guess the Number

This took me about 2 hours to complete.

## What did I learn?

### HTML

1. I reinforced the use of forms.

### CSS

1. I utlized flexbox to quickly center my interface.
   - I used min-height, along with flexbox and border-box, to place the interface directly in the middle of the window.

### JavaScript

1. I learned some differences between textContent, innerText, and innerHTML.
2. Functions in JS are first-class citizens, which means that you can use functions to obtain a value and use that obtained value you got from a function within another function.
3. You can reference HTML DOM elements using selectors like "document.querySelector('thing you select')".
4. You can put an event listener in another event listener.
5. You can affect the attributes of HTML DOM elements.
6. Using "document.querySelectorAll('element')" allows us to create an Array-like item (also known as a "NodeList") that we can loop through, it is NOT an array.
   - You can't use common array methods like push(), pop(), slice(), or join() directly, in order to do that you must convert the NodeList using the "Array.from()" method.
7. The forEach, which is a method, can be used if you need to loop through items in an array.
   - Using forEach means you probably don't need to manipulate what you're looping through.
