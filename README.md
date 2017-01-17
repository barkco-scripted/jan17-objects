# Group exercise

Open a new jsfiddle at jsfiddle.net

Add this to the to HTML section:

```
<h1>Students</h1>
<ul id='students'>  
</ul>

<h1>Teachers</h1>
<ul id='teachers'>
</ul>
```

Add this to the Javascript section:
```
var roster =  { 
  students: ["Alma", "Celina", "Daniel", "Imani", "Jashmine", "Johanny", "Raishan", "Richard",  "Wensael"],
  teachers: ["Ali", "Alvin", "Becky", "Erin", "Ray"]
};

// TODO: Add the names of all the students to the students list. 
// Make sure you add them as list items 
// <li>NAME</li>


// TODO: Add the names of all the teachers to the teachers list. 
// Make sure you add them as list items 
// <li>NAME</li>
```

Add "https://code.jquery.com/jquery-3.1.1.min.js" to the External links section so you can use jQuery.

Do the TODO items! 


# Partner exercise

In index.html, there is a skeleton web page. In data.js, there is a function named 'getData' that returns an object with image data.

1. Update page.js to print the result of `getData()` to the console when the page loads.
2. Add the images returned in `getData()` to the `#gifs` div on index.html. 
   Use functions to display the data!!
3.  Wrap the images in the link_url so when you click on them, you go to the original page.
4. Do the same exercise but use data2.js instead of data.js.     
5. Make it pretty
