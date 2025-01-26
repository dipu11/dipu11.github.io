# dipu11.github.io
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background: #004080;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1rem;
            background: #0066cc;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 900px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .profile {
            display: flex;
            gap: 1rem;
            margin-bottom: 2rem;
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .profile div {
            flex: 1;
        }
        .profile h1 {
            margin: 0;
        }
        .section {
            margin-bottom: 2rem;
        }
        .section h2 {
            border-bottom: 2px solid #0066cc;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }
        .section ul {
            list-style-type: none;
            padding: 0;
        }
        .section ul li {
            margin-bottom: 0.5rem;
        }
        .footer {
            text-align: center;
            margin-top: 2rem;
            font-size: 0.9rem;
            color: #666;
        }
    </style>
</head>
<body>

<header>
    <h1>Dipu</h1>
    <p>Software Engineer</p>
</header>

<nav>
    <a href="#updates">Updates</a>
    <a href="#experience">Experience</a>
    <a href="#education">Education</a>
    <a href="#publications">Publications</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <div class="profile">
        <img src="profile.jpg" alt="Dipu">
        <div>
            <h1>Dipu Roy</h1>
            <p>Email: myEmailId</p>
            <p><a href="https://dipu11.medium.com/">Medium</a></p>
            <p><a href="https://stackoverflow.com/users/5332914/user404">Stack Overflow</a></p>
        </div>
    </div>

    <div class="section" id="updates">
        <h2>Updates</h2>
        <ul>          
        </ul>
    </div>

    <div class="section" id="experience">
        <h2>Experience</h2>
        <ul>
            <li>Senior Software Engineer- Tekarsh | MarginEdge [Feb 2023 - present]</li>
            <li>Software Engineer - TigerIT Bd. Ltd [March 2019 - Jan 2023]</li>
            <li>Software Engineer - REVE Chat, REVE Systems [April 2017 - Feb 2019]</li>
        </ul>
    </div>
    
    <div class="section" id="education">
        <h2>Education</h2>
        <ul>
            <li>Bachelor in Computer Science and Engineering, CSE, BUET [Feb, 2017]</li>            
        </ul>
    </div>

    <div class="section" id="publications">
        <h2>Selected Publications</h2>
    </div>

    <div class="section" id="contact">
        <h2>Contact</h2>
        <p>Shoot me an email</p>
    </div>
</div>

<footer class="footer">
    <p>&copy; 2025 Dipu Roy. All rights reserved.</p>
</footer>

</body>
</html>

