<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum Vitae</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/estilos.css">
</head>
<div class="gradient"></div>
<header>
    <div>
        <div class="principio">
            <h1 class="programador">Programador</h1>
            <h2 class="nombre">Nicolás García Blanco</h3>
                <h3 class="año">2023
            </h2>
        </div>
        <nav>
            <ul>
                <li><a href="#presentacion">Presentación</a></li>
                <li><a href="#boton">Educación</a> </li>
                <li><a href="#boton3">Experiencia laboral</a> </li>
            </ul>
        </nav>
    </div>

</header>

<body id="fondo" data-speed="4" class="background">
    <div id="#presentacion">
        <div class="presentacion">
            <h1>Presentación</h1>

            <div class="presentacion1">
                <img src="/img/foto cv.png" alt="">
                <div>
                    <p class="pres">nicogarciablanco99@gmail.com</p>
                    <p class="pres">+54 3487 695354</p>
                    <p>linkedin.com/in/nicojngb</p>
                </div>
            </div>
        </div>

        <div class="presentacion2">
            <div class="pres2">
                <h1>Idiomas</h1>
                <p>Español Ingles B2 Intermedio Avanzado</p>
            </div>
            <div class="pres2a">
                <h1>Skills</h1>
                <p>HTML</p>
                <P>CSS</P>
                <p>Javascript basico</p>
                <p>Express.js</p>
            </div>
        </div>
    </div>
    <button id="boton" onclick="mostrar();">
        <h5>Educación</h5>
    </button>
    <div id="educacion" class="educacion">
        <div>
            <h1>Educación</h1>
            <div>
                <h3 class="edu">2017</h3>
                <p>Me recibi de la secundaria como Tecnico en Informatica Personal y Profesional</p>
            </div>
            <div>
                <h3 class="edu">2020</h3>
                <p> Programación autodidacta</p>
            </div>
            <div>
                <h3 class="edu">2021</h3>
                <p>Curso Professional Webmaster
                    (HTML, CSS, GIT, Javascript, Express.js, SQL, Node.js)</p>
            </div>
            <div>
                <h3 class="edu">2022</h3>
                <p>Curso Argentina Programa "Sé programar" 1ra parte</p>
            </div>
            <div>
                <h3 class="edu">2023</h3>
                <p>En proceso</p>
                <p>Curso de Javascript Basico en openbootcamp</p>
                <p>Curso Argentina Programa "Sé programar" Frontend
                    (HTML, CSS, Javascript) 2da parte</p>
            </div>
            <button id="boton2" onclick="ocultar();">Ver menos</button>
        </div>


    </div>
    <div>
        <button id="boton3" onclick="mostrar2();">
            <h5>Experiencia Laboral</h5>
        </button>
        <div id="experiencia" class="experiencia">
            <h1>Experiencia laboral</h1>
            <div>
                <h3 class="exp">2017</h3>
                <p>Practicas profesionalizantes Municipalidad de Zárate</p>
            </div>
            <div>
                <h3 class="exp">2018 >></h3>
                <p>Profesor y ayudante de Tenis</p>
            </div>
            <div>
                <h3 class="exp">2019 - 2021</h3>
                <p>Gamemaster</p>
                <p>Trabajo sin remuneración como Gamemaster/Director en servidor de Roleplay TumberosRP con una
                    comunidad de
                    mas de 4000 personas</p>
            </div>
            <div>
                <h3 class="exp">2021</h3>
                <p>Emprendimiento @linus.tec (servicio técnico e informático)</p>
            </div>
            <div>
                <h3 class="exp">2023</h3>
                <p>Agregado de secciones de recomendaciones y noticias a pintureriacolorval.com.ar y estudioshon.com.ar
                </p>
            </div>
            <button id="boton4" onclick="ocultar2();">Ver menos</button>
        </div>
    </div>
    <script src="/js/botones.js" src="/js/codigo.js"></script>
</body>

</html>
