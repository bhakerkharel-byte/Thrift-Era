# Thrift-Era
Thrift Era is a Pakistan-based online thrift store redefining fashion through sustainability and affordability. We offer handpicked pre-owned clothing for those who love style with purpose — available for online shopping across Pakistan only.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thrift Era Shopping Mall</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #8B4513; /* Vintage brown */
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #A0522D;
            padding: 0.5rem;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav li {
            margin: 0 1rem;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x400?text=Thrift+Era+Mall'); /* Placeholder image */
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }
        .hero h1 {
            font-size: 3rem;
            margin: 0;
        }
        .section {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .stores {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }
        .store {
            background: white;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            nav ul {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Thrift Era Shopping Mall</h1>
        <p>Your Vintage Shopping Destination</p>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#stores">Stores</a></li>
            <li><a href="#events">Events</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="home" class="hero">
        <div>
            <h1>Welcome to Thrift Era</h1>
            <p>Discover unique vintage finds, retro fashion, and timeless treasures in our curated shopping mall. Step back in time and find your next favorite item!</p>
        </div>
    </section>
    <section id="stores" class="section">
        <h2>Featured Stores</h2>
        <div class="stores">
            <div class="store">
                <h3>Vintage Threads</h3>
                <p>Retro clothing and accessories from the 70s and 80s.</p>
            </div>
            <div class="store">
                <h3>Antique Alley</h3>
                <p>Rare collectibles and vintage furniture.</p>
            </div>
            <div class="store">
                <h3>Record Revival</h3>
                <p>Vinyl records, turntables, and music memorabilia.</p>
            </div>
            <div class="store">
                <h3>Thrift Treasures</h3>
                <p>Eclectic mix of second-hand goods and unique finds.</p>
            </div>
        </div>
    </section>
    <section id="events" class="section">
        <h2>Upcoming Events</h2>
        <p>Join us for thrift swaps, vintage markets, and live music nights. Check back for schedules!</p>
        <ul>
            <li><strong>Thrift Swap Meet:</strong> Every first Saturday, 10 AM - 4 PM</li>
            <li><strong>Vintage Fashion Show:</strong> Monthly, last Sunday</li>
        </ul>
    </section>
    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Address: 123 Vintage Lane, Retro City, USA</p>
        <p>Phone: (123) 456-7890</p>
        <p>Email: info@thrftera.com</p>
    </section>
    <footer>
        <p>&copy; 2023 Thrift Era Shopping Mall. All rights reserved.</p>
    </footer>
    <script>
        // Simple smooth scroll for nav links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>
</body>
</html>
