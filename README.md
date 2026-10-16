<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        :root {
            --bg: #f4f4f9;
            --text: #333;
            --accent: #0070f3;
            --card-bg: #ffffff;
        }
        @media (prefers-color-scheme: dark) {
            :root {
                --bg: #121212;
                --text: #e0e0e0;
                --accent: #00bcd4;
                --card-bg: #1e1e1e;
            }
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        header {
            margin-bottom: 40px;
        }
        h1 { margin-bottom: 10px; }
        .links a {
            color: var(--accent);
            text-decoration: none;
            margin-right: 15px;
            font-weight: bold;
        }
        .links a:hover { text-decoration: underline; }
        section { margin-bottom: 40px; }
        .project-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }
        @media(min-width: 600px) {
            .project-grid { grid-template-columns: 1fr 1fr; }
        }
        .project-card {
            background: var(--card-bg);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }
        .project-card h3 { margin-top: 0; }
        .tag {
            background: var(--bg);
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 0.85rem;
            margin-right: 5px;
            display: inline-block;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header / About Me -->
        <header>
            <h1>Your Name</h1>
            <p><strong>Software Engineer / Designer / Student</strong></p>
            <p>Hi, I build clean digital experiences. Passionate about solving complex problems and learning new tech stacks.</p>
            <div class="links">
                <a href="https://github.com" target="_blank">GitHub</a>
                <a href="https://linkedin.com" target="_blank">LinkedIn</a>
                <a href="mailto:your.email@example.com">Email</a>
            </div>
        </header>

        <!-- Skills Section -->
        <section>
            <h2>Skills</h2>
            <div>
                <span class="tag">JavaScript</span>
                <span class="tag">Python</span>
                <span class="tag">HTML/CSS</span>
                <span class="tag">Git</span>
                <span class="tag">React</span>
            </div>
        </section>

        <!-- Projects Section -->
        <section>
            <h2>Projects</h2>
            <div class="project-grid">
                
                <!-- Project 1 -->
                <div class="project-card">
                    <h3>Project One</h3>
                    <p>A short description of what your project does and the problem it solves.</p>
                    <p>
                        <span class="tag">Python</span>
                        <span class="tag">Flask</span>
                    </p>
                    <a class="links" href="#" target="_blank">View Project →</a>
                </div>

                <!-- Project 2 -->
                <div class="project-card">
                    <h3>Project Two</h3>
                    <p>A short description of what your project does and the problem it solves.</p>
                    <p>
                        <span class="tag">JavaScript</span>
                        <span class="tag">API</span>
                    </p>
                    <a class="links" href="#" target="_blank">View Project →</a>
                </div>

            </div>
        </section>

        <!-- Footer -->
        <footer>
            <p style="font-size: 0.85rem; opacity: 0.7;">&copy; 2026 Your Name. Built with simple HTML & CSS.</p>
        </footer>
    </div>

</body>
</html>
