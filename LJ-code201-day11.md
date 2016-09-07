#LJ Code 201 - Day 11

#Truthy and Falsy

Realized that I still don't all the way get the concept of Truthy and Falsy, so I went back through the chapters on it to try and distill an understanding:
- FALSY values are treated as if they are false (values of: null, 0, false, empty string, NaN, or a variable with no assigned value)
- TRUTHY values are treated as if they are true - pretty much everything outside of the falsy values (numbers other than 0, true, strings w content, number calculations, true/false/0 as a string)

#Using truthy and Falsy

A unary operator returns a result with just one operand. Use an if statement to check for the presence of an element - if it's found, then the result is truthy, so the first set of code runs. If it isn't found, then the second set of code is run instead.

if (document.getElementById('header')) {
  // Found: do this
} else {
  // Not found: do this instead
}
