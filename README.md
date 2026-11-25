
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SK Production Official</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    background: #080808;
    color: white;
    font-family: Arial, sans-serif;
}

header {
    padding: 22px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #111;
    position: sticky;
    top: 0;
    z-index: 10;
    border-bottom: 1px solid #c9a227;
}

.logo {
    color: #d4af37;
    font-size: 25px;
    font-weight: bold;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-size: 14px;
}

nav a:hover {
    color: #d4af37;
}

.hero {
    min-height: 85vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 30px;
    background: linear-gradient(135deg,#080808,#24200f,#080808);
}

.hero h1 {
    font-size: clamp(38px, 7vw, 75px);
    color: #d4af37;
    margin-bottom: 20px;
}

.hero p {
    color: #ccc;
    font-size: 18px;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    padding: 14px 30px;
    background: #d4af37;
    color: black;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

section {
    padding: 80px 8%;
    text-align: center;
}

h2 {
    color: #d4af37;
    font-size: 35px;
    margin-bottom: 25px;
}

.about p {
    color: #ccc;
    line-height: 1.8;
    max-width: 750px;
    margin: auto;
}

.services {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
    gap: 20px;
}

.card {
    background: #171717;
    padding: 35px 20px;
    border: 1px solid #333;
    border-radius: 10px;
    transition: .3s;
}

.card:hover {
    transform: translateY(-8px);
    border-color: #d4af37;
}

.card h3 {
    color: #d4af37;
    margin-bottom: 15px;
}

.card p {
    color: #bbb;
    line-height: 1.6;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
    gap: 15px;
}

.gallery img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    border-radius: 8px;
    border: 1px solid #444;
}

.contact p {
    color: #ccc;
    margin: 15px;
}

footer {
    background: #111;
    padding: 25px;
    text-align: center;
    color: #aaa;
    border-top: 1px solid #d4af37;
}

@media(max-width:600px) {
    header {
        flex-direction: column;
        gap: 18px;
    }
    nav a {
        margin: 0 7px;
        font-size: 12px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">SK PRODUCTION</div>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero" id="home">
    <div>
        <h1>SK PRODUCTION</h1>
        <p>Creativity • Quality • Excellence</p>
        <a href="#about" class="btn">Explore More</a>
    </div>
</div>

<section class="about" id="about">
    <h2>About Us</h2>
    <p>
        Welcome to SK Production Official.
        We believe in creativity, innovation and quality.
        Our mission is to turn ideas into reality
        through professional production and creative work.
    </p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">

        <div class="card">
            <h3>Photography</h3>
            <p>Creative photography and visual storytelling.</p>
        </div>

        <div class="card">
            <h3>Video Production</h3>
            <p>Professional video creation and editing.</p>
        </div>

        <div class="card">
            <h3>Graphic Design</h3>
            <p>Modern and creative graphic designs.</p>
        </div>

        <div class="card">
            <h3>Digital Media</h3>
            <p>Creative digital content and media solutions.</p>
        </div>

    </div>
</section>

<section id="gallery">
    <h2>Our Gallery</h2>
    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1497366754035-f200968a6e72?w=600" alt="Creative workspace">
        <img src="https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?w=600" alt="Photography">
        <img src="https://images.unsplash.com/photo-1492619375914-88005aa9e8fb?w=600" alt="Camera">
    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>Have a project in mind? Let's connect.</p>
    <a href="mailto:your-email@example.com" class="btn">
        Email Us
    </a>
</section>

<footer>
    © 2026 SK Production Official. All Rights Reserved.
</footer>

</body>
</html>
