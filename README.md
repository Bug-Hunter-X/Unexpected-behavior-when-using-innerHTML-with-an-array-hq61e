# Uncommon HTML Error: Incorrect innerHTML usage with arrays
This repository demonstrates an uncommon error that can occur when using the innerHTML property in JavaScript with an array.  The error is subtle and can be difficult to debug.

## Description
The bug arises from attempting to directly assign a JavaScript array to the innerHTML property of an HTML element. This results in the array being represented as a string, rather than its intended contents being rendered in the HTML. This can cause unexpected behavior and prevent the intended output from being shown.

## Solution
The solution involves correctly iterating through the array and creating the HTML content dynamically using string manipulation or more robust methods.  This example provides two solutions:

1. A basic approach using string concatenation to create the HTML.
2. A preferred approach using map to produce the HTML.

The corrected code will properly display each element of the array as individual elements on the page.