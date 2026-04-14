# Sketchora-Studio
Sketchora Studio is a curated digital art portfolio showcasing original works that explore emotion, memory, and visual storytelling through minimalist design.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sketchora Studio</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500&family=Inter:wght@300;400&display=swap" rel="stylesheet">

<style>
html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    background: #f3efe9;
    color: #2b2b2b;
    font-family: 'Inter', sans-serif;
}

/* NAV */
nav {
    display: flex;
    justify-content: space-between;
    padding: 30px 60px;
}

nav a {
    text-decoration: none;
    color: #2b2b2b;
    margin-left: 30px;
}

/* HERO */
.hero {
    text-align: center;
    padding: 150px 20px;
}

.hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: 70px;
    font-weight: 400;
}

.hero p {
    color: #777;
    font-size: 18px;
}

.button {
    display: inline-block;
    margin-top: 30px;
    padding: 12px 28px;
    border: 1px solid #ccc;
    text-decoration: none;
    color: #333;
}

/* SECTIONS */
section {
    padding: 100px 60px;
}

h2 {
    font-family: 'Playfair Display', serif;
    font-size: 38px;
    text-align: center;
}

/* GALLERY */
.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 40px;
    margin-top: 50px;
}

.card img {
    width: 100%;
    height: 350px;
    object-fit: cover;
}

.card h3 {
    font-family: 'Playfair Display', serif;
    margin-top: 10px;
}

.card p {
    color: #777;
}

/* ABOUT */
.about {
    max-width: 700px;
    margin: auto;
    text-align: center;
    line-height: 1.8;
    color: #555;
}

/* CONTACT */
.contact {
    text-align: center;
}

.contact a {
    display: block;
    margin-top: 10px;
    color: #333;
    text-decoration: none;
}

/* FOOTER */
footer {
    display: flex;
    justify-content: space-between;
    padding: 40px 60px;
    color: #777;
    font-size: 14px;
}
</style>

</head>

<body>

<nav>
    <div><a href="#home">Sketchora</a></div>
    <div>
        <a href="#collection">COLLECTION</a>
        <a href="#about">ABOUT</a>
        <a href="#contact">CONTACT</a>
    </div>
</nav>

<section id="home" class="hero">
    <h1>Sketchora Studio</h1>
    <p>Art that feels like a memory</p>
    <a href="#collection" class="button">VIEW COLLECTION</a>
</section>

<section id="collection">
    <h2>Original Works</h2>

    <div class="gallery">
        <div class="card">
            <img src="art1.jpg">
            <h3>Emerald Whispers</h3>
            <p>₹12,500</p>
        </div>

        <div class="card">
            <img src="art2.jpg">
            <h3>Soft Silhouette</h3>
            <p>₹9,800</p>
        </div>

        <div class="card">
            <img src="art3.jpg">
            <h3>Freckled Dawn</h3>
            <p>₹18,500</p>
        </div>
    </div>
</section>

<section id="about">
    <h2>The Studio</h2>
    <div class="about">
        <p>Sketchora Studio is a quiet space where art begins with feeling.</p>
        <p>Every piece is built from emotion, light, and memory.</p>
    </div>
</section>

<section id="contact">
    <h2>Let's Connect</h2>
    <p>Interested in a piece? Reach out.</p>

    <a href="#">Instagram: @sketchora.studio</a>
    <a href="mailto:2012aadyaagarwal@gmail.com">Email</a>
</section>

<footer>
    <div>Sketchora Studio</div>
    <div>© 2026 All rights reserved</div>
</footer>

</body>
</html>
