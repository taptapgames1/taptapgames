
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
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.tt31.roomescame.survival.game"><p>Room Escape</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.tt30.iam.car.driver.megaramp.stunts"><p>Taxi Driver VR</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.swing.obby.brainrot.game"><p>Prison Escape</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.ps.monkey.crazy.prankster.game"><p>Monkey Pranks</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.escape.tsunami.brainrot"><p>Tsunami Escape</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.gl.brainrot.collector.game"><p>Brainrots Games</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=ru.antkarlov.zombotron"><p>Zombotron Game</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.MobEntertainment.PoppyPlaytimeChapter3"><p>Poppy Playtoys</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.touchfoo.swordigo"><p>TouchFoo Sword</p></div>
        <div class="game"><img src="https://play.google.com/store/apps/details?id=com.gv.steal.supercar.fish.memerot"><p>Super Fish</p></div>
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
