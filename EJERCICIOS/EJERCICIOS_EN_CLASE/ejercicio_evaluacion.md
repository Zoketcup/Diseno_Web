![image](https://user-images.githubusercontent.com/91554777/165175601-f95d8714-091a-4687-a21b-70a75beae3ea.png)

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Título de página</title>
    </head>
    <body>

        <header>
            <h1>ENCABEZADO NIVEL 1</h1>
            <nav>
                <ul>
                    <li><a href="">ENLACE 1</a></li>
                    <li><a href="">ENLACE 2</a></li>
                    <li><a href="">ENLACE 3</a></li>
                    <li><a href="">ENLACE 4</a></li>
                </ul>
            </nav>
        </header>


        <main>

            <article>
                <h2>Encabezado nivel 2</h2>
                <p>Aqui va el texto del primer <b>Párrafo</b></p>
                <p>Aqui va el texto del segundo párrafo</p>
            </article>

            <aside>
                <h2>Apartado</h2>
                <p>Elige una opción</p>
                <form action="">
                    <input type="radio" name="opcion">Opción 1 <br>
                    <input type="radio" name="opcion">Opción 2 <br>
                    <input type="radio" name="opcion">Opción 3 <br>
                    <input type="submit" value="Enviar">
                </form>
            </aside>

        </main>


        <footer>
            <p>Sección de información de contacto, derechos de autor, etc</p>

        </footer>

    </body>
    </html>


## AGREGA EL CSS NECESARIO A LA PÁGINA.

HTML:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Título de página</title>
        <link rel="stylesheet" href="estilos.css">
    </head>
    <body>

        <header>
            <h1>ENCABEZADO NIVEL 1</h1>
            <nav>
                <ul>
                    <li><a href="">ENLACE 1</a></li>
                    <li><a href="">ENLACE 2</a></li>
                    <li><a href="">ENLACE 3</a></li>
                    <li><a href="">ENLACE 4</a></li>
                </ul>
            </nav>
        </header>


        <main>

            <article>
                <h2>Encabezado nivel 2</h2>
                <p>Aqui va el texto del primer <b>Párrafo</b></p>
                <p>Aqui va el texto del segundo párrafo</p>
            </article>

            <aside>
                <h2>Apartado</h2>
                <p>Elige una opción</p>
                <form action="">
                    <input type="radio" name="opcion">Opción 1 <br>
                    <input type="radio" name="opcion">Opción 2 <br>
                    <input type="radio" name="opcion">Opción 3 <br>
                    <input type="submit" value="Enviar">
                </form>
            </aside>

        </main>


        <footer>
            <p>Sección de información de contacto, derechos de autor, etc</p>

        </footer>

    </body>
    </html>

css:

    body{background-color: rgb(170, 207, 170);}
    header{ background-color: rgba(53, 44, 44, 0.637);}
    header h1{color: rgb(163, 219, 163);text-align: center; }
    header nav{ background-color: rgb(120, 185, 120);text-align: center;}
    main{background-color: rgb(166, 231, 166);
    text-align: center;}
    article{background-color: deepskyblue;
    text-align: center;}
    aside{background-color: magenta;}
    footer{background-color:yellow ;text-align: center;}
