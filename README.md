<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Stock Market Data</title>
</head>
<body>
  <h1>Stock Market Data</h1>
  <form id="symbol-form">
    <label for="symbol">Enter Stock Symbol:</label>
    <input type="text" id="symbol" required>
    <button type="submit">Fetch Data</button>
  </form>
  <div id="result">
    <!-- Display stock data here -->
  </div>
  <script src="app.js"></script>
</body>
</html>
