<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Royal Feast | Premium Catering Menu</title>
    <style>
        :root {
            --gold: #d4af37;
            --dark: #0b0d17;
            --card-bg: #1a1c23;
        }

        body {
            font-family: 'Playfair Display', serif;
            margin: 0;
            background-color: var(--dark);
            color: white;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1514362545857-3bc16c4c7d1b?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            border-bottom: 3px solid var(--gold);
        }

        h1 { color: var(--gold); font-size: 3rem; margin-bottom: 10px; }
        
        .menu-container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 20px;
        }

        .section-title {
            text-align: center;
            color: var(--gold);
            font-size: 2rem;
            margin-top: 50px;
            border-bottom: 1px solid #333;
            padding-bottom: 10px;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }

        .dish-card {
            background: var(--card-bg);
            border-radius: 15px;
            overflow: hidden;
            border: 1px solid #333;
            transition: 0.4s;
        }

        .dish-card:hover {
            transform: translateY(-10px);
            border-color: var(--gold);
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.2);
        }

        .dish-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-bottom: 2px solid var(--gold);
        }

        .dish-info { padding: 20px; }
        .dish-info h3 { color: var(--gold); margin-top: 0; }
        .price { color: #aaa; font-style: italic; }

        .btn-order {
            display: block;
            width: 100%;
            padding: 12px;
            background: var(--gold);
            color: black;
            text-align: center;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            margin-top: 15px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Royal Feast Catering</h1>
        <p>Exquisite Flavors for Your Grand Celebrations</p>
    </header>

    <div class="menu-container">
        
        <h2 class="section-title">✨ Signature Starters</h2>
        <div class="menu-grid">
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1601050638917-3f887b40d04c?auto=format&fit=crop&w=500&q=80" alt="Paneer Tikka" class="dish-img">
                <div class="dish-info">
                    <h3>Paneer Malai Tikka</h3>
                    <p>Creamy marinated cottage cheese grilled to perfection in tandoor.</p>
                    <span class="price">Premium Selection</span>
                </div>
            </div>

            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1599487488170-d11ee9917509?auto=format&fit=crop&w=500&q=80" alt="Hara Bhara Kabab" class="dish-img">
                <div class="dish-info">
                    <h3>Hara Bhara Kabab</h3>
                    <p>Classic spinach and green pea patties with traditional spices.</p>
                </div>
            </div>
        </div>

        <h2 class="section-title">🥘 Royal Main Course</h2>
        <div class="menu-grid">
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1546833999-b9f581a1996d?auto=format&fit=crop&w=500&q=80" alt="Dal Makhani" class="dish-img">
                <div class="dish-info">
                    <h3>Signature Dal Makhani</h3>
                    <p>Slow-cooked black lentils simmered overnight with butter and cream.</p>
                </div>
            </div>

            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1631515243349-e0cb75fb8d3a?auto=format&fit=crop&w=500&q=80" alt="Shahi Paneer" class="dish-img">
                <div class="dish-info">
                    <h3>Shahi Paneer Masala</h3>
                    <p>Rich cashew-based gravy with soft cubes of premium cottage cheese.</p>
                </div>
            </div>
        </div>

        <h2 class="section-title">🍰 Sweet Indulgence</h2>
        <div class="menu-grid">
            <div class="dish-card">
                <img src="https://images.unsplash.com/photo-1589119908995-c6837fa14848?auto=format&fit=crop&w=500&q=80" alt="Gulab Jamun" class="dish-img">
                <div class="dish-info">
                    <h3>Gulab Jamun with Rabri</h3>
                    <p>Warm dumplings soaked in syrup, served with chilled thick milk.</p>
                </div>
            </div>
        </div>

        <div style="text-align: center; margin-top: 50px;">
            <a href="mailto:contact@yourcatering.com" class="btn-order">Get Custom Quote for Your Event</a>
        </div>
    </div>

</body>
</html>
