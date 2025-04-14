# zero-to-all
Zero to All is a completely free educational platform designed to help students learn and grow through various resources such as video tutorials, study materials, and practice tests. Perfect for anyone who wants to enhance their academic knowledge at no cost.
<!DOCTYPE html>
<html>
<head>
  <title>Zero to All - Study Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Zero to All</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="subjects.html">Subjects</a>
    </nav>
  </header>
  <main>
    <h2>Welcome to Zero to All!</h2>
    <p>Yeh ek study website hai jahan aap free me notes aur videos dekh sakte hain.</p>
  </main>
</body>
</html>


body {
  font-family: Arial;
  margin: 0;
  background: #f0f0f0;
  text-align: center;
}

header {
  background: #333;
  color: white;
  padding: 20px;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
  font-weight: bold;
}

* {
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f0f0f0;
  text-align: center;
}

header {
  background: #333;
  color: white;
  padding: 20px;
}

nav a {
  color: white;
  margin: 10px;
  text-decoration: none;
  font-weight: bold;
  display: inline-block;
}

main {
  padding: 20px;
}

/* Responsive YouTube and PDF */
iframe {
  max-width: 100%;
  height: auto;
}

/* Mobile layout tweak */
@media (max-width: 600px) {
  header h1 {
    font-size: 24px;
  }
  nav a {
    display: block;
    margin: 10px 0;
  }
}


<!DOCTYPE html>
<html>
<head>
  <title>Subjects - Zero to All</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Subjects</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="subjects.html">Subjects</a>
    </nav>
  </header>

  <main>
    <h2>Maths Video</h2>
    <iframe width="100%" height="315" src="https://www.youtube.com/embed/nlTnBcvhS54" frameborder="0" allowfullscreen></iframe>

    <h2>Science Notes PDF</h2>
    <iframe src="https://drive.google.com/file/d/1AbcdEfgh1234XYZ/preview" width="100%" height="600px"></iframe>
  </main>
</body>
</html>


