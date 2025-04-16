<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arshapriya A - Portfolio</title>
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            line-height: 1.6;
        }
        header {
            background-color: #c0e218;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #d30000;
            padding: 10px;
            text-align: center;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
            padding: 8px 15px;
            border-radius: 5px;
            transition: background 0.3s;
        }
        nav a:hover {
            background: #a00000;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #d30000;
        }
        ul {
            list-style-type: square;
            padding-left: 20px;
        }
        ul li {
            margin-bottom: 5px;
        }
        .resume-button {
            text-align: center;
            margin-top: 20px;
        }
        .resume-button a {
            background-color: black;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            transition: background 0.3s;
        }
        .resume-button a:hover {
            background: #444;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #222;
            color: white;
            margin-top: 20px;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            .container {
                width: 90%;
                padding: 15px;
            }
            nav {
                flex-direction: column;
                align-items: center;
            }
            nav a {
                display: block;
                width: 100%;
                text-align: center;
                padding: 10px 0;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Arshapriya A</h1>
    <p>An Electronics Engineer</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
</nav>

<div class="container">
    <section id="about">
        <h2>About Me</h2>
        <p>
            I'm a <strong>cybersecurity</strong> expert and technology enthusiast passionate about helping 
            organizations protect their data and create secure online environments. 
            With over 7 years of experience, I stay up to date with the latest trends in cybersecurity 
            and help others learn about staying safe online.
        </p>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p>Madras University - Electrical & Electronics Engineering</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Cyber Security</li>
            <li>Internet of Things (IoT)</li>
            <li>Cloud Computing</li>
            <li>Python</li>
            <li>IBM Cloud</li>
            <li>Machine Learning & AI</li>
            <li>Java</li>
            <li>Blockchain</li>
            <li>C++</li>
            <li>JavaScript</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><a href="https://github.com/yourusername/AI-Alternator-Control" target="_blank">AI-Based Alternator Control System</a></li>
            <li><a href="https://github.com/yourusername/CloudSecurityIBM" target="_blank">Cloud Security with IBM</a></li>
            <li><a href="https://github.com/yourusername/IBM-Chatbot" target="_blank">IBM Chatbot</a></li>
            <li><a href="https://github.com/yourusername/Chatbot" target="_blank">Chatbot Project</a></li>
        </ul>
    </section>

    <section id="resume" class="resume-button">
        <a href="Arshapriya_Resume.pdf" download>Download CV</a>
    </section>
</div>

<footer>
    © 2024 Arshapriya A | All Rights Reserved
</footer>

</body>
</html>
