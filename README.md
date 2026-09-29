<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Carti World</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#0d0d0d;
    color:white;
}

header{
    background:black;
    padding:20px;
    text-align:center;
    border-bottom:2px solid red;
}

header h1{
    font-size:3rem;
    color:red;
}

nav{
    margin-top:10px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}

.hero{
    text-align:center;
    padding:80px 20px;
    background:linear-gradient(to bottom,#111,#000);
}

.hero h2{
    font-size:2.5rem;
    margin-bottom:15px;
}

.hero p{
    max-width:700px;
    margin:auto;
    color:#ccc;
}

.posts{
    max-width:1000px;
    margin:40px auto;
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
    padding:20px;
}

.card{
    background:#151515;
    border:1px solid #222;
    border-radius:10px;
    overflow:hidden;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.card-content{
    padding:15px;
}

.card-content h3{
    margin-bottom:10px;
    color:red;
}

footer{
    text-align:center;
    padding:20px;
    border-top:1px solid #222;
    margin-top:40px;
    color:#888;
}
</style>
</head>
<body>

<header>
    <h1>CARTI WORLD</h1>
    <nav>
        <a href="#">Início</a>
        <a href="#">Álbuns</a>
        <a href="#">Notícias</a>
        <a href="#">Contato</a>
    </nav>
</header>

<section class="hero">
    <h2>O Universo de Playboi Carti</h2>
    <p>
        Notícias, curiosidades, lançamentos e tudo sobre um dos artistas
        mais influentes do trap moderno.
    </p>
</section>

<section class="posts">
    <div class="card">
        <img src="https://images.unsplash.com/photo-1493225457124-a3eb161ffa5f" alt="">
        <div class="card-content">
            <h3>Whole Lotta Red</h3>
            <p>O álbum que redefiniu o trap moderno e influenciou uma geração.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1501386761578-eac5c94b800a" alt="">
        <div class="card-content">
            <h3>Shows e Turnês</h3>
            <p>Confira informações sobre apresentações e eventos recentes.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1516280440614-37939bbacd81" alt="">
        <div class="card-content">
            <h3>Estilo Vamp</h3>
            <p>Moda, estética e influência cultural do artista.</p>
        </div>
    </div>
</section>

<footer>
    © 2026 Carti World • Blog feito para fãs de Playboi Carti
</footer>

</body>
</html>
