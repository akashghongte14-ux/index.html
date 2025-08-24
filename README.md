<img src="images/logo.png" alt="HARIGANDH Logo">
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HARIGANDH</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #111;
      color: #fff;
      padding: 15px;
      text-align: center;
    }
    header img {
      height: 60px;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #f39c12;
    }
    .banner {
      background: url('banner.jpg') no-repeat center center/cover;
      height: 350px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .videos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }
    iframe {
      width: 400px;
      height: 225px;
      border-radius: 12px;
      border: none;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
    footer a {
      color: #f39c12;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="logo.jpg" alt="HARIGANDH Logo">
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#videos">Videos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Banner -->
  <section id="home" class="banner">
    <h1>Welcome to HARIGANDH</h1>
  </section>

  <!-- About -->
  <section id="about" class="section">
    <h2>About Me</h2>
    <p>HARIGANDH ek YouTube channel hai jo aapke liye interesting aur engaging content lata hai. 
       Yahaan par aapko entertainment, knowledge aur fun videos milenge.</p>
  </section>

  <!-- Videos -->
  <section id="videos" class="section">
    <h2>My Videos</h2>
    <div class="videos">
      <iframe src="https://www.youtube.com/embed/VPSfWKXg8mU" allowfullscreen></iframe>
      <iframe src="https://www.youtube.com/embed/9GYxyWtoqNU" allowfullscreen></iframe>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="section">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:yogeshghongate223@gmail.com">yogeshghongate223@gmail.com</a></p>
    <p>Instagram: <a href="https://instagram.com/yogesh_ghongate_patil_01" target="_blank">@yogesh_ghongate_patil_01</a></p>
    <p>YouTube: <a href="https://youtube.com/@harigandh" target="_blank">HARIGANDH Channel</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 HARIGANDH | All Rights Reserved</p>
  </footer>

</body>
</html>
