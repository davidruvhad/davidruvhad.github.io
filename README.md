<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> David Hadar | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            background-color: #f4f4f4;
            color: #333;
        }

        nav {
            background: #1f2937;
            color: white;
            padding: 20px;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            gap: 30px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: #2563eb;
            color: white;
        }

        .hero h1 {
            font-size: 48px;
        }

        .hero p {
            margin-top: 15px;
            font-size: 20px;
        }

        .button {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: white;
            color: #2563eb;
            text-decoration: none;
            border-radius: 8px;
            font-weight: bold;
        }

        section {
            width: 80%;
            margin: auto;
            padding: 60px 0;
        }

        h2 {
            margin-bottom: 20px;
            color: #2563eb;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 2px 8px rgba(0,0,0,.1);
        }

        footer {
            text-align: center;
            background: #1f2937;
            color: white;
            padding: 20px;
        }
    </style>

</head>

<body>

<nav>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<header class="hero">
    <h1>Hi, I'm David Hadar</h1>
    <p>Data Analyst • AI Engineer • Software Developer</p>

<p> Attached will include a demo website for my father, Joseph, as I unveil a state of the art website for his business:</p>
                                                  <p>VIP Car Center</p>
    <a href="#projects" class="button">View My Projects</a>
</header>

<section id="about">

    <h2>About Me</h2>

    <p>
        Welcome to my portfolio! I enjoy building AI applications,
        machine learning models, automation tools, and software solutions.
        I work with Python, SQL, Pandas, Spark, Docker, Git, and modern
        data engineering technologies.
    </p>

</section>

<section id="projects">

    <h2>Projects</h2>

    <div class="projects">

        <div class="card">
            <h3>Machine Learning</h3>
            <p>Built predictive models and AI solutions.</p>
        </div>

        <div class="card">
            <h3>Data Analytics</h3>
            <p>SQL, Python, dashboards, and ETL pipelines.</p>
        </div>

        <div class="card">
            <h3>Software Development</h3>
            <p>Full-stack applications and automation tools.</p>
        </div>

    </div>

</section>

<section id="contact">

    <h2>Contact</h2>

    <p>Email: davidruvhad@gmail.com</p>

    <p>GitHub: github.com/yourusername</p>

    <p>LinkedIn: linkedin.com/in/davidruvhad</p>

</section>

<footer>

    <p>© 2026 Davey. All Rights Reserved.</p>

</footer>

</body>
</html>
