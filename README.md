<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilo.css">
    <title>Página com Unidades de Medida CSS</title>
</head>
<body>
    <header>
        <h1>Meu Cabeçalho</h1>
        <nav>
            <ul>
                <li><a href="#section1">Seção 1</a></li>
                <li><a href="#section2">Seção 2</a></li>
                <li><a href="#section3">Seção 3</a></li>
            </ul>
        </nav>
    </header>
    
    <article>
        <h2 id="section1">Seção 1</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </article>
    
    <section>
        <h2 id="section2">Seção 2</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </section>
    
    <section>
        <h2 id="section3">Seção 3</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </section>
</body>
</html>
/* Reset de estilos básicos */
body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
}

/* Estilo para o cabeçalho */
header {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}

/* Estilo para as âncoras como botões */
nav ul {
    list-style-type: none;
}

nav li {
    display: inline;
    margin-right: 10px;
}

nav a {
    text-decoration: none;
    background-color: #007bff;
    color: white;
    padding: 5px 10px;
    border: 1px solid #007bff;
    border-radius: 5px;
}

/* Estilo para as seções */
article, section {
    margin: 20px;
    padding: 20px;
    border: 1px solid #ccc;
}

/* Estilo para os títulos das seções */
h2 {
    font-size: 1.5rem; /* Unidade relativa (rem) */
    margin-bottom: 10px;
}
