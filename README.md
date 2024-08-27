<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>John - Web Developer</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="hero">
            <h1>sanjay</h1>
            <p>Full-Stack Web Developer</p>
            <a href="#projects" class="btn">View My Work</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a full-stack web developer with a passion for building responsive, user-friendly websites and web applications.</p>
        <!-- Timeline content here -->
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>E-commerce Website</h3>
            <p>A fully responsive e-commerce website built with React, Node.js, and MongoDB.</p>
            <p><strong>Technologies Used:</strong> React, Node.js, MongoDB, Stripe API, CSS.</p>
            <a href="#" class="btn">Live Demo</a>
            <a href="#" class="btn">GitHub</a>
        </div>
        <div class="project">
            <h3>Portfolio Website</h3>
            <p>A personal portfolio website showcasing my work and skills.</p>
            <p><strong>Technologies Used:</strong> HTML, CSS, JavaScript, and Bootstrap.</p>
            <a href="#" class="btn">Live Demo</a>
            <a href="#" class="btn">GitHub</a>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML, CSS, JavaScript, Python, SQL</li>
            <li>React, Angular, Vue, Node.js, Express</li>
            <li>Git, Docker, AWS, Jenkins, Webpack</li>
            <li>Responsive Design, RESTful APIs, Unit Testing</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject"><br><br>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea><br>

            <br><button type="submit">Send</button>
        </form>
        <p>Connect with me:</p>
        <ul class="social-media">
            <li><a href="#">LinkedIn</a></li>
            <li><a href="#">GitHub</a></li>
            <li><a href="#">Twitter</a></li>
        </ul>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 John Doe. All rights reserved.</p>
    </footer>

    <!-- Back to Top Button -->
    <a href="#home" class="back-to-top">Back to Top</a>

    <script src="script.js"></script>
</body>
</html>
