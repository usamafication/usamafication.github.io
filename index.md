<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Usama Faheem - Global Development Specialist</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --bg-color: #ffffff;
            --text-color: #333333;
            --accent-color: #3498db;
            --secondary-bg: #f4f4f4;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            transition: background-color 0.3s ease, color 0.3s ease;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background-color: var(--accent-color);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav ul {
            display: flex;
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            margin-left: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            margin-top: 80px;
        }
        .hero {
            background: linear-gradient(135deg, #3498db, #8e44ad);
            color: white;
            text-align: center;
            padding: 100px 0;
        }
        .hero h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 40px 0;
        }
        .card {
            background-color: var(--secondary-bg);
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skill-tag {
            background-color: var(--accent-color);
            color: white;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 0.9em;
        }
        .dark-mode-toggle {
            background: none;
            border: none;
            color: white;
            font-size: 1.2em;
            cursor: pointer;
        }
        .dark-mode {
            --bg-color: #1a1a1a;
            --text-color: #ffffff;
            --secondary-bg: #2c2c2c;
        }
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                position: absolute;
                top: 60px;
                left: 0;
                width: 100%;
                background-color: var(--accent-color);
                display: none;
            }
            nav ul.show {
                display: flex;
            }
            nav ul li {
                margin: 10px 0;
            }
            .menu-toggle {
                display: block;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav class="container">
            <h1>Usama Faheem</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <button class="dark-mode-toggle" aria-label="Toggle dark mode">
                <i class="fas fa-moon"></i>
            </button>
            <button class="menu-toggle" aria-label="Toggle menu">
                <i class="fas fa-bars"></i>
            </button>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="container">
                <h1>Usama Faheem</h1>
                <p>Global Development Specialist | Data-Driven Policy Analyst | Climate Justice Advocate</p>
            </div>
        </section>

        <section id="about" class="container">
            <h2>About Me</h2>
            <div class="grid">
                <div class="card">
                    <h3>Mission</h3>
                    <p>Leveraging 5 years of experience in social development to drive sustainable change and enhance public policies globally.</p>
                </div>
                <div class="card">
                    <h3>Vision</h3>
                    <p>Connecting research with policy to create a more equitable and sustainable world.</p>
                </div>
            </div>
        </section>

        <section id="experience" class="container">
            <h2>Impactful Experiences</h2>
            <div class="grid">
                <div class="card">
                    <h3>Global Hunger Analyst</h3>
                    <p>Analyzing data on global indicators for CARE USA, producing insightful reports on hunger and gender issues.</p>
                </div>
                <div class="card">
                    <h3>Reintegration Specialist</h3>
                    <p>Facilitated the reintegration of 23,000 individuals, including vulnerable groups, into the workforce.</p>
                </div>
                <div class="card">
                    <h3>Gender Equality Champion</h3>
                    <p>Conducted gender analyses and trained over 300 people on gender competencies and anti-sexual harassment.</p>
                </div>
            </div>
        </section>

        <section id="skills" class="container">
            <h2>Skills & Expertise</h2>
            <div class="skills-container">
                <span class="skill-tag">Data-Driven Policy Analysis</span>
                <span class="skill-tag">Project Management</span>
                <span class="skill-tag">Impact Assessment</span>
                <span class="skill-tag">Climate Justice</span>
                <span class="skill-tag">Gender Competence</span>
                <span class="skill-tag">STATA</span>
                <span class="skill-tag">R</span>
                <span class="skill-tag">MATLAB</span>
                <span class="skill-tag">SQL</span>
                <span class="skill-tag">Python</span>
                <span class="skill-tag">Power BI</span>
                <span class="skill-tag">Tableau</span>
            </div>
        </section>

        <section id="contact" class="container">
            <h2>Let's Connect</h2>
            <p>Ready to collaborate on making the world a better place? Get in touch!</p>
            <p>Email: usama_faheem@berkeley.edu | Phone: +1 541 674 3147</p>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Usama Faheem. Changing the world, one data point at a time.</p>
        </div>
    </footer>

    <script>
        // Dark mode toggle
        const darkModeToggle = document.querySelector('.dark-mode-toggle');
        darkModeToggle.addEventListener('click', () => {
            document.body.classList.toggle('dark-mode');
            const icon = darkModeToggle.querySelector('i');
            icon.classList.toggle('fa-moon');
            icon.classList.toggle('fa-sun');
        });

        // Mobile menu toggle
        const menuToggle = document.querySelector('.menu-toggle');
        const navUl = document.querySelector('nav ul');
        menuToggle.addEventListener('click', () => {
            navUl.classList.toggle('show');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
