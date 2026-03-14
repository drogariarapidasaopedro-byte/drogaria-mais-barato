<!DOCTYPE html>
<html lang="pt-BR">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Drogaria Mais Barato</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,Arial;
}

body{
background:#f3f3f3;
}

/* HEADER */

header{
background:#ffd400;
padding:15px;
}

.header-container{
max-width:1200px;
margin:auto;
display:flex;
align-items:center;
gap:20px;
flex-wrap:wrap;
}

.logo{
font-size:24px;
font-weight:700;
color:#d6362e;
}

.search{
flex:1;
}

.search input{
width:100%;
padding:10px;
border-radius:6px;
border:none;
}

.whatsapp{
background:#25D366;
color:white;
padding:10px 20px;
border-radius:6px;
text-decoration:none;
font-weight:600;
}

/* MENU */

.menu{
background:white;
border-bottom:1px solid #ddd;
}

.menu-container{
max-width:1200px;
margin:auto;
display:flex;
gap:20px;
padding:10px;
flex-wrap:wrap;
}

.menu a{
text-decoration:none;
color:#333;
font-weight:500;
}

/* BANNER */

.banner{
background:linear-gradient(90deg,#c40000,#ff2e2e);
color:white;
padding:60px 20px;
text-align:center;
}

.banner h1{
font-size:28px;
margin-bottom:20px;
}

/* PRODUTOS */

.container{
max-width:1200px;
margin:auto;
padding:40px 20px;
}

.title{
text-align:center;
font-size:26px;
margin-bottom:30px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.product{
background:white;
border-radius:10px;
padding:20px;
text-align:center;
box-shadow:0 5px 15px rgba(0,0,0,0.08);
}

.product img{
width:100%;
height:150px;
object-fit:contain;
}

.price{
color:#d60000;
font-weight:700;
font-size:20px;
margin:10px 0;
}

.buy{
background:#25D366;
color:white;
padding:10px;
border-radius:6px;
text-decoration:none;
display:inline-block;
}

/* FOOTER */

footer{
background:#2b2b2b;
color:white;
padding:40px 20px;
margin-top:40px;
}

.footer-container{
max-width:1200px;
margin:auto;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

footer p{
font-size:13px;
color:#ccc;
}

</style>

</head>

<body>

<header>

<div class="header-container">

<div class="logo">
Drogaria Mais Barato
</div>

<div class="search">
<input placeholder="Buscar medicamentos e produtos...">
</div>

<a class="whatsapp" href="https://wa.me/5511976881196">
WhatsApp
</a>

</div>

</header>

<div class="menu">

<div class="menu-container">

<a href="#">Medicamentos</a>
<a href="#">Genéricos</a>
<a href="#">Perfumaria</a>
<a href="#">Bebê</a>
<a href="#">Higiene</a>
<a href="#">Promoções</a>

</div>

</div>

<section class="banner">

<h1>
Ofertas especiais em medicamentos e perfumaria
</h1>

<p>Peça agora pelo WhatsApp</p>

</section>

<div class="container">

<div class="title">🔥 Ofertas da Semana</div>

<div class="products">

<div class="product">

<h3>Dipirona Gotas</h3>

<img src="https://drogariasp.vteximg.com.br/arquivos/ids/1192421-1000-1000/492116-dipirona-500mg-ml-generico-gotas-Neo-Quimica-20ml.jpg.jpg">

<div class="price">R$ 5,99</div>

<a class="buy" href="https://wa.me/5511976881196?text=Quero%20Dipirona">
Pedir no WhatsApp
</a>

</div>

<div class="product">

<h3>Loratamed 10mg</h3>

<img src="https://drogariasp.vtexassets.com/arquivos/ids/1135947-200-200/Anti-Alergico-Loratamed-10Mg-12-Comprimidos---165972_0001_Layer-1.png">

<div class="price">R$ 11,99</div>

<a class="buy" href="https://wa.me/5511976881196?text=Quero%20Loratamed">
Pedir no WhatsApp
</a>

</div>

<div class="product">

<h3>Dorflex</h3>

<img src="https://drogariasp.vtexassets.com/arquivos/ids/1113365-200-200/59790---Dorflex-Analgesico-e-Relaxante-Muscular-10-comprimidos_0003_Layer-1.png">

<div class="price">R$ 8,49</div>

<a class="buy" href="https://wa.me/5511976881196?text=Quero%20Dorflex">
Pedir no WhatsApp
</a>

</div>

</div>

</div>

<footer>

<div class="footer-container">

<div>

<h3>Drogaria Mais Barato</h3>

<p>
Av. Dom Pedro de Alcântara, 242<br>
Montanhão<br>
São Bernardo do Campo
</p>

</div>

<div>

<h3>Horário</h3>

<p>
Seg a Sáb: 07h às 21h<br>
Domingo: 08h às 14h
</p>

</div>

<div>

<h3>Contato</h3>

<p>
WhatsApp: (11) 97688-1196
</p>

</div>

</div>

</footer>

</body>
</html>
