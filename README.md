# my-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      min-height: 100vh;
      width: 100%;
      background-image: url('Pop177.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      align-items: center;
      padding-bottom: 50px;
    }

    .enter-button {
      display: inline-block;
      padding: 15px 30px;
      background-color: rgba(128, 0, 128, 0.85);
      color: white;
      text-decoration: none;
      font-size: 1.2rem;
      font-weight: bold;
      border-radius: 25px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
      transition: transform 0.2s ease;
    }

    .enter-button:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

  <!-- Tap this button to enter the main page
-->
<a href="Pop177.html" class="enter-button">Enter Web Page</a>
</body>
</html>
