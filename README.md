<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome to my website!</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <main>
    <h2>About</h2>
    <p>This is a simple website that I created using HTML and CSS.</p>

    <h2>Contact</h2>
    <form action="/contact" method="post">
      <input type="name" name="name" placeholder="Your name">
      <input type="email" name="email" placeholder="Your email">
      <textarea name="message" placeholder="Your message"></textarea>
      <input type="submit" value="Send">
    </form>
  </main>

  <footer>
    <p>Copyright &copy; 2023 My Website</p>
  </footer>
</body>
</html>
