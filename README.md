<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Star Cricket Academy</title>
    <style>
        /* CSS Styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        nav {
            background-color: #111;
            display: flex;
            justify-content: center;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-weight: bold;
        }
        nav a:hover {
            color: #f39c12;
        }
        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        h2 {
            color: #2c5364;
            border-bottom: 2px solid #f39c12;
            padding-bottom: 5px;
        }
        .facilities, .batches {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .card {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 5px;
            border-left: 5px solid #f39c12;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }
        .card h3 {
            margin-top: 0;
        }
        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
            font-size: 0.9rem;
        }
        .contact-btn {
            display: inline-block;
            background-color: #f39c12;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 15px;
        }
        .contact-btn:hover {
            background-color: #e67e22;
        }
    </style>
</head>
<body>

    <header>
        <h1>🏏 STAR CRICKET ACADEMY 🏏</h1>
        <p>Apne Cricket Ke Sapne Ko Sach Karein | Professional Coaching & Training</p>
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#facilities">Facilities</a>
        <a href="#batches">Timings & Fees</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        
        <section id="about">
            <h2>Hamare Bare Mein</h2>
            <p>Welcome to Star Cricket Academy! Hum young talents ko train karke unhe agla cricket star banane ke liye commit hain. Hamare paas experienced coaches aur behtareen training grounds hain.</p>
        </section>

        <section id="facilities">
            <h2>Academy Ki Facilities</h2>
            <div class="facilities">
                <div class="card">
                    <h3>Turf & Betting Wickets</h3>
                    <p>Net practice ke liye turf aur cement pitches available hain.</p>
                </div>
                <div class="card">
                    <h3>Bowling Machine</h3>
                    <p>Modern bowling machines jisse aap har speed aur swing par practice kar sakein.</p>
                </div>
                <div class="card">
                    <h3>Video Analysis</h3>
                    <p>Aapki batting aur bowling technique ko sudharne ke liye video analysis.</p>
                </div>
            </div>
        </section>

        <section id="batches">
            <h2>Timings aur Fees</h2>
            <div class="batches">
                <div class="card">
                    <h3>Morning Batch</h3>
                    <p><b>Time:</b> 6:00 AM - 9:00 AM</p>
                    <p><b>Age Group:</b> 8 se 18 saal</p>
                </div>
                <div class="card">
                    <h3>Evening Batch</h3>
                    <p><b>Time:</b> 4:00 PM - 7:00 PM</p>
                    <p><b>Age Group:</b> Sabhi ke liye</p>
                </div>
            </div>
            <p style="margin-top: 15px;"><b>Monthly Fee:</b> ₹1,500 / Mahina</p>
        </section>

        <section id="contact">
            <h2>Humse Sampark Karein (Contact Us)</h2>
            <p>📍 <b>Address:</b> Stadium Road, Near Sports Complex, Aapka City</p>
            <p>📞 <b>Phone:</b> +91 98765 43210</p>
            <p>✉️ <b>Email:</b> info@starcricket.com</p>
            <a href="https://wa.me/919876543210" target="_blank" class="contact-btn">WhatsApp Par Baat Karein</a>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 Star Cricket Academy. All Rights Reserved.</p>
    </footer>

</body>
</html>
