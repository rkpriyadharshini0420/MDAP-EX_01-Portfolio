# MDAP-EX_01-Portfolio
## Date:
06-08-2025

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
```
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Priyadharshini R K - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="logo">Priyadharshini R K</div>
        <nav>
            <ul>
                <li><a href="#about">ABOUT</a></li>
                <li><a href="#projects">PROJECTS</a></li>
                <li><a href="#contact">CONTACT</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <img src="profile-placeholder.png" alt="Profile Picture" class="profile-pic">
        <div class="intro">
            <h1>Hi, I’m Priyadharshini R K</h1>
            <p class="role">Student</p>
            <p class="email">rkpriyadharshini0420@gmail.com</p>
        </div>
    </section>

    <section id="about">
        <h2>ABOUT</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    </section>

    <section id="projects">
        <h2>PROJECTS</h2>
        <ul>
            <li>Portfolio Website</li>
            <li>To-Do List App</li>
            <li>Simple Calculator</li>
        </ul>
    </section>

    <section id="contact">
        <h2>CONTACT</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    </section>

    <footer>
        © 2025 Priyadharshini R K. All rights reserved.
    </footer>

</body>
</html>
```
```

style.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f9f9f9;
    color: #222;
}

header {
    background-color: #0a2a51;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-weight: bold;
    font-size: 20px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 25px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    display: flex;
    align-items: center;
    padding: 40px;
    gap: 30px;
    background-color: #fff;
}

.profile-pic {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 2px solid #ccc;
    background-color: #f0f0f0;
    object-fit: cover;
}

.intro h1 {
    font-size: 28px;
    margin-bottom: 10px;
}

.role {
    font-style: italic;
    font-size: 16px;
    color: #555;
}

.email {
    font-size: 16px;
    color: #333;
    margin-top: 5px;
}

section {
    padding: 30px 40px;
    border-bottom: 1px solid #ddd;
    background-color: #fff;
}

section h2 {
    margin-bottom: 10px;
    color: #111;
}

section ul {
    margin-top: 10px;
    padding-left: 20px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #0a2a51;
    color: white;
}

```

## OUTPUT
<img width="1917" height="962" alt="image" src="https://github.com/user-attachments/assets/d6b2620a-950a-4c96-b2ac-fb411b2ec614" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
