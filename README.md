# my-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome</title>
  <style>
    /* Reset margins and ensure full height */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      min-height: 100vh;
      width: 100%;
      /* Background setup to fill the entire screen without repeating */
      background-image: url('Pop177.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;
      
      font-family: 'happytree', sans-serif;
      color: purple;
      text-align: center;
      
      /* Center contents vertically and horizontally */
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-content: center;
      padding: 20px;
    }

    h1 {
      font-size: clamp(1.8rem, 5vw, 3rem);
      margin-bottom: 15px;
    }

    .loading-text {
      font-size: clamp(1rem, 3vw, 1.5rem);
      margin-bottom: 25px;
    }

    /* Keeps your button image fitted and responsive */
    .custom-button {
      max-width: 80%;
      height: auto;
      display: inline-block;
      border: none;
    }

    a {
      display: inline-block;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <h1>Welcome to the web</h1>
  
  <div class="loading-text">
    starting loading web...
  </div>

  <!-- Button linking to page or image -->
  <a href="Pop177.jpg">
    <img src="Pop177.jpg" alt="Enter" class="custom-button">
  </a>

</body>
</html>

  