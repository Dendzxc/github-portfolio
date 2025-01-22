
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Phil Andrei Lazaro</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
        }

        nav {
            margin-top: 1rem;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
            font-size: 1.1rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 960px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .section {
            margin-bottom: 2rem;
        }

        .section h2 {
            font-size: 1.8rem;
            color: #444;
            margin-bottom: 1rem;
        }

        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .project {
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            width: calc(33.333% - 1rem);
            min-width: 200px;
        }

        .project img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .project h3 {
            font-size: 1.2rem;
            margin: 0.5rem;
        }

        .project p {
            padding: 0 0.5rem 0.5rem;
        }

        footer {
            text-align: center;
            background: #333;
            color: #fff;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        footer a {
            color: #fff;
            text-decoration: underline;
        }

        footer a:hover {
            color: #ddd;
        }
    </style>
</head>
<body>
    <header>
        <h1>Phil Andrei Lazaro</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>I am Phil Andrei Lazaro, a Software QA Engineer with 2 years of experience in manual and automation testing. I specialize in ensuring high-quality releases by meticulously identifying and resolving issues. In my free time, I enjoy working as a bike mechanic and riding my classic Kawasaki W175.</p>
        </section>

        <section id="projects" class="section">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                    <img src="https://via.placeholder.com/300" alt="Project Image">
                    <h3>E-Commerce Bike Shop</h3>
                    <p>An e-commerce platform for a local bike shop, showcasing my technical skills applied to real-world needs.</p>
                </div>
                <div class="project">
                    <img src="https://via.placeholder.com/300" alt="Project Image">
                    <h3>Traxion Pay Wallet</h3>
                    <p>Performed end-to-end testing and ensured smooth releases for a digital banking app.</p>
                </div>
                <div class="project">
                    <img src="https://via.placeholder.com/300" alt="Project Image">
                    <h3>Coopnet Teller Machine</h3>
                    <p>Validated the functionality of the Philippines' first cardless teller machine through rigorous testing.</p>
                </div>
            </div>
        </section>

        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>If you'd like to collaborate or have any questions, feel free to reach out!</p>
            <p>Email: <a href="mailto:lazarophilandrei@gmail.com">lazarophilandrei@gmail.com</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Phil Andrei Lazaro | <a href="https://github.com/">GitHub</a></p>
    </footer>
</body>
</html>
