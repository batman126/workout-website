
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Workout Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2a2a72;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }

        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #fdd835;
        }

        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            margin-bottom: 15px;
            color: #2a2a72;
        }

        .workout-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .workout-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .workout-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
        }

        .workout-card h3 {
            margin: 0 0 10px;
            color: #2a2a72;
        }

        .workout-card p {
            margin: 0;
        }

        footer {
            background-color: #2a2a72;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Workout Pro</h1>
        <p>Your ultimate guide to staying fit and healthy</p>
    </header>

    <nav>
        <a href="#workouts">Workouts</a>
        <a href="#nutrition">Nutrition</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="workouts" class="section">
            <h2>Workouts</h2>
            <div class="workout-grid">
                <div class="workout-card">
                    <h3>Cardio Blast</h3>
                    <p>Get your heart pumping with this high-intensity cardio session.</p>
                </div>
                <div class="workout-card">
                    <h3>Strength Training</h3>
                    <p>Build muscle and improve your endurance with targeted strength exercises.</p>
                </div>
                <div class="workout-card">
                    <h3>Yoga Flow</h3>
                    <p>Enhance flexibility and calm your mind with a soothing yoga routine.</p>
                </div>
            </div>
        </section>

        <section id="nutrition" class="section">
            <h2>Nutrition</h2>
            <p>Explore healthy recipes, meal plans, and tips to fuel your fitness journey.</p>
        </section>

        <section id="contact" class="section">
            <h2>Contact Us</h2>
            <p>Email: support@workoutpro.com</p>
            <p>Phone: (123) 456-7890</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Workout Pro. All Rights Reserved.</p>
    </footer>
</body>
</html>
