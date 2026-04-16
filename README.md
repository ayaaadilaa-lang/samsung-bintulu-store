<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Samsung The Spring Bintulu</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #000;
    color: #fff;
}

nav {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(0,0,0,0.85);
    backdrop-filter: blur(10px);
    display: flex;
    justify-content: center;
    gap: 15px;
    padding: 12px;
    font-size: 13px;
}

nav a {
    color: #fff;
    text-decoration: none;
    opacity: 0.8;
}

.hero {
    height: 90vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    background: linear-gradient(to bottom, rgba(0,0,0,0.5), #000),
    url('https://images.samsung.com/is/image/samsung/assets/global/galaxy-s24-ultra.jpg');
    background-size: cover;
    background-position: center;
    padding: 20px;
}

.hero h1 { font-size: 38px; }
.hero p { color: #ccc; }

.btn {
    margin-top: 15px;
    padding: 12px 22px;
    background: #1428A0;
    border-radius: 30px;
    color: #fff;
    text-decoration: none;
}

section {
    padding: 80px 20px;
    text-align: center;
}

h2 { margin-bottom: 25px; }

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 18px;
}

.card {
    background: #111;
    padding: 14px;
    border-radius: 15px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-6px);
}

.card img {
    width: 100%;
    border-radius: 10px;
}

/* PLACEHOLDER STYLE */
.placeholder {
    width: 100%;
    height: 180px;
    border-radius: 10px;
    background: linear-gradient(135deg, #1a1a1a, #333);
    display: flex;
    align-items: center;
    justify-content: center;
    color: #777;
    font-size: 13px;
}

.cat { color: #aaa; font-size: 12px; }

footer {
    text-align: center;
    padding: 25px;
    color: #666;
    font-size: 12px;
}
</style>

</head>

<body>

<nav>
<a href="#phone">Phone</a>
<a href="#tablet">Tablet</a>
<a href="#watch">Watch</a>
<a href="#buds">Buds</a>
</nav>

<div class="hero">
<h1>Samsung The Spring Bintulu</h1>
<p>Official Galaxy Catalog • Premium Experience Store</p>

<a class="btn" href="https://wa.me/6086422327">💬 WhatsApp</a>
</div>

<!-- PHONE -->
<section id="phone">
<h2>📱 Smartphones</h2>

<div class="grid">

<div class="card">
<img src="https://images.samsung.com/is/image/samsung/p6pim/my/galaxy-s24-ultra.jpg">
<h3>S26 Series</h3>
<div class="placeholder">Official image coming soon</div>
</div>

<div class="card">
<img src="https://images.samsung.com/is/image/samsung/p6pim/my/galaxy-s24.jpg">
<h3>S25 Series</h3>
<div class="placeholder">Flagship Series</div>
</div>

<div class="card">
<div class="placeholder">Z Fold 7 Image Soon</div>
<h3>Z Fold 7</h3>
</div>

<div class="card">
<div class="placeholder">Z Flip 7 Image Soon</div>
<h3>Z Flip 7</h3>
</div>

<div class="card">
<div class="placeholder">Z Flip 7 FE Image Soon</div>
<h3>Z Flip 7 FE</h3>
</div>

<div class="card"><div class="placeholder">A56 Image</div><h3>A56</h3></div>
<div class="card"><div class="placeholder">A57 Image</div><h3>A57</h3></div>
<div class="card"><div class="placeholder">A26 Image</div><h3>A26</h3></div>
<div class="card"><div class="placeholder">A27 Image</div><h3>A27</h3></div>
<div class="card"><div class="placeholder">A37 Image</div><h3>A37</h3></div>
<div class="card"><div class="placeholder">A07 Image</div><h3>A07</h3></div>
<div class="card"><div class="placeholder">A07 5G Image</div><h3>A07 5G</h3></div>
<div class="card"><div class="placeholder">A17 5G Image</div><h3>A17 5G</h3></div>

</div>
</section>

<!-- TABLET -->
<section id="tablet">
<h2>📟 Tablets</h2>
<div class="grid">

<div class="card"><div class="placeholder">Tab S11 Series</div></div>
<div class="card"><div class="placeholder">Tab S10 Series</div></div>
<div class="card"><div class="placeholder">Tab A11 Series</div></div>

</div>
</section>

<!-- WATCH -->
<section id="watch">
<h2>⌚ Watch</h2>
<div class="grid">

<div class="card"><div class="placeholder">Watch 8</div></div>
<div class="card"><div class="placeholder">Watch 8 Classic</div></div>
<div class="card"><div class="placeholder">Watch Ultra 2025</div></div>

</div>
</section>

<!-- BUDS -->
<section id="buds">
<h2>🎧 Buds</h2>
<div class="grid">

<div class="card"><div class="placeholder">Buds 3 Pro</div></div>
<div class="card"><div class="placeholder">Buds 3 FE</div></div>
<div class="card"><div class="placeholder">Buds 4</div></div>
<div class="card"><div class="placeholder">Buds 4 Pro</div></div>
<div class="card"><div class="placeholder">Buds Core</div></div>

</div>
</section>

<footer>
© 2026 Samsung The Spring Bintulu • Official Catalog Experience
</footer>

</body>
</html>
