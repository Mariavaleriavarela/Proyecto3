![PROYECTO](https://github.com/Mariavaleriavarela/Proyecto3/assets/162743143/546cf999-db5e-4bbd-b4e0-1d10b97beb8b)

# Introducción:
Valeria Pastelera es mi sitio web dedicado a la venta de productos de repostería artesanal, incluyendo tortas decoradas, postres y panadería. El objetivo de este proyecto es crear una landing page personalizada que represente la esencia y la calidad de mis productos, asegurando una excelente experiencia para el usuario en diversas plataformas y dispositivos.

# Proceso de Desarrollo:
## Planificación y Prototipado
Antes de comenzar con el desarrollo del sitio web, realicé un prototipo simple para definir la estructura y el diseño. Utilicé una herramienta de dibujo gratuita, draw.io, para crear un esquema visual de cómo quería que fuera la página.

![PROTOTIPON](https://github.com/Mariavaleriavarela/Proyecto3/assets/162743143/c48425e8-c0bc-4c13-b6b8-c7d41131f4e2)

Este dibujo me permitió visualizar la disposición de cada sección y asegurarme de que todos los elementos necesarios estuvieran presentes.

# Desarrollo de la Estructura HTML
Con el prototipo como guía, construí la estructura básica del sitio utilizando HTML5. Definí las siguientes secciones:

- Header: Incluye el logo y las áreas principales del sitio.
- Main: Presenta el producto al usuario, incluyendo un título, una descripción y un formulario para introducir el correo.
- Products: Muestra un catálogo breve de los productos destacados.
- Footer: Contiene enlaces a las diferentes áreas del sitio y nuestras redes sociales.


```scss
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilos.css">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet"/>

    <title>Valeria Pastelera</title>
</head>
<body>
    <main class="container">
        <!-- Navegación -->
        <nav>
            <div class="nav__bar">
                <a href="#" class="nav__logo">
                     <!-- Logo de la empresa -->
                  <img src="IMAGES/VP LOGO.png" alt="valeria pastelera" width="100">
                 
                </a>
                <div class="nav__menu__btn" id="menu-btn">
                    <i class="ri-menu-3-line"></i>
                </div>
            </div>
            <!-- Enlaces de navegación -->
            <ul class="nav__links" id="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="./galeria.html">Galería</a></li>
                <li><a href="#">Productos</a></li>
                <li><a href="#">Contactos</a></li>
            </ul>
        </nav>

        <!-- Contenido principal -->

        <div class="container__grid">
        <!-- Contenido principal -->
           <img src="IMAGES/gaspar.JPG" alt="bg" class="bg__1">
            <div class="container__content">
                <h1>Pasteleria y Panadería </h1>
                <h2>¡Endulza tu día con nuestras delicias artesanales!</h2>
                <p> En Valeria Pastelera, creemos que cada momento especial merece un toque de dulzura. Nuestra pasión es crear experiencias inolvidables a través de nuestros productos, elaborados con dedicación, amor y los mejores ingredientes.</p>
                <!-- Redes sociales -->
                <div class="socials">
                    <div>
                        <a href="https://www.instagram.com/valeriapastelera/?igsh=NDJhaXB6ZDJjN2t5"><i class="ri-instagram-line"></i></a>
                        <a href="#"><i class="ri-facebook-line"></i></a>
                        <a href="https://www.tiktok.com/@valeriapastelera?_t=8n1GjbtNVsU&_r=1"><i class="ri-tiktok-line"></i></a>
                        <a href="#"><i class="ri-twitter-line"></i></a>
                    </div>
                </div>
            </div>
         </div>
         <!-- Sección de productos -->
         <section class="container__flex">
            <div class="container__content2">
                <h1>Productos</h1>
                <p>Tortas Decoradas y personalizadas para cualquier ocasión especial.</p>
                <p>Una amplia variedad de delicias dulces que harán agua la boca.</p>
                <p>Panes frescos y llenos de sabor, hechos con técnicas tradicionales.</p>
                <div id="productos" class="productos">
                    <img src="IMAGES/FF5D9EB6-1028-48B9-8C50-0A6B625BA746.JPG" alt="profiterol">
                    <img src="IMAGES/F56BD7C8-0D17-47E0-AD5D-6E404821E62A.JPG" alt="Cumple">
                    <img src="IMAGES/14CE5BB1-88DB-44B3-8056-0ECEC8BD573C.JPG" alt="leon">
                    <img src="IMAGES/8E8EA438-F67E-4BA9-AB01-39246F468DB9.JPG" alt="torta">
                </div>
                <div id="productos" class = "productos">
                    <img src="IMAGES/cachitos.JPG" alt="cachitos">
                    <img src="IMAGES/6B22623F-E706-4B13-BBED-A8D08D00F7F5.JPG" alt="Cumple2">
                    <img src="IMAGES/DF325C29-703F-4B86-B40F-144DC141A6D5.JPG" alt="torta">
                    <img src="IMAGES/barco.JPG" alt="Barquito">
                </div>

            </div>
        </section>

        <footer class="footer">
            <div class="footer__content">
                <p>Contacto: <a href="mailto:info@valeriapastelera.com">valeriapastelera@gmail.com</a></p>
                <div class="socials">
                    <a href="https://www.instagram.com/valeriapastelera/?igsh=NDJhaXB6ZDJjN2t5"><i class="ri-instagram-line"></i></a>
                    <a href="#"><i class="ri-facebook-line"></i></a>
                    <a href="https://www.tiktok.com/@valeriapastelera?_t=8n1GjbtNVsU&_r=1"><i class="ri-tiktok-line"></i></a>
                    <a href="#"><i class="ri-twitter-line"></i></a>
            </div>
            <div>
                <p>&copy; 2024 Valeria Pastelera. Todos los derechos reservados.</p>
            </div>

        </footer>
     </main>
     <script src="./vp.js"></script>
</body>
</html>
```
# Aplicación de Estilos CSS

Luego, apliqué estilos CSS para dar formato y mejorar la apariencia de la página. Utilicé un archivo styles.css para mantener el código organizado y facilitar futuras modificaciones.

A continuación, presento solo algunas partes del código CSS utilizado en el desarrollo del sitio, ya que es bastante extenso:
Encabezado:
```scss
nav {
    top: 0;
    width: 100%;
    background-color: rgb(250, 253, 255);
    z-index: 9;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 1.5rem;
}

.nav__bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    max-width: var(--max-width);
}

.nav__logo img {
    max-width: 250px;
    width: 70%;
}

.nav__links {
    list-style: none;
    display: flex;
    gap: 2rem;
    margin-left: auto;
}

.nav__links a {
    font-size: 1.5rem;
    font-weight: 500;
    color: var(--primary-color);
    transition: 0.3s;
}

```
Sección Principal: 

```scss
.container__grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 2rem;
    max-width: var(--max-width);
    margin: auto;
    padding: 2rem 1rem;
    align-items: center;
    text-align: left;
}

.container__content h1 {
    font-size: 2.5rem;
    font-weight: 600;
    line-height: 3rem;
    color: var(--primary-color);
    margin-bottom: 0.5rem;
}

.container__content h2 {
    margin-bottom: 0.5rem;
    max-width: 450px;
    font-size: 1.5rem;
    font-weight: 400;
    line-height: 2rem;
    color: var(--primary-color);
}

.container__content p {
    margin-bottom: 1rem;
    max-width: 450px;
    color: var(--primary-color);
}
```

Sección de Productos:

```scss

.container__content2 h1 {
    font-size: 2rem;
    font-weight: 600;
    line-height: 2.5rem;
    color: var(--primary-color);
    margin-bottom: 1rem;
}

.productos {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    justify-content: center;
}

.productos img {
    width: calc(35% - 0.5rem);
    height: auto;
    max-width: 150px;
    border-radius: 8px;
    transition: 0.5s;
}

.productos img:hover {
    transform: scale(1.05);
}
```

Pie de Página:

```scss

.footer {
    background-color: rgb(250, 253, 255);
    padding: 2rem;
    text-align: center;
    width: 100%;
}

.footer__content {
    max-width: var(--max-width);
    margin: auto;
    color: var(--text-dark);
}

.footer__content a {
    color: var(--primary-color);
    text-decoration: none;
}

.footer__content a:hover {
    text-decoration: underline;
}

.footer__content .socials a {
    color: var(--primary-color);
    font-size: 1.5rem;
    transition: 0.3s;
}

.footer__content .socials a:hover {
    color: hotpink;
}

```

Este resumen destaca las secciones principales del código CSS que afectan el encabezado, el contenido principal, la sección de productos y el pie de página.


# Aplicación de JS

 ```scss

const menuBtn = document.getElementById(`menu-btn`);
const navLinks = document.getElementById(`nav-links`);
const menuBtnIcon = menuBtn.querySelector("i")

menuBtn.addEventListener("click", ()=> {
    navLinks.classList.toggle("open");

    const isOpen = navLinks.classList.contains("open");
    menuBtnIcon.setAttribute(
        "class",
        isOpen ? "ri-close-line" : "ri-menu-3-line"
    );
});

const scrollRevealOption = {
    distance: "50px",
    origin: "buttom",
    duration: 1000,
}

ScrollReveal().reveal(".container__content h1", {
    ...scrollRevealOption,
});

```



Desplegué el sitio utilizando GitHub Pages para que estuviera accesible en línea. Puedes visitar el sitio en Valeria Pastelera.
https://mariavaleriavarela.github.io/Proyecto3/

# Conclusión:

Este proyecto me permitió aplicar conocimientos en HTML y CSS para crear una página web funcional y estética. Desde la planificación, el prototipado Y hasta el desarrollo. Cada paso fue crucial para asegurar que el producto final cumpliera con los requisitos y ofreciera una excelente experiencia de usuario.

# Gracias!!


