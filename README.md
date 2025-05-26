
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chaity: Water</title>
  <link href="https://cthomas9524.github.io/charity.water" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', sans-serif;
      background: linear-gradient(to right, #77a8bb, #c8a1b2, #77a8bb);

    }

    .container {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      min-height: 100vh;
      padding: 40px;
      box-sizing: border-box;
      background: linear-gradient(to top right, #77a8bb, #fbc2eb);
    }

    .left-section,
    .right-section {
      flex: 1 1 300px;
      min-width: 300px;
    }

    .left-section img {
      width: 100%;
      border-radius: 40px;
    }

    .right-section {
      color: #002244;
      padding-top: 20px;
      text-align: right;
    }

    .logo {
      font-family: 'Playfair Display', serif;
      font-size: 28px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    h1 {
      font-family: 'Georgia Pro Condensed', serif;
      font-size: 64px;
      color: #002244;
      margin: 0;
    }

    .tagline {
      font-size: 24px;
      color: #336666;
      margin: 10px 0 30px;
    }

    .message {
      font-size: 18px;
      line-height: 1.6;
      margin-bottom: 30px;
    }

    .buttons {
      display: flex;
      gap: 20px;
      flex-wrap: row-reverse;
      justify-content: flex-end;
    }

    .buttons button {
      padding: 15px 25px;
      font-size: 18px;
      color: #77a8bb;
      border: 2px solid #002244;
      background-color: #eeecde;
      border-radius: 20px;
      cursor: pointer;
      transition: all 0.3s ease;
      font-family: 'Georgia Pro', serif;
      font-weight: bold;
    }

    .buttons button:hover {
      background-color: #002244;
      color: white;
    }

    @media (max-width: 900px) {
      .container {
        flex-direction: column;
        padding: 20px;
      }

      .right-section {
        text-align: left;
        padding-top: 10px;
      }

      .buttons {
        justify-content: flex-start;
      }

      h1 {
        font-size: 40px;
      }
    }

    @media (max-width: 600px) {
      .container {
        padding: 10px;
      }

      .left-section img,
      .logo img {
        width: 100%;
        height: auto;
        border-radius: 20px;
      }

      h1 {
        font-size: 28px;
      }

      .tagline {
        font-size: 16px;
      }

      .message {
        font-size: 14px;
      }

      .buttons button {
        font-size: 14px;
        padding: 10px 15px;
      }
    }
  </style>
</head>

<body>
  <div class="container">
    <div class="logo">
      <img src="cw_logo.png" alt="Charity: Water Logo" style="height:50px;">
    </div>
    <div class="left-section">
      <img src="womanpouringwater.jpg" alt="Woman at water pump">
    </div>
    <div class="right-section">
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
