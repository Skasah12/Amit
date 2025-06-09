<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amit Freelancer | Tempting Solutions</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
        }
        header {
            background: linear-gradient(135deg, #6e48aa 0%, #9d50bb 100%);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        .container {
            width: 85%;
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
        }
        nav {
            display: flex;
            justify-content: space-between;
            padding: 1rem 0;
        }
        nav ul {
            display: flex;
            list-style: none;
        }
        nav ul li {
            padding: 0 1rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
        }
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        .hero p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        .cta-button {
            display: inline-block;
            background: #ff7e5f;
            color: white;
            padding: 0.8rem 2rem;
            margin-top: 1rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        .cta-button:hover {
            background: #f45c43;
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        section {
            padding: 3rem 0;
        }
        .services {
            background: white;
        }
        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .service-card {
            background: #fff;
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-10px);
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">Amit Freelancer</div>
                <ul>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#testimonials">Testimonials</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="hero">
                <h1>Tempted by Quality Work?</h1>
                <p>Professional freelance services that will make you say "Yes!"</p>
                <a href="#contact" class="cta-button">Hire Me Today</a>
            </div>
        </div>
    </header>

    <section id="services" class="services">
        <div class="container">
            <h2>Irresistible Services</h2>
            <div class="service-grid">
                <div class="service-card">
                    <h3>Web Development</h3>
                    <p>Custom websites that look great and perform even better. Built with the latest technologies to ensure speed and reliability.</p>
                </div>
                <div class="service-card">
                    <h3>UI/UX Design</h3>
                    <p>Beautiful interfaces that users love. Intuitive designs that increase engagement and conversion rates.</p>
                </div>
                <div class="service-card">
                    <h3>Digital Marketing</h3>
                    <p>Strategies that get results. From SEO to social media, I'll help your business get noticed.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Tempting Portfolio</h2>
            <p>Here are some of my recent projects that clients couldn't resist...</p>
            <!-- Portfolio items would go here -->
        </div>
    </section>

    <section id="testimonials" style="background: #f1f1f1;">
        <div class="container">
            <h2>Client Temptations</h2>
            <p>What my clients say about working with me...</p>
            <!-- Testimonials would go here -->
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Too Tempting to Resist?</h2>
            <p>Let's discuss how I can help with your project.</p>
            <!-- Contact form would go here -->
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 Amit Freelancer. All rights reserved.</p>
        </div>
    </footer>
</body>
</html># Amit