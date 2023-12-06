# UpdatedAirbnb1.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Airbnb</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background: #FF5A5F;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        nav {
            background: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }

        section {
            padding: 20px;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .search-bar {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        .listing {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Airbnb</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Explore</a>
        <a href="#">List Your Space</a>
        <a href="#">Help</a>
    </nav>

    <section>
        <div class="search-bar">
            <label for="location">Location</label>
            <input type="text" id="location" placeholder="Location" fdprocessedid="2844cr">

            <label for="check-in">Check-in Date</label>
            <input type="date" id="check-in">
            
            <button>Search</button>
        </div>

        <div class="listing">
            <img src="property1.jpg" alt="Property 1">
            <h2>Beautiful Beachfront Villa</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            <button>View Details</button>
        </div>

        <!-- Add more listings, videos, and other elements here -->

    </section>

    <footer>
        <p>&copy; 2023 Airbnb, Inc.</p>
    </footer>
</body>
</html>
