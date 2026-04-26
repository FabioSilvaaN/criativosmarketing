<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Criativos Marketing Digital</title>
    
    <style>
        /* Ajuste do efeito do menu para Azul Claro */
        .elementor-nav-menu--main .e--pointer-background .elementor-item:before {
            background-color: #00BFFF !important; /* Deep Sky Blue */
        }
        
        /* Barra de Redes Sociais e Contato */
        .social-bar-criativos {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: flex;
            flex-direction: column;
            gap: 12px;
            z-index: 9999;
        }
        
        .social-button {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 15px rgba(0,0,0,0.4);
            transition: all 0.3s ease;
            background: white;
            padding: 5px;
        }

        .social-button img {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            object-fit: cover;
        }

        .whatsapp-icon { background-color: #25d366; color: white; font-size: 30px; }
        .insta-icon { background-color: #E1306C; color: white; font-size: 30px; }
        
        .social-button:hover { transform: translateY(-5px); }

        /* Painel Editável Simples */
        .painel-container {
            max-width: 1100px;
            margin: 40px auto;
            padding: 20px;
            background: #f9f9f9;
            border-radius: 20px;
            border: 1px solid #eee;
            text-align: center;
        }

        .grid-painel {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 25px;
        }

        .card-editavel {
            background: #fff;
            padding: 10px;
            border-radius: 12px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .card-editavel img {
            width: 100%;
            border-radius: 8px;
            display: block;
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>

<body>

    <header style="background: #000033; padding: 20px; text-align: center;">
        <img src="https://i.postimg.cc/mD7Xp7N2/LOGO-CRIATIVOS.png" alt="Criativos Marketing" style="max-width: 250px;">
    </header>

    <nav style="padding: 15px; background: #fff; box-shadow: 0 2px 5px rgba(0,0,0,0.1);">
        <ul style="display: flex; justify-content: center; list-style: none; gap: 30px; margin: 0; font-family: sans-serif; font-weight: bold;">
            <li><a href="#" style="text-decoration: none; color: #333;">Home</a></li>
            <li><a href="#" style="text-decoration: none; color: #333;">Sobre</a></li>
            <li><a href="https://www.instagram.com/criativos_marketing/" target="_blank" style="text-decoration: none; color: #333;">Instagram</a></li>
            <li><a href="https://wa.me/5581985544867" target="_blank" style="text-decoration: none; color: #333;">Contato</a></li>
        </ul>
    </nav>

    <div class="painel-container">
        <h2>Painel de Projetos</h2>
        <div class="grid-painel">
            <div class="card-editavel">
                <img src="https://via.placeholder.com/400x300" alt="Projeto">
                <p>Social Media</p>
            </div>
            <div class="card-editavel">
                <img src="https://via.placeholder.com/400x300" alt="Projeto">
                <p>Design Estratégico</p>
            </div>
        </div>
    </div>

    <div class="social-bar-criativos">
        <a href="https://www.instagram.com/criativos_marketing/" class="social-button insta-icon" target="_blank">
            <i class="fab fa-instagram"></i>
        </a>
        <a href="https://wa.me/5581985544867" class="social-button whatsapp-icon" target="_blank">
            <i class="fab fa-whatsapp"></i>
        </a>
        <a href="#" class="social-button">
            <img src="https://i.postimg.cc/mD7Xp7N2/LOGO-CRIATIVOS.png" alt="Logo Criativos">
        </a>
    </div>

</body>
</html>
