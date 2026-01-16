<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Umwiza Kettya | IT Professional</title>
    <style>
        :root {
            --primary: #2563eb;
            --dark: #1e293b;
            --light: #f8fafc;
        }
        body {
            font-family: 'Segoe UI', sans-serif;
            line-height: 1.6;
            margin: 0;
            color: var(--dark);
            background-color: var(--light);
        }
        header {
            background: linear-gradient(135deg, #1e293b 0%, #334155 100%);
            color: white;
            padding: 4rem 2rem;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 2rem;
        }
        .card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }
        h1 { margin: 0; font-size: 2.5rem; }
        .contact-info { margin-top: 1rem; }
        .contact-info a { color: #94a3b8; text-decoration: none; margin: 0 10px; }
        .btn {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 0.8rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
        }
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
        }
        .skill-item {
            background: #e2e8f0;
            padding: 0.5rem;
            border-radius: 4px;
            text-align: center;
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <h1>Umwiza Kettya</h1>
    <p>IT Professional & Solutions Provider</p>
    <div class="contact-info">
        <a href="mailto:umwizakettya@gmail.com">umwizakettya@gmail.com</a> | 
        <a href="tel:+250738115925">+250 738 115 925</a>
    </div>
</header>

<div class="container">
    <div class="card">
        <h2>Welcome! 😊</h2>
        <p>Hello! I am a dedicated IT professional based in Rwanda. I am passionate about technology, troubleshooting, and building digital systems that work. I'm glad you're visiting my portfolio—feel free to look around and reach out if you have a project in mind!</p>
    </div>

    <div class="card">
        <h2>Technical Skills</h2>
        <div class="skills-grid">
            <div class="skill-item">IT Support</div>
            <div class="skill-item">Networking</div>
            <div class="skill-item">Hardware</div>
            <div class="skill-item">Cybersecurity</div>
            <div class="skill-item">HTML/CSS</div>
            <div class="skill-item">Systems Admin</div>
        </div>
    </div>

    <div class="card">
        <h2>Current Projects</h2>
        <h3>System Monitoring Automation</h3>
        <p>Currently developing a script-based solution to track hardware performance and alert users of low disk space.</p>
        <a href="#" class="btn">View on GitHub</a>
    </div>

    <div class="card" style="text-align: center;">
        <h2>Let's Work Together</h2>
        <p>I am currently available for IT consultancy and junior developer roles.</p>
        <a href="mailto:umwizakettya@gmail.com" class="btn">Send me an Email</a>
    </div>
</div>

</body>
</html># project
