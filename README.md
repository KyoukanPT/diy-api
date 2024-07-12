<h2>DIY API</h2>

<p>Instructions on how to download the source files and use the App: </p>

<h3>Terminal (Chosen directory to clone the files - Recommended --> Desktop)</h3>

- git clone https://github.com/KyoukanPT/diy-api.git

<hr>

<h3>Node Installation</h3>
 
- Download and install <a href="https://nodejs.org/en/download"> Node.js </a> <br>

<hr>

<h3>Project Folder Directory (Terminal)</h3>
- npm install <br>
- npm install <a href="https://expressjs.com/en/starter/installing.html"> Express </a> <br>
- npm install <a href="https://ejs.co/"> EJS </a> <br>
- npm install <a href="https://www.npmjs.com/package/body-parser"> Body Parser </a> <br>
- node index.js

<hr>

<h3>How to use the App?</h3>
<p> - After running the app with Node, go to <a href="http://localhost:3000/">Localhost</a>. </p>
<p> - href="http://localhost:3000/random > Generates a new random joke.
<p> - href="http://localhost:3000/23 > Generates the joke number 23. You can replace "23" by any number you want, under 101.</p>

<h4> You'll need to use <a href="https://www.postman.com/downloads/"> Postman </a> for API testing. </h4>
<p> -  <b> Method: </b> "POST" </p>
<p> - <b> URL: </b> href="http://localhost:3000/jokes </p>
 
<p> - Testing "PATCH" > Fill in the <b>Id</b>. Then, you have the option to fill in the <b>Secret</b> and/or the <b>Score</b>. The non-updated option(s) will be returned with the already saved data from the API. The updated option(s), will update the data from the API. Don't forget to click on the "PATCH" button to update the selected <b>Id</b>.</p>
<p> - Testing "DELETE" > Fill in the <b>Id</b> and click on the "DELETE" button to delete everything from the selected <b>Id</b>.</p>
