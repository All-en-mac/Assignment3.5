To make this project clean and modular, we will build a professional two-page portfolio and blog website (index.html for the home portfolio and blog.html for the blog posts), fully equipped with semantic tags, working internal/external links, images, lists, and a footer contact section.

Step 1: Project Folder Structure
Ensure your workspace is organized like this:

Plaintext
web-development-practice/
│
├── index.html       (Home & Portfolio Page)
├── blog.html        (Blog Posts Page)
└── images/
    ├── profile.jpg
    └── project1.jpg
Step 2: index.html (Home & Portfolio Page)
Create or update your index.html file with the following clean, semantic code:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex Johnson — Portfolio Home</title>
</head>
<body>

    <!-- Header with Name / Logo -->
    <header>
        <h1>Alex Johnson</h1>
        <p>Aspiring Full-Stack Web Developer</p>
        
        <!-- Navigation Bar -->
        <nav aria-label="Main Navigation">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="blog.html">Blog</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <hr>

    <!-- Main Content Area -->
    <main>
        
        <!-- About Me Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! Welcome to my personal portfolio website. I am passionate about learning modern web development, writing clean semantic code, and building user-friendly applications.</p>
            
            <figure>
                <img src="images/profile.jpg" alt="Portrait photo of Alex Johnson" width="250" height="200">
                <figcaption>Alex Johnson — Web Development Student</figcaption>
            </figure>
        </section>

        <hr>

        <!-- Skills & Interests Section (Lists) -->
        <section id="skills">
            <h2>Skills & Interests</h2>
            <ul>
                <li><strong>Core Technologies:</strong> HTML5, CSS3, JavaScript</li>
                <li><strong>Development Tools:</strong> Git, GitHub, VS Code, Chrome DevTools</li>
                <li><strong>Interests:</strong> UI/UX Design, Open Source Contributing, Technical Writing</li>
            </ul>
        </section>

        <hr>

        <!-- Projects Section (Images & Lists) -->
        <section id="projects">
            <h2>Featured Projects</h2>
            
            <article>
                <h3>Project One: Responsive Landing Page</h3>
                <p>A fully semantic, mobile-first landing page built using pure HTML structures and custom layouts.</p>
                <img src="images/project1.jpg" alt="Preview screenshot of the landing page project" width="300" height="180">
            </article>
        </section>

        <hr>

        <!-- Useful Links Section -->
        <section id="links">
            <h2>Useful Resources</h2>
            <ul>
                <li><a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a></li>
                <li><a href="https://github.com" target="_blank" rel="noopener noreferrer">GitHub Community</a></li>
            </ul>
        </section>

    </main>

    <hr>

    <!-- Footer with Contact Details -->
    <footer id="contact">
        <h2>Contact Information</h2>
        <p>Feel free to connect with me:</p>
        <ul>
            <li>Email: <a href="mailto:alex.johnson@example.com">alex.johnson@example.com</a></li>
            <li>GitHub Profile: <a href="https://github.com" target="_blank" rel="noopener noreferrer">github.com/alexjohnson</a></li>
        </ul>
        <p>&copy; 2026 Alex Johnson. All rights reserved.</p>
    </footer>

</body>
</html>
Step 3: blog.html (Blog Posts Page)
Create a new file named blog.html in your project folder with the following code:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog — Alex Johnson</title>
</head>
<body>

    <!-- Header with Name / Logo -->
    <header>
        <h1>Alex's Tech Blog</h1>
        <p>Thoughts on learning code, web standards, and developer workflows.</p>
        
        <!-- Navigation Bar -->
        <nav aria-label="Main Navigation">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="blog.html">Blog</a></li>
            </ul>
        </nav>
    </header>

    <hr>

    <!-- Main Content Area -->
    <main>
        <section>
            <h2>Latest Articles</h2>

            <article>
                <h3>Why Semantic HTML Matters</h3>
                <p><em>Published on October 18, 2026</em></p>
                <p>Semantic markup goes beyond making your code look neat. By using tags like <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, and <code>&lt;article&gt;</code>, you empower screen readers and search engines to interpret your document structure accurately.</p>
            </article>

            <article>
                <h3>Getting Started with Git and GitHub</h3>
                <p><em>Published on October 15, 2026</em></p>
                <p>Version control is a developer's best friend. Learning how to initialize repositories, manage commits, and push your projects online is essential for modern collaboration.</p>
            </article>
        </section>
    </main>

    <hr>

    <!-- Footer -->
    <footer>
        <p>Connect via email: <a href="mailto:alex.johnson@example.com">alex.johnson@example.com</a></p>
        <p>&copy; 2026 Alex Johnson.</p>
    </footer>

</body>
</html>
Step 4: Git Commit & Push Instructions
To wrap up your project and push it to your GitHub repository for final submission, run these terminal commands:

Bash
# Check status of files
git status

# Stage all files (HTML files and images)
git add .

# Commit changes with a descriptive message
git commit -m "feat: complete blog and portfolio mini-project (Assignment 3.5)"

# Push your changes to GitHub
git push origin main
Submission Checklist
Source Code: Ensure both index.html and blog.html are saved and properly indented in your workspace.

Assets: Verify your images folder contains your profile picture and project graphic.

Local Testing: Open index.html via Live Server to verify that navigation links between Home and Blog work seamlessly, images load properly, and external links open securely.

GitHub Link: Submit your public GitHub repository URL (e.g., [https://github.com/YOUR-USERNAME/web-development-practice](https://github.com/YOUR-USERNAME/web-development-practice)) to complete your mini-project assignment!