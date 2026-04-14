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

/* NAVBAR */
nav {
    display: flex;
    justify-content: space-between;
    padding: 30px 100px;
    font-size: 15px;
    letter-spacing: 1px;
}

nav a {
    text-decoration: none;
    color: #2b2b2b;
    margin-left: 50px;
}

/* HERO */
.hero {
    text-align: center;
    padding: 180px 20px;
}

.hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: 80px;
    font-weight: 400;
}

.hero p {
    margin-top: 20px;
    font-size: 20px;
    color: #777;
}

.button {
    margin-top: 40px;
    display: inline-block;
    padding: 14px 32px;
    border: 1px solid #ccc;
    text-decoration: none;
    color: #333;
}

/* SECTIONS */
section {
    padding: 120px 100px;
}

h2 {
    font-family: 'Playfair Display', serif;
    font-size: 42px;
    font-weight: 400;
    text-align: center;
    margin-bottom: 70px;
}

/* GALLERY */
.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 70px;
}

.card img {
    width: 100%;
    height: 450px;
    object-fit: cover;
}

.card h3 {
    font-family: 'Playfair Display', serif;
    font-size: 20px;
    margin-top: 15px;
}

.card p {
    color: #777;
    font-size: 16px;
}

/* ABOUT */
.about {
    max-width: 700px;
    margin: auto;
    text-align: center;
    font-size: 18px;
    line-height: 1.9;
    color: #555;
}

/* CONTACT */
.contact {
    text-align: center;
}

.contact h2 {
    font-size: 40px;
}

.contact p {
    font-size: 18px;
}

.contact a {
    margin: 0 20px;
    text-decoration: none;
    color: #333;
    font-size: 16px;
}

/* FOOTER */
footer {
    display: flex;
    justify-content: space-between;
    padding: 50px 100px;
    font-size: 14px;
    color: #777;
}
</style>

</head>

<body>

<!-- NAVBAR -->

<nav>
    <div><a href="#home">Sketchora</a></div>
    <div>
        <a href="#collection">COLLECTION</a>
        <a href="#about">ABOUT</a>
        <a href="#contact">CONTACT</a>
    </div>
</nav>

<!-- HERO -->

<section id="home" class="hero">
    <h1>Sketchora Studio</h1>
    <p>Art that feels like a memory</p>
    <a href="#collection" class="button">VIEW COLLECTION ↓</a>
</section>

<!-- COLLECTION -->

<section id="collection">
    <h2>Original Works</h2>

```
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

    <div class="card">
        <img src="art4.jpg">
        <h3>Quiet Reflection</h3>
        <p>₹14,200</p>
    </div>

    <div class="card">
        <img src="art5.jpg">
        <h3>Golden Spirit</h3>
        <p>₹11,000</p>
    </div>

    <div class="card">
        <img src="art6.jpg">
        <h3>Serene Grace</h3>
        <p>₹22,000</p>
    </div>
</div>
```

</section>

<!-- ABOUT -->

<section id="about">
    <h2>The Studio</h2>
    <div class="about">
        <p>
            Sketchora Studio is a quiet space where art finds its voice. Each piece begins with a feeling —
            a fleeting moment, a half-remembered dream, the way light falls through a window at dusk.
        </p>
        <p>
            We believe art should breathe. It should whisper rather than shout, invite rather than demand.
            Every brushstroke carries intention, every color tells a story waiting to be remembered.
        </p>
    </div>
</section>

<!-- CONTACT -->

<section id="contact" class="contact">
    <h2>Let's Connect</h2>
    <p>Interested in a piece? Reach out.</p>

```
<a href="#">Instagram-@sketchora.studio</a>
<a href="mailto:">Email-2012aadyaagarwal@gmail.com</a>
```

</section>

<!-- FOOTER -->

<footer>
    <div>Sketchora Studio</div>
    <div>© 2026 Sketchora Studio. All rights reserved.</div>
</footer>

</body>
</html>
