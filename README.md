# codenotes-by-bhumika
"Website to sell  programming notes"
<div class="notes">
  <div class="note">
    <h2>AI/ML CheatSheet</h2>
    <a href="assets/AIML_CheatSheet.pdf" download>Preview</a>
  </div>
  <div class="note">
    <h2>Complete SQL Guide</h2>
    <a href="assets/Complete_SQL_Guide.pdf" download>Preview</a>
  </div>
</div>

<h3>Scan & Pay ₹100</h3>
<img src="assets/your_qr_code.png" alt="UPI QR Code" class="qr">

<p>UPI ID: <strong>yourupi@okaxis</strong></p>

<button onclick="showDownloads()">I Paid ₹100 – Show Downloads</button>

<div id="downloads" style="display:none;">
  <h3>Download Notes</h3>
  <a href="assets/AIML_CheatSheet.pdf" download>AI/ML CheatSheet</a><br>
  <a href="assets/Complete_SQL_Guide.pdf" download>SQL Guide</a>
</div>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Buy Programming Notes - ₹100</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Buy Programming Notes</h1>
    <p>Each note just ₹100. Pay via PhonePe or GPay and download instantly!</p>

    <div class="notes">
      <div class="note">
        <h2>AI/ML CheatSheet</h2>
        <a href="assets/AIML_CheatSheet.pdf" download>Preview</a>
      </div>
      <div class="note">
        <h2>Complete SQL Guide</h2>
        <a href="assets/Complete_SQL_Guide.pdf" download>Preview</a>
      </div>
    </div>

    <h3>Scan & Pay ₹100</h3>
    <img src="assets/your_qr_code.png" alt="UPI QR Code" class="qr">

    <p>UPI ID: <strong>yourupi@okaxis</strong></p>

    <button onclick="showDownloads()">I Paid ₹100 – Show Downloads</button>

    <div id="downloads" style="display:none;">
      <h3>Download Notes</h3>
      <a href="assets/AIML_CheatSheet.pdf" download>AI/ML CheatSheet</a><br>
      <a href="assets/Complete_SQL_Guide.pdf" download>SQL Guide</a>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: sans-serif;
  background: #f0f0f0;
  text-align: center;
  padding: 20px;
}

.container {
  background: white;
  padding: 30px;
  border-radius: 10px;
  max-width: 600px;
  margin: auto;
}

.qr {
  width: 200px;
  margin: 20px 0;
}

button {
  padding: 10px 20px;
  background: #4CAF50;
  color: white;
  border: none;
  cursor: pointer;
}
function showDownloads() {
  document.getElementById("downloads").style.display = "block";
}

