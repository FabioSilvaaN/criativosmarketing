<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Criativos Marketing</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
body{
    margin:0;
    font-family:'Poppins', sans-serif;
    background:#050505;
    color:#fff;
}

/* NAV */
header{
    position:fixed;
    width:100%;
    display:flex;
    justify-content:space-between;
    padding:20px 10%;
    background:rgba(0,0,0,0.9);
}

.logo{
    color:#00ff88;
    font-weight:700;
}

nav a{
    margin-left:20px;
    color:#fff;
    text-decoration:none;
}

/* HERO */
.hero{
    height:100vh;
    display:flex;
    align-items:center;
    padding:0 10%;
    background:linear-gradient(180deg,#000,#050505);
}

.hero h1{
    font-size:50px;
    max-width:600px;
}

.hero span{
    color:#00ff88;
}

.hero p{
    color:#aaa;
    margin:20px 0;
    max-width:500px;
}

.btn{
    background:#00ff88;
    color:#000;
    padding:15px 30px;
    border:none;
    font-weight:600;
    cursor:pointer;
}

/* PROVA SOCIAL */
.stats{
    display:flex;
    justify-content:space-around;
    padding:60px 10%;
    background:#0a0a0a;
}

.stat h2{
    color:#00ff88;
}

/* SERVIÇOS */
.services{
    padding:80px 10%;
}

.services h2{
    text-align:center;
    margin-bottom:50px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.box{
    background:#111;
    padding:30px;
    border-radius:10px;
    transition:0.3s;
}

.box:hover{
    border:1px solid #00ff88;
    transform:translateY(-5px);
}

/* DIFERENCIAL */
.diferencial{
    padding:80px 10%;
    text-align:center;
    background:#00ff88;
    color:#000;
}

/* CTA FINAL */
.cta{
    padding:80px 10%;
    text-align:center;
}

footer{
    background:#000;
    padding:20px;
    text-align:center;
}
</style>
</head>

<body>

<header>
    <div class="logo">Criativos Marketing</div>
    <nav>
        <a href="#">Início</a>
        <a href="#servicos">Serviços</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section class="hero">
    <div>
        <h1>Mais clientes, mais vendas e mais <span>RESULTADO</span></h1>
        <p>Transformamos o seu Instagram e seus anúncios em uma máquina de gerar clientes todos os dias.</p>

        <a href="https://wa.me/5581985544867">
            <button class="btn">Falar com especialista</button>
        </a>
    </div>
</section>

<section class="stats">
    <div class="stat">
        <h2>+100K</h2>
        <p>Visualizações geradas</p>
    </div>

    <div class="stat">
        <h2>+50</h2>
        <p>Clientes atendidos</p>
    </div>

    <div class="stat">
        <h2>+200%</h2>
        <p>Crescimento médio</p>
    </div>
</section>

<section class="services" id="servicos">
    <h2>O que fazemos</h2>

    <div class="grid">
        <div class="box">
            <h3>Gestão de Redes Sociais</h3>
            <p>Criamos conteúdo estratégico para atrair seguidores e gerar vendas.</p>
        </div>

        <div class="box">
            <h3>Tráfego Pago</h3>
            <p>Anúncios no Instagram e Google que trazem clientes todos os dias.</p>
        </div>

        <div class="box">
            <h3>Criação de Conteúdo</h3>
            <p>Reels virais e criativos que fazem sua marca crescer.</p>
        </div>

        <div class="box">
            <h3>Identidade Visual</h3>
            <p>Design profissional para destacar sua empresa no mercado.</p>
        </div>
    </div>
</section>

<section class="diferencial">
    <h2>Não fazemos posts bonitos. Fazemos você vender.</h2>
    <p>Estratégia, posicionamento e execução focada em resultado real.</p>
</section>

<section class="cta" id="contato">
    <h2>Quer crescer no digital?</h2>
    <p>Fale agora com a Criativos Marketing</p>

    <a href="https://wa.me/5581985544867">
        <button class="btn">Quero clientes</button>
    </a>
</section>

<footer>
    © 2026 Criativos Marketing
</footer>

</body>
</html>
