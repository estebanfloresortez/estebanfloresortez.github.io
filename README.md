<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Your Name | Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: linear-gradient(to right, #1e3c72, #2a5298);
            color: white;
            text-align: center;
        }

        header {
            padding: 60px 20px;
        }

        header h1 {
            font-size: 3rem;
        }

        header p {
            margin-top: 10px;
            font-size: 1.2rem;
            opacity: 0.9;
        }

        section {
            padding: 50px 20px;
            background: white;
            color: #333;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: #f4f4f4;
            padding: 20px;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: scale(1.05);
        }

        footer {
            padding: 20px;
            background: #111;
        }

        a {
            color: #2a5298;
            text-decoration: none;
            font-weight: bold;
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background: #2a5298;
            color: white;
            border-radius: 5px;
        }

        .btn:hover {
            background: #1e3c72;
        }
    </style>
</head>

<body>

<header>
    <h1>Your Name</h1>
    <p>Web Developer | Designer | Creator</p>
    <a href="#projects" class="btn">View My Work</a>
</header>

<section id="projects">
    <h2>My Projects</h2>

    <div class="projects">
        <div class="card">
            <h3>Project One</h3>
            <p>Short description of your project.</p>
        </div>

        <div class="card">
            <h3>Project Two</h3>
            <p>Short description of your project.</p>
        </div>

        <div class="card">
            <h3>Project Three</h3>
            <p>Short description of your project.</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2026 Your Name | Hosted on GitHub Pages</p>
</footer>

</body>
</html>
