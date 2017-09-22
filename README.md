# Birth_DAY_Invitation_Project
This is a simple project using HTML,CSS, JavaScript
<!doctype html>
<html>

  <head>
    <link rel="stylesheet" href="Style.css">
    <script src="Script.js"></script>
    <script src="Prifixfree.js"></script>
  </head>

  <body>
  
   <div class="border">
		 <div id="outside">
    
      <p id="outside-title">
        Happy Birthday!
      </p>

      <img id="outside-pic" src="superman.jpg">

      <p>
        <button onclick="open_card()">Click to open</button>
      </p>

    </div>
   </div>
  
    <div id="inside">
    
      <p id="inside-title">
        Happy Birthday!
      </p>
      
      <img id="inside-pic" src="A.jpg">
      
      <p id="message">
        Your message here!
      </p>

      <p>
        <button onclick="close_card()">Click to close</button>
      </p>
      
    </div>
    
  </body>
  
</html>
