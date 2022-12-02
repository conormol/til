# The Script Element 

The script element (<script>) is used in HTML files to link to javascript files for interactivity. External javascript files are linked using the src attribute.
  
  By default, the linked javascript file is loaded and executed the moment the HTML parser encounters it. It does not continue to parse the rest of the document until the Javascript file has been fully executed.
  ```
  <script src='script.js'></script> 
  ```
 ## defer
  
  The defer attribute within the script tag indicates that the parser should finish with the HTML file before dealing with the linked Javascript file.
  ```
    <script src='script.js' defer></script> 
 ```
  
  ## async
  The async attribute will allow the HTML parser to continue as the javascript file is loading, but will execute the javascript file as soon as it is fully loaded, and only resume parsing the HTML file once the javascript file has finished executing.
   ```
    <script src='script.js' async></script> 
 ```
  
