# CHOTELAL-caterers-
catering website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CLCY Caterers</title>

<style>
:root{
  --matcha:#7a9e7e;
  --honey:#caa85c;
  --milky:#f7f3ea;
}

body{
  margin:0;
  font-family:Arial;
  background:#fff;
}

/* NAV */
.nav{
  padding:15px;
  background:var(--matcha);
  color:#fff;
  text-align:center;
  font-size:22px;
}

/* HERO */
.hero{
  padding:80px 20px;
  text-align:center;
  background:var(--milky);
}

.btn{
  padding:12px 25px;
  background:var(--honey);
  color:white;
  text-decoration:none;
  border-radius:20px;
}

/* SECTION */
.section{
  padding:40px 20px;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:20px;
}

/* CARD */
.card{
  background:#f9f9f9;
  border-radius:10px;
  overflow:hidden;
}

.card img{
  width:100%;
  height:160px;
  object-fit:cover;
}

.card h4{
  padding:10px;
}
</style>
</head>

<body>

<div class="nav">CLCY Caterers</div>

<div class="hero">
  <h1>Luxury Catering Experience</h1>
  <p>Veg & Jain Catering for Weddings</p>
  <br>
  <a href="https://wa.me/91XXXXXXXXXX" class="btn">Book Now</a>
</div>

<!-- MENU -->
<div class="section">
<h2>Our Menu</h2>

<div class="grid">

<!-- EDIT YAHAN SE KARNA -->
<div class="card">
<img src="https://source.unsplash.com/600x400/?shahi,paneer,indian">
<h4>Shahi Paneer</h4>
</div>

<div class="card">
<img src="https://source.unsplash.com/600x400/?malai,kofta">
<h4>Malai Kofta</h4>
</div>

<div class="card">
<img src="https://source.unsplash.com/600x400/?palak,paneer">
<h4>Palak Paneer</h4>
</div>

<div class="card">
<img src="https://source.unsplash.com/600x400/?jeera,aloo">
<h4>Jeera Aloo</h4>
</div>

<div class="card">
<img src="https://source.unsplash.com/600x400/?bhindi,indian">
<h4>Bhindi Do Pyaza</h4>
</div>

<div class="card">
<img src="https://source.unsplash.com/600x400/?baingan,bharta">
<h4>Baingan Bharta</h4>
</div>

</div>
</div>

<!-- GALLERY -->
<div class="section">
<h2>Our Events</h2>

<div class="grid">

<div class="card">
<img src="https://source.unsplash.com/600x400/?indian,wedding,food">
</div>

<div class="card">
<img src="https://source.unsplash.com/600x400/?buffet,setup">
</div>

<div class="card">
<img src="https://source.unsplash.com/600x400/?catering,event">
</div>

</div>
</div>

<!-- CONTACT -->
<div class="section">
<h2>Contact</h2>
<p>📞 91XXXXXXXXXX</p>
</div>

</body>
</html> 
