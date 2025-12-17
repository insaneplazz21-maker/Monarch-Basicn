<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monarch - Premium Web Design Agency</title>
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background-color: #000000;
            color: #cccccc;
            line-height: 1.6;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }
        html {
            scroll-behavior: smooth;
        }

        /* Typography */
        h1, h2, h3 {
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        h1 {
            font-size: 4rem;
        }
        h2 {
            font-size: 2.5rem;
        }
        h3 {
            font-size: 1.8rem;
        }
        p {
            font-size: 1.1rem;
            margin-bottom: 1rem;
        }

        /* Layout */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            text-align: center;
        }
        section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 100px 0;
            position: relative;
        }
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease, transform 0.6s ease;
        }
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Home Section */
        #home {
            background: linear-gradient(135deg, #000000 0%, #333333 100%);
        }
        #home .container {
            position: relative;
        }
        #home h1 {
            margin-bottom: 20px;
            color: #ffffff;
        }
        #home h2 {
            margin-bottom: 40px;
            color: #aaaaaa;
        }
        .btn {
            background-color: #666666;
            color: #000000;
            padding: 15px 30px;
            border: none;
            border-radius: 25px;
            font-size: 1.2rem;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }
        .btn:hover {
            background-color: #999999;
            transform: scale(1.05);
        }

        /* About Section */
        #about {
            background-color: #111111;
        }
        #about .container {
            max-width: 800px;
        }
        #about p {
            margin-bottom: 30px;
        }
        .quote {
            font-style: italic;
            color: #888888;
            margin-top: 30px;
            font-size: 1.3rem;
        }

        /* Services Section */
        #services {
            background-color: #000000;
        }
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 50px;
        }
        .service-card {
            background-color: #222222;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.5);
        }
        .service-card h3 {
            margin-bottom: 15px;
            color: #ffffff;
        }
        .service-card p {
            color: #aaaaaa;
        }
        #services .quote {
            margin-top: 50px;
            grid-column: 1 / -1;
        }

        /* Contact Section */
        #contact {
            background-color: #111111;
        }
        #contact .container {
            max-width: 600px;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        input, textarea {
            background-color: #333333;
            border: 1px solid #555555;
            border-radius: 10px;
            padding: 15px;
            color: #cccccc;
            font-size: 1rem;
            transition: border-color 0.3s ease;
        }
        input:focus, textarea:focus {
            outline: none;
            border-color: #888888;
        }
        textarea {
            resize: vertical;
            min-height: 120px;
        }
        .btn-submit {
            align-self: center;
            width: 200px;
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.9);
            padding: 20px 0;
            z-index: 100;
            transition: background-color 0.3s ease;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 40px;
        }
        nav a {
            color: #cccccc;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #ffffff;
        }

        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            h2 {
                font-size: 1.8rem;
            }
            .services-grid {
                grid-template-columns: 1fr;
            }
            nav ul {
                flex-direction: column;
                gap: 20px;
            }
            section {
                padding: 50px 0;
            }
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home" class="fade-in">
        <div class="container">
            <h1>MONARCH</h1>
            <h2>Premium Web Design Agency</h2>
            <a href="#contact" class="btn">Get Started</a>
        </div>
    </section>

    <section id="about" class="fade-in">
        <div class="container">
            <h2>About Monarch</h2>
            <p>Monarch is a premium web design agency dedicated to crafting elegant, modern websites that elevate your brand. We specialize in clean, minimal designs with a luxurious touch, ensuring every project reflects sophistication and innovation.</p>
            <div class="quote">"The best way to predict the future is to create it." – Peter Drucker</div>
        </div>
    </section>

    <section id="services" class="fade-in">
        <div class="container">
            <h2>Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <h3>Web Design</h3>
                    <p>Custom websites tailored to your vision, blending aesthetics with functionality.</p>
                </div>
                <div class="service-card">
                    <h3>Branding</h3>
                    <p>Develop a unique brand identity that resonates with your audience.</p>
                </div>
                <div class="service-card">
                    <h3>UI/UX</h3>
                    <p>Intuitive user interfaces and experiences that engage and convert.</p>
                </div>
                <div class="service-card">
                    <h3>Landing Pages</h3>
                    <p>High-converting landing pages designed for maximum impact.</p>
                </div>
            </div>
            <div class="quote">"Design is not just what it looks like and feels like. Design is how it works." – Steve Jobs</div>
        </div>
    </section>

    <section id="contact" class="fade-in">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit" class="btn btn-submit">Send Message</button>
            </form>
            <div class="quote">"Innovation distinguishes between a leader and a follower." – Steve Jobs</div>
        </div>
    </section>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Fade-in animation on scroll
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        });

        document.querySelectorAll('.fade-in').forEach(el => {
            observer.observe(el);
        });
    </script>
</body>
</html>
