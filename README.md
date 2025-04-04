<!DOCTYPE html><html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Online</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        html, body {
            height: 100%;
        }
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .banner {
            text-align: center;
            background: #f4f4f4;
            padding: 50px 20px;
        }
        .products {
            padding: 20px;
            text-align: center;
        }
        .product-grid {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .product {
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 10px;
            width: 200px;
            max-width: 90%;
        }
        .product img {
            width: 100%;
            border-radius: 5px;
        }
        .product button {
            background: #333;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            margin-top: 10px;
            border-radius: 5px;
        }
        .product button:hover {
            background: #555;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: auto;
        }
        @media (max-width: 600px) {
            .product-grid {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Minha Loja</h1>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#products">Produtos</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header><section id="home" class="banner">
    <h2>Bem-vindo à Nossa Loja!</h2>
    <p>Encontre os melhores produtos aqui.</p>
</section>

<section id="products" class="products">
    <h2>Produtos</h2>
    <div class="product-grid">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Produto 1">
            <h3>Produto 1</h3>
            <p>R$ 99,90</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Produto 2">
            <h3>Produto 2</h3>
            <p>R$ 149,90</p>
            <button>Comprar</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Produto 3">
            <h3>Produto 3</h3>
            <p>R$ 199,90</p>
            <button>Comprar</button>
        </div>
    </div>
</section>

<footer id="contact">
    <p>Entre em contato: contato@minhaloja.com</p>
</footer>

</body>
</html>
