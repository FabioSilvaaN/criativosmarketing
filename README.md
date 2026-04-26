<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Criativos Marketing Digital - Estratégias que Performam</title>
    <meta name="description" content="Criativos Marketing Digital: Ecossistema de mídia com inteligência e otimização em tempo real." />
    
    <style id="custom-theme-styles">
        /* ALTERAÇÃO: Efeito do Menu para Azul Claro */
        .elementor-nav-menu--main .e--pointer-background .elementor-item:before {
            background-color: #ADD8E6 !important; /* Azul Claro */
        }
        
        /* Estilo para a Barra de Redes Sociais Fixa */
        .social-bar-criativos {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: flex;
            flex-direction: column;
            gap: 10px;
            z-index: 9999;
        }
        .social-button {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-decoration: none;
            font-size: 24px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            transition: 0.3s;
        }
        .whatsapp-btn { background-color: #25d366; }
        .instagram-btn { background-image: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%); }
        .social-button:hover { transform: scale(1.1); }

        /* Painel Editável Simples */
        .painel-editavel {
            width: 100%;
            max-width: 1200px;
            margin: 50px auto;
            padding: 20px;
            background: #f4f4f4;
            border-radius: 15px;
            text-align: center;
        }
        .grid-imagens {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        .item-editavel {
            background: #ddd;
            height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 2px dashed #999;
            border-radius: 10px;
            overflow: hidden;
        }
        .item-editavel img { width: 100%; height: 100%; object-fit: cover; }
    </style>
</head>

<body class="home elementor-page-5440">

    <div class="social-bar-criativos">
        <a href="https://wa.me/SEU_NUMERO" class="social-button whatsapp-btn" target="_blank" title="WhatsApp Criativos">
            <i class="fab fa-whatsapp"></i>
        </a>
        <a href="https://instagram.com/criativos.marketing" class="social-button instagram-btn" target="_blank" title="Instagram Criativos">
            <i class="fab fa-instagram"></i>
        </a>
    </div>

    <div data-elementor-type="wp-page" class="elementor elementor-5440">
        <div class="elementor-element e-con-boxed">
            <div class="elementor-widget-container" style="text-align: center; padding: 20px;">
                <a href="#">
                    <img width="300" src="URL_DA_LOGO_CRIATIVOS.png" alt="Criativos Marketing">
                </a>
            </div>
        </div>

        <nav class="elementor-nav-menu--main e--pointer-background e--animation-sweep-up">
            <ul class="elementor-nav-menu" style="display: flex; justify-content: center; list-style: none; gap: 20px;">
                <li class="menu-item"><a href="#" class="elementor-item">Início</a></li>
                <li class="menu-item"><a href="#" class="elementor-item">Serviços</a></li>
                <li class="menu-item"><a href="#" class="elementor-item">Portfólio</a></li>
                <li class="menu-item"><a href="#" class="elementor-item">Contato</a></li>
            </ul>
        </nav>

        <section class="painel-editavel">
            <h2>Painel de Destaques</h2>
            <p>Espaço para galeria de imagens e campanhas da Criativos Marketing</p>
            <div class="grid-imagens">
                <div class="item-editavel"><img src="https://via.placeholder.com/400x400" alt="Projeto 1"></div>
                <div class="item-editavel"><img src="https://via.placeholder.com/400x400" alt="Projeto 2"></div>
                <div class="item-editavel"><img src="https://via.placeholder.com/400x400" alt="Projeto 3"></div>
            </div>
        </section>

    </div>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</body>
</html>
