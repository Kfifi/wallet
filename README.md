<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saksham Wallet</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    .container {
      max-width: 700px;
      margin: auto;
      background: white;
      margin-top: 50px;
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    }

    h1 {
      color: #222;
      margin-bottom: 10px;
    }

    .subtitle {
      font-size: 18px;
      color: #666;
      margin-bottom: 30px;
    }

    .qr {
      margin: 30px 0;
    }

    .upi-id {
      font-size: 18px;
      font-weight: bold;
      color: #333;
      background: #e0ffe0;
      padding: 10px;
      border-radius: 8px;
      display: inline-block;
      margin-top: 10px;
    }

    ul {
      text-align: left;
      margin-top: 30px;
      color: #333;
      padding-left: 20px;
    }

    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #aaa;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>💰 Saksham Wallet</h1>
    <p class="subtitle">Receive UPI Payments & Manage Your Balance</p>

    <div class="qr">
      <img src="https://chart.googleapis.com/chart?cht=qr&chs=250x250&chl=upi://pay?pa=8530355291@ybl&pn=Saksham&cu=INR" alt="UPI QR Code" />
      <div class="upi-id">UPI ID: 8530355291@ybl</div>
    </div>

    <h3>✨ Features:</h3>
    <ul>
      <li>Receive money using UPI QR or link</li>
      <li>Wallet-style balance tracking</li>
      <li>See transaction history</li>
      <li>Simple, clean macOS app design</li>
    </ul>

    <footer>
      Made with ❤️ by Saksham
    </footer>
  </div>
</body>
</html>
