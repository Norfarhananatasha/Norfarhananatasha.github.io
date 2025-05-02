<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Academic Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>Welcome to My Academic Portfolio</h1>
    <p>Select a section:</p>
    <div class="links">
      <a href="partial-transcript.html">📄 Partial Transcript</a>
      <a href="certificates.html">🎓 Certificates</a>
      <a href="curriculum.html">📘 Curriculum</a>
    </div>
  </div>
</body>
</html>

#css
body {
  font-family: Arial, sans-serif;
  background-color: #f0f4f8;
  text-align: center;
  margin: 0;
  padding: 0;
}

.container {
  padding: 40px;
}

h1 {
  color: #333;
}

.links a {
  display: block;
  margin: 15px auto;
  padding: 12px 24px;
  background-color: #007bff;
  color: white;
  text-decoration: none;
  width: 250px;
  border-radius: 10px;
  font-weight: bold;
}

.links a:hover {
  background-color: #0056b3;
}

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Partial Transcript</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>My Partial Transcript</h1>
    <p>Here you can view or download my partial transcript:</p>
    <a href="files/partial-transcript.pdf" target="_blank">📥 Download Transcript (PDF)</a>
    <br><br>
    <a href="index.html">← Back to Home</a>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Certificates</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>My Certificates</h1>
    <ul style="text-align: left; display: inline-block;">
      <li><a href="files/certificate-1.pdf" target="_blank">Certificate in Excel</a></li>
      <li><a href="files/certificate-2.pdf" target="_blank">Participation in Data Science Workshop</a></li>
    </ul>
    <br>
    <a href="index.html">← Back to Home</a>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Curriculum</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>My Curriculum Overview</h1>
    <p>You can find my course structure and specializations here:</p>
    <a href="files/curriculum.pdf" target="_blank">📥 Download Curriculum (PDF)</a>
    <br><br>
    <a href="index.html">← Back to Home</a>
  </div>
</body>
</html>


