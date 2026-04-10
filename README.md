<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bubbly K Creations</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Poppins:wght@300;500&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: black;
    color: white;
}

/* HERO */
.hero {
    height: 90vh;
    background: linear-gradient(rgba(0,0,0,0.6), black),
    url('PASTE-YOUR-BEST-PHOTO-LINK-HERE');
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: 3.5em;
    background: linear-gradient(45deg, gold, #b76e79);
    -webkit-background-clip: text;
    color: transparent;
}

.btn {
    background: linear-gradient(45deg, gold, #b76e79);
    padding: 12px 25px;
    border: none;
    color: black;
    font-weight: bold;
    cursor: pointer;
}

/* SECTIONS */
.section {
    padding: 60px 20px;
    text-align: center;
}

.https://imgur.com/a/ckQi604
}

.gallery img {
    width: 100%;
    border-radius: 12px;
    transition: 0.3s;
}

.gallery img:hover {
    transform: scale(1.05);
}

/* PAYMENT BOX */
.payment-box {
    margin-top: 30px;
    padding: 25px;
    border: 1px solid gold;
    border-radius: 10px;
    max-width: 500px;
    margin-left: auto;
    margin-right: auto;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    background: #111;
}
</style>
</head>

<body>

<!-- HERO -->
<div class="hero">
    <div>
        <h1>Bubbly K Creations</h1>
        <p>Luxury Balloon Decor • Designed to Impress</p>
        <br>
        <button class="btn" onclick="document.getElementById('booking').scrollIntoView()">Book Now</button>
    </div>
</div>

<!-- SERVICES -->
<section class="section">
    <h2>Luxury Event Styling</h2>
    <p>
        Custom balloon garlands, statement backdrops, and full event setups designed to elevate your celebration.
    </p>
</section>

<!-- GALLERY -->
<section class="section">
    <h2>Our Work</h2>
    <div class="gallery">
        <img src="PASTE-IMAGE-1">
        <img src="PASTE-IMAGE-2">
        <img src="PASTE-IMAGE-3">
        <img src="PASTE-IMAGE-4">
    </div>
</section>

<!-- BOOKING -->
<section class="section" id="booking">
    <h2>Book Your Event</h2>

    <p>Tell us about your vision and secure your date below.</p>

    <div class="payment-box">
        <h3>Secure Your Date</h3>
        <p>Non-refundable deposit required.</p>

        <button class="btn" onclick="window.open('https://cash.app/$bubblykcreations')">
            Pay Deposit – Cash App
        </button>

        <br><br>

        <button class="btn" onclick="window.open('https://square.link/u/YOUR-LINK')">
            Pay Deposit – Square
        </button>

        <p style="margin-top:15px;">
            Zelle: bubbly.k.creations@gmail.com
        </p>

        <p style="font-size:12px; opacity:0.6;">
            By submitting payment, you agree to all terms & conditions.
        </p>
    </div>
</section>

<!-- CONTACT -->
<section class="section">
    <h2>Connect</h2>
    <p>
        📧 bubbly.k.creations@gmail.com <br><br>

        Instagram: <a href="https://instagram.com/bubbly.k.creations" target="_blank">@bubbly.k.creations</a><br>
        Facebook: Bubbly K Creations
    </p>
</section>

<footer>
    <p>© 2026 Bubbly K Creations</p>
</footer>

</body>
</html>
