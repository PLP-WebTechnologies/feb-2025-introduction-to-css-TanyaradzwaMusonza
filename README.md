# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Styled Page</title>
  <!-- Link to external CSS -->
  <link rel="stylesheet" href="stye.css" />
</head>
<body>
  <h1 class="title">Welcome to My Page</h1>
  <p id="intro">This is a sample paragraph with custom styling.</p>
  <img src="example.jpg" alt="Example Image" class="styled-image" />

  <div class="content-box">
    <p>This box is styled with margins, padding, and borders.</p>
  </div>
</body>
</html>
/* General styling */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f4f4f9;
  margin: 20px;
}

/* Selector 1: Class selector */
.title {
  color: #2c3e50;
  font-size: 2em;
  text-align: center;
  margin-bottom: 10px;
}

/* Selector 2: ID selector */
#intro {
  color: #34495e;
  font-size: 1.1em;
  padding: 10px;
  background-color: #eaf2f8;
  border-left: 4px solid #2980b9;
}

/* Selector 3: Class selector for an image */
.styled-image {
  display: block;
  width: 300px;
  margin: 20px auto;
  padding: 10px;
  border: 5px solid #3498db;
  border-radius: 10px;
}

/* Additional class styling with spacing and typography */
.content-box {
  background-color: #ffffff;
  border: 2px solid #bdc3c7;
  padding: 15px;
  margin: 20px auto;
  max-width: 600px;
  font-family: Georgia, serif;
  font-size: 1em;
}

