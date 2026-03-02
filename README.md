<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>APEX PERFORMANCE</title>

<style>
body{
    margin:0;
    font-family: 'Arial', sans-serif;
    background-color:#0a0a0a;
    color:white;
}

/* HEADER */
header{
    background: linear-gradient(90deg,#0a0a0a,#1a1a1a);
    padding:20px;
    text-align:center;
    border-bottom: 2px solid #1e90ff;
}

header h1{
    font-size:40px;
    letter-spacing:4px;
    background: linear-gradient(90deg,#c0c0c0,#ffffff,#a9a9a9);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

/* HERO */
.hero{
    height:90vh;
    background: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.9)),
    url('https://images.unsplash.com/photo-1558611848-73f7eb4001ab') center/cover no-repeat;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero h2{
    font-size:50px;
    margin:0;
}

.hero p{
    font-size:18px;
    color:#c0c0c0;
    margin:20px 0;
}

.btn{
    padding:12px 30px;
    background:linear-gradient(90deg,#1e90ff,#0047ab);
    border:none;
    color:white;
    font-weight:bold;
    cursor:pointer;
    border-radius:30px;
    transition:0.3s;
}

.btn:hover{
    transform:scale(1.1);
    background:linear-gradient(90deg,#0047ab,#1e90ff);
}

/* PRODUCTS */
.products{
    padding:60px 20px;
    text-align:center;
}

.products h3{
    font-size:30px;
    margin-bottom:40px;
}

.grid{
    display:grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#111;
    border:1px solid #222;
    padding:20px;
    border-radius:10px;
    transition:0.3s;
}

.card:hover{
    border:1px solid #1e90ff;
    transform:translateY(-5px);
}

.card img{
    width:100%;
    border-radius:10px;
}

.card h4{
    margin:15px 0 10px 0;
}

/* FOOTER */
footer{
    background:#000;
    padding:20px;
    text-align:center;
    border-top:1px solid #1e90ff;
    color:#888;
}

</style>
</head>

<body>

<header>
    <h1>APEX PERFORMANCE</h1>
</header>

<section class="hero">
    <h2>SILENCIO. ENFOQUE. PROGRESO.</h2>
    <p>Rendimiento sin límites. Diseño premium. Mentalidad APEX.</p>
    <button class="btn">Ver Colección</button>
</section>

<section class="products">
    <h3>Nuestra Colección</h3>
    <div class="grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab" alt="">
            <h4>Camiseta Pro Metal</h4>
            <p>Compresión y estilo de alto rendimiento.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1571019614242-c5c5dee9f50b" alt="">
            <h4>Short Training Elite</h4>
            <p>Diseñado para fuerza y movilidad total.</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1594737625785-c72d4f1a5b79" alt="">
            <h4>Women Power Fit</h4>
            <p>Estilo, ajuste y rendimiento superior.</p>
        </div>

    </div>
</section>

<footer>
    © 2026 APEX PERFORMANCE | Instagram: @apexperformance.co
</footer>

</body>
</html>
