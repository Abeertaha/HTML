# HTML
<DOCTYPE html>

<html>
    <head>
          <title> Poetic </title>
          <style>
            body {
                font-family: Georgia, 'Times New Roman', Times, serif;
                font-size:x-large;
                background-image: url(Background.jpg);
                background-size: contain;
                background-position: center;
              }   
            h1 {
            text-align: center;
            color: darkred;    
          }
          #myButton {
            padding: 10px 20px;
            background-color: darkcyan;
            color: black;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: large;
            font-weight: bold;
            border-radius: 7px;
            cursor:pointer;   
          }
          p {
            font-weight: bold;
          }
          img {
            position: fixed;
          }
            </style>        
        </head>
      <body>
        <img src="logo.jpg">
          <h1>Welcome</h1>
          <p>Click the button</p>
          <button id="myButton">Here</button>
          <p id="myText" style="display: none;"> "All that we see or seem is but a dream within a dream" </p>
          <script>
          document.getElementById("myButton").addEventListener("click", function() {
            document.getElementById("myText").style.display = "block"; 
            document.getElementById("myText").style.color = "darkred";
            document.getElementById("myText").style.fontFamily = "'Times New Roman', Times, serif";
            document.getElementById("myText").style.fontWeight = "bolder";
            document.getElementById("myText").style.backgroundColor = "lightyellow";
            document.getElementById("myText").style.textAlign = "center";
          });
          </script>
          </body>
</html>
