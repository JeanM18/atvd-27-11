<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Perfil</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000000;
        }

        /* Estilo do cabeçalho */
        header {
            background-color: #000000;
            color: rgb(245, 245, 245);
            text-align: center;
            padding: 20px;
        }

        /* Estilo do contêiner flexível */
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around; /* Distribui os perfis ao redor do espaço disponível */
            padding: 20px;
        }

        /* Estilo do perfil individual */
        .profile {
            flex: 1; /* Ocupa uma parte flexível do contêiner */
            background-color: #ffffff;
            margin: 10px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgb(0, 0, 0);
        }

        /* Estilo da imagem do perfil */
        .profile img {
            width: 100%;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        /* Estilo do rodapé */
        footer {
            background-color: #000000;
            color: rgb(253, 253, 253);
            text-align: center;
            padding: 10px;
            position: fixed; /* Fixa o rodapé na parte inferior da tela */
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <!-- Cabeçalho -->
    <header>
        <h1>Meu Perfil</h1>
    </header>

    <!-- Contêiner de perfis -->
    <div class="container">
        <!-- Perfil 1 -->
        <div class="profile">
            <img src="transferir (1).jpeg" alt="Minha Foto">
            <h2>compra</h2>
            <p>Descrição</p> 
                </p>celulares de marcas iphones e xiaomi</p>
        </div>

        <!-- Perfil 2 -->
        <div class="profile">
            <img src="transferir (2).jpeg" alt="Minha Foto 2">
            <h2>celular samsung galaxy A21s</h2>
            <p>Ele é um aparelho grande devido à tela de 6,5 polegadas. Poderia ter bordas mais finas para ajudar, mas até que está melhor do que temos no A20s. A qualidade de construção é boa e a pintura tem um leve efeito cromático que é mais discreto do que vimos no A30s.</p>
        </div>

        <!-- Adicione mais perfis conforme necessário -->

    </div>

    <!-- Rodapé -->
    <footer>
        &copy; 2023 Meu Perfil
    </footer>

</body>
</html>
