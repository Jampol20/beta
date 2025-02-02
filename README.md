<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Te gustaria salir conmigo arelys?</title>
</head>
<body>
    <div class="container">
        <div class="tenor-gif-embed" data-postid="2871482820979272488" data-share-method="host" data-aspect-ratio="1.28351" data-width="100%"><a href="https://tenor.com/view/mochi-pet-mochi-cat-cute-squiddy-gif-2871482820979272488">Mochi Pet GIF</a>from <a href="https://tenor.com/search/mochi-gifs">Mochi GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
        <h1>¿Te gustaria salir conmigo arelys? 🥰</h1>
        <p>Eres la persona mas especial del mundo</p>
        <div class="btn">
            <a href="si.html">SI</a>
            <a href="no1.html">NO</a>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Piensatelo...</title>
</head>
<body>
    <div class="container">
        <div class="tenor-gif-embed" data-postid="18148463711766725559" data-share-method="host" data-aspect-ratio="1.0641" data-width="100%"><a href="https://tenor.com/view/peach-cat-crying-peach-goma-peach-and-goma-mochi-mochi-peach-cat-gif-gif-18148463711766725559">Peach Cat Crying Peach Goma Sticker</a>from <a href="https://tenor.com/search/peach+cat+crying-stickers">Peach Cat Crying Stickers</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
        <h1>¿Estas Segura? Piensalo bien 😥  </h1>
        <div class="btn">
            <a href="si.html">SI</a>
            <a href="no2.html">NO</a>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Seras mia...</title>
</head>
<body>
    <div class="container">
        <div class="tenor-gif-embed" data-postid="21443416" data-share-method="host" data-aspect-ratio="0.95625" data-width="100%"><a href="https://tenor.com/view/white-cat-cats-hell-yeah-cat-gif-21443416">White Cat Cats GIF</a>from <a href="https://tenor.com/search/white+cat-gifs">White Cat GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
        <h1>Seras mia a las buenas o a las malas 😈  </h1>
        <div class="btn">
            <a href="si.html">SI</a>
            <a href="#" id="btn-random">NO</a>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
const btnNo = document.querySelector("#btn-random")
function moverAleatoriamente(btn) {
    btn.style.position = "absolute";
    btn.style.fontWeight = "bolder";
    btn.style.top = Math.floor(Math.random() * 90 + 5) + "%"
    btn.style.left = Math.floor(Math.random() * 90 + 5) + "%"
}
btnNo.addEventListener("mouseenter", function (e) {
    moverAleatoriamente(e.target)
})
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Preguntale a tu flaca</title>
</head>
<body>
    <div class="container">
        <div class="tenor-gif-embed" data-postid="11000679121036284802" data-share-method="host" data-aspect-ratio="1" data-width="100%"><a href="https://tenor.com/view/khanov1-gif-11000679121036284802">Khanov1 GIF</a>from <a href="https://tenor.com/search/khanov1-gifs">Khanov1 GIFs</a></div> <script type="text/javascript" async src="https://tenor.com/embed.js"></script>
        <h1>Heheheh, Lo sabia!!! </h1>
    </div>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}
body {
    position: relative;
    width: 100%;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #ffe5e5;
}
.container {
    display: flex;
    flex-direction: column;
    text-align: center;
    align-items: center;
    gap: 20px;
    max-width: 500px;
    margin: 20px;
}
.container .tenor-gif-embed {
    display: flex;
    max-width: 200px;
}
.container .btn {
    display: flex;
    gap: 25px;
}
.btn a {
    text-decoration: none;
    color: #111;
    background: #fff;
    padding: 10px 25px;
    border-radius: 8px;
    box-shadow: 0.5rem 1rem 3rem hsl(0, 0, 0,0.3);
}
