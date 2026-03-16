<!DOCTYPE html>
<html lang="ar" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahjoub Rahmon · Full Stack Developer in progress</title>
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, system-ui, sans-serif;
        }

        body {
            background: linear-gradient(145deg, #0f172a 0%, #1e293b 100%);
            color: #e2e8f0;
            line-height: 1.6;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: rgba(15, 23, 42, 0.8);
            backdrop-filter: blur(10px);
            border-radius: 2.5rem;
            padding: 2.5rem;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.8), 0 0 0 1px #334155 inset;
            border: 1px solid #3b82f620;
        }

        h1 {
            font-size: 3rem;
            font-weight: 700;
            background: linear-gradient(135deg, #60a5fa, #c084fc);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 0.25rem;
            letter-spacing: -0.02em;
        }

        .badge {
            display: inline-block;
            background: #1e293b;
            padding: 0.4rem 1.2rem;
            border-radius: 40px;
            font-size: 0.9rem;
            font-weight: 500;
            border: 1px solid #3b82f6;
            color: #90d2ff;
            margin: 1rem 0 2rem 0;
            box-shadow: 0 0 12px #3b82f640;
        }

        .section-title {
            font-size: 1.8rem;
            font-weight: 600;
            margin: 2.5rem 0 1.5rem 0;
            padding-bottom: 0.5rem;
            border-bottom: 3px solid #3b82f6;
            display: inline-block;
        }

        .skill-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .skill-category {
            background: #0f172a;
            padding: 1.5rem;
            border-radius: 1.8rem;
            border: 1px solid #334155;
            transition: 0.2s;
        }

        .skill-category:hover {
            border-color: #3b82f6;
            box-shadow: 0 8px 20px #00000060;
        }

        .skill-category h3 {
            color: #94a3b8;
            font-weight: 500;
            font-size: 1rem;
            letter-spacing: 1px;
            margin-bottom: 1rem;
        }

        .skill-category p {
            font-size: 1.25rem;
            font-weight: 500;
            color: #f1f5f9;
            line-height: 1.8;
        }

        .project-card {
            background: #0f172a;
            border-radius: 2rem;
            padding: 1.5rem;
            margin: 1.5rem 0;
            border: 1px solid #334155;
            transition: 0.2s;
        }

        .project-card:hover {
            border-color: #c084fc;
            transform: translateY(-4px);
        }

        .project-title {
            font-size: 1.6rem;
            font-weight: 600;
            color: #cbd5e1;
            margin-bottom: 0.75rem;
        }

        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 0.6rem;
            margin: 1rem 0;
        }

        .tech-tag {
            background: #1e293b;
            padding: 0.3rem 1rem;
            border-radius: 30px;
            font-size: 0.85rem;
            border: 1px solid #3b82f6;
            color: #b9d9ff;
        }

        .project-desc {
            color: #a0afc0;
            margin: 0.75rem 0;
        }

        .stats-container {
            display: flex;
            gap: 1.5rem;
            flex-wrap: wrap;
            margin: 2rem 0;
        }

        .stat-box {
            background: #0f172a;
            border-radius: 2rem;
            padding: 1.5rem;
            flex: 1;
            min-width: 180px;
            border: 1px solid #334155;
            text-align: center;
        }

        .stat-number {
            font-size: 2.4rem;
            font-weight: 700;
            color: #60a5fa;
        }

        .social-links {
            display: flex;
            gap: 1.5rem;
            margin: 2rem 0 1rem 0;
            flex-wrap: wrap;
        }

        .social-link {
            background: #1e293b;
            color: #e2e8f0;
            text-decoration: none;
            padding: 0.8rem 1.8rem;
            border-radius: 40px;
            font-size: 1.1rem;
            border: 1px solid #334155;
            transition: 0.15s;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }

        .social-link i {
            color: #60a5fa;
            font-size: 1.3rem;
        }

        .social-link:hover {
            border-color: #60a5fa;
            background: #263449;
        }

        .footer-note {
            margin-top: 4rem;
            text-align: center;
            color: #667c9e;
            font-size: 1.1rem;
            border-top: 1px dashed #334155;
            padding-top: 2rem;
        }

        .motto {
            font-size: 1.3rem;
            font-style: italic;
            background: #131e33;
            padding: 1.2rem 2rem;
            border-radius: 60px;
            border-left: 5px solid #3b82f6;
            margin: 2rem 0;
        }

        @media (max-width: 600px) {
            h1 { font-size: 2.2rem; }
            .container { padding: 1.5rem; }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <h1>Mahjoub Rahmon</h1>
        <div class="badge">
            <i class="fas fa-code" style="margin-right: 8px;"></i> IT student · Software Engineering · Full Stack (in progress)
        </div>

        <!-- About -->
        <p style="font-size: 1.2rem; max-width: 700px; color: #b9c9e0;">
            👨‍💻 Passionate about C#, OOP, and data structures. 
            Currently building the foundation to become a professional full‑stack developer. 
            I turn ideas into clean code.
        </p>

        <!-- Skills -->
        <div class="section-title"><i class="fas fa-cogs" style="margin-right: 12px;"></i> Technical skills</div>
        <div class="skill-grid">
            <div class="skill-category">
                <h3>⚡ STRONG</h3>
                <p>C# · OOP (inheritance, polymorphism, encapsulation) · Data Structures (arrays, lists, stacks, queues, trees)</p>
            </div>
            <div class="skill-category">
                <h3>🌱 LEARNING</h3>
                <p>ASP.NET Core · Entity Framework · HTML/CSS/JS · SQL · REST APIs · MVC</p>
            </div>
            <div class="skill-category">
                <h3>🛠 TOOLS</h3>
                <p>Git · GitHub · Visual Studio · VS Code · LINQ · .NET</p>
            </div>
        </div>

        <!-- Projects (examples) -->
        <div class="section-title"><i class="fas fa-folder-open" style="margin-right: 12px;"></i> Projects I've built</div>
        
        <div class="project-card">
            <div class="project-title">📋 Task Manager (Console)</div>
            <div class="project-tech">
                <span class="tech-tag">C#</span>
                <span class="tech-tag">OOP</span>
                <span class="tech-tag">Data structures</span>
            </div>
            <div class="project-desc">
                A task management app using Lists and Queues. Implements classes, inheritance, and file persistence.
            </div>
        </div>

        <div class="project-card">
            <div class="project-title">🏦 Simple Banking System</div>
            <div class="project-tech">
                <span class="tech-tag">C#</span>
                <span class="tech-tag">Polymorphism</span>
                <span class="tech-tag">Encapsulation</span>
            </div>
            <div class="project-desc">
                Simulates deposit, withdraw, and transfer operations. Uses abstract classes and interfaces.
            </div>
        </div>

        <div class="project-card">
            <div class="project-title">📊 Student Management (LINQ)</div>
            <div class="project-tech">
                <span class="tech-tag">C#</span>
                <span class="tech-tag">LINQ</span>
                <span class="tech-tag">Collections</span>
            </div>
            <div class="project-desc">
                CRUD operations on student records. Filtering and searching with LINQ.
            </div>
        </div>

        <!-- GitHub stats area (static example, you can replace with real stats images) -->
        <div class="section-title"><i class="fab fa-github" style="margin-right: 12px;"></i> GitHub at a glance</div>
        <div class="stats-container">
            <div class="stat-box">
                <div class="stat-number">8+</div>
                <div style="color: #94a3b8;">repositories</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">⭐ 15</div>
                <div style="color: #94a3b8;">total stars</div>
            </div>
            <div class="stat-box">
                <div class="stat-number">📌 3</div>
                <div style="color: #94a3b8;">pinned projects</div>
            </div>
        </div>

        <!-- Real GitHub stats images (you can uncomment and replace 'mahjoubrahmon' with your username) -->
        <!--
        <div style="display: flex; gap: 15px; flex-wrap: wrap; margin: 25px 0;">
            <img src="https://github-readme-stats.vercel.app/api?username=mahjoubrahmon&show_icons=true&theme=radical" alt="GitHub stats" style="max-width: 100%; border-radius: 18px;">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mahjoubrahmon&layout=compact&theme=radical" alt="Top langs" style="max-width: 100%; border-radius: 18px;">
        </div>
        -->

        <!-- Motto -->
        <div class="motto">
            <i class="fas fa-quote-right" style="color: #3b82f6; margin-right: 12px;"></i> 
            “Consistency over perfection — every day a little better.”
        </div>

        <!-- Connect -->
        <div class="section-title"><i class="fas fa-link" style="margin-right: 12px;"></i> Connect with me</div>
        <div class="social-links">
            <a href="#" class="social-link"><i class="fas fa-envelope"></i> mahjoub.rahmon@email.com</a>
            <a href="#" class="social-link"><i class="fab fa-github"></i> github/mahjoubrahmon</a>
            <a href="#" class="social-link"><i class="fab fa-linkedin"></i> linkedin/in/mahjoub-rahmon</a>
            <a href="#" class="social-link"><i class="fab fa-twitter"></i> @mahjoub_rahmon</a>
        </div>

        <!-- Footer -->
        <div class="footer-note">
            <i class="fas fa-crown" style="color: #fbbf24; margin-right: 6px;"></i> 
            Full‑stack developer in the making — open to opportunities & collaboration.
        </div>
    </div>
</body>
</html>
