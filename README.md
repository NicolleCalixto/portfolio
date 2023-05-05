# portfolio
<!DOCTYPE html><!-- Declaração do tipo de documento -->
<html lang=" pt-br "> <!-- Abertura da tag html com definição do idioma padrão -->

<head>
    <meta charset=" UTF-8 "> <!-- Definição da codificação de caracteres -->
    <meta http-equiv=" X-UA-Compatible " content=" IE=edge ">
    <!-- Configuração para compatibilidade com Internet Explorer -->
    <meta name="viewport" content="width=device-width, initial-sacale=1.0 ">
    <!-- Configuração da exibição para dispositivos móveis -->
    <link rel=" stylesheet" href="./style.css "><!-- Importação do arquivo CSS -->
    <link rel=" preconnect " href=" https://fonts.googleapis.com ">
    <!-- Configuração da conexão prévia para o Google Fonts -->
    <link rel=" preconnect " href=" https://fonts.gstatic.com " crossorigin>
    <!-- Configuração da conexão prévia para o Google Fonts com cross-origin -->
    <link href=" https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@200;500&display=swap " rel=" stylesheet ">
    <!-- Importação da fonte Josefin Sans do Google Fonts -->
    <título>Nicolle Calixto</título> <!-- Definição do título da página -->
</head>
<!--Fim da seção head, início da seção body-->

<body>
    <!--Div principal com classe "caixa-principal" e id "home"-->
    <div class="caixa-principal" id="home">

        <!--Barra de navegação-->
        <nav>
            <ul><!--Lista de itens de navegação-->

                <!--Item de navegação "Home" com link para o início da página-->
                <li> <a class="link-meunu" href="#home"> Home </a> </li>

                <!--Item de navegação "Sobre" com link para a seção "Sobre" na página-->
                <li> <a class="link-meunu" href="#sobre"> Sobre </a> </li>

                <!--Item de navegação "Projetos" com link para a seção "Projetos" na página-->
                <li> <a class="link-meunu" href="#projetos-id"> Projetos </a> </li>

                <!--Item de navegação "Fale comigo" com link para a seção "Fale comigo" na página-->
                <li> <a class="link-meunu" href="#fale-comigo"> Fale comigo </a> </li>

            </ul>

        </nav>

        <div class="meu-nome">
            <h1>Nicolle <span> Calixto</span></h1>
            <h3>Programadora Front End</h3>
        </div>
    </div>

    <section id="sobre">
        <img src="Nicolle.png">
        <div>
            <h2> Sobre mim </h2>
            <p> Eu sou uma Programadora Front End, já criei projetos e venho procurar a aprender cada vez mais as
                linguagens aplicadas: HTML, CSS,
                JavaScript, React e Java. </p>
            <button> Entre em contato </button>
        </div>
    </section>

    <div class="projetos" id="projetos-id">
        <h2> Principais Projetos </h2>

        <div class="card-projetos">

            <div class=" card">
                <img src="clima.png">
                <h5> Clima </h5>
                <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti ad error harum doloribus
                    labore, odio necessitatibus oficia illum rem veritatis possimus aut </p>
                <a href="https://github.com/NicolleCalixto/Clima.git" target=" _blank "> Ver Projeto </a>
            </div>
            <div class=" card">
                <img src="starbucks.png ">
                <h5> Starbucks </h5>
                <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti ad error harum doloribus
                    labore,
                    odio necessitatibus ofi cia illum rem veritatis possimus aut </p>
                <a href=" https://starbucks-rodolfo.netlify.app/ " target=" _blank "> Ver Projeto </a>
            </div>

            <div class=" card ">
                <img src="crono.png ">
                <h5> Cronometro </h5>
                <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti ad error harum doloribus
                    labore,
                    odio necessitatibus oficia illum rem veritatis possimus aut </p>
                <a href=" https://cronometro-mpdz.netlify.app/ " target=" _blank "> Ver Projeto </a>
            </div>
        </div>
    </div>
    </div>
    <footer id="fale-comigo">

        <h5> Nicolle Calixto </h5>
        <p> Para mais informações </p>
        <div class="social">

            <a href="https://www.linkedin.com/in/nicolle-calixto-67487a208/">
                <img src="linkedin.png">
            </a>

            <a href="tel:+5537999836427">
                <img src="telefone.png">
            </a>
        </div>

    </footer>
</body>

</html>
