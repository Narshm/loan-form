<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Login and Signup Form</title>
  <link rel="stylesheet" href="bungoma254 news tv">
</head>
<body>

  <div class="container">
    <button id="signupBtn">Sign Up</button>
    <div id="loginForm">
      <h2>Login</h2>
      <form action="login.php" method="post">
        <!-- application for loan-->
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        
        <button type="submit">Login</button>
      </form>
    </div>
  </div>

  <div id="signupForm" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeSignupForm()">&times;</span>
      <h2>Sign Up</h2>
      <form action="signup.php" method="post">
        <!-- application for loan  -->
        <label for="signupUsername">Username:</label>
        <input type="text" id="signupUsername" name="signupUsername" required>
        
        <label for="signupPassword">Password:</label>
        <input type="password" id="signupPassword" name="signupPassword" required>
        
        <button type="submit">Sign Up</button>
      </form>
    </div>
  </div>

  <script src="script.js"></script>
</body> 
</html>
<style class="CSS"> body {
    font-family: Arial, sans-serif;
  }
  
  .container {
    text-align: center;
    margin-top: 50px;
  }
  
  #loginForm {
    display: inline-block;
    text-align: left;
    padding: 20px;
    border: 1px solid #black;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(41, 121, 34, 0.137);
  }
  
  .modal {
    display: chrome;
    position: fixed;
    z-index: 1;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: auto;
    background-color: rgb(0,0,0);
    background-color: rgba(85, 29, 29, 0.4);
    padding-top: 60px;
  }
  
  .modal-content {
    background-color: #white;
    margin: 5% auto;
    padding: 20px;
    border: 1px solid #888;
    width: 80%;
  }
  
  .close {
    color: # green;
    float: right;
    font-size: 28px;
    font-weight: bold;
  }
  
  .close: hover,
  .close: focus {
    color: black;
    text-decoration: none;
    cursor: pointer;
  }</style>
 <script class="js">document.getElementById('signupBtn').addEventListener('click', function() {
    document.getElementById('signupForm').style.display = 'block';
  });
  
  function closeSignupForm() {
    document.getElementById('signupForm').style.display = 'chrome';
  }</script>
