---
name: Custom issue template
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ankit Gautam - Personal Website</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <h1>Ankit Gautam</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- About Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>Welcome to my personal website! I'm Ankit Gautam, a passionate web developer based in [Your Location]. I love creating clean and functional websites that make a positive impact.</p>
        </section>

        <!-- Portfolio Section -->
        <section id="portfolio">
            <h2>Portfolio</h2>
            <div class="portfolio-item">
                <img src="project1.jpg" alt="Project 1">
                <h3>Project 1</h3>
                <p>Description of Project 1</p>
                <a href="#">View Project</a>
            </div>
            <!-- More portfolio items go here -->
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact Me</h2>
            <p>Feel free to reach out to me for any inquiries or collaboration opportunities!</p>
            <form action="contact.php" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Ankit Gautam. All rights reserved.</p>
    </footer>
</body>
</html>
