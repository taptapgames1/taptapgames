
<html lang="en">
<head>
<meta charset="UTF-8">
<title>TapTap Games</title>
<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #111;
    color: white;
}

nav {
    background: #222;
    padding: 15px;
    text-align: center;
}

nav button {
    margin: 5px;
    padding: 10px 20px;
    border: none;
    background: #ff3c3c;
    color: white;
    cursor: pointer;
    font-weight: bold;
}

section {
    display: block;
    padding: 20px;
    text-align: center;
}

.active {
    display: block;
}

.game-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 15px;
    margin-top: 20px;
}

.game {
    background: #222;
    padding: 10px;
    border-radius: 10px;
}

.game img {
    width: 100%;
    border-radius: 10px;
}
</style>
</head>

<body>

<nav>
    <button onclick="showPage('home')">HOME</button>
    <button onclick="showPage('games')">OUR GAMES</button>
    <button onclick="showPage('contact')">CONTACT US</button>
</nav>

<!-- HOME -->
<section id="home" class="active">
    <h1>TapTap Games</h1>
    <p>Welcome to TapTap Games!</p>
    <p>We are a passionate Games Development Company creating exciting and engaging mobile games.</p>
    <p>Our focus is on high-quality racing and action games that deliver fun and immersive experiences.</p>
</section>

<!-- GAMES -->
<section id="games">
    <h1>Our Games</h1>
    <div class="game-grid">
        <div class="game"><img src="https://play-lh.googleusercontent.com/ERDu0Q6wgP6vi4sDn22tfikLEOD1AFie_vbU5dZB5oQq5RpT-IzYLxs7zF29_vNQ-cHdGzuVX9ztyDIG5YVH=w480-h960"><p>Room Escape</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/iK60hJInXfyvqYCCHXh1YiS0VGK3iWe_M0DiwlAGYHZDrAB1mMZfLwoW3QkAw7ikdYrGI4FQ9YinNBaqZQ0pLw=w480-h960-rw"><p>Taxi Driver VR</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/24ZYFEKHmZIDc9gHpwAGkFeAbu2E_UIG37KuJy9zPOiNwz0eX5dFFMQF_RnI3JtdKi4=w480-h960"><p>Prison Escape</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/6lAkKAffFkNh0zEqsW-omE8pDpQyiCi1u9iwWTB-SP0QH6vO0d6Bir49qpE709P6qGP5BU0SlsamJmCx6SD3=w480-h960"><p>Monkey Pranks</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/qrnNqb_9AfidSIa6QKlGRqfIAyBtGw16y-qf7FQ8nh2oIe5a8swcXp2-lrT1bf73TMKI7DgXLDWeBOnozt48qcI=w480-h960"><p>Tsunami Escape</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/ikHZSSLzci3WXTBR1Vie3mIQlaqdd4iRU40Z7dcd-du11d4JYjbn1Dfog6s_In9awty77uUw4iUbPhd7gSmsCQ=s512"><p>Brainrots Games</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/ji2zm6a8BxoFiIOdImIpEVcrJ43wvN0Z-NanHEWJ0Syl-r_xLBvm4Us7uFPvRiWr7hc81Rc3IKV4wiDFH8DLug=w480-h960"><p>Zombotron Game</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/-4dSZjsh1LX-aczh0SrslsgUIH6s7qMOSLFcsTlNn1B6M4zSnm_IC5hw2xFcPH9Jhi4=w480-h960"><p>Poppy Playtoys</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/4f4J0nS4nZydWXx2rtt9dqRU71ItAEc7-bEQPaHyFMdSZMK63FjY0pC0cwH9mHeZLLFWKqRNxCmlS6g6GlCxPg=s512"><p>TouchFoo Sword</p></div>
        <div class="game"><img src="https://play-lh.googleusercontent.com/ikHZSSLzci3WXTBR1Vie3mIQlaqdd4iRU40Z7dcd-du11d4JYjbn1Dfog6s_In9awty77uUw4iUbPhd7gSmsCQ=w480-h960"><p>Super Fish</p></div>
    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <h1>Contact Us</h1>
    <p>Email us at:</p>
    <p><b>taptapgames1@gmail.com</b></p>
</section>

<script>
function showPage(pageId) {
    let sections = document.querySelectorAll("section");
    sections.forEach(section => section.classList.remove("active"));
    document.getElementById(pageId).classList.add("active");
}
</script>

</body>
</html>
