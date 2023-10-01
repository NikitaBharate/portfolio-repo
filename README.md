# portfolio-repo
my portfolio

Html Code:

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css">
    <title>My Portfolio</title>
</head>

<body>
    <header>
        <h1>Nikita Bharate</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am Nikita Bharate, a passionate web developer with a keen interest in creating responsive and user-friendly websites.I'm a student in Bharati Vidyapeeth's College of Engineering,Pune</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Landing page using html and css</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Flipkart clone</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: bharatenikita7@gmail.com</p>
        <p>LinkedIn: <a href="www.linkedin.com/in/nikita-bharate-0a213822a" target="_blank">linkedin.com/in/johndoe</a></p>
    </section>

    <footer>
        <p>&copy; 2023 Nikita Bharate. All rights reserved.</p>
    </footer>
</body>

</html>


CSS Code:

body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
  }
  
  header {
      background-color: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
  }
  
  nav ul {
      list-style: none;
  }
  
  nav ul li {
      display: inline;
      margin-right: 20px;
  }
  
  nav ul li a {
      color: #fff;
      text-decoration: none;
  }
  
  section {
      padding: 50px;
      text-align: center;
      background-color: rgb(212, 123, 230);
  }
  
  footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
      position: fixed;
      bottom: 0;
      width: 100%;
  }
div{
      background-color: rgb(147, 246, 246);
      border-color: black;
}
  
