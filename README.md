<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Signup Form</title>
  <style>
    body {
      background: #f0f0f0;
      font-family: Arial, sans-serif;
    }

    .form-container {
      width: 350px;
      background: white;
      margin: 50px auto;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
      overflow: hidden;
      border: 1px solid #ccc;
    }

    .form-header {
      background: linear-gradient(to bottom, #dbe7f9, #b6cde5);
      padding: 15px;
      text-align: center;
      font-size: 18px;
      font-weight: bold;
      border-bottom: 1px solid #ccc;
      position: relative;
    }

    .form-header img {
      position: absolute;
      right: 10px;
      top: 10px;
      height: 40px;
    }

    .form-body {
      padding: 20px;
    }

    .form-body label {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }

    .form-body input[type="text"],
    .form-body input[type="password"],
    .form-body input[type="email"] {
      width: 100%;
      padding: 8px;
      border: 1px solid #ccc;
      border-radius: 6px;
      margin-top: 5px;
      background-color: #f9f9f9;
    }

    .form-body .checkbox {
      margin-top: 15px;
      display: flex;
      align-items: flex-start;
    }

    .form-body .checkbox input {
      margin-right: 10px;
      margin-top: 3px;
    }

    .form-footer {
      background: linear-gradient(to bottom, #dbe7f9, #b6cde5);
      padding: 15px;
      text-align: center;
      border-top: 1px solid #ccc;
    }

    .form-footer button {
      padding: 8px 20px;
      font-size: 14px;
      background-color: #e3eaf6;
      border: 1px solid #999;
      border-radius: 6px;
      cursor: pointer;
    }

    .login-text {
      font-size: 14px;
      margin-bottom: 10px;
    }

    .login-text a {
      color: #2a74d2;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <div class="form-container">
    <div class="form-header">
      Signup
      <img src="https://i.ibb.co/hFvtHfL/giit-logo.png" alt="Logo"> <!-- Replace with real logo if needed -->
    </div>

    <div class="form-body">
      <div class="login-text">
        Already have an account? <a href="#">Login.</a>
      </div>

      <label>Username:</label>
      <input type="text" placeholder="Enter username">

      <label>Password:</label>
      <input type="password" placeholder="Enter password">

      <label>Confirm Password:</label>
      <input type="password" placeholder="Confirm password">

      <label>Email Address:</label>
      <input type="email" placeholder="Enter email">

      <label>First Name:</label>
      <input type="text" placeholder="Enter first name">

      <label>Last Name:</label>
      <input type="text" placeholder="Enter last name">

      <div class="checkbox">
        <input type="checkbox" id="terms">
        <label for="terms" style="font-weight: normal;">I have read the Grooveshark Terms of Service. (opens in a new window)</label>
      </div>
    </div>

    <div class="form-footer">
      <button type="submit">Signup</button>
    </div>
  </div>

</body>
</html>
