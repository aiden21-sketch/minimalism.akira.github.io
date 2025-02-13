<header>
    <h1>minimlism.
  </h1>
    <nav>
        <a href="#videos">music videos.</a>
        <a href="#albums">albums.</a>
        <a href="#tracks">tracks.</a>
    </nav>
</header>

<section id="videos">
    <h2>music videos.</h2>
    <iframe width="560" height="315" src= frameborder="0" allowfullscreen></iframe>
</section>

<section id="albums">
    <h2>albums.</h2>
    <div class="album">
        <img src="https://via.placeholder.com/200" alt="Album Cover">
        <p>NEMESIS.</p>
    </div>
    <div class="album">
        <img src="https://via.placeholder.com/200" alt="Album Cover">
        <p>SAVIOR.</p>
    </div>
</section>

<section id="tracks">
    <h2>tracks.</h2>
    <audio controls>
        <source src="your-song.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    <audio controls>
        <source src="your-second-song.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</section>
/body {
    background: white;
    color: black;
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 0;
    padding: 0;
}

/* Header */
header {
    padding: 20px;
    font-size: 24px;
    font-weight: bold;
}

/* Navigation */
nav {
    margin: 20px 0;
}
nav a {
    margin: 15px;
    text-decoration: none;
    color: black;
    font-size: 18px;
    font-weight: bold;
    padding: 10px 20px;
    border: 2px solid black;
    border-radius: 5px;
    transition: background 0.3s, color 0.3s;
}
nav a:hover {
    background: black;
    color: white;
}

/* Sections */
section {
    margin: 50px 0;
}
h2 {
    font-size: 22px;
    margin-bottom: 20px;
}

/* Video Section */
iframe {
    width: 80%;
    max-width: 560px;
    height: 315px;
    border-radius: 10px;
}

/* Albums */
.album {
    display: inline-block;
    margin: 20px;
}
.album img {
    width: 200px;
    height: auto;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}
.album p {
    font-size: 18px;
    margin-top: 10px;
}

/* Audio (Tracks) */
audio {
    margin-top: 10px;
    width: 80%;
    max-width: 400px;
}* General Styles */
