# Polygon Diagonals Calculator and Drawer

This HTML document contains a simple web page for calculating and visualizing the number of diagonals in a polygon with a specified number of sides.

## Features

- **Calculate Diagonals:**
  - Enter the number of sides of the polygon in the input field.
  - Click the "गणना और चित्रण" button to calculate the number of diagonals and draw the polygon.

- **Polygon Drawing:**
  - The SVG element with id "svg" is used to draw the polygon and its diagonals.

- **Dark/Light Mode Toggle:**
  - (Commented Out)
  - Toggle between dark and light modes using the provided button.

## [HTML Code](https://github.com/itskuldipsingh/Math/blob/main/Polygon%20Diagonals%20Calculator%20and%20Drawer/Polygon%20Diagonals%20Calculator%20and%20Drawer.html)

```html
<!DOCTYPE html>
<html>
<head>
  <title></title>
  <script>
    // JavaScript functions for calculating diagonals and drawing polygons
    // (Code provided in the original HTML document)
  </script>
</head>
<body>
  <!-- Uncomment the following style and script section for dark/light mode toggle -->
  <!--
  <style>
    .dark-mode {
      background-color: black;
      color: white;
    }
  </style>
  <button onclick="darkmode()">Dark/Light mode</button>

  <script>
    function darkmode() {
      var element = document.body;
      element.classList.toggle("dark-mode");
    }
  </script>
  -->

  <h1></h1>
  <label for="numSides">भुजाओं की संख्या दर्ज करें:</label>
  <input type="text" id="numSides"><br><br>
  <button onclick="calculateDiagonals()">गणना और चित्रण</button>
  <div id="result"></div>
  <br>
  <svg id="svg" width="500" height="500"></svg>
</body>
</html>
