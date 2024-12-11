<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Layout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f9f9f9;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid #ccc;
            padding-bottom: 10px;
        }

        header h1 {
            display: flex;
            align-items: center;
            font-size: 1.2rem;
        }

        header h1 img {
            width: 30px;
            height: 30px;
            margin-right: 10px;
        }

        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #333;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .main-title {
            text-align: center;
            margin: 20px 0;
        }

        .main-title h2 {
            font-size: 2rem;
            margin: 0;
            font-family: cursive;
        }

        .main-title p {
            font-size: 1rem;
            color: #666;
        }

        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            gap: 20px;
            border-top: 2px solid #ccc;
            padding-top: 20px;
        }

        .grid .section {
            border: 1px solid #ccc;
            padding: 10px;
        }

        .section h3 {
            font-size: 1rem;
            margin-bottom: 10px;
            font-family: cursive;
        }

        .section ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .section ul li {
            margin-bottom: 5px;
        }

        .reviews {
            margin-top: 40px;
            text-align: center;
        }

        .reviews h3 {
            margin-bottom: 20px;
            font-family: cursive;
        }

        .review-cards {
            display: flex;
            justify-content: space-between;
            gap: 20px;
        }

        .review-card {
            flex: 1;
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 10px;
        }

        .review-card p {
            font-size: 0.9rem;
            color: #333;
        }

        .review-card .author {
            margin-top: 10px;
            font-size: 0.8rem;
            color: #555;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.8rem;
            color: #888;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>
                <img src="logo.png" alt="Logo">
                your name
            </h1>
            <nav>
                <a href="#">Home</a>
                <a href="#">Projects</a>
                <a href="#">Articles</a>
                <a href="#">Contact</a>
            </nav>
        </header>

        <div class="main-title">
            <h2>Frontend Developer</h2>
            <p>html only with proper layout, no styling</p>
        </div>

        <div class="grid">
            <div class="section">
                <h3>Projects</h3>
                <ul>
                    <li>HTML Only Portfolio</li>
                    <li>Calculator</li>
                    <li>Quiz App</li>
                    <li>Countdown Timer</li>
                    <li>Product Upcoming Page</li>
                </ul>
            </div>
            <div class="section">
                <h3>Work Experience</h3>
                <p><strong>roadmap.sh</strong></p>
                <p>Solved all the frontend projects</p>
                <a href="#">Visit my Profile</a>
                <p><strong>OpenSource Work</strong></p>
                <p>Contributed to 50 opensource projects. Made my own projects with 200 GitHub Stars.</p>
                <a href="#">Visit my GitHub Profile</a>
            </div>
            <div class="section">
                <h3>Education</h3>
                <p>Graduated with 3.76 out of 4 CGPA. Won Acme Hackathon. Organized 30 sessions.</p>
                <h4>Courses I took:</h4>
                <ul>
                    <li>Object Oriented Programming</li>
                    <li>Data Structures and Algorithms</li>
                    <li>Web Engineering</li>
                    <li>Artificial Intelligence</li>
                    <li>Human Computer Interaction</li>
                    <li>Computer Graphics</li>
                    <li>Database Management Systems</li>
                    <li>Distributed Database Systems</li>
                    <li>Discrete Mathematics</li>
                </ul>
            </div>
        </div>

        <div class="reviews">
            <h3>Reviews from my Teachers</h3>
            <div class="review-cards">
                <div class="review-card">
                    <p>John Doe was a brilliant student; always stood out with his assignments.</p>
                    <div class="author">Jane Doe <br> Assistant Professor</div>
                </div>
                <div class="review-card">
                    <p>John Doe was a brilliant student; always stood out with his assignments.</p>
                    <div class="author">Jane Doe <br> Assistant Professor</div>
                </div>
                <div class="review-card">
                    <p>John Doe was a brilliant student; always stood out with his assignments.</p>
                    <div class="author">Jane Doe <br> Assistant Professor</div>
                </div>
            </div>
        </div>

        <footer>
            &copy; all rights reserved 2025
        </footer>
    </div>
</body>
</html>
