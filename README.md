<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sketchora Studio</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

<style>
:root {
    --bg: #f5efe6;
    --text: #2e2a27;
    --muted: #7b746d;
    --accent: #9b6b43;
    --card: #ffffff;
    --border: #e7dccf;
}

body {
    margin: 0;
    font-family: 'Inter', sans-serif;
    background: var(--bg);
    color: var(--text);
}

/* NAV */
nav {
    display: flex;
    justify-content: space-between;
    padding: 25px 60px;
}

nav a {
    text-decoration: none;
    color: var(--text);
    margin-left: 30px;
    font-size: 14px;
    letter-spacing: 1px;
}

nav a:hover {
    color: var(--accent);
}

/* HERO */
.hero {
    text-align: center;
    padding: 150px 20px 100px;
}

.hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: 80px;
    margin: 0;
    font-weight: 400;
}

.hero p {
    color: var(--muted);
    font-size: 18px;
    margin-top: 15px;
}

.btn {
    display: inline-block;
    margin-top: 30px;
    padding: 12px 28px;
    border: 1px solid var(--border);
    text-decoration: none;
    color: var(--text);
    transition: 0.3s;
}

.btn:hover {
    background: var(--accent);
    color: white;
}

/* SECTIONS */
section {
    padding: 100px 60px;
}

h2 {
    text-align: center;
    font-family: 'Playfair Display', serif;
    font-size: 42px;
    font-weight: 400;
    margin-bottom: 50px;
}

/* GALLERY */
.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
}

.card {
    background: var(--card);
    border: 1px solid var(--border);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.08);
}

.card img {
    width: 100%;
    aspect-ratio: 1/1;
    object-fit: cover;
}

.card h3 {
    font-family: 'Playfair Display', serif;
    margin: 12px 15px 5px;
}

.card p {
    margin: 0 15px 15px;
    color: var(--muted);
}

/* ABOUT */
.about {
    max-width: 700px;
    margin: auto;
    text-align: center;
    line-height: 1.8;
    color: var(--muted);
}

/* CONTACT */
.contact {
    text-align: center;
}

.contact a {
    display: block;
    margin-top: 10px;
    color: var(--text);
    text-decoration: none;
}

.contact a:hover {
    color: var(--accent);
}

/* FOOTER */
footer {
    display: flex;
    justify-content: space-between;
    padding: 40px 60px;
    color: var(--muted);
    font-size: 13px;
    border-top: 1px solid var(--border);
}

/* MOBILE */
@media (max-width: 900px) {
    .gallery {
        grid-template-columns: 1fr;
    }

    .hero h1 {
        font-size: 50px;
    }

    nav {
        flex-direction: column;
        gap: 10px;
    }
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
    <p>Soft art. Quiet stories. Earthy memories.</p>
    <a class="btn" href="#collection">View Collection</a>
</section>

<section id="collection">
    <h2>Selected Works</h2>

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
    <h2>About</h2>
    <div class="about">
        Sketchora Studio creates calm, earthy visuals inspired by light, texture, and emotion.
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <div class="contact">
        <a href="#">Instagram: @sketchora.studio</a>
        <a href="mailto:2012aadyaagarwal@gmail.com">Email Us</a>
    </div>
</section>

<footer>
    <div>Sketchora Studio</div>
    <div>© 2026</div>
</footer>

</body>
</html>
