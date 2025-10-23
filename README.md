<!DOCTYPE html>
<html lang="pt-BR">
<cabeça>
    <meta charset="UTF-8">
    <meta name="viewport" content="largura=largura-do-dispositivo, escala-inicial=1.0">
    <title>Barbearia Estilo Clássico | Araxá MG</title>
    
    <!-- Meta tags para redes sociais -->
    <meta property="og:title" content="Barbearia Estilo Clássico | Araxá MG">
    <meta property="og:description" content="A melhor barbearia de Araxá e região. Cortes clássicos, barba e cuidados masculinos.">
    <meta property="og:image" content="https://images.unsplash.com/photo-1585747860715-2ba37e788b70?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1476&q=80">
    <meta propriedade="og:url" conteúdo="https://www.barbeariaestiloclassico.com.br">
    <meta propriedade="og:type" content="website">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Barbearia Estilo Clássico | Araxá MG">
    <meta name="twitter:description" content="A melhor barbearia de Araxá e região.">
    <meta name="twitter:image" content="https://images.unsplash.com/photo-1585747860715-2ba37e788b70?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1476&q=80">
    
    <!-- Fonte Awesome -->
    <link rel="folha de estilo" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <estilo>
        /* ESTILO PARA SCROLL SUAVE */
        html {
            comportamento de rolagem: suave;
        }
        
        /* Variáveis ​​de núcleos */
        :raiz {
            --primário: #111111;
            --secundário: #2d2d2d;
            --acento: #c0c0c0;
            --accent-hover: #ffffff;
            --texto: #f8f9fa;
            --texto silenciado: #adb5bd;
            --card-bg: rgba(45, 45, 45, 0.8);
            --card-border: rgba(255, 255, 255, 0.1);
            --altura do cabeçalho: 70px;
        }
        
        * {
            margem: 0;
            preenchimento: 0;
            dimensionamento de caixa: caixa de borda;
            família de fontes: 'Segoe UI', Tahoma, Genebra, Verdana, sans-serif;
            -webkit-tap-highlight-color: transparente;
        }
        
        html, corpo {
            largura: 100%;
            altura: 100%;
            overflow-x: oculto;
        }
        
        corpo {
            plano de fundo: gradiente linear (135 graus, var (--primário) 0%, var (--secundário) 100%);
            cor: var(--texto);
            altura da linha: 1,5;
            tamanho da fonte: 16px;
            altura mínima: 100vh;
        }
        
        .recipiente {
            largura: 100%;
            largura máxima: 1200px;
            margem: 0 automático;
            preenchimento: 0 4%;
        }
        
        /* Elementos flutuantes (WhatsApp e voltar ao topo) */
        .voltar ao topo {
            posição: fixa;
            direita: 20px;
            largura: 55px;
            altura: 55px;
            raio da borda: 50%;
            exibição: flexível;
            alinhar-itens: centro;
            justificar-conteúdo: centro;
            índice z: 1000;
            transição: todos os 0,3s;
            caixa-sombra: 0 4px 15px rgba(0,0,0,0.2);
            inferior: 85px;
            fundo: var(--accent);
            cor: var(--primary);
            tamanho da fonte: 18px;
            caixa-sombra: 0 4px 15px rgba(192, 192, 192, 0.4);
            opacidade: 0;
            visibilidade: oculto;
        }
        
        .voltar-ao-topo.visível {
            opacidade: 1;
            visibilidade: visível;
        }
        
        .voltar ao topo:passar o mouse {
            transformar: escala(1.1);
            plano de fundo: var(--accent-hover);
        }
        
        /* Cabeçalho */
        cabeçalho {
            fundo: rgba(17, 17, 17, 0,95);
            filtro de pano de fundo: desfoque(10px);
            preenchimento: 12px 0;
            posição: fixa;
            largura: 100%;
            topo: 0;
            índice z: 1000;
            caixa-sombra: 0 2px 15px rgba(0, 0, 0, 0.3);
            altura: var(--header-height);
        }
        
        cabeçalho .container {
            exibição: flexível;
            justificar-conteúdo: espaço-entre;
            alinhar-itens: centro;
        }
        
        .logotipo {
            exibição: flexível;
            alinhar-itens: centro;
            lacuna: 8px;
        }
        
        .logo-img {
            largura: 40px;
            altura: 40px;
            raio da borda: 50%;
            borda: 2px sólido var(--accent);
            exibição: flexível;
            alinhar-itens: centro;
            justificar-conteúdo: centro;
            fundo: var(--accent);
            cor: var(--primary);
            tamanho da fonte: 18px;
        }
        
        .logotipo h1 {
            tamanho da fonte: 20px;
            espessura da fonte: 700;
            cor: var(--accent);
        }
        
        /* Navegação */
        navegação {
            exibição: flexível;
            lacuna: 12px;
            alinhar-itens: centro;
        }
        
        navegar a {
            cor: var(--texto);
            decoração de texto: nenhuma;
            espessura da fonte: 500;
            transição: todos os 0,3s;
            tamanho da fonte: 14px;
            preenchimento: 6px 12px;
            raio da borda: 5px;
        }
        
        nav a:hover {
            cor: var(--accent);
            fundo: rgba(192, 192, 192, 0.1);
        }
        
        /* Menu Móvel */
        .menu-alternar {
            exibição: nenhuma;
            flex-direction: coluna;
            justificar-conteúdo: espaço-ao-redor;
            largura: 28px;
            altura: 22px;
            fundo: transparente;
            borda: nenhuma;
            cursor: ponteiro;
            preenchimento: 0;
        }
        
        .menu-toggle span {
            largura: 100%;
            altura: 2,5px;
            cor de fundo: var(--accent);
            raio da borda: 5px;
            transição: todos os 0,3s;
        }
        
        /* Seção Hero */
        .herói {
            altura mínima: 80vh;
            exibição: flexível;
            alinhar-itens: centro;
            preenchimento: 90px 0 40px;
            fundo: gradiente linear(rgba(17, 17, 17, 0,85), rgba(45, 45, 45, 0,85)),
                        url('https://images.unsplash.com/photo-1585747860715-2ba37e788b70?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1476&q=80');
            tamanho-do-fundo: capa;
            posição de fundo: centro;
            alinhamento de texto: centro;
        }
        
        .conteúdo do herói {
            largura: 100%;
            largura máxima: 800px;
            margem: 0 automático;
            preenchimento: 0 15px;
        }
        
        .conteúdo do herói h2 {
            tamanho da fonte: clamp(1.8rem, 5vw, 2.5rem);
            margem inferior: 15px;
            cor: var(--accent);
            espessura da fonte: 700;
            altura da linha: 1,2;
        }
        
        .conteúdo do herói p {
            tamanho da fonte: clamp(1rem, 2.5vw, 1.1rem);
            margem inferior: 25px;
            opacidade: 0,9;
            cor: var(--text-muted);
        }
        
        .botões de herói {
            exibição: flexível;
            lacuna: 12px;
            flex-wrap: envolver;
            margem: 30px 0 25px;
            justificar-conteúdo: centro;
        }
        
        .btn {
            exibição: inline-flex;
            alinhar-itens: centro;
            lacuna: 8px;
            preenchimento: 14px 22px;
            decoração de texto: nenhuma;
            raio da borda: 50px;
            espessura da fonte: 600;
            transição: todos os 0,3s;
            caixa-sombra: 0 4px 12px rgba(0,0,0,0.4);
            borda: nenhuma;
            cursor: ponteiro;
            tamanho da fonte: clamp(14px, 3vw, 16px);
            altura mínima: 44px;
        }
        
        .btn do whatsapp {
            fundo: #25D366;
            cor: branco;
        }
        
        .instagram-btn {
            fundo: gradiente linear(45 graus, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
            cor: branco;
        }
        
        .localização-btn {
            fundo: #336a8f;
            cor: branco;
        }
        
        /* BOTÕES MODIFICADOS */
        .serviços-herói-btn {
            fundo: var(--accent);
            cor: var(--primary);
        }
        
        .btn:passe o mouse {
            transformar: translateY(-3px);
            caixa-sombra: 0 6px 18px rgba(0,0,0,0.6);
        }
        
        /* Características */
        .características {
            preenchimento: 40px 0;
            fundo: var(--primário);
        }
        
        .título-da-seção {
            alinhamento de texto: centro;
            tamanho da fonte: clamp(1.6rem, 5vw, 1.8rem);
            margem inferior: 30px;
            cor: var(--accent);
            espessura da fonte: 700;
        }
        
        .grade de recursos {
            exibição: grade;
            grid-template-columns: repetir(ajuste automático, minmax(min(180px, 100%), 1fr));
            lacuna: 15px;
        }
        
        .recurso {
            alinhamento de texto: centro;
            preenchimento: 20px 15px;
            fundo: var(--card-bg);
            raio da borda: 12px;
            filtro de pano de fundo: desfoque(10px);
            borda: 1px sólido var(--card-border);
            transição: transformação 0,3s;
        }
        
        .recurso: pairar {
            transformar: translateY(-5px);
            fundo: rgba(192, 192, 192, 0.1);
        }
        
        .recurso i {
            tamanho da fonte: clamp(28px, 8vw, 32px);
            cor: var(--accent);
            margem inferior: 12px;
        }
        
        .recurso h4 {
            margem inferior: 8px;
            cor: var(--accent);
            tamanho da fonte: clamp(0.9rem, 3vw, 1rem);
        }
        
        .recurso p {
            opacidade: 0,9;
            altura da linha: 1,4;
            tamanho da fonte: clamp(0,8rem, 2,5vw, 0,85rem);
            cor: var(--text-muted);
        }
        
        /* Serviços */
        .serviços {
            preenchimento: 40px 0;
            plano de fundo: gradiente linear (135 graus, var (--secundário) 0%, var (--primário) 100%);
            alinhamento de texto: centro;
        }
        
        .serviços-carrossel {
            posição: relativa;
            largura máxima: min(850px, 95vw);
            margem: 0 automático;
            estouro: oculto;
            raio da borda: 12px;
            caixa-sombra: 0 8px 25px rgba(0, 0, 0, 0.3);
            cursor: agarrar;
        }
        
        .services-carousel:ativo {
            cursor: agarrando;
        }
        
        .carrossel-container {
            exibição: flexível;
            transição: transformação 0,5s de facilidade;
        }
        
        .carrossel-slide {
            largura mínima: 100%;
            exibição: flexível;
            flex-direction: coluna;
            alinhar-itens: centro;
            justificar-conteúdo: centro;
            fundo: var(--card-bg);
            preenchimento: 20px;
            raio da borda: 12px;
            filtro de pano de fundo: desfoque(10px);
            borda: 1px sólido var(--card-border);
            seleção de usuário: nenhum;
        }
        
        .carrossel-img {
            largura: 100%;
            largura máxima: min(450px, 90vw);
            altura: min(250px, 50vh);
            plano de fundo: gradiente linear (45 graus, var (--primário), var (--secundário));
            raio da borda: 10px;
            exibição: flexível;
            alinhar-itens: centro;
            justificar-conteúdo: centro;
            margem inferior: 12px;
            estouro: oculto;
            borda: 2px sólido var(--accent);
            posição: relativa;
        }
        
        .carrossel-img img {
            largura: 100%;
            altura: 100%;
            ajuste de objeto: capa;
            transição: transformação 0,5s de facilidade;
        }
        
        .carrossel-img:img flutuante {
            transformar: escala(1,05);
        }
        
        .conteúdo-carrossel {
            alinhamento de texto: centro;
            largura: 100%;
        }
        
        .conteúdo do carrossel h3 {
            tamanho da fonte: clamp(1.4rem, 4vw, 1.5rem);
            margem inferior: 12px;
            cor: var(--accent);
        }
        
        .conteúdo do carrossel p {
            cor: var(--texto);
            margem inferior: 15px;
            opacidade: 0,9;
            tamanho da fonte: clamp(0.9rem, 3vw, 1rem);
            espessura da fonte: 500;
        }
        
        .carousel-content ul {
            estilo de lista: nenhum;
            margem: 15px 0;
            alinhamento de texto: esquerda;
            preenchimento: 0 15px;
        }
        
        .carousel-content ul li {
            margem inferior: 8px;
            preenchimento-esquerdo: 25px;
            posição: relativa;
            tamanho da fonte: clamp(0,9rem, 2,5vw, 0,95rem);
            cor: var(--texto);
            altura da linha: 1,5;
        }
        
        .carousel-content ul li:antes {
            conteúdo: "✓";
            cor: var(--accent);
            posição: absoluta;
            esquerda: 0;
            espessura da fonte: negrito;
            tamanho da fonte: 1.1rem;
        }
        
        /* Botão Ver Serviços Completos */
        .serviços-btn-container {
            margem superior: 25px;
            alinhamento de texto: centro;
        }
        
        .serviços-btn {
            exibição: inline-flex;
            alinhar-itens: centro;
            lacuna: 8px;
            preenchimento: 14px 22px;
            fundo: var(--accent);
            cor: var(--primary);
            decoração de texto: nenhuma;
            raio da borda: 50px;
            espessura da fonte: 600;
            transição: todos os 0,3s;
            caixa-sombra: 0 4px 12px rgba(192, 192, 192, 0.4);
            tamanho da fonte: clamp(14px, 3vw, 16px);
            altura mínima: 44px;
        }
        
        .serviços-btn:hover {
            transformar: translateY(-3px);
            caixa-sombra: 0 6px 18px rgba(192, 192, 192, 0.6);
            plano de fundo: var(--accent-hover);
        }
        
        /* Controles do carrossel */
        .controles-carrossel {
            posição: absoluta;
            topo: 50%;
            esquerda: 0;
            direita: 0;
            exibição: flexível;
            justificar-conteúdo: espaço-entre;
            alinhar-itens: centro;
            transformar: traduzirY(-50%);
            preenchimento: 0 15px;
            eventos de ponteiro: nenhum;
        }
        
        .seta-carrossel {
            fundo: rgba(255, 255, 255, 0.1);
            largura: clamp(30px, 8vw, 40px);
            altura: clamp(30px, 8vw, 40px);
            raio da borda: 50%;
            exibição: flexível;
            alinhar-itens: centro;
            justificar-conteúdo: centro;
            cursor: ponteiro;
            transição: todos os 0,3s;
            borda: 1px sólido rgba(255, 255, 255, 0.2);
            tamanho da fonte: clamp(14px, 4vw, 16px);
            cor: var(--accent);
            eventos de ponteiro: automático;
        }
        
        .seta-carrossel:passe o mouse {
            fundo: rgba(192, 192, 192, 0.2);
            transformar: escala(1.1);
        }
        
        .indicadores-carrossel {
            exibição: flexível;
            justificar-conteúdo: centro;
            lacuna: 10px;
            margem: 20px 0 10px;
        }
        
        .indicador {
            largura: 10px;
            altura: 10px;
            raio da borda: 50%;
            fundo: rgba(255, 255, 255, 0.3);
            cursor: ponteiro;
            transição: todos os 0,3s;
        }
        
        .indicador.ativo {
            fundo: var(--accent);
            transformar: escala(1.2);
        }
        
        /* Produtos */
        .produtos {
            preenchimento: 60px 0;
            fundo: var(--primário);
        }
        
        .produtos-simples {
            largura máxima: min(800px, 90vw);
            margem: 0 automático;
            fundo: var(--card-bg);
            raio da borda: 12px;
            preenchimento: 30px;
            filtro de pano de fundo: desfoque(10px);
            borda: 1px sólido var(--card-border);
            alinhamento de texto: centro;
        }
        
        .produtos-simples h3 {
            cor: var(--accent);
            margem inferior: 20px;
            tamanho da fonte: clamp(1.3rem, 4vw, 1.5rem);
        }
        
        .lista de produtos {
            estilo de lista: nenhum;
            margem inferior: 25px;
            alinhamento de texto: esquerda;
        }
        
        .lista de produtos li {
            margem inferior: 12px;
            preenchimento-esquerdo: 25px;
            posição: relativa;
            tamanho da fonte: clamp(0,9rem, 2,5vw, 0,95rem);
            cor: var(--texto);
        }
        
        .lista de produtos li:antes {
            conteúdo: "✓";
            cor: var(--accent);
            posição: absoluta;
            esquerda: 0;
            espessura da fonte: negrito;
            tamanho da fonte: 1rem;
        }
        
        .produto-btn {
            exibição: inline-flex;
            alinhar-itens: centro;
            lacuna: 8px;
            preenchimento: clamp(12px, 3vw, 14px) clamp(24px, 5vw, 28px);
            fundo: var(--accent);
            cor: var(--primary);
            decoração de texto: nenhuma;
            raio da borda: 50px;
            espessura da fonte: 600;
            transição: todos os 0,3s de facilidade;
            caixa-sombra: 0 4px 12px rgba(192, 192, 192, 0.4);
            tamanho da fonte: clamp(0,9rem, 2,5vw, 1rem);
            borda: nenhuma;
            cursor: ponteiro;
            altura mínima: 44px;
        }
        
        .produto-btn:passe o mouse {
            transformar: translateY(-3px);
            caixa-sombra: 0 6px 18px rgba(192, 192, 192, 0.6);
            plano de fundo: var(--accent-hover);
        }
        
        /* Sobre */
        .sobre {
            preenchimento: 60px 0;
            plano de fundo: gradiente linear (135 graus, var (--secundário) 0%, var (--primário) 100%);
            alinhamento de texto: centro;
        }
        
        .sobre-conteúdo {
            largura máxima: min(800px, 90vw);
            margem: 0 automático;
        }
        
        .sobre-texto p {
            tamanho da fonte: clamp(0,9rem, 2,5vw, 1rem);
            margem inferior: 25px;
            opacidade: 0,9;
            altura da linha: 1,7;
            cor: var(--text-muted);
        }
        
        .sobre-recursos {
            exibição: grade;
            grid-template-columns: repetir(ajuste automático, minmax(min(220px, 100%), 1fr));
            lacuna: 12px;
            margem superior: 25px;
        }
        
        .sobre-recurso {
            exibição: flexível;
            alinhar-itens: centro;
            lacuna: 10px;
            preenchimento: 12px;
            fundo: var(--card-bg);
            raio da borda: 12px;
            transição: transformação 0,3s facilidade;
            alinhamento de texto: esquerda;
        }
        
        .sobre-recurso:hover {
            transformar: translateX(5px);
            fundo: rgba(192, 192, 192, 0.1);
        }
        
        .sobre-recurso i {
            cor: var(--accent);
            tamanho da fonte: clamp(1rem, 3vw, 1.2rem);
            largura: 25px;
        }
        
        .sobre-recurso span {
            tamanho da fonte: clamp(0,85rem, 2,5vw, 0,9rem);
            espessura da fonte: 500;
            cor: var(--texto);
        }
        
        /* Contato */
        .contato {
            preenchimento: 50px 0 30px;
            fundo: var(--primário);
            alinhamento de texto: centro;
        }
        
        .horário comercial {
            fundo: var(--card-bg);
            preenchimento: 20px;
            raio da borda: 12px;
            alinhamento de texto: centro;
            filtro de pano de fundo: desfoque(10px);
            borda: 1px sólido var(--card-border);
            largura máxima: min(380px, 90vw);
            margem: 0 automático;
            animação: fadeIn 1s de facilidade;
        }
        
        .horário comercial h4 {
            cor: var(--accent);
            margem inferior: 12px;
            tamanho da fonte: clamp(1rem, 3vw, 1.1rem);
            espessura da fonte: 600;
            exibição: flexível;
            alinhar-itens: centro;
            justificar-conteúdo: centro;
            lacuna: 8px;
        }
        
        .horário comercial p {
            margem inferior: 6px;
            tamanho da fonte: clamp(0,8rem, 2,5vw, 0,9rem);
            opacidade: 0,9;
            cor: var(--texto);
        }
        
        /* Rodapé */
        rodapé {
            fundo: #0a0a0a;
            preenchimento: 20px 0 12px;
            borda superior: 1px sólido rgba(192, 192, 192, 0.2);
        }
        
        .rodapé-conteúdo {
            exibição: grade;
            colunas de modelo de grade: 1fr 2fr 1fr;
            lacuna: 15px;
            margem inferior: 15px;
            alinhar-itens: centro;
        }
        
        .rodapé-logotipo {
            exibição: flexível;
            alinhar-itens: centro;
            lacuna: 8px;
        }
        
        .rodapé-logotipo .logotipo-img {
            largura: 30px;
            altura: 30px;
            tamanho da fonte: 14px;
        }
        
        .footer-logo span {
            tamanho da fonte: clamp(0,8rem, 2,5vw, 0,85rem);
            espessura da fonte: 700;
            cor: var(--accent);
        }
        
        .rodapé-contato {
            alinhamento de texto: centro;
        }
        
        .rodapé-contato p {
            margem inferior: 4px;
            opacidade: 0,9;
            tamanho da fonte: clamp(0,7rem, 2vw, 0,75rem);
            exibição: flexível;
            justificar-conteúdo: centro;
            alinhar-itens: centro;
            lacuna: 4px;
            cor: var(--texto);
        }
        
        .rodapé-social {
            exibição: flexível;
            lacuna: 10px;
            justificar-conteúdo: flex-end;
        }
        
        .link social {
            largura: 34px;
            altura: 34px;
            fundo: rgba(255, 255, 255, 0.1);
            raio da borda: 50%;
            exibição: flexível;
            alinhar-itens: centro;
            justificar-conteúdo: centro;
            cor: var(--texto);
            decoração de texto: nenhuma;
            transição: todos os 0,3s de facilidade;
            tamanho da fonte: 0,9rem;
        }
        
        .link social:passe o mouse {
            fundo: var(--accent);
            cor: var(--primary);
            transformar: translateY(-2px);
            caixa-sombra: 0 4px 12px rgba(192, 192, 192, 0.4);
        }
        
        /* Correções específicas do Instagram WebView */
        .instagram-webview .herói {
            altura mínima: calc(60vh - 70px) !importante;
        }
        
        .instagram-webview .btn {
            altura mínima: 44px !importante;
            exibição: flex !importante;
            alinhar-itens: centro !importante;
            justificar-conteúdo: centro !importante;
        }
        
        /* Prevenir problemas de rolagem no Instagram */
        .instagram-webview corpo {
            estouro: oculto !importante;
            altura: 100% !importante;
            posição: relativa;
        }
        
        /* Melhorar a visualização de imagens */
        .instagram-webview img {
            transformar: translateZ(0);
        }
        
        /* Indicador de animação de rolagem */
        .indicador de rolagem {
            posição: fixa;
            topo: 50%;
            direita: 20px;
            transformar: traduzirY(-50%);
            exibição: flexível;
            flex-direction: coluna;
            lacuna: 15px;
            índice z: 998;
        }
        
        .scroll-ponto {
            largura: 12px;
            altura: 12px;
            raio da borda: 50%;
            fundo: rgba(255, 255, 255, 0.3);
            borda: 2px sólido transparente;
            transição: todos os 0,3s de facilidade;
            cursor: ponteiro;
        }
        
        .scroll-dot.ativo {
            fundo: var(--accent);
            transformar: escala(1.3);
            cor da borda: rgba(255, 255, 255, 0.5);
        }
        
        .scroll-dot:passe o mouse {
            plano de fundo: var(--accent-hover);
            transformar: escala(1.2);
        }
        
        /* Destaque de seção durante a rolagem */
        .seção-destaque {
            posição: relativa;
        }
        
        .section-highlight::antes de {
            contente: '';
            posição: absoluta;
            topo: -5px;
            esquerda: -5px;
            direita: -5px;
            inferior: -5px;
            borda: 2px sólido var(--accent);
            raio da borda: 10px;
            animação: destaque com facilidade de 1,5s;
            opacidade: 0;
        }
        
        @keyframes destaque {
            0% {
                opacidade: 0;
                transformar: escala(0,95);
            }
            50% {
                opacidade: 1;
                transformar: escala(1.02);
            }
            100% {
                opacidade: 0;
                transformar: escala(1);
            }
        }
        
        @quadros-chave fadeIn {
            de {
                opacidade: 0;
                transformar: translateY(-15px);
            }
            para {
                opacidade: 1;
                transformar: translateY(0);
            }
        }
        
        /* Responsivo */
        @media (largura máxima: 1024px) {
            .rodapé-conteúdo {
                colunas de modelo de grade: 1fr 1fr;
                lacuna: 20px;
            }
            
            .rodapé-contato {
                ordem: 3;
                coluna de grade: intervalo 2;
                alinhamento de texto: centro;
            }
            
            .indicador de rolagem {
                direita: 10px;
            }
        }
        
        @media (largura máxima: 768px) {
            .herói {
                preenchimento: 90px 0 40px;
                altura mínima: 50vh;
            }
            
            .botões de herói {
                justificar-conteúdo: centro;
            }
            
            .título-da-seção {
                tamanho da fonte: 1,7rem;
            }
            
            .rodapé-conteúdo {
                colunas de modelo de grade: 1fr;
                alinhamento de texto: centro;
                lacuna: 15px;
            }
            
            .rodapé-contato {
                ordem: 0;
                coluna de grade: intervalo 1;
            }
            
            .rodapé-social {
                justificar-conteúdo: centro;
            }
            
            /* Menu móvel */
            .menu-alternar {
                exibição: flexível;
            }
            
            navegação {
                posição: fixa;
                topo: 70px;
                esquerda: 0;
                largura: 100%;
                fundo: rgba(17, 17, 17, 0,98);
                flex-direction: coluna;
                preenchimento: 15px;
                lacuna: 10px;
                transformar: traduzirY(-100%);
                opacidade: 0;
                visibilidade: oculto;
                transição: todos os 0,3s de facilidade;
                caixa-sombra: 0 10px 20px rgba(0, 0, 0, 0.2);
            }
            
            nav.ativo {
                transformar: translateY(0);
                opacidade: 1;
                visibilidade: visível;
            }
            
            .grade de recursos {
                grid-template-columns: repetir(ajuste automático, minmax(150px, 1fr));
                lacuna: 12px;
            }
            
            .recurso {
                preenchimento: 15px 12px;
            }
            
            .horário comercial {
                largura máxima: 90%;
            }
            
            .controles-carrossel {
                preenchimento: 0 5px;
            }
            
            .indicador de rolagem {
                exibição: nenhuma;
            }
        }
        
        @media (largura máxima: 480px) {
            .herói {
                altura mínima: 40vh;
                preenchimento: 80px 0 30px;
            }
            
            .botões de herói {
                flex-direction: coluna;
                alinhar-itens: centro;
            }
            
            .btn {
                largura: 100%;
                largura máxima: 280px;
                justificar-conteúdo: centro;
            }
            
            .rodapé-conteúdo {
                lacuna: 12px;
            }
            
            .título-da-seção {
                tamanho da fonte: 1,6rem;
            }
            
            .indicador {
                largura: 8px;
                altura: 8px;
            }
            
            .carousel-content ul li {
                tamanho da fonte: 0,9rem;
            }
        }
        
        /* Orientação paisagem em dispositivos móveis */
        @media screen e (altura máxima: 480px) e (orientação: paisagem) {
            .herói {
                altura mínima: 100vh !importante;
                preenchimento: 80px 0 !importante;
            }
            
            .conteúdo do herói {
                preenchimento superior: 20px;
            }
        }
        
        /* Efeito de fade-in para os frascos */
        seção {
            opacidade: 0;
            transformar: translateY(40px);
            transição: todos os 0,8s de facilidade;
        }
        
        seção.visível {
            opacidade: 1;
            transformar: translateY(0);
        }
    </estilo>
</head>
<corpo>
    <!-- Botão Voltar ao topo -->
    <div class="voltar ao topo">
        <i class="fas fa-seta-para-cima"></i>
    </div>
    
    <!-- Indicador de rolagem ATUALIZADO -->
    <div class="indicador de rolagem">
        <div class="scroll-dot" data-section="hero" title="Início"></div>
        <div class="scroll-dot" data-section="servicos" title="Serviços"></div>
        <div class="scroll-dot" data-section="produtos" title="Produtos"></div>
        <div class="scroll-dot" data-section="sobre" title="Sobre"></div>
        <div class="scroll-dot" data-section="contato" title="Contato"></div>
    </div>
    
    <!-- Cabeçalho -->
    <cabeçalho>
        <div class="container">
            <div class="logotipo">
                <div class="logo-img">
                    <i class="fas fa-cut"></i>
                </div>
                <h1>BARBEARIA CLÁSSICA</h1>
            </div>
            <botão class="menu-toggle">
                <span></span>
                <span></span>
                <span></span>
            </botão>
            <navegação>
                <a href="#servicos">Serviços</a>
                <a href="#produtos">Produtos</a>
                <a href="#sobre">Sobre</a>
                <a href="#contato">Contato</a>
            </navegação>
        </div>
    </cabeçalho>
    
    <!-- Seção de Heróis -->
    <seção class="herói" id="herói">
        <div class="container">
            <div class="hero-content">
                <h2>ESTILO E TRADIÇÃO</h2>
                <p>A melhor barbearia de Araxá e região</p>
                <div class="botões-herói">
                    <a href="https://wa.me/553499269707?text=Olá! Gostaria de agendar um horário na barbearia ✂️" class="btn whatsapp-btn">
                        <i class="fab fa-whatsapp"></i> Agendar Horário
                    </a>
                    <a href="https://www.instagram.com/barbeariaestiloclassico" class="btn instagram-btn">
                        <i class="fab fa-instagram"></i> Instagram
                    </a>
                    <a href="https://maps.app.goo.gl/Z6brWy7twMynjEsm7" class="btn localização-btn">
                        <i class="fas fa-map-marker-alt"></i> Localização
                    </a>
                    <!-- BOTÃO MODIFICADO -->
                    <a href="#servicos" class="btn serviços-herói-btn">
                        <i class="fas fa-cut"></i> Ver Serviços
                    </a>
                </div>
            </div>
        </div>
    </seção>
    
    <!-- Recursos -->
    <section class="recursos">
        <div class="container">
            <div class="grade de recursos">
                <div class="recurso">
                    <i class="fas fa-cut"></i>
                    <h4>Cortes Modernos</h4>
                    <p>Estilo e precisão em cada corte</p>
                </div>
                <div class="recurso">
                    <i class="fas fa-user-tie"></i>
                    <h4>Profissionais</h4>
                    <p>Barbeiros qualificados</p>
                </div>
                <div class="recurso">
                    <i class="fas fa-spa"></i>
                    <h4>Relaxamento</h4>
                    <p>Ambiente climatizado</p>
                </div>
                <div class="recurso">
                    <i class="fas fa-star"></i>
                    <h4>Qualidade</h4>
                    <p>Produtos premium</p>
                </div>
            </div>
        </div>
    </seção>
    
    <!-- Seção de Serviços MODIFICADA -->
    <seção id="serviços" class="serviços">
        <div class="container">
            <h2 class="section-title">Nossos Serviços</h2>
            <div class="carrossel de serviços" id="carrossel de serviços">
                <div class="carrossel-container" id="carrossel-serviços">
                    <!-- Corte de Cabelo -->
                    <div class="carrossel-slide">
                        <div class="carrossel-img">
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
                            <div class="serviços-btn-container">
                                <a href="https://wa.me/553499269707?text=Olá! Gostaria de saber mais sobre os serviços de barbearia ✂️" class="services-btn">
                                    <i class="fas fa-list"></i> Ver Todos os Serviços
                                </a>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Barba -->
                    <div class="carrossel-slide">
                        <div class="carrossel-img">
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
                            <div class="serviços-btn-container">
                                <a href="https://wa.me/553499269707?text=Olá! Gostaria de saber mais sobre os serviços de barbearia ✂️" class="services-btn">
                                    <i class="fas fa-list"></i> Ver Todos os Serviços
                                </a>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Combo Completo -->
                    <div class="carrossel-slide">
                        <div class="carrossel-img">
                            <img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Combo Completo">
                        </div>
                        <div class="carousel-content">
                            <h3>Combo Completo</h3>
                            <p>Corte + Barba com desconto especial</p>
                            <ul>
                                <li>✂️ Corte de cabelo completo</li>
                                <li>🧔 Tratamento para barba</li>
                                <li>🧴Produtos premium</li>
                                <li>💆‍♂️ Massagem relaxante</li>
                                <li>💰 Desconto especial</li>
                            </ul>
                            <!-- BOTÃO VER SERVIÇOS COMPLETOS ADICIONADO DENTRO DO RETÂNGULO -->
                            <div class="serviços-btn-container">
                                <a href="https://wa.me/553499269707?text=Olá! Gostaria de saber mais sobre os serviços de barbearia ✂️" class="services-btn">
                                    <i class="fas fa-list"></i> Ver Todos os Serviços
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Controles do carrossel -->
                <div class="controles-carrossel">
                    <div class="carrossel-seta anterior" id="serviços-anteriores">
                        <i class="fas fa-chevron-left"></i>
                    </div>
                    <div class="carousel-arrow próximo" id="next-services">
                        <i class="fas fa-chevron-right"></i>
                    </div>
                </div>
            </div>
            
            <!-- Indicadores -->
            <div class="carrossel-indicadores" id="indicadores-serviços">
                <div class="indicador ativo" data-index="0"></div>
                <div class="indicador" índice de dados="1"></div>
                <div class="indicador" índice de dados="2"></div>
            </div>
        </div>
    </seção>
    
    <!-- Produtos -->
    <section id="produtos" class="products">
        <div class="container">
            <h2 class="section-title">Produtos e Acessórios</h2>
            <div class="produtos-simples">
                <h3>Produtos de Qualidade</h3>
                <ul class="lista-de-produtos">
                    <li>Pomadas e ceras para cabelo</li>
                    <li>Óleos e bálsamos para barba</li>
                    <li>Shampoo e condicionadores específicos</li>
                    <li>Navalhas e lâminas de qualidade</li>
                    <li>Kits de cuidados masculinos</li>
                    <li>Perfumes e colônias masculinas</li>
                </ul>
                <a href="https://wa.me/553499269707?text=Olá! Gostaria de saber mais sobre os produtos da barbearia ✂️" class="product-btn">
                    <i class="fab fa-whatsapp"></i> Consultar Produtos
                </a>
            </div>
        </div>
    </seção>
    
    <!-- Sobre -->
    <section id="sobre" class="about">
        <div class="container">
            <div class="sobre-conteúdo">
                <h2 class="section-title">Barbearia Estilo Clássico</h2>
                <div class="sobre-texto">
                    <p>Especialistas em cortes masculinos com os melhores preços e atendimento personalizado em Araxá e região. Tradição e modernidade em um só lugar, com profissionais variados e produtos de alta qualidade.</p>
                    <div class="sobre-recursos">
                        <div class="sobre-recurso">
                            <i class="fas fa-check-circle"></i>
                            <span>Produtos de qualidade</span>
                        </div>
                        <div class="sobre-recurso">
                            <i class="fas fa-check-circle"></i>
                            <span>Atendimento personalizado</span>
                        </div>
                        <div class="sobre-recurso">
                            <i class="fas fa-user-tie"></i>
                            <span>Configurações profissionais</span>
                        </div>
                        <div class="sobre-recurso">
                            <i class="fas fa-clock"></i>
                            <span>Horários flexíveis</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </seção>
    
    <!-- Contato -->
    <seção id="contato" class="contato">
        <div class="container">
            <div class="horário-comercial">
                <h4><i class="far fa-clock"></i> Horário de Funcionamento</h4>
                <p>Segunda a Sexta: 8h às 19h</p>
                <p>Sábado: 8h às 18h</p>
                <p>Domingo: 9h às 13h</p>
            </div>
        </div>
    </seção>
    
    <!-- Rodapé -->
    <rodapé>
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
    </rodapé>
    
    <script>
        // ===== DETECÇÃO DE WEBVIEW DO INSTAGRAM =====
        função isInInstagramWebView() {
            const userAgent = navigator.userAgent || navigator.vendor || window.opera;
            retornar /Instagram/i.test(userAgent) || /FBAN|FBAV/i.test(userAgent);
        }
        
        // Aplicar aulas específicas para WebView do Instagram
        função applyInstagramFix() {
            se (isInInstagramWebView()) {
                document.body.classList.add('instagram-webview');
                const estilo = document.createElement('estilo');
                estilo.textContent = `
                    [classe="banner"], [id*="banner"], [classe*="Banner"], [id*="Banner"] {
                        exibição: nenhuma !importante;
                    }
                    .btn, a, botão {
                        cursor: ponteiro !importante;
                        z-index: 9999 !importante;
                        posição: relativa;
                    }
                    corpo {
                        -webkit-overflow-scrolling: toque em !importante;
                    }
                    .herói {
                        posição: relativa;
                        índice z: 1;
                    }
                `;
                document.head.appendChild(estilo);
            }
        }
        
        // ===== SCROLL SUAVE NATIVO - AGORA FEITO VIA CSS =====
        // O scroll suave agora é implementado via CSS com scroll-behavior: smooth
        // Isso funciona melhor no Instagram WebView
        
        // ===== ATUALIZAR INDICADORES DE SCROLL =====
        função updateScrollIndicator() {
            const seções = document.querySelectorAll('seção[id]');
            const scrollDots = document.querySelectorAll('.scroll-dot');
            const scrollPosition = janela.scrollY;
            
            seções.forEach(seção => {
                const sectionTop = seção.offsetTop - 100;
                const sectionHeight = seção.offsetHeight;
                const sectionId = seção.getAttribute('id');
                
                se (scrollPosition >= sectionTop && scrollPosition < sectionTop + sectionHeight) {
                    scrollDots.forEach(ponto => {
                        dot.classList.remove('ativo');
                        se (dot.getAttribute('seção de dados') === sectionId) {
                            dot.classList.add('ativo');
                        }
                    });
                }
            });
        }
        
        // ===== OBSERVADOR DE INTERSEÇÃO PARA ANIMAÇÕES =====
        const observerOptions = {
            limite: 0,1,
            rootMargin: '0px 0px -50px 0px'
        };
        
        const observer = new IntersectionObserver((entradas) => {
            entradas.paraCada(entrada => {
                se (entrada.isIntersecting) {
                    entrada.target.classList.add('visível');
                }
            });
        }, observerOptions);
        
        // Observar todas as letras
        document.querySelectorAll('seção').forEach(seção => {
            observador.observar(seção);
        });
        
        // ===== ROLAGEM SUAVE PARA LINKS INTERNOS =====
        // Agora usando o método nativo do CSS, mas mantemos a prevenção de comportamento padrão
        função setupSmoothScroll() {
            document.querySelectorAll('a[href^="#"]').forEach(âncora => {
                anchor.addEventListener('clique', função (e) {
                    // Verifique se o link é para uma seção interna
                    const href = this.getAttribute('href');
                    se (href !== '#' && href.startsWith('#')) {
                        e.preventDefault();
                        const targetId = href;
                        const targetElement = document.querySelector(targetId);
                        
                        se (elemento_alvo) {
                            // Usar scroll nativo com comportamento suave (agora controlado pelo CSS)
                            targetElement.scrollIntoView({
                                comportamento: 'suave'
                            });
                            
                            // Fechar menu mobile após clicar em um link
                            se (window.innerWidth <= 768) {
                                document.querySelector('nav').classList.remove('ativo');
                                document.body.style.overflow = 'automático';
                                document.querySelector('.menu-toggle').classList.remove('ativo');
                            }
                        }
                    }
                });
            });
        }
        
        // Navegação pelos pontos do indicador de rolagem
        função setupScrollDots() {
            document.querySelectorAll('.scroll-dot').forEach(ponto => {
                dot.addEventListener('clique', () => {
                    const targetId = '#' + dot.getAttribute('seção de dados');
                    const targetElement = document.querySelector(targetId);
                    
                    se (elemento_alvo) {
                        targetElement.scrollIntoView({
                            comportamento: 'suave'
                        });
                    }
                });
            });
        }
        
        // ===== CARROSSEL DE SERVIÇOS =====
        função setupCarousel(carouselId, prevButtonId, nextButtonId, indicatorsId) {
            const carrossel = document.getElementById(carouselId);
            const slides = carrossel.querySelectorAll('.carousel-slide');
            indicadores const = document.getElementById(indicatorsId).querySelectorAll('.indicator');
            const carouselContainer = carrossel.closest('.services-carousel');
            const prevButton = document.getElementById(prevButtonId);
            const nextButton = document.getElementById(nextButtonId);
            
            deixe currentIndex = 0;
            const slideCount = slides.length;
            deixe autoSlideInterval;
            deixe userInteractionTimeout;
            deixe isDragging = falso;
            deixe startX = 0;
            deixe startScrollLeft = 0;
            
            função updateCarousel() {
                carrossel.style.transform = `translateX(-${currentIndex * 100}%)`;
                
                // Atualizar indicadores
                indicadores.forEach((indicador, índice) => {
                    se (índice === currentIndex) {
                        indicador.classList.add('ativo');
                    } outro {
                        indicator.classList.remove('ativo');
                    }
                });
            }
            
            função nextSlide() {
                ÍndiceAtual = (ÍndiceAtual + 1) % ContagemDeSlides;
                atualizarCarrossel();
                redefinirAutoSlide();
            }
            
            função prevSlide() {
                ÍndiceAtual = (ÍndiceAtual - 1 + ContagemDeSlides) % ContagemDeSlides;
                atualizarCarrossel();
                redefinirAutoSlide();
            }
            
            // Iniciar slides automáticos
            função startAutoSlide() {
                autoSlideInterval = setInterval(() => {
                    próximoSlide();
                }, 5000);
            }
            
            // Parar slides automáticos
            função stopAutoSlide() {
                clearInterval(autoSlideInterval);
            }
            
            // Reiniciar slides automáticos após 26 segundos de inatividade
            função resetAutoSlide() {
                clearTimeout(Tempo limite de interação do usuário);
                pararAutoSlide();
                Tempo limite de interação do usuário = definir tempo limite (() => {
                    iniciarAutoSlide();
                }, 26000);
            }
            
            // Indicadores clicáveis
            indicadores.forEach(indicador => {
                indicador.addEventListener('clique', () => {
                    currentIndex = parseInt(indicador.getAttribute('índice de dados'));
                    atualizarCarrossel();
                    redefinirAutoSlide();
                });
            });
            
            // Botões de navegação
            nextButton.addEventListener('clique', () => {
                próximoSlide();
            });
            
            prevButton.addEventListener('clique', () => {
                anteriorSlide();
            });
            
            // ===== FUNCIONALIDADE DE ARRASTAR =====
            carouselContainer.addEventListener('mousedown', dragStart);
            carouselContainer.addEventListener('touchstart', dragStart, { passivo: verdadeiro });
            carouselContainer.addEventListener('mousemove', arrastar);
            carouselContainer.addEventListener('touchmove', drag, { passive: true });
            carrosselContainer.addEventListener('mouseup', dragEnd);
            carrosselContainer.addEventListener('mouseleave', dragEnd);
            carrosselContainer.addEventListener('touchend', dragEnd);
            
            // Pausar auto slide quando o mouse estiver sobre o carrossel
            carouselContainer.addEventListener('mouseenter', stopAutoSlide);
            carrosselContainer.addEventListener('mouseleave', () => {
                redefinirAutoSlide();
            });
            
            função dragStart(e) {
                isDragging = verdadeiro;
                startX = e.type.includes('mouse') ? e.pageX : e.touches[0].pageX;
                startScrollLeft = carrossel.scrollLeft;
                pararAutoSlide();
                carousel.style.cursor = 'pegando';
                carousel.style.transition = 'nenhum';
            }
            
            função drag(e) {
                se (!isDragging) retornar;
                e.preventDefault();
                
                const x = e.type.includes('mouse') ? e.pageX : e.touches[0].pageX;
                const caminhada = (x - startX) * 2;
                
                se (andar > 50) {
                    anteriorSlide();
                    isDragging = falso;
                    carousel.style.cursor = 'pegar';
                    carousel.style.transition = 'transformar 0,5s de facilidade';
                } senão se (andar < -50) {
                    próximoSlide();
                    isDragging = falso;
                    carousel.style.cursor = 'pegar';
                    carousel.style.transition = 'transformar 0,5s de facilidade';
                }
            }
            
            função dragEnd() {
                isDragging = falso;
                carousel.style.cursor = 'pegar';
                carousel.style.transition = 'transformar 0,5s de facilidade';
                redefinirAutoSlide();
            }
            
            //inicia a apresentação de slides automaticamente
            iniciarAutoSlide();
        }
        
        // ===== MENU MÓVEL ALTERNAR =====
        função setupMobileMenu() {
            const menuToggle = document.querySelector('.menu-toggle');
            const nav = document.querySelector('nav');
            
            menuToggle.addEventListener('clique', () => {
                nav.classList.toggle('ativo');
                menuToggle.classList.toggle('ativo');
                document.body.style.overflow = nav.classList.contains('ativo') ? 'oculto' : 'automático';
            });
        }
        
        // ===== BOTÃO VOLTAR AO TOPO =====
        função setupBackToTop() {
            const backToTopButton = document.querySelector('.back-to-top');
            
            janela.addEventListener('rolagem', () => {
                se (janela.pageYOffset > 300) {
                    backToTopButton.classList.add('visível');
                } outro {
                    backToTopButton.classList.remove('visível');
                }
                
                atualizarScrollIndicator();
            });
            
            backToTopButton.addEventListener('clique', () => {
                janela.scrollTo({
                    topo: 0,
                    comportamento: 'suave'
                });
            });
        }
        
        // ===== INICIALIZAÇÃO GERAL =====
        documento.addEventListener('DOMContentLoaded', função() {
            // Inicializar alguns trechos como visíveis
            document.querySelector('.hero').classList.add('visível');
            
            // Aplicar correções para Instagram
            aplicarInstagramFix();
            
            // Configurar funcionalidades
            configuraçãoSmoothScroll();
            configuraçãoScrollDots();
            
            //Configura carrossel de serviços
            setupCarousel('serviços-carrossel', 'serviços-anteriores', 'próximos-serviços', 'serviços-indicadores');
            
            setupMobileMenu();
            configuraçãoBackToTop();
            
            // Atualizar indicador de rolagem
            atualizarScrollIndicator();
        });
        
        // Altura recalcular do viewport em redimensionamento
        window.addEventListener('redimensionar', () => {
            document.querySelectorAll('seção').forEach(seção => {
                observador.observar(seção);
            });
        });
    </script>
</corpo>
</html>
