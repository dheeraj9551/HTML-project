<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rental Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('background.jpg'); /* Add your background image */
            background-size: cover;
            background-attachment: fixed;
            color: #333;
        }
        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 15px 20px;
            position: sticky;
            top: 0;
            z-index: 1000;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        section {
            margin: 30px 0;
        }
        .grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: 300px;
            background: white;
            transition: transform 0.3s ease-in-out; /* Added transition for smooth scaling */
        }
        .card img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease-in-out; /* Ensure smooth transition on image hover */
        }
        .card:hover {
            transform: scale(1.1); /* Scale up the card slightly on hover */
        }
        .card:hover img {
            transform: scale(1.1); /* Scale up the image inside the card on hover */
        }
        .card-content {
            padding: 15px;
        }
        .card-content h3 {
            margin: 0 0 10px;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rental Services</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="phones.html" target="_blank">Phones</a>
            <a href="cars.html" target="_blank">Cars</a>
            <a href="bikes.html" target="_blank">Bikes</a> <!-- Opens in a new tab -->
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Welcome to Rental Services</h2>
            <p>We provide high-quality bikes, cars, and phones for rent at affordable prices. Explore our collection and choose the one that suits your needs.</p>
        </section>

        <section>
            <h3>Categories</h3>
            <div class="grid">
                <div class="card">
                    <img src="bikes.jpg" alt="Bike">
                    <div class="card-content">
                        <h3>Bikes</h3>
                        <p>Explore our range of bikes available for rent.</p>
                    </div>
                </div>
                <div class="card">
                    <img src="Best-Cars.webp" alt="Car">
                    <div class="card-content">
                        <h3>Cars</h3>
                        <p>Choose from a variety of cars for your journey.</p>
                    </div>
                </div>
                <div class="card">
                    <img src="phones.jpg" alt="Phone">
                    <div class="card-content">
                        <h3>Phones</h3>
                        <p>Rent the latest phones for your needs.</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Rental Services. All rights reserved.</p>
    </footer>
</body>
</html>

BIKes cOde
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bikes for Rent</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        .grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: 300px;
            background: white;
            transition: transform 0.3s ease-in-out; /* Added transition for smooth scaling */
        }
        .card img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease-in-out; /* Ensure smooth transition on image hover */
        }
        .card:hover {
            transform: scale(1.1); /* Scale up the card slightly on hover */
        }
        .card:hover img {
            transform: scale(1.1); /* Scale up the image inside the card on hover */
        }
        .card-content {
            padding: 15px;
        }
        .card-content h3 {
            margin: 0 0 10px;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bikes for Rent</h1>
    </header>

    <div class="grid">
        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="CLASSIC-350.avif" alt="Bike 1">
                <div class="card-content">
                    <h3>Classic-350</h3>
                    <p>Brand:Royal enfield <br>Price: 700/day<br>Configuration: 180-Speed</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="MT-15.webp" alt="Bike 2">
                <div class="card-content">
                    <h3>MT-15</h3>
                    <p>Brand: Yamaha<br>Price: 500/day<br>Configuration: Road Bike, 150-Speed</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="JAWA.png" alt="Bike 3">
                <div class="card-content">
                    <h3>Bobber</h3>
                    <p>Brand: Jawa<br>Price: 1200/day<br>Configuration: 240-Speed</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="R15.webp" alt="Bike 4">
                <div class="card-content">
                    <h3>Bike Model 4</h3>
                    <p>Brand: Brand 4<br>Price: 750/day<br>Configuration: Single-Speed</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="RS-457.webp" alt="Bike 5">
                <div class="card-content">
                    <h3>RS-457</h3>
                    <p>Brand: Aprilia<br>Price: 1200/day<br>Configuration: 26-Inch Tires</p>
                </div>
            </a>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Rental Services. All rights reserved.</p>
    </footer>
</body>
</html>

CARS CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cars for Rent</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        .grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: 300px;
            background: white;
            transition: transform 0.3s ease-in-out; /* Added transition for smooth scaling */
        }
        .card img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease-in-out; /* Ensure smooth transition on image hover */
        }
        .card:hover {
            transform: scale(1.1); /* Scale up the card slightly on hover */
        }
        .card:hover img {
            transform: scale(1.1); /* Scale up the image inside the card on hover */
        }
        .card-content {
            padding: 15px;
        }
        .card-content h3 {
            margin: 0 0 10px;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cars for Rent</h1>
    </header>

    <div class="grid">
        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="compass.webp" alt="Car 1">
                <div class="card-content">
                    <h3>Compass</h3>
                    <p>Brand:Jeep<br>Price: 4000/day<br>Configuration: 4 Seats, </p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="creta.webp" alt="Car 2">
                <div class="card-content">
                    <h3>Creta</h3>
                    <p>Brand:Hyundi<br>Price: 2820/day<br>Configuration: 5 Seats, 4 Doors</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="Ford-Mustang.webp" alt="Car 3">
                <div class="card-content">
                    <h3>Mustang</h3>
                    <p>Brand:Ford<br>Price: 25000/day<br>Configuration: 2 Seats, 2 Doors</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="innova.jpg" alt="Car 4">
                <div class="card-content">
                    <h3>Innova</h3>
                    <p>Brand:Toyota<br>Price: 3000/day<br>Configuration: 7 Seats, 4 Doors</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="Roxx.webp" alt="Car 5">
                <div class="card-content">
                    <h3>Roxx</h3>
                    <p>Brand: Mahindra<br>Price: 2000/day<br>Configuration: 5 Seats, 5 Doors</p>
                </div>
            </a>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Rental Services. All rights reserved.</p>
    </footer>
</body>
</html>

PHONES CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cars for Rent</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        .grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: 300px;
            background: white;
            transition: transform 0.3s ease-in-out; /* Added transition for smooth scaling */
        }
        .card img {
            width: 100%;
            height: auto;
            transition: transform 0.3s ease-in-out; /* Ensure smooth transition on image hover */
        }
        .card:hover {
            transform: scale(1.1); /* Scale up the card slightly on hover */
        }
        .card:hover img {
            transform: scale(1.1); /* Scale up the image inside the card on hover */
        }
        .card-content {
            padding: 15px;
        }
        .card-content h3 {
            margin: 0 0 10px;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Cars for Rent</h1>
    </header>

    <div class="grid">
        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="compass.webp" alt="Car 1">
                <div class="card-content">
                    <h3>Compass</h3>
                    <p>Brand:Jeep<br>Price: 4000/day<br>Configuration: 4 Seats, </p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="creta.webp" alt="Car 2">
                <div class="card-content">
                    <h3>Creta</h3>
                    <p>Brand:Hyundi<br>Price: 2820/day<br>Configuration: 5 Seats, 4 Doors</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="Ford-Mustang.webp" alt="Car 3">
                <div class="card-content">
                    <h3>Mustang</h3>
                    <p>Brand:Ford<br>Price: 25000/day<br>Configuration: 2 Seats, 2 Doors</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="innova.jpg" alt="Car 4">
                <div class="card-content">
                    <h3>Innova</h3>
                    <p>Brand:Toyota<br>Price: 3000/day<br>Configuration: 7 Seats, 4 Doors</p>
                </div>
            </a>
        </div>

        <div class="card">
            <a href="rent.html" target="_blank">
                <img src="Roxx.webp" alt="Car 5">
                <div class="card-content">
                    <h3>Roxx</h3>
                    <p>Brand: Mahindra<br>Price: 2000/day<br>Configuration: 5 Seats, 5 Doors</p>
                </div>
            </a>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Rental Services. All rights reserved.</p>
    </footer>
</body>
</html>
