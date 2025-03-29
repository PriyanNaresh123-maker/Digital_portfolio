<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Priyan S - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .header {
            background-color: #bada55;
            text-align: center;
            padding: 20px;
        }
        .nav {
            background-color: #d60000;
            padding: 10px;
            text-align: center;
        }
        .nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
            background: white;
        }
        .resume {
            text-align: center;
            margin: 20px;
        }
        .resume button {
            background-color: black;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Priyan S</h1>
        <h3>Student</h3>
    </div>
    <div class="nav">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>
    <div class="container" id="about">
        <h2>About Me</h2>
        <p>I am currently pursuing a BSc in Computer Science.</p>
    </div>
    <div class="container" id="education">
        <h2>Education</h2>
        <p>Madras University - BSc Computer Science</p>
    </div>
    <div class="container" id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>HTML</li>
        </ul>
    </div>
    <div class="container" id="projects">
        <h2>Projects</h2>
        <p>Coming soon...</p>
    </div>
    <div class="container resume" id="resume">
        <h2>Resume</h2>
        <button>Download CV</button>
    </div>
    <footer style="text-align: center; padding: 10px; background: #222; color: white;">
        &copy; 2024 Priyan S
    </footer>
</body>
</html>
