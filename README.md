<!DOCTYPE html>
<html lang="pt-PT">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>O Meu Site JavaScript</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Menu de Navegação -->
    <header>
        <div class="logo">DevSite</div>
        <nav>
            <a href="#inicio">Início</a>
            <a href="#servicos">Serviços</a>
            <a href="#contacto">Contacto</a>
            <button id="theme-toggle">🌙</button>
        </nav>
    </header>

    <!-- Secção Principal / Hero -->
    <section id="inicio" class="hero">
        <h1>Bem-vindo ao Futuro do Desenvolvimento</h1>
        <p>Criamos soluções digitais incríveis utilizando JavaScript moderno, HTML5 e CSS3.</p>
        <button onclick="scrollToSection('contacto')">Começar Agora</button>
    </section>

    <!-- Secção de Serviços -->
    <section id="servicos" class="services">
        <h2>O Que Fazemos</h2>
        <div class="card-container">
            <div class="card">
                <h3>Designs Modernos</h3>
                <p>Interfaces limpas, intuitivas e totalmente adaptáveis a qualquer ecrã de telemóvel ou PC.</p>
            </div>
            <div class="card">
                <h3>Código Otimizado</h3>
                <p>Aplicações rápidas e eficientes escritas com as melhores práticas de JavaScript.</p>
            </div>
        </div>
    </section>

    <!-- Secção de Contacto -->
    <section id="contacto" class="contact">
        <h2>Fale Connosco</h2>
        <form id="contact-form">
            <input type="text" id="name" placeholder="O seu nome" required>
            <input type="email" id="email" placeholder="O seu e-mail" required>
            <textarea id="message" placeholder="A sua mensagem" rows="5" required></textarea>
            <button type="submit">Enviar Mensagem</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 DevSite. Todos os direitos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
