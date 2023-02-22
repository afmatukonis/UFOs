# UFOs
Module-12

**Overview**

Using JavaScript, HTML, and CSS code we were tasked with creating a new table with different filters on a website. 

**Analysis**

I used JavaScript to create the HTML table and referenced two different javascript files, app.js and data.js. I created a filtered data function that extracted matching data from the whole set of data. 

Using visual studio code I editied the base of the webpage. I referenced <nav class="navbar navbar-dark bg-dark navbar-expand-lg"> so that the nav bar would fit the page regardless of size, and then linked the css stye sheets to modify the stylistic elements. I added a jumbotron element that read "The Truth is our There" using this text:
  
  <div class="jumbotron">

    <h1 class="display-4">The Truth is Out There</h1>

  </div>
  
  I used bootstrap styling reference classes such as container-fluid, col-md, and bg-dark. Using the general HTML structure of col-md which when nested in a row element split the row on the webpage into equal spaces. 
  
  To build the data table with filtering I first referenced the data as a javascript object and then iterated through each element. I imported the code inot the webpage and referenced the D3 library. 
  
<script src="https://cdnjs.cloudflare.com/ajax/libs/d3/4.11.0/d3.js"></script>

<script src="static/js/data.js"></script>

<script src="static/js/app.js"></script>
  
Then I imported a javascript list of objects using const tableData = data and used the D3 library to select the tbody element. 
  
**Results**
  
To perform a search on the webpage the user must enter information inot one of the search fields.
  
My web page did not properly load for some reason, my code is correct but I believe it has to do with the ability to reference the app.js and data.js and css.style files. 
  
