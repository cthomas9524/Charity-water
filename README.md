<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Charity: Water</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(to top right, #a1c4fd, #fbc2eb);
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 40px;
    }

    .container {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      background-color: #d2e8f1;
      border-radius: 30px;
      overflow: hidden;
      max-width: 1200px;
      width: 100%;
    }

    .left-section {
      flex: 1;
      min-width: 300px;
    }

    .left-section img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    .right-section {
      flex: 1;
      min-width: 300px;
      padding: 40px;
      background: linear-gradient(to top right, #fefcea, #f1f9ff);
    }

    .logo {
      font-family: 'Playfair Display', serif;
      font-size: 20px;
      margin-bottom: 10px;
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: 48px;
      color: #002244;
      margin-bottom: 10px;
    }

    .tagline {
      font-size: 20px;
      color: #2e7d75;
      margin-bottom: 30px;
    }

    .message {
      font-size: 18px;
      line-height: 1.6;
      color: #222;
      margin-bottom: 30px;
    }

    .buttons {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }

    .buttons button {
      padding: 12px 24px;
      font-size: 16px;
      border: 2px solid #336666;
      background-color: #e1f5f2;
      border-radius: 20px;
      color: #336666;
      font-weight: bold;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .buttons button:hover {
      background-color: #336666;
      color: #ffffff;
    }
  </style>
</head>

<body>
  <div class="container">
    <div class="left-section">
      <img src="womanpouringwater.jpg" alt="Woman at water pump">
    </div>
    <div class="right-section">
      <div class="logo">charity: water</div>
      <h1>Charity: Water</h1>
      <div class="tagline">Change isn’t a Donation. It’s a Movement</div>
      <div class="message">
        When clean water flows into a village, girls go back to school.<br>
        When education programs are funded, whole families rise.<br>
        When voices are heard, systems shift.<br><br>
        This isn’t just about helping. It’s about rebuilding futures with those who’ve been left out of the story.<br><br>
        So, how do you get connected..?
      </div>
      <div class="buttons">
        <button>Get Involved</button>
        <button>Donate</button>
        <button>About Us</button>
      </div>
    </div>
  </div>
</body>

</html>

