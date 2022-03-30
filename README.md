<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Portifólio </title>

    <!-- IconScout Content Delivery Network (CDN) - Site no qual foi pego os ícones -->
    <link rel="stylesheet" href="https://unicons.iconscout.com/release/v2.1.6/css/unicons.css">
    
    <!-- Google Fonts (Poppins) - Site no qual foi pego as fontes -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">

    <!-- Arquivo de Estilos Padrões -->
    <link rel="stylesheet" href="./style.css">
</head>

<body>
    <!-- Início dos links de navegação (navbar) -->
    <nav class="margin_nav">
        <div class="container nav__container">
            <a href="index.html" class="nav__logo">
                <h3>.exe</h3>
            </a>

            <ul class="nav__menu">
                <li><a href="index.html">Início</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#portfolios">Portifólio</a></li>
                <li><a href="#contato">Contato</a></li>
                <ul class="Nav_download">
                    <li><p href="./images/Curriculum Vitae - Thalles.pdf" class="btn btn-primary" download="Curriculum Vitae - Thalles.pdf"><i class="uil uil-download-alt"></i>Download</p></li>
                </ul>
                <i id="icon" class="uil uil-moon"></i>
            </ul>
            <button id="open-menu-btn"><i class="uil uil-bars"></i></button>
            <button id="close-menu-btn"><i class="uil uil-multiply"></i></button>
        </div>
    </nav>
    <!-- Fim dos links de navegação (navbar) -->

    <!-- Ínício do cabeçalho (header) -->
    <header>
        <div class="container header__container">
            <div class="header_left">
                <div>
                    <h3>Hello! Eu sou</h3>
                    <h1>Thalles<br/>Cansi</h1>
                    <p>
                        Designer UI/UX e desenvolvedor web Full Stack. Já ajudei mais de 300 clientes em oferecer a eles brilhantes ideias para seus negócios online. Vamos trabalhar juntos hoje! 
                    </p>
                    <a href="#contato" class="btn btn-primary btn-lg">Entrar em contato</a>
                </div>
            </div>

            <div class="header__right">
                <div class="header__image">
                    <img src="./images/avatar.png">
                </div>
                <div class="header__right-bg"></div>
                <ul class="header__socials">
                    <li><a href="https://instagram.com/thllscns" target="_blank"><i class="uil uil-instagram"></i></a></li>
                    <li><a href="https://twitter.com/thllscns" target="_blank"><i class="uil uil-twitter"></i></a></li>
                    <li><a href="https://github.com/ThallesCansi" target="_blank"><i class="uil uil-github"></i></a></li>
                </ul>
            </div>
        </div>
    </header>
    <!-- Fim do cabeçalho (header) -->

    <!-- Ínício das empresas (companies) -->
    <section id="companies">
        <div class="container companies__container">
            <span><img src="./images/company1.png"></span>
            <span><img src="./images/company2.png"></span>
            <span><img src="./images/company3.png"></span>
            <span><img src="./images/company4.png"></span>
            <span><img src="./images/company5.png"></span>
            <span><img src="./images/company6.png"></span>
        </div>     
    </section>
    <!-- Fim das empresas (companies) -->

    <!-- Início da sessão de serviços (services) -->
    <section id="servicos">
        <div class="container services__container">
            <div class="services__left">
                <h1>7+</h1>
                <h4>Anos de experiência</h4>
                <small>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    Quis, ducimus, adipisci sed quos soluta voluptas quisquam laboriosam dolor natus iste doloremque molestiae, nulla saepe.
                </small>
            </div>

            <div class="services__right">
                <h2>
                    Designer de produto e desenvolvedor, especializado em UI/UX e design digital.
                </h2>
                <div class="services__cards">
                    <div class="services__card">
                        <span class="services__card-icon"><i class="uil uil-layers-alt"></i></span>
                        <h5>Designer de Produto</h5>
                        <a href="#">Descubra mais <i class="uil uil-arrow-right"></i></a>
                    </div>

                    <div class="services__card">
                        <span class="services__card-icon"><i class="uil uil-browser"></i></span>
                        <h5>Desenvolvimento Web</h5>
                        <a href="#">Descubra mais <i class="uil uil-arrow-right"></i></a>
                    </div>

                    <div class="services__card">
                        <span class="services__card-icon"><i class="uil uil-lightbulb"></i></span>
                        <h5>Designer de Marca</h5>
                        <a href="#">Descubra mais <i class="uil uil-arrow-right"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Fim da sessão de serviços (services) -->

    <!-- Início da sessão de portfólio (portfolio) -->
    <section id="portfolios">
        <div class="container portfolio__container">
            <div class="portfolio__head">
                <h3>Trabalhos externos, sucesso de produtos de clientes</h3>
                <div class="portfolio__head-right">
                    <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
                        Iusto perspiciatis quidem eos labore optio temporibus, deserunt cumque quasi reiciendis. 
                        Aspernatur maxime harum dolorem omnis quod repellendus vel quaerat iure quasi.
                    </p>
                    <a href="#">Conheça mais <i class="uil uil-arrow-right"></i></a>
                </div>
            </div>

            <div class="portfolio__projects">
                <article class="language" class="portfolio__project">
                    <span class="portfolio__project-image"><img src="./images/project1.jpg"></span>
                    <div class="portfolio__cta">
                        <a href="https://github.com/ThallesCansi" class="btn" target="_blank">Github</a>
                        <a href="https://twitter.com/thllscns" class="btn btn-primary" target="_blank">Live Demo</a>
                    </div>
                </article>

                <article class="language" class="portfolio__project">
                    <span class="portfolio__project-image"><img src="./images/project2.jpg"></span>
                    <div class="portfolio__cta">
                        <a href="https://github.com/ThallesCansi" class="btn" target="_blank">Github</a>
                        <a href="https://twitter.com/thllscns" class="btn btn-primary" target="_blank">Live Demo</a>
                    </div>
                </article>

                <article class="language" class="portfolio__project">
                    <span class="portfolio__project-image"><img src="./images/project3.jpg"></span>
                    <div class="portfolio__cta">
                        <a href="https://github.com/ThallesCansi" class="btn" target="_blank">Github</a>
                        <a href="https://twitter.com/thllscns" class="btn btn-primary" target="_blank">Live Demo</a>
                    </div>
                </article>

                <article class="language" class="portfolio__project">
                    <span class="portfolio__project-image"><img src="./images/project4.jpg"></span>
                    <div class="portfolio__cta">
                        <a href="https://github.com/ThallesCansi" class="btn" target="_blank">Github</a>
                        <a href="https://twitter.com/thllscns" class="btn btn-primary" target="_blank">Live Demo</a>
                    </div>
                </article>
            </div>
        </div>
    </section>
    <!-- Fim da sessão de portfólio (portfolio) -->

    <!-- Início da sessão de competencias (competences) -->
    <section id="competences">
        <div class="container competences__container">
            <div class="competences__head">
                <h2>Competências do grupo</h3>
                <p>
                    Testando aqui para ver onde falaremos sobre as linguas que nós sabemos logo antes de apresentar a lingua que moldamos com maestria.
                </p>
            </div>
            <div class="all__languages">
                <h2>Línguas Dominadas</h2>
                <div class="languages">
                    <div>
                        <article class="language">
                            <img src="./images/python.png">
                            <a href="https://www.python.org/">Python</a>
                        </article>
                        <article class="language">
                            <img src="./images/react.png">
                            <a href="https://www.python.org/">React</a>
                        </article>
                        <article class="language">
                            <img src="./images/vue.png">
                            <a href="https://www.python.org/">Vue</a>
                        </article>
                    </div>
                    <div>
                        <article class="language">
                            <img src="./images/html.png">
                            <a href="https://www.python.org/">HTML</a>
                        </article>
                        <article class="language">
                            <img src="./images/css3.png">
                            <a href="https://www.python.org/">CSS</a>
                        </article>
                        <article class="language">
                            <img src="./images/javascript.png">
                            <a href="https://www.python.org/">JavaScript</a>
                        </article>
                    </div>
                    <div>
                        <article class="language">
                            <img src="./images/mysql.png">
                            <a href="https://www.python.org/">MySQL</a>
                        </article>
                        <article class="language">
                            <img src="./images/docker.png">
                            <a href="https://www.python.org/">Docker</a>
                        </article>
                        <article class="language">
                            <img src="./images/angular.png">
                            <a href="https://www.python.org/">Angular</a>
                        </article>
                    </div>
                </div>
            </div>
    </section>

    <!-- Início da sessão de comentários (testimonials) -->
    <section id="testimonials">
        <h2>O que nossos clientes estão dizendo</h2>
        <p class="lead">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam, corrupti!
        </p>
        
        <div class="container testimonials__container"></div>
    </section>
    <!-- Fim da sessão de comentários (testimonials) -->

    <!-- Início da sessão de contato (rodapé/contact) -->
    <section id="contato">
        <div class="container contact__container">
            <div class="contact__left">
                <h2>Vamos conversar!</h2>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    Error veritatis placeat nesciunt molestias harum earum numquam saepe ut reprehenderit ad sequi laudantium excepturi tempora, voluptates officia minus animi, obcaecati esse.
                </p>
                <ul class="contact__socials">
                    <li><a href="https://instagram.com/thllscns" target="_blank"><i class="uil uil-instagram"></i></a></li>
                    <li><a href="https://twitter.com/thllscns" target="_blank"><i class="uil uil-twitter"></i></a></li>
                    <li><a href="https://github.com/ThallesCansi" target="_blank"><i class="uil uil-github"></i></a></li>
                </ul>
            </div>

            <form action="https://formspree.io/f/mayvbrvk" method="post">
                <input type="text" name="Nome" placeholder="Seu nome" required>
                <input type="email" name="E-Mail" placeholder="Seu e-mail" required>
                <textarea name="message" rows="6" placeholder="Mensagem" required></textarea>
                <button style="align-self: flex-end;" type="submit" class="btn">Enviar<i class="uil uil-arrow-right"></i></button>
            </form>
        </div>
    </section>

    <footer>
        <small>
            Todos os direitos reservados à .exe &copy;
        </small>
    </footer>
    <!-- Fim da sessão de contato (rodapé/contact) -->

    <script src="./main.js"></script>
    <script src="./testimonials.js"></script>
</body>
</html>
