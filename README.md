<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Siti Norfarhana Natasha | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #ffffff;
      margin: 0;
      padding: 0;
      color: #222;
      line-height: 1.6;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 40px 20px;
    }

    header {
      text-align: center;
      padding-bottom: 40px;
      animation: fadeInDown 1.5s ease-out;
      background-color: #f0f0f0;
      height: 300px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.7);
      position: relative;
    }

    .header-bg {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }

    @keyframes slideInFromRight {
      0% {
        opacity: 0;
        transform: translateX(150px); /* Start off to the right */
      }
      100% {
        opacity: 1;
        transform: translateX(0); /* End at its final position */
      }
    }

    .pfp {
      width: 140px;
      height: 140px;
      border-radius: 50%; /* This makes the image circular */
      object-fit: cover;
      border: 4px solid white;
      margin-bottom: 15px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
      z-index: 1;
      opacity: 0;
      animation: slideInFromRight 1s ease-out 1.2s forwards; /* Animation applied */
    }

    header h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
      color: white;
      opacity: 0;
      animation: shiftLeft 1s ease-out 2.2s forwards;
    }

    header p {
      font-size: 1.1em;
      opacity: 0;
      animation: fadeInText 1s ease-out 3.2s forwards;
    }

    @keyframes shiftLeft {
      0% {
        opacity: 0;
        transform: translateX(0);
      }
      100% {
        opacity: 1;
        transform: translateX(-20px);
      }
    }

    @keyframes fadeInText {
      0% {
        opacity: 0;
        transform: translateY(10px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    section {
      margin: 40px 0;
      animation: fadeInUp 1s ease-out;
    }

    h2 {
      font-size: 1.8em;
      border-left: 5px solid #002b5b;
      padding-left: 15px;
      color: #002b5b;
      margin-bottom: 20px;
    }

    ul {
      list-style-type: none;
      padding-left: 0;
    }

    ul li::before {
      content: "\2022";
      color: #002b5b;
      font-weight: bold;
      display: inline-block;
      width: 1em;
      margin-left: -1em;
    }

    a {
      color: #004e89;
      text-decoration: none;
      transition: color 0.3s;
    }

    a:hover {
      text-decoration: underline;
      color: #001f3f;
    }

    footer {
      text-align: center;
      margin-top: 60px;
      font-size: 0.9em;
      color: #888;
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img src="building.jpg" alt="Background Header" class="header-bg">
      <img src="pfp.jpg" alt="Profile Picture" class="pfp"> <!-- Ensure the correct path to the image -->
      <h1>Siti Norfarhana Natasha binti Mohd Aiesha</h1>
      <p>Economics graduate specializing in Finance</p>
    </header>

    <section>
      <h2>About Me</h2>
      <p>I am an Economics soon-to-be graduate from International Islamic University Malaysia, specializing in finance. I am passionate about analyzing financial trends, working with data, and applying quantitative tools such as R and EViews to generate insights and support decision-making.</p>
    </section>

    <section>
      <h2>Education</h2>
      <ul>
        <li>Bachelor of Economics, International Islamic University Malaysia</li>
      </ul>
    </section>

    <section>
      <h2>Skills</h2>
      <ul>
        <li>Microsoft Excel</li>
        <li>R Programming</li>
        <li>EViews</li>
        <li>Canva (Visual & Report Design)</li>
      </ul>
    </section>

    <section>
      <h2>Projects</h2>
      <p>Coming soon... (You can list your final year project, forecasting models, economic analysis, etc.)</p>
    </section>

    <section>
      <h2>Contacts</h2>
      <ul>
        <li><a href="https://www.linkedin.com/in/siti-norfarhana-natasha-binti-mohd-aiesha-173200278" target="_blank">LinkedIn</a></li>
      </ul>
    </section>

    <section>
      <h2>Resume</h2>
      <p><a href="#">Click here to download my resume (upload PDF link)</a></p>
    </section>

    <footer>
      <p>&copy; 2025 Siti Norfarhana Natasha. All rights reserved.</p>
    </footer>
  </div>
</body>
</html>
