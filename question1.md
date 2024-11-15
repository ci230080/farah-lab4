# farah-lab4
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Change Content with JavaScript</title>
</head>
<body>
  <div id="myElement">
    <p id="myParagraph">Welcome to my website!</p>
  </div>

  <button onclick="changeContent()">Click Me!</button>

  <script>
    function changeContent() {
      document.getElementById("myParagraph").innerText = "Hello there!";
    }
  </script>
</body>
</html>
