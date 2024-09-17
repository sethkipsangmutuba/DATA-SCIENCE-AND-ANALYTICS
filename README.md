<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            color: #4CAF50;
        }
        .projects a {
            color: #4CAF50;
            text-decoration: none;
        }
        .projects a:hover {
            text-decoration: underline;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        form {
            max-width: 600px;
            margin: 0 auto;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Personal Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#interests">Interests</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hello! I'm [Your Name], a passionate developer with a love for technology and innovation. I'm driven by solving problems and creating impactful solutions.</p>
        </section>

        <section id="education" class="section">
            <h2>Educational Background</h2>
            <p>You can download my CV <a href="[CV Link]" target="_blank">here</a>.</p>
        </section>

        <section id="interests" class="section">
            <h2>Interests</h2>
            <p>I enjoy exploring new technologies, participating in hackathons, and staying updated with the latest trends in the tech world.</p>
        </section>

        <section id="projects" class="section">
            <h2>Projects</h2>
            <p>Check out some of my projects:</p>
            <ul>
                <li><a href="[Project 1 Link]" target="_blank">Project 1: Description</a></li>
                <li><a href="[Project 2 Link]" target="_blank">Project 2: Description</a></li>
                <li><a href="[Project 3 Link]" target="_blank">Project 3: Description</a></li>
            </ul>
        </section>

        <section id="contact" class="section">
            <h2>Contact Me</h2>
            <form action="[Form Submission URL]" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>
