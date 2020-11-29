Cuarta Entrega:
- Se agrega Menu Hanburguesa para tamaño mobile menor a md
- Se Suben los tamaños de texto de cuerpo, subtitulo y copete.
- Se cambian colores de Titulo - Subtitulo y Cuerpo.
- Se quita el fondo del footer.
- Se cambia en la clase foto el atributo padding-botton x margin-bottom

Desafío Clases 13 y 14: Se hace un rollback de las clases SASS que solo se agregaron para completar el desafío 12. Se inicializa el repo git, y se hacen los cambios para el desafío SEO. Optimización de Imagenes, titulos y keywords para la página. 
Carpeta Media antes de la optimización: 12.594.713 bytes
Carpeta Media despues de la optimización: 4.128.800 bytes
Se Aplican las etiquetas <h1> y <h2> para su indexación.
Se cambiaros las etiquetas <Title>
Sa añadio la Meta description a la página principal.
Se añadieron al index.html las siguientes keywords: humor grafico, chistes graficos, chistes para whatsapp, chistes argentinos, humor, satira, revsita, divertido, humor negro, chistes de humor negro, imagenes de chistes, coco legrand, satira significado, frases de humor, frases graciosas de amor, videos de humor, memes de humor negro, memes humor negro, imagenes chistosas para whatsapp, divertida, humor on.

Tercera Entrega: Para poder incorporar exitosamente Boostrap - SASS y BEM sin perder diseño responsive ni pisar boostrap donde no se necesita consideré necesaria una migración completa del sitio entre la segunda y tercera entrega. Manteniendo todos los contenidos y estructura, pero reescribiendo el layout completo a fin de reescribir los contenedores y sus clases.

El body completo de la página está basado en 4 rows de boostrap. Delegando en el framework la mayor parte del comportamiento responsive.
    <body>
        <div class="container"> <!--Container Boostrap-->
            <header class="row">
            </header>
            <nav class="row">
            </nav>
            <div class="row">
            </div>
            <footer class="row">                
            </footer>
        </div>
    </body>

Desafío Clase 10:
    -Se implementó Boostrap a todo el proyecto.
    -Se agregaron modals.

Desafío Clase 9 - Boostrap:
    -Se incorporó Boostrap a toda la página index.html
    -La página index usa temporalmente el archivo style-index.css (Para no romper el resto del sitio. Se vuelve a unificar al homogeneizar en la próxima entrega.)
    -Se adaptó el responsive en toda la página.

Elementos Desafío Transformaciones y Animaciones.
    -Se imcorporaron gradientes en Header y Footer.
    -Transformaciones al NavBar
    -Animaciones a los fielset en 'pre_XXX.html
    -Animacion en hoover sobre el boton en footer.

Elementos Segunda Entrega Proyecto Final.
    -Toda la página es responsive. (Mobie - Tablet - Desktop)
    -Header y Nav son responsive Flexbox.
    -El Cuerpo principal es del tipo grid, con mediaOverrides min & max.
    -Nota: Se mantuvieron algunas tablas dentro del grid. A fin de reutilizar código existente.