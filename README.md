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

.nav{
  padding:15px;
  background:var(--matcha);
  color:#fff;
  text-align:center;
  font-size:22px;
}

.section{
  padding:40px 20px;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:20px;
}

.card{
  background:var(--milky);
  border-radius:12px;
  overflow:hidden;
  text-align:center;
  transition:0.3s;
}
.card:hover{
  transform:translateY(-8px);
}

.card img{
  width:100%;
  height:180px;
  object-fit:cover;
}

h4{
  padding:10px;
}
</style>
</head>

<body>

<div class="nav">CLCY Caterers</div>

<div class="section">
<h2>Our Menu</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1601050690597-df0568f70950">
<h4>Shahi Paneer</h4>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1631452180519-c014fe946bc7">
<h4>Malai Kofta</h4>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1628294896516-5d0d1c6d93d2">
<h4>Palak Paneer</h4>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1596797038530-2c107aa5cfe8">
<h4>Jeera Aloo</h4>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1666001094190-9a9cfa0b1d1f">
<h4>Bhindi Do Pyaza</h4>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1630409351217-bc4fa6422075">
<h4>Baingan Bharta</h4>
</div>

</div>
</div>

</body>
</html>
