<!DOCTYPE html>

<html lang="es">
    <head>
        <title>Portafolio</title>
        <meta charset="UTF-8"/>
        <link href='http://fonts.googleapis.com/css?family=Open+Sans:400italic,700italic,300,400,700' rel='stylesheet' type='text/css'>
        <link rel="stylesheet" href="static/css/normalize.css"/>
        <link rel="stylesheet" href="static/css/estilos.css"/>
        <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
    </head>
    
    <body>
        
        
        <header id="Perfil" class="Header">
            
            <nav class="MainMenu">
                <ul class="MainMenu-list">
                    
                    <li class="MainMenu-item">
                        <a class="MainMenu-link" href="#Perfil">Perfil</a>
                    </li>
                    <li class="MainMenu-item">
                        <a class="MainMenu-link" href="#Trabajo">Mi trabajo</a>
                    </li>
                    <li class="MainMenu-item">
                        <a class="MainMenu-link" href="#contacto">Contáctame</a>
                    </li>
                </ul>
            </nav>

            <figure class="Header-imageContainer">
                <img src="static/images/avatar.jpg" alt="@" class="Header-image"/>
                <figcaption class="Header-description">
                    <a href="https://twitter.com/MiguelRamirez7u" target="_blank" class="Header-link">@MiguelRamirez7u</a>
                </figcaption>
                <p class="Header-name">Miguel Ramirez</p>
            </figure>
        </header>
        
        <section id="Perfil" class="Profile">
            <div class="u-containerDefault"> 
                <h2 class="Profile-title u-title">Mi Perfil</h2>

                <p class="Profile-description">Puedes <strong>visitar</strong> mis redes <span class="Profile-span">sociales</span> si quieres <em>seguirme</em></p>

                <a class="Profile-link" href="https://twitter.com/MiguelRamirez7u">Twitter</a>

                <a class="Profile-link" href="https://www.facebook.com/profile.php?id=100006195313991">Miguel Ramirez Mx</a>

                <a class="Profile-link" href="https://github.com/Waeex">Waeex</a>
            </div>
        </section>
        <section id="Trabajo" class="Work">
            <div class="u-containerDefault"> 
                <h2 class="Work-title u-title">Mi Trabajo</h2>
            </div>
                <article class="Work-item">
                    <figure class="Work-imageContainer">
                        <img class="Work-image" src="static/images/proyecto.jpg" alt="Mejorando.la"/>
                        <figcaption>www.------.com</figcaption>
                    </figure>
                </article>
                <article class="Work-item">
                    <figure class="Work-imageContainer">
                        <img class="Work-image" src="static/images/proyecto.jpg" alt="Mejorando.la"/>
                        <figcaption class="Work-description">www.------.com</figcaption>
                    </figure>
                </article>
                <article class="Work-item">
                    <figure class="Work-imageContainer">
                        <img class="Work-image" src="static/images/proyecto.jpg" alt="Mejorando.la"/>
                        <figcaption class="Work-description">www.------.com</figcaption>
                    </figure>
                </article>
                <article class="Work-item">
                    <figure class="Work-imageContainer">
                        <img class="Work-image" src="static/images/proyecto.jpg" alt="Mejorando.la"/>
                        <figcaption class="Work-description">www.------.com</figcaption>
                    </figure>
                </article>
        </section>
        <footer id="contacto" class="Footer">
            <div class="Footer-left">
                <h3 class="Footer-title">Contacto</h3>
                <p class="Footer-description">Si tienes alguna duda o sugerencia esta es mi información de contacto</p>
                <p><i class="fas fa-lg fa-envelope"></i> Miguelandroit100@gmail.com</p>
                <p><i class="fas fa-lg fa-phone"></i> +52 9983012309</p>
    
            </div>
            <form action="" class="Footer-form">
                <input type="text" placeholder="Nombre" class="Footer-input">
                <input type="email" placeholder="Email" class="Footer-input">
                <textarea placeholder="motivo" class="Footer-textarea"></textarea>
                <button type="submit" class="Footer-button">Contactarme</button>
            </form>
        </footer>
    </body>
</html>

