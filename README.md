<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sketchora Studio</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

<style>
:root{
    --bg:#f4ede4;
    --text:#2b2622;
    --muted:#7a736c;
    --accent:#a06a45;
    --card:#ffffff;
    --border:#e8ddd2;
}

*{
    box-sizing:border-box;
}

body{
    margin:0;
    font-family:'Inter',sans-serif;
    background:var(--bg);
    color:var(--text);
}

/* NAV */
nav{
    display:flex;
    justify-content:space-between;
    padding:25px 70px;
}

nav a{
    text-decoration:none;
    color:var(--text);
    margin-left:35px;
    font-size:13px;
    letter-spacing:1px;
    transition:0.2s;
}

nav a:hover{
    color:var(--accent);
}

/* HERO */
.hero{
    text-align:center;
    padding:160px 20px 110px;
}

.hero h1{
    font-family:'Playfair Display',serif;
    font-size:86px;
    font-weight:400;
    margin:0;
}

.hero p{
    margin-top:15px;
    color:var(--muted);
    font-size:18px;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:13px 30px;
    border:1px solid var(--border);
    text-decoration:none;
    color:var(--text);
    transition:0.3s;
}

.btn:hover{
    background:var(--accent);
    color:white;
    border-color:var(--accent);
}

/* SECTIONS */
section{
    padding:100px 70px;
}

h2{
    text-align:center;
    font-family:'Playfair Display',serif;
    font-size:44px;
    font-weight:400;
    margin-bottom:55px;
}

/* GALLERY */
.gallery{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:28px;
}

.card{
    background:var(--card);
    border:1px solid var(--border);
    overflow:hidden;
    transition:0.25s;
}

.card:hover{
    transform:translateY(-12px);
    box-shadow:0 18px 40px rgba(0,0,0,0.08);
}

.card img{
    width:100%;
    aspect-ratio:1/1;
    object-fit:cover;
}

.card h3{
    font-family:'Playfair Display',serif;
    margin:12px 14px 4px;
    font-size:20px;
}

.card p{
    margin:0 14px 14px;
    color:var(--muted);
}

/* ABOUT */
.about{
    max-width:720px;
    margin:auto;
    text-align:center;
    color:var(--muted);
    line-height:1.9;
    font-size:18px;
}

/* CONTACT */
.contact{
    text-align:center;
}

.contact a{
    display:block;
    margin-top:10px;
    text-decoration:none;
    color:var(--text);
}

.contact a:hover{
    color:var(--accent);
}

/* FOOTER */
footer{
    display:flex;
    justify-content:space-between;
    padding:40px 70px;
    border-top:1px solid var(--border);
    color:var(--muted);
    font-size:13px;
}

/* RESPONSIVE */
@media(max-width:900px){
    .gallery{
        grid-template-columns:1fr;
    }

    .hero h1{
        font-size:52px;
    }

    nav{
        flex-direction:column;
        gap:10px;
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
    <p>Earthy tones. Quiet emotion. Minimal stories.</p>
    <a href="#collection" class="btn">Explore Work</a>
</section>

<section id="collection">
    <h2>Selected Pieces</h2>

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
        Sketchora Studio is built on calm visuals and earthy tones.
        Every piece is designed to feel soft, intentional, and quietly emotional.
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <div class="contact">
        <a href="#">Instagram: @sketchora.studio</a>
        <a href="mailto:2012aadyaagarwal@gmail.com">Email</a>
    </div>
</section>

<footer>
    <div>Sketchora Studio</div>
    <div>© 2026 All rights reserved</div>
</footer>

</body>
</html>
