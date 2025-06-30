# Index
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UBER APP</title>
   <link rel="stylesheet" type="text/css" href="Style.css">
        </head>
        <body>
          <style>
            body {font-family: 'Times New Roman', Times, serif, Helvetica, sans-serif;
     background-image: url('Uber.png');
     background-repeat: no-repeat;
     background-size: 100%;
     align-content: center;
     max-width: 500px;
     margin: auto;
     padding: 10px;
}
          </style>
        
        <h1>Uber Login Form</h1>
        
        <button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Login</button>
        
        <div id="id01" class="modal">
          
          <form class="modal-content animate" action ="Main.html"  method="post">
            <div class="imgcontainer">
              <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
              <img src="logo.png" alt="logo" class="logo">
            </div>
        
            <div class="container">
              <label for="uname"><b>Username</b></label>
              <input type="text" placeholder="Enter Username" name="uname" required>
        
              <label for="psw"><b>Password</b></label>
              <input type="password" placeholder="Enter Password" name="psw" required>
              <span class="psw">Forgot <a href="#">password?</a></span>

              <button type="submit">Login</button>
              <label>
                <input type="checkbox" checked="checked" name="remember"> Remember me
              </label>
            </div>
        
            <div class="container" style="background-color:#f1f1f1">
              <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
              <span class="signup"> Don't have an account? <a href="Signup.html"> Signup </a></span>
            </div>
          </form>
        </div>
        
        <script>
        // Get the modal
        var modal = document.getElementById('id01');
        
        // When the user clicks anywhere outside of the modal, close it
        window.onclick = function(event) {
            if (event.target == modal) {
                modal.style.display = "none";
            }
        }
        </script>
</body>
</html>
