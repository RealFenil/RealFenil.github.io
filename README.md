<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website</title>
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background-color: #f8f9fa;
            color: #333333;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Header / Hero Section */
        header {
            text-align: center;
            padding: 40px 0;
            border-bottom: 2px solid #eef2f3;
        }
        header h1 {
            font-size: 2.5rem;
            color: #2c3e50;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2rem;
            color: #7f8c8d;
        }

        /* Section Styling */
        section {
            margin: 40px 0;
        }
        h2 {
            font-size: 1.8rem;
            color: #2c3e50;
            margin-bottom: 20px;
            border-left: 4px solid #3498db;
            padding-left: 10px;
        }

        /* Skills Tags */
        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skill-tag {
            background-color: #eef2f3;
            color: #2c3e50;
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: 500;
            font-size: 0.9rem;
        }

        /* Projects Cards */
        .projects-list {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }
        .project-card {
            background: #ffffff;
            padding: 24px;
            border-radius: 8px;
            border: 1px solid #eef2f3;
            box-shadow: 0 2px 4px rgba(0,0,0,0.02);
            transition: transform 0.2s;
        }
        .project-card:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        }
        .project-card h3 {
            color: #2c3e50;
            margin-bottom: 8px;
        }
        .project-card p {
            color: #616e7c;
            margin-bottom: 12px;
        }
        .project-link {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
            font-size: 0.9rem;
        }
        .project-link:hover {
            text-decoration: underline;
        }

        /* Contact Section */
        .contact-links {
            display: flex;
            gap: 20px;
        }
        .contact-links a {
            color: #3498db;
            text-decoration: none;
            font-weight: 500;
        }
        .contact-links a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            margin-top: 60px;
            font-size: 0.9rem;
            color: #bdc3c7;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header Section -->
        <header>
            <h1>Hi, I'm Fenil</h1>
            <p>Tech Enthusiast | Student | Aspiring Developer</p>
        </header>

        <!-- About Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>Welcome to my website. I am a student passionate about technology, systems, and building tools that make a difference. Currently, I am learning Python, getting comfortable with Git/GitHub, and building hands-on projects to sharpen my technical skills.</p>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2>Skills & Technologies</h2>
            <div class="skills-grid">
                <div class="skill-tag">Python (Learning)</div>
                <div class="skill-tag">Git & GitHub</div>
                <div class="skill-tag">HTML5 & CSS3</div>
                <div class="skill-tag">Technical Troubleshooting</div>
                <div class="skill-tag">Hardware Diagnostics</div>
                <div class="skill-tag">System Imaging</div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2>Featured Projects</h2>
            <div class="projects-list">
                
                <!-- Project 1 -->
                <div class="project-card">
                    <h3>Personal Portfolio Website</h3>
                    <p>A clean, responsive website built to showcase my learning journey, technical skills, and software development projects. Hosted entirely for free using GitHub Pages.</p>
                    <a href="#" class="project-link">View Repository →</a>
                </div>

                <!-- Project 2 -->
                <div class="project-card">
                    <h3>Python Project Placeholder</h3>
                    <p>This is where my first real Python script or application will go! Stay tuned as I work through my coding courses and build out automated tools.</p>
                    <a href="#" class="project-link">Coming Soon →</a>
                </div>

            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Connect With Me</h2>
            <p style="margin-bottom: 15px;">Feel free to check out my work or reach out online:</p>
            <div class="contact-links">
                <a href="https://github.com/RealFenil" target="_blank">GitHub</a>
                <a href="fp2468fp@gmail.com">Email Me</a>
            </div>
        </section>

        <footer>
            <p>&copy; 2026 Fenil. Built from scratch.</p>
        </footer>
    </div>

</body>
</html>
