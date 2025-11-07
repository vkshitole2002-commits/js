<!DOCTYPE html>
<html>
<head>
  <title>Multiplication Table</title>
</head>
<body>
  <h2>Multiplication Table Generator</h2>

  <script>
    // Program to generate a multiplication table up to a range

    // take number input from the user
    const number = parseInt(prompt('Enter an integer: '));

    // take range input from the user
    const range = parseInt(prompt('Enter a range: '));

    // creating a multiplication table
    for (let i = 1; i <= range; i++) {
      const result = i * number;
      document.write(`${number} * ${i} = ${result}<br>`);
    }
  </script>
</body>
</html>
