# MDAP-EX_01-Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

  <header>
    <nav>
      <h1 class="logo">My Portfolio</h1>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section">
    <h2>Welcome!</h2>
    <p>Hi, I'm [Your Name], a passionate Web Developer.</p>
  </section>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>I’m a student/aspiring developer with a passion for designing modern and responsive websites.</p>
  </section>

  <section id="projects" class="section">
    <h2>Projects</h2>
    <ul>
      <li>✔️ Portfolio Website</li>
      <li>✔️ To-Do List App</li>
      <li>✔️ Simple Calculator</li>
    </ul>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: rkpriyadharshini0420@gmail.com</p>
    <p>GitHub: <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Priyadharshini r k. All rights reserved.</p>
  </footer>

</body>
</html>


style.css
css
Copy
Edit
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f9f9f9;
}

/* Header and Navbar */
header {
  background-color: #333;
  color: #fff;
  padding: 1rem 0;
  position: sticky;
  top: 0;
  z-index: 1000;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 90%;
  margin: auto;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #00bcd4;
}

/* Sections */
.section {
  padding: 4rem 2rem;
  text-align: center;
  background-color: #fff;
  margin-bottom: 1rem;
  border-radius: 10px;
  width: 80%;
  margin: 2rem auto;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Projects list */
.section ul {
  list-style: none;
  padding: 0;
}

.section li {
  margin: 0.5rem 0;
}

/* Footer */
footer {
  text-align: center;
  padding: 1rem;
  background-color: #333;
  color: #fff;
  margin-top: 2rem;
}

/* Responsive design */
@media (max-width: 768px) {
  .nav-links {
    flex-direction: column;
    gap: 1rem;
  }
}


## OUTPUT
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/ff0e4f4c-7a7d-4db3-935e-f303a3ebda09" />

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/0ed0704a-883e-4f39-8b2a-2ab2f33ad822" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
