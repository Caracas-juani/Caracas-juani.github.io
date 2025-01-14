<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Just Padel</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }

        header h1 {
            margin: 0;
            font-size: 2em;
        }

        nav {
            display: flex;
            gap: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 1em;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        .hero h2 {
            font-size: 2.5em;
        }

        main {
            padding: 20px;
        }

        section {
            margin: 20px auto;
            max-width: 800px;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .image-gallery {
            display: flex;
            justify-content: center;
            gap: 10px;
            flex-wrap: wrap;
        }

        .image-gallery img {
            width: 300px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        footer {
            margin-top: 20px;
            padding: 20px 0;
            background-color: #333;
            color: white;
            text-align: center;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Just Padel</h1>
        <nav>
            <a href="#cost">Cost</a>
            <a href="#gallery">Gallery</a>
            <a href="#about">About Us</a>
        </nav>
    </header>

    <div class="hero">
        <h2>Welcome to Just Padel</h2>
    </div>

    <main>
        <section id="cost">
            <h2>Cost of Reservation</h2>
            <p>
                Reserve a court for just $100 for one hour and a half. Enjoy the best facilities and a vibrant padel community.
            </p>
        </section>

        <section id="gallery">
            <h2>Gallery</h2>
            <div class="image-gallery">
                <img src="https://via.placeholder.com/300" alt="People playing padel 1">
                <img src="https://via.placeholder.com/300" alt="People playing padel 2">
                <img src="https://via.placeholder.com/300" alt="People playing padel 3">
            </div>
        </section>

        <section id="about">
            <h2>About Our Club</h2>
            <p>
                Just Padel is a state-of-the-art padel club located in Miami, offering an exceptional experience for players of all levels. Whether you're a beginner looking to learn the basics or a seasoned player seeking high-energy matches, our club provides the perfect environment to enjoy this thrilling sport.
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Just Padel. All rights reserved.</p>
    </footer>
</body>
</html>
