---
layout: page
title: JavaScript Projects 4
subtitle: JavaScript Projects for our Pre Apprenticeship Training
use-site-title: true
permalink: /projects/js4
---

# About Me
Start with this HTML
```html
<!DOCTYPE html>
<html>
 <head>
  <meta charset="utf-8"/>
  <title>About Me</title>
</head>
<body>
  <h1>About Me</h1>

  <ul>
    <li>Nickname:
      <span id="nickname"></span>
    </li>
    <li>Favorites:
      <span id="favorites"></span>
    </li>
    <li>Hometown:
      <span id="hometown"></span>
    </li>
   </ul>

 </body>
</html>
```

1. (In JavaScript) Change the body tag's style so it has a font-family of "Arial, sans-serif".
1. (In JavaScript) Replace the content of each of the spans (nickname, favorites, hometown) with your own information.
1. Iterate through each li and add a class of "listitem". Add a style tag that sets a rule for "listitem" to make the color red.
1. Create a new img element and set its src attribute to a picture of you. Append that element to the body.

# Logo Hijack
1. Open up www.google.com in Chrome or Firefox, and open up the console.
1. Find the Google logo and store it in a variable.
1. Modify the source of the logo IMG so that it's a Yahoo logo instead. (http://www.logostage.com/logos/yahoo.GIF)

# The Reading List Part II
1. Create a webpage with an `h1` of "My Book List".
1. Copy the array of books from the previous exercise.
1. Iterate through the array of books. For each book, create a `p` element with the book title and author and append it to the page.
1. **Bonus:** Use a `ul` and `li` to display the books.
1. **Bonus:** add a property to each book with the URL of the book cover, and add an `img` element for each book on the page.
1. **Bonus:** Change the style of the book depending on whether you have read it or not.

# Challenge Question: The Counter
Write a function that takes a certain type of tag and counts the number of elements with that tag. The function should return "There a X tags of type y on the page. For example:
```
countTags('p'): 'There are 3 tags of type p on the page'
```
