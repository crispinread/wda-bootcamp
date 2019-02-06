---
layout: page
title: JavaScript Projects 1
subtitle: JavaScript Projects for our Pre Apprenticeship Training
use-site-title: true
permalink: /projects/javascript-projects1
---

# The Age Calculator
Forgot how old someone is? Calculate it!

1. Store the current year in a variable.
1. Store their birth year in a variable.
1. Calculate their 2 possible ages based on the stored values.
1. Output them to the screen like so: "They are either NN or NN", substituting the values.

# The Fortune Teller
Why pay a fortune teller when you can just program your fortune yourself?

1. Store the following into variables:
    * number of children
    * partner's name
    * geographic location
    * job title
2. Output your fortune to the screen like so: "You will be a X in Y, and married to Z with N kids."

# Using Math functions
JavaScript has a built-in tool that can generate a random number between 0 and 1. This tool is called a *method*. We'll talk about methods more later in the class. For now, know if you type `Math.random()`, you'll get a random number between 0 and 1.

Using this tool, update your fahrenheit to celsius tempature conversion program to do the following:

1. Instead of inputing a value for the Fahrenheit tempature, use Math.random() to generate a random tempature between 0 and 100
1. Have to program output: "It is NN°F today. That's NN°C."

# The Temperature Converter
Let's make a program to convert celsius tempatures to fahrenheit and vice versa, so we can complain about the weather with our friends oversees.

**Reminder:** To convert celsius to fahrenheit, multiply by 9, then divide by 5, then add 32. To convert fahrenheit to celsius, deduct 32, then multiply by 5, then divide by 9.

**Unicode Characters:** To print the degrees symbol in JavaScript, we need to use the write \u00B0 to represent the unicode character for the degress symbol.

1. Store a celsius temperature into a variable.
1. Convert it to fahrenheit and output "NN°C is NN°F".
1. Now store a fahrenheit temperature into a variable.
1. Convert it to celsius and output "NN°F is NN°C."
