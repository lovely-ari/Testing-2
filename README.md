<!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Page Title</title>
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <!-- Link external style sheets here if you have them -->
    <link rel="stylesheet" href="">
    <!-- Put css here if you don't have an external style sheet-->
    <style>
    
    .box {
  float: left;
  height: 20px;
  width: 20px;
  margin-bottom: 15px;
  border: 1px solid black;
  clear: both;
}

.red {
  background-color: red;
}
    
    </style>
    <!-- For Javascript -->
    <script>
    	function balert() {
    		window.alert("This is a color game where a color shows and you'll have to guess the name of the color! Easy mode :)");
    +
    }
    
    
    
    </script>
  </head>
  <body>
    
    <div class="">
      <h1>Guess the Color Game</h1>
      
      <button type="button" onclick="balert()">Directions</button>
      
      <p>Start:</p>
      
      <div class='box red'></div> <br>
      
      <input type="text" id="fname" name="fname"><br><br>

      
    </div>
  </body>
</html> 
