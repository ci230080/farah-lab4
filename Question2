<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Number Checker</title>
</head>
<body>
  <input type="text" id="userInput" placeholder="Enter a number">
  <button onclick="checkInput()">Check</button>

  <script>
    function checkInput() {
      const userInput = document.getElementById("userInput").value;
      const number = parseFloat(userInput);

      if (isNaN(number)) {
        alert("Please insert a number!");
      } else if (number < 10) {
        alert("The number is lower than 10");
      } else if (number > 10) {
        alert("The number is higher than 10");
      } else {
        alert("The number is exactly 10");
      }
    }
  </script>
</body>
</html>
