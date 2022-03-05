<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8"/>
        <title> WebAgency </title>
        <link rel="stylesheet" href="css/Style.css">
        <script src="https://kit.fontawesome.com/280622fd2a.js" crossorigin="anonymous"></script>
    </head>
    <body>
<!-- Ceci est l'entête de mon site -->
        <header>
            <div class="logo_menu"></div>
                <div class="logo">
                    <img src="images/logo.png" alt="logo de webagency" />
                </div>

                <nav><!-- Ceci est menu de la page -->
                    <ul>
                        <li> <a href="webagency.html"> Accueil</a></li>
                        <li> <a href="#SERVICES"> Services</a></li>
                        <li> <a href="#Portfolio"> Portfolio</a></li>
                        <li><a href="#contacter"> contact</a></li>
                    </ul>
                </nav>
                
            </div>

            <div class="slider">
                <div class=" slider_text">
                    <h2> 
                        <span>WEBAGENCY</span> : 
                        L'AGENCE DE TOUS VOS PROJETS
                    </h2> 
                    <h4>Vous avez un projet ? La WebAgency vous aide à le réaliser !</h4>
                    <h3> 
                        <span class="booton">Plus d'infos</span> 
                    </h3>
                </div> 
            </div>
        </header>
<!-- Cette section concerne le corps du projet (main)-->
        <main>

            <section>
                <div class="services">
                    <h1 id="SERVICES">NOS SERVICES</h1>
                    <h2>
                        Lorem ipsum dolor sit emet, consectetur adipisicing elit, sed eiusmod tempor 
                        incididunt ut et dolore magna aliqua. Ut enim ad minim veniam
                    </h2>
                </div>
                <div class="contenu_services">
                    <p>
                        <img src="images/main-feature.png" alt="image écran "/>
                    </p>
                    <aside>
                        <div class="contenu">
                            <div class="contenu">
                            </div>
                           <div>
                                <h1>UX design</h1>
                                <p>
                                    Lorem ipsum dolor sit emet, consectetur adipisicing elit, sed eiusmod tempor 
                                    incididunt ut et dolore magna aliqua
                                </p>
                           </div>
                        </div>

                        <div class="contenu">
                            <div class="contenu_icone">
                                <i class=" fa-solid fa-cubes"></i><!-- Les icons de ce site ont été inserer avec fontd awesomne,
                                     grace à la balise i -->
                            </div>
                            <div>
                                <h1>UI design</h1>
                                <p>
                                    Lorem ipsum dolor sit emet, consectetur adipisicing elit, sed eiusmod tempor 
                                    incididunt ut et dolore magna aliqua
                                </p>
                            </div>
                        </div>

                        <div class="contenu">
                            <div class="contenu_icone">
                                <i class=" fa-solid fa-chart-pie"></i>
                            </div>
                           <div>
                            <h1>SEO</h1>
                            <p>
                                Lorem ipsum dolor sit emet, consectetur adipisicing elit, sed eiusmod tempor 
                                incididunt ut et dolore magna aliqua
                            </p>
                           </div>
                        </div>
                    </aside>
                </div>
            </section>
            
            <section class="sec_projets">
                <div class="projets">
                    <h1>NOS PROJETS</h1>
                    <h2>
                        Lorem ipsum dolor sit emet, consectetur adipisicing elit, sed eiusmod tempor 
                        incididunt ut et dolore magna aliqua. Ut enim ad minim veniam
                    </h2>
                </div>
                <div class="navigation">
                    <p><a style="background-color: blue; padding: 16px;" href="#">All Works</a></p>
                    <p><a href="#">Creative</a></p>
                    <p><a href="#">Corporate</a></p>
                    <p class="class_port"><a href="#" id="Portfolio">Portfolio</a></p>
                </div>
                <div class="images">
                    <p>
                        <img src="images/portfolio/01.jpg" alt="" />
                        <img src="images/portfolio/02.jpg" alt="" />
                        <img src="images/portfolio/03.jpg" alt="" />
                        <img src="images/portfolio/04.jpg" alt="" />
                    </p>
                    <p>
                        <img src="images/portfolio/05.jpg" alt="" />
                        <img src="images/portfolio/06.jpg" alt="" />
                        <img src="images/portfolio/07.jpg" alt="" />
                        <img src="images/portfolio/08.jpg" alt="" />
                    </p>

                </div>
            </section>

        </main>
<!-- Ceci est le pied de la page -->
        <footer>
        <!-- La section formulaire -->
            <div class="arriere_plan">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d25512.97618395858!2d2.3191001831243514!3d48.87235682575259!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47e66e145ccb3091%3A0x9495beee8c96ec27!2s25%20Rue%20d&#39;Hauteville%2C%2075010%20Paris%2C%20France!5e0!3m2!1sfr!2sbj!4v1645461849761!5m2!1sfr!2sbj"
                 width="1367" height="600" style="border:0;" allowfullscreen="" loading="lazy"></iframe><!-- Cette portion de code m'a permis d'inserer 
                    google maps sur la page, on fait recours donc à la balise iframe-->
                <div class="contactez_nous">
                    <h1 id="contacter">Contact Info</h1>
                    <h4>WebAgency</h4>
                    <p>
                        25 Rue d'Hauteville 75010 Paris </br>
                        Tel : 62 90 86 75
                    </p>
                    <form action="/page-traitement-donnees" method="POST">
                        <div>
                            <input type="text" id="nom" name="nom" placeholder="Name" required>
                        </div>
    
                        <div>
                            <input type="email" id="email" name="email" placeholder="Email" required>
                        </div>
    
                        <div>
                            <input type="text" id="sujet" name="sujet" placeholder="Subject" required>
                        </div>
    
                        <div>
                            <textarea id="message" name="message" placeholder="Message" required></textarea>
                        </div>
    
                        <div>
                            <button type="submit">Send message</button>
                        </div>
                    </form>
                </div>
            </div>
        </footer>

    </body>
</html>
