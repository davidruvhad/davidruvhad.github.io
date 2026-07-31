<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Davey Productions | Portfolio</title>

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
    <h1>VIP Car Center</h1>
    <p>Reliable Cars • Affordable Prices • Even Groms</p>

    <a href="#projects" class="button">View My Projects</a>
</header>


<div style="
    display: flex; 
    justify-content: center; 
    align-items: center; 
    min-height: 400px; 
    background: linear-gradient(135deg, #667eea, #764ba2);
    border-radius: 30px;
    padding: 60px;
    margin: 40px auto;
    width: 80%;
    box-shadow: 0 20px 60px rgba(102, 126, 234, 0.3);
">
   <button onclick="window.location.href='about.html'" class="big-button"
        style="
            background: white;
            color: #667eea;
            border: none;
            padding: 40px 80px;
            font-size: 2.5rem;
            font-weight: 800;
            border-radius: 20px;
            cursor: pointer;
            box-shadow: 0 15px 40px rgba(0,0,0,0.25);
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 3px;
            max-width: 90%;
            white-space: nowrap;
        "
        onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 20px 50px rgba(0,0,0,0.35)';"
        onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 15px 40px rgba(0,0,0,0.25)';">
    >Check out of cars!<
</button>
</div>

<section id="about">

    <h2>About Me</h2>
<p>Welcome to my alpha version of vipcarcenter.net </p>

</section>

<section id="projects">

    <h2>Projects</h2>

    <div class="projects">

        <div class="card">
            <h3>Pre-Owned Vehicles</h3>
            <p>Built predictive models and AI solutions.</p>
        </div>

        <div class="card">
            <h3>Auction Spotter</h3>
            <p>Check out a list of upcoming vehicles available at the auction</p>
        </div>

        <div class="card">
            <h3>Bikes</h3>
            <p>Full-stack applications and automation tools.</p>
        </div>

    </div>

</section>

<section id="contact">

    <h2>Contact</h2>

    <p>Email: davidruvhad@gmail.com</p>
    <p>GitHub: github.com/davidruvhad</p>
    <p>LinkedIn: linkedin.com/in/davidhadar</p>


</section>

<footer>

    <p>© 2026 VIP Car Center. All Rights Reserved.</p>

</footer>

</body>
</html>
