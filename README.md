<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Antoni Zborowski</title>
    <!-- Stylizacja strony -->
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #4b6cb7, #182848);
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            width: 360px;
            border-radius: 20px;
            padding: 20px;
            background-color: #1a1a1a;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
        }

        .header {
            text-align: left;
            margin-bottom: 20px;
            position: relative;
        }

        .header h1 {
            font-size: 1.5rem;
            margin: 0;
        }

        .header p {
            margin: 5px 0 0 0;
            font-size: 1rem;
            color: #aaa;
        }

        .profile {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            overflow: hidden;
            margin: 0 auto;
            border: 3px solid #fff;
        }

        .profile img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .card {
            border-radius: 15px;
            padding: 20px;
            margin-bottom: 15px;
            position: relative;
            color: #fff;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        }

        .card.skills {
            background-color: #ffccb3;
            color: #4a2c27;
        }

        .card.goals {
            background-color: #b3ffd9;
            color: #2d4a39;
        }

        .card h2 {
            font-size: 1.2rem;
            margin: 0 0 10px 0;
        }

        .card p {
            font-size: 1rem;
            margin: 0 0 10px 0;
        }

        .contact {
            text-align: center;
            margin-top: 20px;
        }

        .contact a {
            display: block;
            color: #aaa;
            text-decoration: none;
            margin: 5px 0;
            font-size: 1rem;
        }

        .contact a:hover {
            color: #fff;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Nagłówek -->
        <div class="header">
            <h1>Antoni Zborowski</h1>
            <p>Get to know the goat!</p>
        </div>

        <!-- Karta: Umiejętności -->
        <div class="card skills">
            <h2>About Me</h2>
            <p>
                I am a creator, focused on artificial intelligence and life-changing apps. With a background in e-commerce and expertise in AI.
                My current focus is understanding fundamentals of DRL and firstly creating AI-driven applications, and continuing personal development through exploring cultures and contact with art.
                I love to create, therefore to the table I bring loads of ideas and inconventional solutions, that combined with my experience in sales and logistics becomes miracle.
            </p>
        </div>

        <!-- Karta: Cele -->
        <div class="card goals">
            <h2>Goals for 2025</h2>
            <p>Visit at least 5 countries</p>
            <p>Create at least one fully working app</p>
            <p>Conquer the fundamentals of Deep Reinforcement Learning</p>
        </div>

        <!-- Sekcja kontaktowa -->
        <div class="contact">
            <h2>Let's create something!</h2>
            <a href="https://wa.me/1234567890" target="_blank">WhatsApp</a>
            <a href="https://www.linkedin.com/in/antoni-zborowski/" target="_blank">LinkedIn</a>
            <a href="https://github.com/senk" target="_blank">GitHub</a>
        </div>
    </div>
</body>
</html>
