# Author
![@Rafase282](https://avatars0.githubusercontent.com/Rafase282?&s=128)

Submitted by Rafase282

[Github](https://github.com/Rafase282) | [FreeCodeCamp](http://www.freecodecamp.com/rafase282) | [CodePen](http://codepen.io/Rafase282/) | [LinkedIn](https://www.linkedin.com/in/rafase282) | [Blog/Site](https://rafase282.wordpress.com/) | [E-Mail](mailto:rafase282@gmail.com)

# Details
The algorithm to convert from Celsius to Fahrenheit is the temperature in Celsius times 9/5, plus 32.

You are given a variable `celsius` representing a temperature in Celsius. Create a variable `fahrenheit` and apply the algorithm to assign it the corresponding temperature in Fahrenheit.

Remember to use [ Read-Search-Ask](http://github.com/FreeCodeCamp/freecodecamp/wiki/How-to-get-help-when-you-get-stuck) if you get stuck. Try to pair program. Write your own code.

## Useful Links
- [The Order of Operations: PEMDAS](http://www.purplemath.com/modules/orderops.htm)
- [Order of Operation: Video](https://www.khanacademy.org/math/pre-algebra/order-of-operations/order_of_operations/v/order-of-operations)

## Problem Explanation:
- Explain what is asked in an easy to understand way.

## Hint: 1
- Take a look at the code, there is an area that yoya re not supposed to edit, from there ask yourself, what is used there that I don't see before?

## Hint: 2
- Keep in mind the `order of operation` check the link in the _link_ section for more information.

## Spoiler Alert!
[![687474703a2f2f7777772e796f75726472756d2e636f6d2f796f75726472756d2f696d616765732f323030372f31302f31302f7265645f7761726e696e675f7369676e5f322e676966.gif](https://files.gitter.im/FreeCodeCamp/Wiki/nlOm/thumb/687474703a2f2f7777772e796f75726472756d2e636f6d2f796f75726472756d2f696d616765732f323030372f31302f31302f7265645f7761726e696e675f7369676e5f322e676966.gif)](https://files.gitter.im/FreeCodeCamp/Wiki/nlOm/687474703a2f2f7777772e796f75726472756d2e636f6d2f796f75726472756d2f696d616765732f323030372f31302f31302f7265645f7761726e696e675f7369676e5f322e676966.gif)

**Solution ahead!**

## Code Solution:

```js
function convert(celsius) {
  // Only change code below this line
  var fahrenheit = (celsius * (9/5)) + 32;

  // Only change code above this line
  if ( typeof fahrenheit !== 'undefined' ) {
  return fahrenheit;
  } else {
    return 'fahrenheit not defined';
  }
}

// Change the inputs below to test your code
convert(30);
```

# Code Explanation:
- Make sure the proper order is followed with arithmetic using `()` when needed.
- Declare the `fahrenheit` variable.

## [Go Home](https://github.com/Rafase282/My-FreeCodeCamp-Code/wiki)
