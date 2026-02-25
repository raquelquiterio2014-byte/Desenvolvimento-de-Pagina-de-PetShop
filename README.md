# Desenvolvimento-de-Pagina-de-PetShop
/petshop-aumiaus

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PetShop AuMiaus</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>

    <!-- Cabeçalho -->
    <header>
        <div class="container-header">
            <img src="logo.png" alt="Logo AuMiaus" class="logo">
            <h1>PetShop AuMiaus</h1>
        </div>
    </header>

    <!-- Sobre nós -->
    <section id="sobre">
        <h2>🐾 Sobre Nós</h2>
        <p>
            No PetShop AuMiaus, cuidamos do seu pet como se fosse da nossa família!
            Oferecemos serviços de alta qualidade com profissionais apaixonados por animais.
            Nosso diferencial está no carinho, segurança e bem-estar de cada cliente de quatro patas.
        </p>
    </section>

    <!-- Serviços -->
    <section id="servicos">
        <h2>🛁 Serviços</h2>
        <ul>
            <li>Banho e tosa profissional</li>
            <li>Consultas veterinárias</li>
            <li>Adestramento</li>
            <li>Venda de rações e acessórios</li>
            <li>Hotelzinho para pets</li>
        </ul>
    </section>

    <!-- Contato -->
    <section id="contato">
        <h2>📞 Contato</h2>
        <p><strong>Endereço:</strong> Rua dos Animais, 123 - Campinas/SP</p>
        <p><strong>Telefone:</strong> (19) 99999-9999</p>
        <p>
            <strong>Email:</strong> 
            <a href="mailto:contato@petshopaumiaus.com.br">
                contato@petshopaumiaus.com.br
            </a>
        </p>
    </section>

    /* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Corpo */
body {
    font-family: Arial, sans-serif;
    background-color: #fef6f0;
    color: #333;
    line-height: 1.6;
}

/* Cabeçalho */
header {
    background-color: #ff914d;
    color: white;
    padding: 20px;
    text-align: center;
}

.container-header {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 15px;
}

.logo {
    width: 60px;
    height: 60px;
}

/* Seções */
section {
    padding: 40px 20px;
    max-width: 800px;
    margin: auto;
}

/* Títulos */
h1 {
    font-size: 2rem;
}

h2 {
    color: #ff6f3c;
    margin-bottom: 15px;
}

/* Lista */
ul {
    list-style: none;
}

ul li {
    background: #ffe0cc;
    margin: 10px 0;
    padding: 10px;
    border-radius: 8px;
}

/* Links */
a {
    color: #ff6f3c;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    text-decoration: underline;
}

/* Rodapé */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
}

/* Responsividade */
@media (max-width: 600px) {
    .container-header {
        flex-direction: column;
    }

    h1 {
        font-size: 1.5rem;
    }
}

    <!-- Rodapé -->
    <footer>
        <p>© 2026 PetShop AuMiaus - Todos os direitos reservados</p>
    </footer>

</body>
</html>
