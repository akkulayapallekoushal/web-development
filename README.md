# web-development
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Assignment</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #24292e;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #0366d6;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        section {
            padding: 20px;
            margin: 20px;
            background: white;
            border-radius: 8px;
        }

        h2 {
            color: #24292e;
        }

        .project {
            border: 1px solid #ddd;
            padding: 15px;
            margin-top: 10px;
            border-radius: 5px;
        }

        footer {
            background-color: #24292e;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }

        button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #218838;
        }
    </style>
</head>

<body>

    <header>
        <h1>Welcome to My GitHub Assignment</h1>
        <p>Simple HTML Webpage Project</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! My name is Student Name. This webpage is created for my GitHub assignment using HTML and CSS.</p>
    </section>

    <section id="projects">
        <h2>My Projects</h2>

        <div class="project">
            <h3>Project 1</h3>
            <p>A simple calculator using HTML, CSS, and JavaScript.</p>
            <button>View Project</button>
        </div>

        <div class="project">
            <h3>Project 2</h3>
            <p>A personal portfolio website.</p>
            <button>View Project</button>
        </div>

    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: student@example.com</p>
        <p>GitHub: github.com/yourusername</p>
    </section>

    <footer>
        <p>© 2026 My GitHub Assignment | Designed with HTML & CSS</p>
    </footer>

</body>
</html>
