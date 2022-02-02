# JavaScript
i am starting JavaScript tutorials

<!DOCTYPE html>
<html>
<body>

<h2>My First JavaScript</h2>

<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

<p id="demo"></p>
  
#----------------------------------
  <h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

#---------------------------------
 
<h3>In this case JavaScript changes the value of the src (source) attribute of an image</h3> 
  
  <button onclick="document.getElementById('myImage').src='pic_bulbon.gif'">Turn on the light</button>

<img id="myImage" src="pic_bulboff.gif" style="width:100px">

<button onclick="document.getElementById('myImage').src='pic_bulboff.gif'">Turn off the light</button>
  
#---------------------------------

  <h3>JavaScript Statements</h3>
  <p>JavaScript statements are seprated by semicolons.</p>
  
  <p id="demo1></p>
   
  <script>
         let a, b, c;
         a = 5;
         b = 7;
         c = a + b;
  documents.getElementById("demo1").innerHTML = c;
  </script>
  
</body>
</html> 
