<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tara32473 - Professional Software Engineer Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .header {
            text-align: center;
            background: rgba(255, 255, 255, 0.95);
            padding: 3rem 2rem;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.1);
            margin-bottom: 3rem;
            backdrop-filter: blur(10px);
        }

        .header h1 {
            font-size: 3rem;
            font-weight: 700;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 1rem;
        }

        .header p {
            font-size: 1.3rem;
            color: #666;
            margin-bottom: 2rem;
        }

        .navigation {
            display: flex;
            gap: 1rem;
            justify-content: center;
            flex-wrap: wrap;
        }

        .nav-btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
        }

        .nav-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(102, 126, 234, 0.4);
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }

        .project-card {
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-title {
            font-size: 1.5rem;
            font-weight: 700;
            color: #333;
            margin-bottom: 0.5rem;
        }

        .project-tech {
            color: #667eea;
            font-weight: 600;
            font-size: 0.9rem;
            margin-bottom: 1rem;
        }

        .project-desc {
            color: #666;
            margin-bottom: 1.5rem;
        }

        .project-links {
            display: flex;
            gap: 1rem;
        }

        .project-link {
            background: #667eea;
            color: white;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 25px;
            font-size: 0.9rem;
            transition: all 0.3s ease;
        }

        .project-link:hover {
            background: #764ba2;
            transform: scale(1.05);
        }

        .skills-section {
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
            margin-bottom: 2rem;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }

        .skill-category {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1rem;
            border-radius: 10px;
            text-align: center;
        }

        .footer {
            text-align: center;
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
            backdrop-filter: blur(10px);
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2rem;
            }

            .navigation {
                flex-direction: column;
                align-items: center;
            }

            .projects-grid {
                grid-template-columns: 1fr;
            }

            .container {
                padding: 1rem;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <header class="header">
            <h1>tara32473</h1>
            <p>Professional Software Engineer | Full-Stack Development & DevOps</p>
            <nav class="navigation">
                <a href="portfolio.html" class="nav-btn">🎨 Portfolio Website</a>
                <a href="https://github.com/tara32473" class="nav-btn">💻 GitHub Profile</a>
                <a href="https://github.com/tara32473/budget-manager" class="nav-btn">⭐ Featured Project</a>
            </nav>
        </header>

        <main>
            <section class="projects-grid">
                <div class="project-card">
                    <h3 class="project-title">💰 Budget Manager</h3>
                    <div class="project-tech">Python • SQLite • Docker • CI/CD • 87% Test Coverage</div>
                    <p class="project-desc">Enterprise-grade CLI personal finance management tool with professional
                        DevOps practices, comprehensive testing, and production deployment.</p>
                    <div class="project-links">
                        <a href="https://github.com/tara32473/budget-manager" class="project-link">Repository</a>
                        <a href="https://tara32473.github.io/budget-manager" class="project-link">Documentation</a>
                    </div>
                </div>

                <div class="project-card">
                    <h3 class="project-title">🧠 Quiz Application</h3>
                    <div class="project-tech">JavaScript • Node.js • HTML/CSS • Testing</div>
                    <p class="project-desc">Interactive learning platform with full-stack architecture, modern
                        JavaScript practices, and comprehensive test suite.</p>
                    <div class="project-links">
                        <a href="https://github.com/tara32473/quiz-app" class="project-link">Repository</a>
                    </div>
                </div>

                <div class="project-card">
                    <h3 class="project-title">🌤️ Weather Dashboard</h3>
                    <div class="project-tech">Node.js • APIs • JavaScript • Testing</div>
                    <p class="project-desc">API integration showcase with external weather services, professional error
                        handling, and modern development practices.</p>
                    <div class="project-links">
                        <a href="https://github.com/tara32473/weather-dashboard" class="project-link">Repository</a>
                    </div>
                </div>

                <div class="project-card">
                    <h3 class="project-title">📝 Task Tracker</h3>
                    <div class="project-tech">JavaScript • HTML • CSS • Frontend</div>
                    <p class="project-desc">Productivity management tool demonstrating clean frontend development with
                        modern web standards and user experience focus.</p>
                    <div class="project-links">
                        <a href="https://github.com/tara32473/task-tracker" class="project-link">Repository</a>
                    </div>
                </div>
            </section>

            <section class="skills-section">
                <h2>🛠️ Technical Expertise</h2>
                <div class="skills-grid">
                    <div class="skill-category">
                        <strong>Languages</strong><br>
                        Python • JavaScript • Node.js
                    </div>
                    <div class="skill-category">
                        <strong>DevOps</strong><br>
                        Docker • CI/CD • GitHub Actions
                    </div>
                    <div class="skill-category">
                        <strong>Testing</strong><br>
                        pytest • Jest • 80%+ Coverage
                    </div>
                    <div class="skill-category">
                        <strong>Databases</strong><br>
                        SQLite • PostgreSQL
                    </div>
                </div>
            </section>
        </main>

        <footer class="footer">
            <h3>🎯 Ready for Professional Opportunities</h3>
            <p>Seeking software engineering roles where I can apply expertise in full-stack development, DevOps
                practices, and quality-focused engineering.</p>
            <br>
            <p><strong>GitHub:</strong> <a href="https://github.com/tara32473" style="color: #667eea;">@tara32473</a>
            </p>
            <p><em>All projects are public and available for employer review</em></p>
        </footer>
    </div>
</body>

</html>
