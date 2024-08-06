<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tremlipe Studios - Mixagem e Masterização</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav {
            margin: 0;
            padding: 0;
            list-style: none;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0.5rem 1rem;
        }
        section {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
            background: #fff;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
        }
        .service {
            flex: 1;
            margin: 0.5rem;
            padding: 1rem;
            background: #e0e0e0;
            border-radius: 8px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
        }
        .contact-form {
            margin: 2rem 0;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.5rem;
            margin: 0.5rem 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .contact-form button {
            background: #333;
            color: #fff;
            border: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tremlipe Studios</h1>
        <nav>
            <a href="#services">Serviços</a>
            <a href="#about">Sobre</a>
            <a href="#contact">Contato</a>
        </nav>
    </header>

    <section id="services">
        <h2>Serviços de Mixagem e Masterização</h2>
        <div class="services">
            <div class="service">
                <h3>Mixagem Ilimitada</h3>
                <p>Pacote completo de mixagem para suas músicas, com ajustes detalhados e aprimoramento do som.</p>
            </div>
            <div class="service">
                <h3>Masterização Ilimitada</h3>
                <p>Serviço de masterização para garantir que suas faixas soem perfeitas em qualquer sistema de reprodução.</p>
            </div>
            <div class="service">
                <h3>Plano de Mix/Master Ilimitada</h3>
                <p>Obtenha mixagem e masterização ilimitadas com nosso plano exclusivo. Ideal para artistas que precisam de serviços constantes.</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>Sobre Nós</h2>
        <p>Na Tremlipe Studios, oferecemos serviços profissionais de mixagem e masterização para ajudar suas músicas a alcançarem o seu melhor potencial. Com anos de experiência e um compromisso com a qualidade, estamos aqui para transformar suas ideias em músicas perfeitas.</p>
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <p>Para mais informações ou para contratar nossos serviços, preencha o formulário abaixo:</p>
        <form class="contact-form">
            <input type="text" name="name" placeholder="Seu Nome" required>
            <input type="email" name="email" placeholder="Seu E-mail" required>
            <textarea name="message" rows="4" placeholder="Sua Mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Tremlipe Studios. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
