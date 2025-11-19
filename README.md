# bishops-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bishop’s Recycling and Waste-Management Limited provides licensed garbage disposal, recycling, and waste solutions in Kingston, St. Andrew & St. Catherine.">
    <title>Bishop’s Recycling and Waste-Management Limited | Waste Management Jamaica</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* Basic Reset */
        * { margin:0; padding:0; box-sizing: border-box; font-family: Arial, sans-serif; }
        body { line-height: 1.6; color: #333; }
        a { text-decoration: none; color: #fff; }
        header { background: #4CAF50; color: #fff; padding: 20px 0; text-align: center; }
        nav ul { list-style: none; display: flex; justify-content: center; gap: 20px; }
        nav ul li { display: inline; }
        .container { width: 90%; max-width: 1200px; margin: 20px auto; }
        .hero { background: url('hero.jpg') no-repeat center center/cover; color: #fff; padding: 100px 20px; text-align: center; }
        .hero h1 { font-size: 2.5rem; margin-bottom: 20px; }
        .btn { display: inline-block; background: #4CAF50; padding: 10px 20px; margin-top: 10px; border-radius: 5px; }
        section { margin-bottom: 50px; }
        h2 { color: #4CAF50; margin-bottom: 10px; }
        footer { background: #333; color: #fff; text-align: center; padding: 20px 0; }
        .service-cards { display: flex; flex-wrap: wrap; gap: 20px; justify-content: space-between; }
        .card { background: #f4f4f4; padding: 20px; flex: 1 1 calc(25% - 20px); border-radius: 5px; }
        form input, form textarea { width: 100%; padding: 10px; margin-bottom: 10px; border-radius: 5px; border: 1px solid #ccc; }
        form button { background: #4CAF50; color: #fff; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; }
        @media(max-width: 768px){ .service-cards { flex-direction: column; } }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Bishop’s Recycling and Waste-Management Limited</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <h1>Efficient, Licensed Waste Management Services</h1>
        <p>Providing garbage disposal, recycling, and waste solutions in Kingston, St. Andrew & St. Catherine.</p>
        <a href="#contact" class="btn">Get a Free Quote</a>
        <a href="#services" class="btn">Our Services</a>
    </section>

    <!-- About Section -->
    <section id="about" class="container">
        <h2>About Us</h2>
        <p>Bishop’s Recycling and Waste-Management Limited is a licensed waste disposal company dedicated to eco-friendly, cost-efficient, and reliable garbage collection and recycling services for residential, commercial, and industrial clients.</p>
        <h3>Our Mission</h3>
        <p>To provide safe, reliable, and eco-friendly waste management and recycling services that help communities and businesses reduce their environmental impact.</p>
        <h3>Our Vision</h3>
        <p>To be the leading licensed waste disposal and recycling company in Jamaica, recognized for efficiency, sustainability, and customer satisfaction.</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="container">
        <h2>Our Services</h2>
        <div class="service-cards">
            <div class="card">
                <h3>Industrial & Commercial Waste</h3>
                <p>Scheduled pickups, bulk disposal, and recycling services for factories, offices, and retail businesses.</p>
            </div>
            <div class="card">
                <h3>Residential Waste</h3>
                <p>On-site bins, regular pickups, furniture and bulk debris removal for homes and apartment complexes.</p>
            </div>
            <div class="card">
                <h3>Construction & Development Waste</h3>
                <p>Debris removal, temporary dumpsters, and disposal of wood, metals, and concrete.</p>
            </div>
            <div class="card">
                <h3>Recycling Services</h3>
                <p>Cardboard, paper, plastics, and other eco-friendly recycling solutions tailored to your needs.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <p>Call or email us to schedule a pickup or request a free quote.</p>
        <form>
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <input type="tel" name="phone" placeholder="Your Phone">
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Bishop’s Recycling and Waste-Management Limited. All Rights Reserved.</p>
        <p>Serving Kingston, St. Andrew & St. Catherine, Jamaica</p>
    </footer>
</body>
</html>
