<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barbearia Estilo Clássico | Araxá MG</title>
    
    <!-- Meta tags para redes sociais -->
    <meta property="og:title" content="Barbearia Estilo Clássico | Araxá MG">
    <meta property="og:description" content="A melhor barbearia de Araxá e região. Cortes clássicos, barba e cuidados masculinos.">
    <meta property="og:image" content="https://images.unsplash.com/photo-1585747860715-2ba37e788b70?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1476&q=80">
    <meta property="og:url" content="https://www.barbeariaestiloclassico.com.br">
    <meta property="og:type" content="website">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Barbearia Estilo Clássico | Araxá MG">
    <meta name="twitter:description" content="A melhor barbearia de Araxá e região.">
    <meta name="twitter:image" content="https://images.unsplash.com/photo-1585747860715-2ba37e788b70?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1476&q=80">
    
    <!-- Fonte Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        /* ESTILO PARA SCROLL SUAVE */
        html {
            scroll-behavior: smooth;
        }
        
        /* Variáveis de cores */
        :root {
            --primary: #111111;
            --secondary: #2d2d2d;
            --accent: #c0c0c0;
            --accent-hover: #ffffff;
            --text: #f8f9fa;
            --text-muted: #adb5bd;
            --card-bg: rgba(45, 45, 45, 0.8);
            --card-border: rgba(255, 255, 255, 0.1);
            --header-height: 70px;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            -webkit-tap-highlight-color: transparent;
        }
        
        html, body {
            width: 100%;
            height: 100%;
            overflow-x: hidden;
        }
        
        body {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: var(--text);
            line-height: 1.5;
            font-size: 16px;
            min-height: 100vh;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 4%;
        }
        
        /* Elementos flutuantes (WhatsApp e voltar ao topo) */
        .back-to-top {
            position: fixed;
            right: 20px;
            width: 55px;
            height: 55px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 1000;
            transition: all 0.3s;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
            bottom: 85px;
            background: var(--accent);
            color: var(--primary);
            font-size: 18px;
            box-shadow: 0 4px 15px rgba(192, 192, 192, 0.4);
            opacity: 0;
            visibility: hidden;
        }
        
        .back-to-top.visible {
            opacity: 1;
            visibility: visible;
        }
        
        .back-to-top:hover {
            transform: scale(1.1);
            background: var(--accent-hover);
        }
        
        /* Cabeçalho */
        header {
            background: rgba(17, 17, 17, 0.95);
            backdrop-filter: blur(10px);
            padding: 12px 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.3);
            height: var(--header-height);
        }
        
        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .logo-img {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            border: 2px solid var(--accent);
            display: flex;
            align-items: center;
            justify-content: center;
            background: var(--accent);
            color: var(--primary);
            font-size: 18px;
        }
        
        .logo h1 {
            font-size: 20px;
            font-weight: 700;
            color: var(--accent);
        }
        
        /* Navegação */
        nav {
            display: flex;
            gap: 12px;
            align-items: center;
        }
        
        nav a {
            color: var(--text);
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s;
            font-size: 14px;
            padding: 6px 12px;
            border-radius: 5px;
        }
        
        nav a:hover {
            color: var(--accent);
            background: rgba(192, 192, 192, 0.1);
        }
        
        /* Menu Móvel */
        .menu-toggle {
            display: none;
            flex-direction: column;
            justify-content: space-around;
            width: 28px;
            height: 22px;
            background: transparent;
            border: none;
            cursor: pointer;
            padding: 0;
        }
        
        .menu-toggle span {
            width: 100%;
            height: 2.5px;
            background-color: var(--accent);
            border-radius: 5px;
            transition: all 0.3s;
        }
        
        /* Seção Hero */
        .hero {
            min-height: 80vh;
            display: flex;
            align-items: center;
            padding: 90px 0 40px;
            background: linear-gradient(rgba(17, 17, 17, 0.85), rgba(45, 45, 45, 0.85)), 
                        url('https://images.unsplash.com/photo-1585747860715-2ba37e788b70?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1476&q=80');
            background-size: cover;
            background-position: center;
            text-align: center;
        }
        
        .hero-content {
            width: 100%;
            max-width: 800px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        .hero-content h2 {
            font-size: clamp(1.8rem, 5vw, 2.5rem);
            margin-bottom: 15px;
            color: var(--accent);
            font-weight: 700;
            line-height: 1.2;
        }
        
        .hero-content p {
            font-size: clamp(1rem, 2.5vw, 1.1rem);
            margin-bottom: 25px;
            opacity: 0.9;
            color: var(--text-muted);
        }
        
        .hero-buttons {
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
            margin: 30px 0 25px;
            justify-content: center;
        }
        
        .btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 14px 22px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s;
            box-shadow: 0 4px 12px rgba(0,0,0,0.4);
            border: none;
            cursor: pointer;
            font-size: clamp(14px, 3vw, 16px);
            min-height: 44px;
        }
        
        .whatsapp-btn {
            background: #25D366;
            color: white;
        }
        
        .instagram-btn {
            background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
            color: white;
        }
        
        .location-btn {
            background: #336a8f;
            color: white;
        }
        
        /* BOTÕES MODIFICADOS */
        .services-hero-btn {
            background: var(--accent);
            color: var(--primary);
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 18px rgba(0,0,0,0.6);
        }
        
        /* Características */
        .features {
            padding: 40px 0;
            background: var(--primary);
        }
        
        .section-title {
            text-align: center;
            font-size: clamp(1.6rem, 5vw, 1.8rem);
            margin-bottom: 30px;
            color: var(--accent);
            font-weight: 700;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(min(180px, 100%), 1fr));
            gap: 15px;
        }
        
        .feature {
            text-align: center;
            padding: 20px 15px;
            background: var(--card-bg);
            border-radius: 12px;
            backdrop-filter: blur(10px);
            border: 1px solid var(--card-border);
            transition: transform 0.3s;
        }
        
        .feature:hover {
            transform: translateY(-5px);
            background: rgba(192, 192, 192, 0.1);
        }
        
        .feature i {
            font-size: clamp(28px, 8vw, 32px);
            color: var(--accent);
            margin-bottom: 12px;
        }
        
        .feature h4 {
            margin-bottom: 8px;
            color: var(--accent);
            font-size: clamp(0.9rem, 3vw, 1rem);
        }
        
        .feature p {
            opacity: 0.9;
            line-height: 1.4;
            font-size: clamp(0.8rem, 2.5vw, 0.85rem);
            color: var(--text-muted);
        }
        
        /* Serviços */
        .services {
            padding: 40px 0;
            background: linear-gradient(135deg, var(--secondary) 0%, var(--primary) 100%);
            text-align: center;
        }
        
        .services-carousel {
            position: relative;
            max-width: min(850px, 95vw);
            margin: 0 auto;
            overflow: hidden;
            border-radius: 12px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
            cursor: grab;
        }
        
        .services-carousel:active {
            cursor: grabbing;
        }
        
        .carousel-container {
            display: flex;
            transition: transform 0.5s ease;
        }
        
        .carousel-slide {
            min-width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: var(--card-bg);
            padding: 20px;
            border-radius: 12px;
            backdrop-filter: blur(10px);
            border: 1px solid var(--card-border);
            user-select: none;
        }
        
        .carousel-img {
            width: 100%;
            max-width: min(450px, 90vw);
            height: min(250px, 50vh);
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 12px;
            overflow: hidden;
            border: 2px solid var(--accent);
            position: relative;
        }
        
        .carousel-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        
        .carousel-img:hover img {
            transform: scale(1.05);
        }
        
        .carousel-content {
            text-align: center;
            width: 100%;
        }
        
        .carousel-content h3 {
            font-size: clamp(1.4rem, 4vw, 1.5rem);
            margin-bottom: 12px;
            color: var(--accent);
        }
        
        .carousel-content p {
            color: var(--text);
            margin-bottom: 15px;
            opacity: 0.9;
            font-size: clamp(0.9rem, 3vw, 1rem);
            font-weight: 500;
        }
        
        .carousel-content ul {
            list-style: none;
            margin: 15px 0;
            text-align: left;
            padding: 0 15px;
        }
        
        .carousel-content ul li {
            margin-bottom: 8px;
            padding-left: 25px;
            position: relative;
            font-size: clamp(0.9rem, 2.5vw, 0.95rem);
            color: var(--text);
            line-height: 1.5;
        }
        
        .carousel-content ul li:before {
            content: "✓";
            color: var(--accent);
            position: absolute;
            left: 0;
            font-weight: bold;
            font-size: 1.1rem;
        }
        
        /* Botão Ver Serviços Completos */
        .services-btn-container {
            margin-top: 25px;
            text-align: center;
        }
        
        .services-btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 14px 22px;
            background: var(--accent);
            color: var(--primary);
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s;
            box-shadow: 0 4px 12px rgba(192, 192, 192, 0.4);
            font-size: clamp(14px, 3vw, 16px);
            min-height: 44px;
        }
        
        .services-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 18px rgba(192, 192, 192, 0.6);
            background: var(--accent-hover);
        }
        
        /* Controles do carrossel */
        .carousel-controls {
            position: absolute;
            top: 50%;
            left: 0;
            right: 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transform: translateY(-50%);
            padding: 0 15px;
            pointer-events: none;
        }
        
        .carousel-arrow {
            background: rgba(255, 255, 255, 0.1);
            width: clamp(30px, 8vw, 40px);
            height: clamp(30px, 8vw, 40px);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.3s;
            border: 1px solid rgba(255, 255, 255, 0.2);
            font-size: clamp(14px, 4vw, 16px);
            color: var(--accent);
            pointer-events: auto;
        }
        
        .carousel-arrow:hover {
            background: rgba(192, 192, 192, 0.2);
            transform: scale(1.1);
        }
        
        .carousel-indicators {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin: 20px 0 10px;
        }
        
        .indicator {
            width: 10px;
            height: 10px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.3);
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .indicator.active {
            background: var(--accent);
            transform: scale(1.2);
        }
        
        /* Produtos */
        .products {
            padding: 60px 0;
            background: var(--primary);
        }
        
        .products-simple {
            max-width: min(800px, 90vw);
            margin: 0 auto;
            background: var(--card-bg);
            border-radius: 12px;
            padding: 30px;
            backdrop-filter: blur(10px);
            border: 1px solid var(--card-border);
            text-align: center;
        }
        
        .products-simple h3 {
            color: var(--accent);
            margin-bottom: 20px;
            font-size: clamp(1.3rem, 4vw, 1.5rem);
        }
        
        .products-list {
            list-style: none;
            margin-bottom: 25px;
            text-align: left;
        }
        
        .products-list li {
            margin-bottom: 12px;
            padding-left: 25px;
            position: relative;
            font-size: clamp(0.9rem, 2.5vw, 0.95rem);
            color: var(--text);
        }
        
        .products-list li:before {
            content: "✓";
            color: var(--accent);
            position: absolute;
            left: 0;
            font-weight: bold;
            font-size: 1rem;
        }
        
        .product-btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: clamp(12px, 3vw, 14px) clamp(24px, 5vw, 28px);
            background: var(--accent);
            color: var(--primary);
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            transition: all 0.3s ease;
            box-shadow: 0 4px 12px rgba(192, 192, 192, 0.4);
            font-size: clamp(0.9rem, 2.5vw, 1rem);
            border: none;
            cursor: pointer;
            min-height: 44px;
        }
        
        .product-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 18px rgba(192, 192, 192, 0.6);
            background: var(--accent-hover);
        }
        
        /* Sobre */
        .about {
            padding: 60px 0;
            background: linear-gradient(135deg, var(--secondary) 0%, var(--primary) 100%);
            text-align: center;
        }
        
        .about-content {
            max-width: min(800px, 90vw);
            margin: 0 auto;
        }
        
        .about-text p {
            font-size: clamp(0.9rem, 2.5vw, 1rem);
            margin-bottom: 25px;
            opacity: 0.9;
            line-height: 1.7;
            color: var(--text-muted);
        }
        
        .about-features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(min(220px, 100%), 1fr));
            gap: 12px;
            margin-top: 25px;
        }
        
        .about-feature {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 12px;
            background: var(--card-bg);
            border-radius: 12px;
            transition: transform 0.3s ease;
            text-align: left;
        }
        
        .about-feature:hover {
            transform: translateX(5px);
            background: rgba(192, 192, 192, 0.1);
        }
        
        .about-feature i {
            color: var(--accent);
            font-size: clamp(1rem, 3vw, 1.2rem);
            width: 25px;
        }
        
        .about-feature span {
            font-size: clamp(0.85rem, 2.5vw, 0.9rem);
            font-weight: 500;
            color: var(--text);
        }
        
        /* Contato */
        .contact {
            padding: 50px 0 30px;
            background: var(--primary);
            text-align: center;
        }
        
        .business-hours {
            background: var(--card-bg);
            padding: 20px;
            border-radius: 12px;
            text-align: center;
            backdrop-filter: blur(10px);
            border: 1px solid var(--card-border);
            max-width: min(380px, 90vw);
            margin: 0 auto;
            animation: fadeIn 1s ease;
        }
        
        .business-hours h4 {
            color: var(--accent);
            margin-bottom: 12px;
            font-size: clamp(1rem, 3vw, 1.1rem);
            font-weight: 600;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }
        
        .business-hours p {
            margin-bottom: 6px;
            font-size: clamp(0.8rem, 2.5vw, 0.9rem);
            opacity: 0.9;
            color: var(--text);
        }
        
        /* Rodapé */
        footer {
            background: #0a0a0a;
            padding: 20px 0 12px;
            border-top: 1px solid rgba(192, 192, 192, 0.2);
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: 1fr 2fr 1fr;
            gap: 15px;
            margin-bottom: 15px;
            align-items: center;
        }
        
        .footer-logo {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .footer-logo .logo-img {
            width: 30px;
            height: 30px;
            font-size: 14px;
        }
        
        .footer-logo span {
            font-size: clamp(0.8rem, 2.5vw, 0.85rem);
            font-weight: 700;
            color: var(--accent);
        }
        
        .footer-contact {
            text-align: center;
        }
        
        .footer-contact p {
            margin-bottom: 4px;
            opacity: 0.9;
            font-size: clamp(0.7rem, 2vw, 0.75rem);
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 4px;
            color: var(--text);
        }
        
        .footer-social {
            display: flex;
            gap: 10px;
            justify-content: flex-end;
        }
        
        .social-link {
            width: 34px;
            height: 34px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--text);
            text-decoration: none;
            transition: all 0.3s ease;
            font-size: 0.9rem;
        }
        
        .social-link:hover {
            background: var(--accent);
            color: var(--primary);
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(192, 192, 192, 0.4);
        }
        
        /* Correções específicas do Instagram WebView */
        .instagram-webview .hero {
            min-height: calc(60vh - 70px) !important;
        }
        
        .instagram-webview .btn {
            min-height: 44px !important;
            display: flex !important;
            align-items: center !important;
            justify-content: center !important;
        }
        
        /* Prevenir problemas de rolagem no Instagram */
        .instagram-webview body {
            overflow: hidden !important;
            height: 100% !important;
            position: relative;
        }
        
        /* Melhorar a visualização de imagens */
        .instagram-webview img {
            transform: translateZ(0);
        }
        
        /* Indicador de animação de rolagem */
        .scroll-indicator {
            position: fixed;
            top: 50%;
            right: 20px;
            transform: translateY(-50%);
            display: flex;
            flex-direction: column;
            gap: 15px;
            z-index: 998;
        }
        
        .scroll-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.3);
            border: 2px solid transparent;
            transition: all 0.3s ease;
            cursor: pointer;
        }
        
        .scroll-dot.active {
            background: var(--accent);
            transform: scale(1.3);
            border-color: rgba(255, 255, 255, 0.5);
        }
        
        .scroll-dot:hover {
            background: var(--accent-hover);
            transform: scale(1.2);
        }
        
        /* Destaque de seção durante a rolagem */
        .section-highlight {
            position: relative;
        }
        
        .section-highlight::before {
            content: '';
            position: absolute;
            top: -5px;
            left: -5px;
            right: -5px;
            bottom: -5px;
            border: 2px solid var(--accent);
            border-radius: 10px;
            animation: highlight 1.5s ease;
            opacity: 0;
        }
        
        @keyframes highlight {
            0% {
                opacity: 0;
                transform: scale(0.95);
            }
            50% {
                opacity: 1;
                transform: scale(1.02);
            }
            100% {
                opacity: 0;
                transform: scale(1);
            }
        }
        
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-15px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        /* Responsivo */
        @media (max-width: 1024px) {
            .footer-content {
                grid-template-columns: 1fr 1fr;
                gap: 20px;
            }
            
            .footer-contact {
                order: 3;
                grid-column: span 2;
                text-align: center;
            }
            
            .scroll-indicator {
                right: 10px;
            }
        }
        
        @media (max-width: 768px) {
            .hero {
                padding: 90px 0 40px;
                min-height: 50vh;
            }
            
            .hero-buttons {
                justify-content: center;
            }
            
            .section-title {
                font-size: 1.7rem;
            }
            
            .footer-content {
                grid-template-columns: 1fr;
                text-align: center;
                gap: 15px;
            }
            
            .footer-contact {
                order: 0;
                grid-column: span 1;
            }
            
            .footer-social {
                justify-content: center;
            }
            
            /* Menu móvel */
            .menu-toggle {
                display: flex;
            }
            
            nav {
                position: fixed;
                top: 70px;
                left: 0;
                width: 100%;
                background: rgba(17, 17, 17, 0.98);
                flex-direction: column;
                padding: 15px;
                gap: 10px;
                transform: translateY(-100%);
                opacity: 0;
                visibility: hidden;
                transition: all 0.3s ease;
                box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
            }
            
            nav.active {
                transform: translateY(0);
                opacity: 1;
                visibility: visible;
            }
            
            .features-grid {
                grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
                gap: 12px;
            }
            
            .feature {
                padding: 15px 12px;
            }
            
            .business-hours {
                max-width: 90%;
            }
            
            .carousel-controls {
                padding: 0 5px;
            }
            
            .scroll-indicator {
                display: none;
            }
        }
        
        @media (max-width: 480px) {
            .hero {
                min-height: 40vh;
                padding: 80px 0 30px;
            }
            
            .hero-buttons {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 100%;
                max-width: 280px;
                justify-content: center;
            }
            
            .footer-content {
                gap: 12px;
            }
            
            .section-title {
                font-size: 1.6rem;
            }
            
            .indicator {
                width: 8px;
                height: 8px;
            }
            
            .carousel-content ul li {
                font-size: 0.9rem;
            }
        }
        
        /* Orientação paisagem em dispositivos móveis */
        @media screen and (max-height: 480px) and (orientation: landscape) {
            .hero {
                min-height: 100vh !important;
                padding: 80px 0 !important;
            }
            
            .hero-content {
                padding-top: 20px;
            }
        }
        
        /* Efeito de fade-in para os frascos */
        section {
            opacity: 0;
            transform: translateY(40px);
            transition: all 0.8s ease;
        }
        
        section.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <!-- Botão Voltar ao topo -->
    <div class="back-to-top">
        <i class="fas fa-arrow-up"></i>
    </div>
    
    <!-- Indicador de rolagem ATUALIZADO -->
    <div class="scroll-indicator">
        <div class="scroll-dot" data-section="hero" title="Início"></div>
        <div class="scroll-dot" data-section="servicos" title="Serviços"></div>
        <div class="scroll-dot" data-section="produtos" title="Produtos"></div>
        <div class="scroll-dot" data-section="sobre" title="Sobre"></div>
        <div class="scroll-dot" data-section="contato" title="Contato"></div>
    </div>
    
    <!-- Header -->
    <header>
        <div class="container">
            <div class="logo">
                <div class="logo-img">
                    <i class="fas fa-cut"></i>
                </div>
                <h1>BARBEARIA CLÁSSICA</h1>
            </div>
            <button class="menu-toggle">
                <span></span>
                <span></span>
                <span></span>
            </button>
            <nav>
                <a href="#servicos">Serviços</a>
                <a href="#produtos">Produtos</a>
                <a href="#sobre">Sobre</a>
                <a href="#contato">Contato</a>
            </nav>
        </div>
    </header>
    
    <!-- Hero Section -->
    <section class="hero" id="hero">
        <div class="container">
            <div class="hero-content">
                <h2>ESTILO E TRADIÇÃO</h2>
                <p>A melhor barbearia de Araxá e região</p>
                <div class="hero-buttons">
                    <a href="https://wa.me/553499269707?text=Olá! Gostaria de agendar um horário na barbearia ✂️" class="btn whatsapp-btn">
                        <i class="fab fa-whatsapp"></i> Agendar Horário
                    </a>
                    <a href="https://www.instagram.com/barbeariaestiloclassico" class="btn instagram-btn">
                        <i class="fab fa-instagram"></i> Instagram
                    </a>
                    <a href="https://maps.app.goo.gl/Z6brWy7twMynjEsm7" class="btn location-btn">
                        <i class="fas fa-map-marker-alt"></i> Localização
                    </a>
                    <!-- BOTÃO MODIFICADO -->
                    <a href="#servicos" class="btn services-hero-btn">
                        <i class="fas fa-cut"></i> Ver Serviços
                    </a>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Recursos -->
    <section class="features">
        <div class="container">
            <div class="features-grid">
                <div class="feature">
                    <i class="fas fa-cut"></i>
                    <h4>Cortes Modernos</h4>
                    <p>Estilo e precisão em cada corte</p>
                </div>
                <div class="feature">
                    <i class="fas fa-user-tie"></i>
                    <h4>Profissionais</h4>
                    <p>Barbeiros qualificados</p>
                </div>
                <div class="feature">
                    <i class="fas fa-spa"></i>
                    <h4>Relaxamento</h4>
                    <p>Ambiente climatizado</p>
                </div>
                <div class="feature">
                    <i class="fas fa-star"></i>
                    <h4>Qualidade</h4>
                    <p>Produtos premium</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Seção de Serviços MODIFICADA -->
    <section id="servicos" class="services">
        <div class="container">
            <h2 class="section-title">Nossos Serviços</h2>
            <div class="services-carousel" id="services-carousel">
                <div class="carousel-container" id="carousel-services">
                    <!-- Corte de Cabelo -->
                    <div class="carousel-slide">
                        <div class="carousel-img">
                            <img src="https://images.unsplash.com/photo-1562322140-8baeececf3df?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1469&q=80" alt="Corte de Cabelo">
                        </div>
                        <div class="carousel-content">
                            <h3>Corte de Cabelo</h3>
                            <p>Estilo e precisão para um visual renovado</p>
                            <ul>
                                <li>✂️ Cortes modernos e clássicos</li>
                                <li>👨‍🦰 Degradê e navalha</li>
                                <li>🧴 Produtos de qualidade</li>
                                <li>⏱️ 30 minutos de duração</li>
                                <li>💈 Acabamento perfeito</li>
                            </ul>
                            <!-- BOTÃO VER SERVIÇOS COMPLETOS ADICIONADO DENTRO DO RETÂNGULO -->
                            <div class="services-btn-container">
                                <a href="https://wa.me/553499269707?text=Olá! Gostaria de saber mais sobre os serviços da barbearia ✂️" class="services-btn">
                                    <i class="fas fa-list"></i> Ver Todos os Serviços
                                </a>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Barba -->
                    <div class="carousel-slide">
                        <div class="carousel-img">
                            <img src="https://images.unsplash.com/photo-1599351431202-1e0f0137899a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1488&q=80" alt="Barba">
                        </div>
                        <div class="carousel-content">
                            <h3>Barba</h3>
                            <p>Cuidados especiais para sua barba</p>
                            <ul>
                                <li>🧔 Aparar e modelar</li>
                                <li>🧼 Limpeza profunda</li>
                                <li>🧴 Produtos específicos</li>
                                <li>🔥 Toalha quente</li>
                                <li>💆‍♂️ Relaxamento garantido</li>
                            </ul>
                            <!-- BOTÃO VER SERVIÇOS COMPLETOS ADICIONADO DENTRO DO RETÂNGULO -->
                            <div class="services-btn-container">
                                <a href="https://wa.me/553499269707?text=Olá! Gostaria de saber mais sobre os serviços da barbearia ✂️" class="services-btn">
                                    <i class="fas fa-list"></i> Ver Todos os Serviços
                                </a>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Combo Completo -->
                    <div class="carousel-slide">
                        <div class="carousel-img">
                            <img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Combo Completo">
                        </div>
                        <div class="carousel-content">
                            <h3>Combo Completo</h3>
                            <p>Corte + Barba com desconto especial</p>
                            <ul>
                                <li>✂️ Corte de cabelo completo</li>
                                <li>🧔 Tratamento para barba</li>
                                <li>🧴 Produtos premium</li>
                                <li>💆‍♂️ Massagem relaxante</li>
                                <li>💰 Desconto especial</li>
                            </ul>
                            <!-- BOTÃO VER SERVIÇOS COMPLETOS ADICIONADO DENTRO DO RETÂNGULO -->
                            <div class="services-btn-container">
                                <a href="https://wa.me/553499269707?text=Olá! Gostaria de saber mais sobre os serviços da barbearia ✂️" class="services-btn">
                                    <i class="fas fa-list"></i> Ver Todos os Serviços
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Controles do carrossel -->
                <div class="carousel-controls">
                    <div class="carousel-arrow prev" id="prev-services">
                        <i class="fas fa-chevron-left"></i>
                    </div>
                    <div class="carousel-arrow next" id="next-services">
                        <i class="fas fa-chevron-right"></i>
                    </div>
                </div>
            </div>
            
            <!-- Indicadores -->
            <div class="carousel-indicators" id="indicators-services">
                <div class="indicator active" data-index="0"></div>
                <div class="indicator" data-index="1"></div>
                <div class="indicator" data-index="2"></div>
            </div>
        </div>
    </section>
    
    <!-- Produtos -->
    <section id="produtos" class="products">
        <div class="container">
            <h2 class="section-title">Produtos e Acessórios</h2>
            <div class="products-simple">
                <h3>Produtos de Qualidade</h3>
                <ul class="products-list">
                    <li>Pomadas e ceras para cabelo</li>
                    <li>Óleos e bálsamos para barba</li>
                    <li>Shampoos e condicionadores específicos</li>
                    <li>Navalhas e lâminas de qualidade</li>
                    <li>Kits de cuidados masculinos</li>
                    <li>Perfumes e colônias masculinas</li>
                </ul>
                <a href="https://wa.me/553499269707?text=Olá! Gostaria de saber mais sobre os produtos da barbearia ✂️" class="product-btn">
                    <i class="fab fa-whatsapp"></i> Consultar Produtos
                </a>
            </div>
        </div>
    </section>
    
    <!-- Sobre -->
    <section id="sobre" class="about">
        <div class="container">
            <div class="about-content">
                <h2 class="section-title">Barbearia Estilo Clássico</h2>
                <div class="about-text">
                    <p>Especialistas em cortes masculinos com os melhores preços e atendimento personalizado em Araxá e região. Tradição e modernidade em um só lugar, com profissionais qualificados e produtos de alta qualidade.</p>
                    <div class="about-features">
                        <div class="about-feature">
                            <i class="fas fa-check-circle"></i>
                            <span>Produtos de qualidade</span>
                        </div>
                        <div class="about-feature">
                            <i class="fas fa-check-circle"></i>
                            <span>Atendimento personalizado</span>
                        </div>
                        <div class="about-feature">
                            <i class="fas fa-user-tie"></i>
                            <span>Profissionais qualificados</span>
                        </div>
                        <div class="about-feature">
                            <i class="fas fa-clock"></i>
                            <span>Horários flexíveis</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Contato -->
    <section id="contato" class="contact">
        <div class="container">
            <div class="business-hours">
                <h4><i class="far fa-clock"></i> Horário de Funcionamento</h4>
                <p>Segunda a Sexta: 8h às 19h</p>
                <p>Sábado: 8h às 18h</p>
                <p>Domingo: 9h às 13h</p>
            </div>
        </div>
    </section>
    
    <!-- Rodapé -->
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">
                    <div class="logo-img">
                        <i class="fas fa-cut"></i>
                    </div>
                    <span>BARBEARIA CLÁSSICA</span>
                </div>
                <div class="footer-contact">
                    <p><i class="fab fa-whatsapp"></i> (34) 9926-9707</p>
                    <p><i class="fas fa-map-marker-alt"></i> Araxá - MG</p>
                    <p><i class="far fa-clock"></i> Seg-Sex: 8h-19h | Sáb: 8h-18h | Dom: 9h-13h</p>
                </div>
                <div class="footer-social">
                    <a href="https://www.instagram.com/barbeariaestiloclassico" class="social-link">
                        <i class="fab fa-instagram"></i>
                    </a>
                    <a href="https://wa.me/553499269707?text=Olá! Gostaria de agendar um horário na barbearia ✂️" class="social-link">
                        <i class="fab fa-whatsapp"></i>
                    </a>
                </div>
            </div>
            <div class="footer-bottom">
                <p>© 2023 Barbearia Estilo Clássico - CNPJ: 57.620.431/0001-78</p>
                <p>Todos os direitos reservados</p>
            </div>
        </div>
    </footer>
    
    <script>
        // ===== DETECÇÃO DE WEBVIEW DO INSTAGRAM =====
        function isInInstagramWebView() {
            const userAgent = navigator.userAgent || navigator.vendor || window.opera;
            return /Instagram/i.test(userAgent) || /FBAN|FBAV/i.test(userAgent);
        }
        
        // Aplicar aulas específicas para WebView do Instagram
        function applyInstagramFix() {
            if (isInInstagramWebView()) {
                document.body.classList.add('instagram-webview');
                const style = document.createElement('style');
                style.textContent = `
                    [class="banner"], [id*="banner"], [class*="Banner"], [id*="Banner"] {
                        display: none !important;
                    }
                    .btn, a, button {
                        cursor: pointer !important;
                        z-index: 9999 !important;
                        position: relative;
                    }
                    body {
                        -webkit-overflow-scrolling: touch !important;
                    }
                    .hero {
                        position: relative;
                        z-index: 1;
                    }
                `;
                document.head.appendChild(style);
            }
        }
        
        // ===== SCROLL SUAVE NATIVO - AGORA FEITO VIA CSS =====
        // O scroll suave agora é implementado via CSS com scroll-behavior: smooth
        // Isso funciona melhor no Instagram WebView
        
        // ===== ATUALIZAR INDICADORES DE SCROLL =====
        function updateScrollIndicator() {
            const sections = document.querySelectorAll('section[id]');
            const scrollDots = document.querySelectorAll('.scroll-dot');
            const scrollPosition = window.scrollY;
            
            sections.forEach(section => {
                const sectionTop = section.offsetTop - 100;
                const sectionHeight = section.offsetHeight;
                const sectionId = section.getAttribute('id');
                
                if (scrollPosition >= sectionTop && scrollPosition < sectionTop + sectionHeight) {
                    scrollDots.forEach(dot => {
                        dot.classList.remove('active');
                        if (dot.getAttribute('data-section') === sectionId) {
                            dot.classList.add('active');
                        }
                    });
                }
            });
        }
        
        // ===== OBSERVADOR DE INTERSEÇÃO PARA ANIMAÇÕES =====
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);
        
        // Observar todas as letras
        document.querySelectorAll('section').forEach(section => {
            observer.observe(section);
        });
        
        // ===== ROLAGEM SUAVE PARA LINKS INTERNOS =====
        // Agora usando o método nativo do CSS, mas mantemos a prevenção de comportamento padrão
        function setupSmoothScroll() {
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    // Verifique se o link é para uma seção interna
                    const href = this.getAttribute('href');
                    if (href !== '#' && href.startsWith('#')) {
                        e.preventDefault();
                        const targetId = href;
                        const targetElement = document.querySelector(targetId);
                        
                        if (targetElement) {
                            // Usar scroll nativo com comportamento suave (agora controlado pelo CSS)
                            targetElement.scrollIntoView({
                                behavior: 'smooth'
                            });
                            
                            // Fechar menu mobile após clicar em um link
                            if (window.innerWidth <= 768) {
                                document.querySelector('nav').classList.remove('active');
                                document.body.style.overflow = 'auto';
                                document.querySelector('.menu-toggle').classList.remove('active');
                            }
                        }
                    }
                });
            });
        }
        
        // Navegação pelos pontos do indicador de rolagem
        function setupScrollDots() {
            document.querySelectorAll('.scroll-dot').forEach(dot => {
                dot.addEventListener('click', () => {
                    const targetId = '#' + dot.getAttribute('data-section');
                    const targetElement = document.querySelector(targetId);
                    
                    if (targetElement) {
                        targetElement.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                });
            });
        }
        
        // ===== CARROSSEL DE SERVIÇOS =====
        function setupCarousel(carouselId, prevButtonId, nextButtonId, indicatorsId) {
            const carousel = document.getElementById(carouselId);
            const slides = carousel.querySelectorAll('.carousel-slide');
            const indicators = document.getElementById(indicatorsId).querySelectorAll('.indicator');
            const carouselContainer = carousel.closest('.services-carousel');
            const prevButton = document.getElementById(prevButtonId);
            const nextButton = document.getElementById(nextButtonId);
            
            let currentIndex = 0;
            const slideCount = slides.length;
            let autoSlideInterval;
            let userInteractionTimeout;
            let isDragging = false;
            let startX = 0;
            let startScrollLeft = 0;
            
            function updateCarousel() {
                carousel.style.transform = `translateX(-${currentIndex * 100}%)`;
                
                // Atualizar indicadores
                indicators.forEach((indicator, index) => {
                    if (index === currentIndex) {
                        indicator.classList.add('active');
                    } else {
                        indicator.classList.remove('active');
                    }
                });
            }
            
            function nextSlide() {
                currentIndex = (currentIndex + 1) % slideCount;
                updateCarousel();
                resetAutoSlide();
            }
            
            function prevSlide() {
                currentIndex = (currentIndex - 1 + slideCount) % slideCount;
                updateCarousel();
                resetAutoSlide();
            }
            
            // Iniciar slides automáticos
            function startAutoSlide() {
                autoSlideInterval = setInterval(() => {
                    nextSlide();
                }, 5000);
            }
            
            // Parar slides automáticos
            function stopAutoSlide() {
                clearInterval(autoSlideInterval);
            }
            
            // Reiniciar slides automáticos após 26 segundos de inatividade
            function resetAutoSlide() {
                clearTimeout(userInteractionTimeout);
                stopAutoSlide();
                userInteractionTimeout = setTimeout(() => {
                    startAutoSlide();
                }, 26000);
            }
            
            // Indicadores clicáveis
            indicators.forEach(indicator => {
                indicator.addEventListener('click', () => {
                    currentIndex = parseInt(indicator.getAttribute('data-index'));
                    updateCarousel();
                    resetAutoSlide();
                });
            });
            
            // Botões de navegação
            nextButton.addEventListener('click', () => {
                nextSlide();
            });
            
            prevButton.addEventListener('click', () => {
                prevSlide();
            });
            
            // ===== FUNCIONALIDADE DE ARRASTAR =====
            carouselContainer.addEventListener('mousedown', dragStart);
            carouselContainer.addEventListener('touchstart', dragStart, { passive: true });
            carouselContainer.addEventListener('mousemove', drag);
            carouselContainer.addEventListener('touchmove', drag, { passive: true });
            carouselContainer.addEventListener('mouseup', dragEnd);
            carouselContainer.addEventListener('mouseleave', dragEnd);
            carouselContainer.addEventListener('touchend', dragEnd);
            
            // Pausar auto slide quando o mouse estiver sobre o carrossel
            carouselContainer.addEventListener('mouseenter', stopAutoSlide);
            carouselContainer.addEventListener('mouseleave', () => {
                resetAutoSlide();
            });
            
            function dragStart(e) {
                isDragging = true;
                startX = e.type.includes('mouse') ? e.pageX : e.touches[0].pageX;
                startScrollLeft = carousel.scrollLeft;
                stopAutoSlide();
                carousel.style.cursor = 'grabbing';
                carousel.style.transition = 'none';
            }
            
            function drag(e) {
                if (!isDragging) return;
                e.preventDefault();
                
                const x = e.type.includes('mouse') ? e.pageX : e.touches[0].pageX;
                const walk = (x - startX) * 2;
                
                if (walk > 50) {
                    prevSlide();
                    isDragging = false;
                    carousel.style.cursor = 'grab';
                    carousel.style.transition = 'transform 0.5s ease';
                } else if (walk < -50) {
                    nextSlide();
                    isDragging = false;
                    carousel.style.cursor = 'grab';
                    carousel.style.transition = 'transform 0.5s ease';
                }
            }
            
            function dragEnd() {
                isDragging = false;
                carousel.style.cursor = 'grab';
                carousel.style.transition = 'transform 0.5s ease';
                resetAutoSlide();
            }
            
            //inicia a apresentação de slides automaticamente
            startAutoSlide();
        }
        
        // ===== MENU MÓVEL ALTERNAR =====
        function setupMobileMenu() {
            const menuToggle = document.querySelector('.menu-toggle');
            const nav = document.querySelector('nav');
            
            menuToggle.addEventListener('click', () => {
                nav.classList.toggle('active');
                menuToggle.classList.toggle('active');
                document.body.style.overflow = nav.classList.contains('active') ? 'hidden' : 'auto';
            });
        }
        
        // ===== BOTÃO VOLTAR AO TOPO =====
        function setupBackToTop() {
            const backToTopButton = document.querySelector('.back-to-top');
            
            window.addEventListener('scroll', () => {
                if (window.pageYOffset > 300) {
                    backToTopButton.classList.add('visible');
                } else {
                    backToTopButton.classList.remove('visible');
                }
                
                updateScrollIndicator();
            });
            
            backToTopButton.addEventListener('click', () => {
                window.scrollTo({
                    top: 0,
                    behavior: 'smooth'
                });
            });
        }
        
        // ===== INICIALIZAÇÃO GERAL =====
        document.addEventListener('DOMContentLoaded', function() {
            // Inicializar alguns trechos como visíveis
            document.querySelector('.hero').classList.add('visible');
            
            // Aplicar correções para Instagram
            applyInstagramFix();
            
            // Configurar funcionalidades
            setupSmoothScroll();
            setupScrollDots();
            
            //Configura carrossel de serviços
            setupCarousel('carousel-services', 'prev-services', 'next-services', 'indicators-services');
            
            setupMobileMenu();
            setupBackToTop();
            
            // Atualizar indicador de rolagem
            updateScrollIndicator();
        });
        
        // Altura recalcular da viewport em redimensionamento
        window.addEventListener('resize', () => {
            document.querySelectorAll('section').forEach(section => {
                observer.observe(section);
            });
        });
    </script>
</body>
</html>
