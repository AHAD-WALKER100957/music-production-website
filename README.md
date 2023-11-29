# music-production-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music Production Studio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 80%;
            margin: 0 auto;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1em 0;
        }

        nav ul {
            list-style-type: none;
        }

        nav li {
            display: inline;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: white;
            font-weight: bold;
        }

        section {
            padding: 50px 0;
        }

        #home {
            background-color: #f0f0f0;
        }

        #services, #portfolio, #contact {
            background-color: #fff;
        }

        h2 {
            color: #333;
        }

        ul {
            padding: 0;
        }

        ul li {
            list-style: none;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }

        /* Portfolio Item Styling */
        .portfolio-item {
            margin-bottom: 20px;
        }

        .portfolio-item img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        .portfolio-item p {
            text-align: center;
            margin-top: 10px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Music Production Studio</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Home Section -->
    <section id="home">
        <div class="container">
            <h2>Welcome to our Music Production Studio</h2>
            <p>Your source for high-quality music production services.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <ul>
                <li>Recording</li>
                <li>Editing</li>
                <li>Mixing</li>
                <li>Mastering</li>
            </ul>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <!-- Add your portfolio items here -->
            <div class="portfolio-item">
                <img src="sample1.jpg" alt="Sample Track 1">
                <p>Sample Track 1</p>
            </div>
            <div class="portfolio-item">
                <img src="sample2.jpg" alt="Sample Track 2">
                <p>Sample Track 2</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: info@musicproductionstudio.com</p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2023 Music Production Studio</p>
        </div>
    </footer>

</body>
</html>
