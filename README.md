<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royal Feast | Luxury Catering Menu</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --gold: #d4af37;
            --dark-bg: #0f111a;
            --card-bg: #1a1e2e;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--dark-bg);
            color: #ffffff;
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url('https://images.unsplash.com/photo-1555244162-803834f70033?auto=format&fit=crop&w=1500&q=80');
            background-size: cover;
            background-position: center;
            height: 350px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            border-bottom: 4px solid var(--gold);
        }

        h1 { font-family: 'Playfair Display', serif; color: var(--gold); font-size: 3.5rem; margin: 0; }
        p.subtitle { font-size: 1.2rem; letter-spacing: 2px; text-transform: uppercase; }

        .container { max-width: 1200px; margin: 0 auto; padding: 50px 20px; }

        .section-title {
            font-family: 'Playfair Display', serif;
            text-align: center;
            color: var(--gold);
            font-size: 2.5rem;
            margin-bottom: 40px;
            position: relative;
        }

        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background: var(--gold);
            margin: 10px auto;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 60px;
        }

        .dish-card {
            background: var(--card-bg);
            border-radius: 20px;
            overflow: hidden;
            transition: transform 0.4s ease;
            border: 1px solid rgba(212, 175, 55, 0.1);
        }

        .dish-card:hover {
            transform: translateY(-10px);
            border-color: var(--gold);
        }

        .dish-img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-bottom: 3px solid var(--gold);
        }

        .dish-content { padding: 25px; }
        .dish-content h3 { color: var(--gold); margin: 0 0 10px 0; font-size: 1.5rem; }
        .dish-content p { color: #ccc; font-size: 0.95rem; }
        .tag {
            background: rgba(212, 175, 55, 0.2);
            color: var(--gold);
            padding: 5px 12px;
            border-radius: 50px;
            font-size: 0.8rem;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 40px;
            background: #000;
            border-top: 1px solid #333;
        }

        .contact-btn {
            background: var(--gold);
            color: #000;
            padding: 15px 40px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: 0.3s;
        }

        .contact-btn:hover { background: #fff; }
    </style>
</head>
<body>

    <header>
        <h1>Royal Feast</h1>
        <p class="subtitle">Luxury Catering Services</p>
    </header>

    <div class="container">
        
        <h2 class="section-title">Royal Starters</h2>
        <div class="menu-grid">
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1599487488170-d11ee9917509?auto=format&fit=crop&w=600&q=80" class="dish-img">
                <div class="dish-content">
                    <span class="tag">VEG</span>
                    <h3>Paneer Tikka Platter</h3>
                    <p>Classic tandoori marinated cottage cheese with mint chutney.</p>
                </div>
            </div>
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1626074353765-517a681e40be?auto=format&fit=crop&w=600&q=80" class="dish-img">
                <div class="dish-content">
                    <span class="tag">NON-VEG</span>
                    <h3>Afghani Chicken Tikka</h3>
                    <p>Juicy chicken pieces marinated in creamy yogurt and mild spices.</p>
                </div>
            </div>
        </div>

        <h2 class="section-title">Exquisite Main Course</h2>
        <div class="menu-grid">
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1631515243349-e0cb75fb8d3a?auto=format&fit=crop&w=600&q=80" class="dish-img">
                <div class="dish-content">
                    <span class="tag">VEG</span>
                    <h3>Shahi Paneer Butter Masala</h3>
                    <p>Rich cashew gravy with cottage cheese and fresh cream.</p>
                </div>
            </div>
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1563379091339-03b17af4a4f9?auto=format&fit=crop&w=600&q=80" class="dish-img">
                <div class="dish-content">
                    <span class="tag">NON-VEG</span>
                    <h3>Hyderabadi Dum Biryani</h3>
                    <p>Long grain basmati rice cooked with aromatic spices and tender meat.</p>
                </div>
            </div>
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1589119908995-c6837fa14848?auto=format&fit=crop&w=600&q=80" class="dish-img">
                <div class="dish-content">
                    <span class="tag">VEG</span>
                    <h3>Dal Makhani Bukhara</h3>
                    <p>Whole black lentils simmered for 24 hours with butter and spices.</p>
                </div>
            </div>
        </div>

        <h2 class="section-title">Heavenly Desserts</h2>
        <div class="menu-grid">
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1596797038530-2c39da81b491?auto=format&fit=crop&w=600&q=80" class="dish-img">
                <div class="dish-content">
                    <span class="tag">SWEET</span>
                    <h3>Gulab Jamun with Rabri</h3>
                    <p>Golden fried dumplings dipped in rose syrup, served with thick rabri.</p>
                </div>
            </div>
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1517427294546-5aa121f68e8a?auto=format&fit=crop&w=600&q=80" class="dish-img">
                <div class="dish-content">
                    <span class="tag">SWEET</span>
                    <h3>Moong Dal Halwa</h3>
                    <p>Traditional Rajasthani dessert made with pure desi ghee and nuts.</p>
                </div>
            </div>
        </div>

        <div style="text-align: center; margin-top: 40px;">
            <a href="https://wa.me/YOURNUMBER" class="contact-btn">Check Custom Packages</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Royal Feast Catering. All Rights Reserved.</p>
    </footer>

</body>
</html>.hero-video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  opacity: 0.35; /* luxury glass feel */
  z-index: 1;
  filter: blur(1px) brightness(0.9);
}

/* Overlay for premium look */
.hero::after {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(120deg, rgba(255,255,255,0.85), rgba(247,243,234,0.7));
  z-index: 1;
}<source src="https://cdn.coverr.co/videos/coverr-chef-cooking-in-kitchen-9716/1080p.mp4" type="video/mp4">
