<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Page</title>
  <style>
    /* Internal CSS (merged from the previous style.css file) */

    /* 1. Styling an element with an ID selector */
    #main-header {
      font-family: 'Arial', sans-serif;
      color: #333;
      text-align: center;
      margin-bottom: 20px;
    }

    /* 2. Styling elements with a class selector */
    .content {
      font-family: 'Verdana', sans-serif;
      color: #444;
      padding: 15px;
      margin: 20px;
      border: 2px solid #ccc;
      background-color: #f9f9f9;
    }

    /* 3. Styling an element with a universal selector */
    img {
      width: 100%;
      height: auto;
      border: 5px solid #ddd;
      border-radius: 8px;
      margin-top: 20px;
    }

    /* 4. Styling using margin, padding, and borders */
    .container {
      margin: 40px;
      padding: 20px;
      border: 3px solid #007bff;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <!-- Header Section with an ID -->
  <header id="main-header">
    <h1>Welcome to My Styled Page</h1>
  </header>

  <!-- Content Section with a Class -->
  <div class="content">
    <h2>Introduction</h2>
    <p>This is a simple example to demonstrate the use of CSS selectors, margins, padding, and borders.</p>
  </div>

  <!-- Image Section with Styling Applied -->
  <div class="container">
    <img src="https://via.placeholder.com/800x400" alt="Placeholder Image">
  </div>

  <footer>
    <p>&copy; 2025 My Styled Page</p>
  </footer>

</body>
</html>

