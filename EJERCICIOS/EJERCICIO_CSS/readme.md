5. LENGUAJE CSS
Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que consideren correcta.

Preguntas:

¿Qué significa CSS? (valor 0.25)

     a) Cascading Style Sheets
   
¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa? (valor 0.25)

 
     b) <link rel="stylesheet" type="text/css" href="style.css">
     
  
¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a una hoja de estilo externa? (valor 0.25)

     a) En la sección <head>

  
¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)

    c) <style>
  
¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)

    a) font
  
  
¿Cuál es la sintaxis CSS correcta? (valor 0.25)


    b) body {color: black;}
   
  
¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

    a) /* esto es un comentario */



¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)

     b) background-color
  

¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)

     a) all.h1 {background-color:#FFFFFF;}


¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)


    b) text-color
   
  
¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25

     b) text-style
     
 
¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)

   
     d) <p style=\"font-size:bold;\">

¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)


      c) No puedes hacer eso con CSS

   
¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)


    b) font-family

   
¿Cómo pones el texto en negrita? (valor 0.25)

    
    c) font-weight:bold;

¿Cómo se muestra un borde como este? (valor 0.25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel
valor 0.25)
   
¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

    a) padding-left
  
   
Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)


    b) Sí

   
¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)


     b) #demo


   
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)

    
        b) .test
  
     
¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)

  
    c) div + p
   
22.¿Cómo se agrupan los selectores? (valor 0.25)

        a) Separe cada selector con un espacio
    
¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

        a) absolute

24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)

      
       c) list-style-type: square;

Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la maquetación en código html y css, valor 36)

![image](https://user-images.githubusercontent.com/101203487/166944950-671ac9a3-783c-48c6-84a2-63be493f9180.png)


● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizarás para realizar esta actividad: Imagen del logo institucional. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”

      INGRESA AQUI EL CÓDIGO HTML
      
      <!DOCTYPE html>
     <html>
     <head>
         <link rel="stylesheet" href="estilos.css">
         <title>evaluacion final</title>
     </head>
     <body>
         <header>
               <img src="logo.svg" alt="logo de la pagina">

                <nav>
                    <div></div>
                    <div>
                       <ul>
                         <li class="ret">Residente</li>
                         <li class="ret">Negocios</li>
                         <li class="ret">Visitantes</li>
                         <li class="ret">Gobierno</li>
                      </ul>
                    </div>
                </nav>
         </header>
         <main>
             <div>
                <p id="w">
                 <span>></span>APRENDE A PROGRAMAR<br> EN LAS <span>ESCUELAS DE CODIGO</span><br> DE LA CDMX
                </p>
             </div>
         </main>
         <footer>
               <p id="ama">
                ¿Quien se puede inscribir?
               </p>
               <p>
                cualquier persona que quiera aprender a programar codigo y cuente con 4-8 horas disponibles a la semana.<br>
                *Menores de edad deberan entrar a las instalaciones acompañado de un adulto*
               </p>
         </footer>
     </body>
     </html>
      
      *{
     margin: 0;
     padding: 0;
     }

     div
     {
     width: 60%;
         text-align: right;
     }

     #ama
     {
     color: goldenrod;
     text-align: center;
     }

     ul
     {
     color: darkgreen;
     display: flex;
     list-style-type: neno;
     }

     main
     {
     height: 60vh;
     background: url("hero.jpg");
     background-repeat: no-repeat;
     backgriund-position: center;
     background-size: cover;
     }

     #w
     {
     color: white;
     text-align: right;
     font-size: 60px;
     width: 55%;
     }

     p
     {
     color: black;
     text-align: center;
     }

     .ret
     {
     margin: 10px;
     }

     img
     {
     height: 5vh;
     }

     span
     {
     font-size: 75px;
     text-width: bold;
     }

     nav
     {
     display: flex;
     justify-content: space-between;
     width: 100%;
     }
      
      INGRESA AQUI EL CSS
Ingresa el link a tu página del proyecto final
