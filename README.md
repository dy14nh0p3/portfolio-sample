<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <h1 class="logo">Your Name</h1>
        <nav class="navbar">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <a href="#contact" class="resume-button">Get in Touch</a>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello! I'm a passionate web developer specializing in front-end technologies. I love creating interactive and user-friendly websites. I’m constantly learning new skills to grow my development expertise and looking forward to working on exciting projects!</p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>A brief description of what the project is about.</p>
                <a href="https://github.com/yourusername/project1" target="_blank">View on GitHub</a>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>A brief description of what the project is about.</p>
                <a href="https://github.com/yourusername/project2" target="_blank">View on GitHub</a>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li

                /* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
    text-decoration: none;
    list-style: none;
}

body {
    background: #f0f0f0; /* Soft light background */
    color: #333;
    font-size: 16px;
    line-height: 1.6;
    margin-top: 60px; /* Space for the fixed header */
}

/* Header */
.header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 20px 12%;
    background: rgba(0, 0, 0, 0.8);
    backdrop-filter: blur(10px);
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 1000;
}

.header .logo {
    font-size: 24px;
    font-weight: 700;
    color: white;
}

.navbar a {
    color: white;
    margin-left: 20px;
    font-weight: 500;
    transition: color 0.3s ease;
}

.navbar a:hover {
    color: #00ffff;
}

/* Resume Button */
.resume-button {
    padding: 10px 20px;
    background: #00ffff;
    color: black;
    font-weight: 600;
    border-radius: 30px;
    text-decoration: none;
    transition: background 0.3s ease;
}

.resume-button:hover {
    background: #00cccc;
}

/* Sections */
section {
    padding: 60px 12%;
    margin-bottom: 60px;
}

section h2 {
    font-size: 32px;
    font-weight: 700;
    color: #333;
    margin-bottom: 20px;
}

/* Projects Section */
.project {
    margin-bottom: 20px;
}

.project a {
    color: #00ffff;
    text-decoration: none;
    transition: color 0.3s ease;
}

.project a:hover {
    color: #009999;
}

/* Footer */
footer {
    background: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

footer a {
    color: #00ffff;
    text-decoration: none;
    margin: 0 10px;
}

footer a:hover {
    text-decoration: underline;
}
