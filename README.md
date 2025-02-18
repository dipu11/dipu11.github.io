<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Dipu Ram Roy</title>
        <style>
            body {
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 0;
                display: flex;
                flex-direction: column;
                scroll-behavior: smooth;
            }
            .header {
                background-color: #333;
                color: white;
                padding: 15px;
                text-align: center;
                position: fixed;
                width: 100%;
                top: 0;
                left: 0;
                z-index: 1000;
            }
            .header nav a {
                color: white;
                text-decoration: none;
                margin: 0 15px;
                cursor: pointer;
            }
            .container {
                display: flex;
                margin-top: 60px;
            }
            .sidebar {
                width: 300px;
                background-color: #f5f5f5;
                padding: 20px;
                text-align: center;
                position: fixed;
                height: 100%;
                top: 60px;
            }
            .sidebar img {
                width: 150px;
                border-radius: 50%;
                margin-bottom: 15px;
            }
            .sidebar a {
                text-decoration: none;
                color: #333;
                display: block;
                margin: 10px 0;
            }
            .content {
                margin-left: 320px;
                padding: 40px;
                max-width: 800px;
            }
            h1, h2 {
                color: #333;
            }
            section {
                padding-top: 80px;
            }
            .experience {
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        .experience h3 {
            margin: 5px 0;
            color: #222;
        }
        .experience p {
            margin: 5px 0;
            color: #555;
        }
        </style>
    </head>
    <body>
        <div class="header">
            <nav>
                <a href="#profile">Profile</a>
                <a href="#experience">Experience</a>
                <a href="#publications">Publications</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
        <div class="container">
            <div class="sidebar">
                <!-- <img src="https://via.placeholder.com/150" alt="Profile Picture"> -->
                <h2>Dipu</h2>
                <p>Software Engineer | Tech Enthusiast | Open Source Contributor</p>
                <p><a href="rdipu.roy01@gmail.com">Email</a></p>
                <p><a href="https://github.com/dipu11">GitHub</a></p>
                <p><a href="https://dipu11.medium.com/">Website</a></p>
            </div>
            <div class="content">
                <section id="profile">
                    <h1>About Me</h1>
                    <p>I am an experienced software engineer with more than 8 years of experience, specializing in backend development and open-source projects. Currently, I am working as a fullstack software engineer based in Dhaka, Bangladesh</p>
                </section>
                <section id="publications">
                    <h1>Publications</h1>
                    <p>coming soon...</p>
                </section>
                <section id="experience">
                    <h1>Experience</h1>
                    <div class="experience">
                        <h3>Senior Software Engineer</h3>
                        <p><strong>Tekarsh Bangladesh Ltd</strong></p>
                        <p>Feb 2023 - Present</p>
                        <p>Worked on developing scalable web applications and cloud-based solutions.</p>
                    </div>
                    <div class="experience">
                        <h3>Senior Software Engineer</h3>
                        <p><strong>TigerIT Bangladesh Ltd.</strong></p>
                        <p>March 2019 - jan 2023</p>
                        <ul>
                            <li>Worked on a very large scale backend service which handled more than 120 million users record</li>
                            <li>Led the backend team for multiple projects</li>
                            <li>Was responsible for design, development and deployment of backend services</li>
                        </ul>
                    </div>
                    <div class="experience">
                        <h3>Software Engineer</h3>
                        <p><strong>REVE Chat, REVE Systems Ltd</strong></p>
                        <p>April 2017 - Feb 2019</p>
                        <ul>
                        </ul>
                    </div>
                </section>
                <section id="contact">
                    <h1>Contact</h1>
                    <p>Email: rdipu.roy01@gmail.com</p>
                    <p>GitHub: <a href="https://github.com/dipu11">dipu11</a></p>
                </section>
            </div>
        </div>
    </body>
</html>