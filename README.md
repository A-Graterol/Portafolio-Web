<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Signika:wght@500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./node_modules/eins-modal/dist/css/eins-modal.min.css">
    <link rel="stylesheet" href="./css/style.css">
    <link rel="stylesheet" href="./css/style-modal.css">
</head>

<body>

    <header>
        <div class="navbar container">
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#briefcase">Portafolio</a></li>
                    <li><a href="#about-me">Sobre mi</a></li>
                </ul>
            </nav>
        </div>

    </header>

    <section>
        <div class="hero" id="inicio">
            <div class="container">
                <img src="./img/fondo.png" alt="">
            </div>
        </div>
        <div class="profile">
            <div class="square"></div>
            <div class="circle-trans"></div>
            <div class="circle"></div>
            <div class="profile-img"><img src="./img/perfil.png" alt=""></div>
            <div class="square-text">ANDRES GRATEROL</div>
            <div class="square-text-2"><span>PROGRAMADOR Y DISEÑADOR WEB</span></div>
            <div class="square-text-3"><span>CONFIGURACIÓN DE MIKROTIK, OLT Y
                    SWITCH</span></div>
            <div class="contact-icon">
                <a href="https://github.com/A-Graterol" target="_blank"><img src="./img/github.svg" alt=""></a>
                <a href="#" target="_blank"><img src="./img/linkedin.svg" alt=""></a>
                <a data-modal-id="message"><img src="./img/message.svg" alt=""></a>

            </div>
            <div class="square-text-4"><a href="#about-me"><span>About me |</span> Sobre mi</a>
            </div>
        </div>
    </section>

    <section class="briefcase" id="briefcase">
        <div class="briefcase-section container">
            <h2><span>Briefcase |</span> Portafolio</h2>
            <div class="briefcase-grid">
                <div><a data-modal-id="pw-portafolio"><img src="./img/Paginaweb.png" alt=""></a></div>
            </div>

        </div>
    </section>

    <section class="skills">
        <div class="skill container">
            <div class="knowledge-part">
                <h2><span>Knowledge |</span> Conocimientos</h2>
                <div class="knowledge">
                    <div><img src="./img/html-icon.png" alt="">
                        <h3>HTML</h3>
                    </div>
                    <div><img src="./img/css-icon.png" alt="">
                        <h3>CSS</h3>
                    </div>
                    <div><img src="./img/js-icon.png" alt="">
                        <h3>JAVASCRIPT</h3>
                    </div>
                    <div><img src="./img/mikrotik.png" alt="">
                        <h3>MIKROTIK</h3>
                    </div>
                    <div><img src="./img/seo-icon.png" alt="">
                        <h3>Optimización SEO</h3>
                    </div>

                </div>

            </div>

            <div class="tools-part">
                <h2><span>Dev Tools |</span> Herramientas</h2>
                <div class="tools">
                    <div><img src="./img/github-icon.png" alt="">
                        <h3>Github</h3>
                    </div>
                    <div><img src="./img/vsc-icon.png" alt="">
                        <h3>Visual Code</h3>
                    </div>
                    <div><img src="./img/git-icon.png" alt="">
                        <h3>GIT</h3>
                    </div>
                    <div><img src="./img/Winbox.png" alt="">
                        <h3>Winbox</h3>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <section class="about" id="about-me">
        <div class="about-flex container">
            <div class="about-info">
                <p>
                    ¡Hola! Soy Andrés Graterol, un apasionado desarrollador web y diseñador gráfico
                    con una sólida base en programación y diseño. Creo que puedo aportar significativamente a
                    cualquier equipo con mis habilidades técnicas y experiencia adicional.
                </p>
                <br>
                <p>
                    <strong>Programación Web </strong>

                <ul>
                    <li>JavaScript: He trabajado en proyectos utilizando frameworks como React y Vue.js.</li>
                    <li>Python: Experiencia en desarrollo backend con Django y Flask.</li>
                    <li>HTML y CSS: Diseño y desarrollo de páginas web responsivas.</li>
                    <li>Node.js: Familiarizado con la creación de aplicaciones en tiempo real y APIs RESTful.</li>
                </ul>
                <br>
                </p>
                <p>
                    <strong>Diseño Gráfico</strong>
                <ul>
                    <li>Adobe Photoshop: Edición avanzada de imágenes y creación de gráficos.</li>
                    <li>Edición de Fotos: Retoque, corrección de color y manipulación de imágenes.</li>
                    <li>Creación de Logos: Diseño de logotipos únicos.</li>
                </ul>

                </p><br>
                <p>
                    <strong>Experiencia Adicional</strong>
                <ul>
                    <li>Configuración de MikroTik: Creación y gestión de VLANs, y estructuración de cableado.</li>
                    <li>Ensamblaje de Computadoras: Experiencia en hardware y sistemas.</li>
                    <li>Sistemas Windows: Administración y solución de problemas.</li>
                </ul>
                </p>
            </div>

            <div class="social">
                <a href="https://github.com/A-Graterol" target="_blank"><img src="./img/github.svg" alt=""></a>
                <a href="#" target="_blank"><img src="./img/linkedin.svg" alt=""></a>
                <a data-modal-id="message"><img src="./img/message.svg" alt=""></a>
            </div>

        </div>

    </section>

    <footer>
        <div class="container">
            <p>ⓒ 2024 Copyright | Designed by N/CODER</p>
        </div>
    </footer>


    <!-- Modal Portafolio -->

    <div id="pw-portafolio" class="eins-modal" data-options="openTransition: expandIn; openDuration: 200;">
        <div class="eins-modal-content">
            <div class="eins-modal-close"></div>
            <div class="pw-content">
                <div class="eins-modal-preview">
                    <img src="./img/Paginaweb.png" alt="">
                </div>
                <div class="eins-modal-text">
                    <p>Portafolio Web Personal, Construido con HTML, CSS Y JS. <br>Se usó librerias de npm y se optimizó
                        la página con webpack. Se uso estructura SEO básica para la semántica en buscadores
                    </p>
                    <p>También puedes acceder a él desde el repositorio de github</p>
                    <div class="eins-modal-text-2">
                        <span>ENLACE:</span><a href="/">Portafolio Web</a>
                    </div>
                    <div class="eins-modal-text-3">
                        <span>Tecnologías Usadas:</span>
                        <div class="eins-modal-tec">
                            <img src="./img/html-icon.png" alt="">
                            <img src="./img/css-icon.png" alt="">
                            <img src="./img/js-icon.png" alt="">
                            <img src="./img/npm-icon.png" alt="">
                            <img src="./img/webpack-icon.png" alt="">
                            <img src="./img/seo-icon.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div id="message" class="eins-modal" data-options="openTransition: expandIn; openDuration: 200;">
        <div class="eins-modal-content">
            <div class="eins-modal-close"></div>

            <form class="form" action="https://formspree.io/f/xnnazkpr" method="POST">
                <h3 class="lb"><span>Escribeme</span> para obtener mas informacionm</h3>
                <label>
                    Tu Correo Electronico:
                    <input type="email" name="email">
                </label>
                <label>
                    Tu Mensaje:
                    <textarea name="message"></textarea>
                </label>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </div>


    <script src="./node_modules/eins-modal/dist/js/eins-modal.min.js"></script>

</body>

</html>
