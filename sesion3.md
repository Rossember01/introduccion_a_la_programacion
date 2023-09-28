<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

### Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

4 Imagenes

2 Videos

4 Audios

2 Inline Frame´

```html
Utiliza encabezados para títulos en cada elemento (<h1>...<h6>).

Crea una descripción para cada elemento utilizando párrafos (<p>).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa <strong> para resaltar texto importante.

- Utiliza <br> para insertar saltos de línea si es necesario.

- Agrega <span> para aplicar estilos específicos a porciones de texto.

- Emplea <i> para enfatizar o dar énfasis a palabras o frases.

- Utiliza <u> para subrayar texto cuando sea necesario.

- Considera el uso de <div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.
```

# Solución

```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1><u>Lo bueno de viajar</u></h1>
        <h3>La mejor forma de disfrutar la vida</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <h2>Una buena playa</h2>

        <center><img src="Playa1.jpg" alt=""></center>

        <h2>Alguito de tomar</h2>
        <center><img src="Bebida en playa.jpg" alt=""></center>

        <h2>Nuevos sitios</h2>
        <center><img src="Paseo.jpg" alt=""></center>

        <h2>Un nuevo impulso</h2>
        <center><img src="Descanso.jpg" alt=""></center>

    </section>

    <section>
        <h2>Video1</h2>
        <video src="Tranquilidad.mp4" controls width="500"></video>


        <h2>Video2</h2>
        <video src="Conexion.mp4" controls width="500"></video>
    </section>

    <section>
        <h2>Audio1</h2>
        <p>Olas</p>
        <audio src="ocean-lake-sea-shore-waves-18921.mp3" controls></audio>

        <h2>Audio2</h2>
        <p>mas olas</p>
        <audio src="ocean-sea-soft-waves-121349.mp3" controls></audio>

        <h2>Audio3</h2>
        <p><span style="color: green;" </span>Tranquilidad absoluta</p>
        <audio src="ocean-waves-112906.mp3" controls></audio>

        <h2>Audio4</h2>
        <p><strong>Cascada</strong></p>
        <audio src="waterfall-in-the-mountains_nature-sound-161925.mp3" controls></audio>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Otra buena opcion de viajar</p>
        <iframe src="https://cnnespanol.cnn.com/seccion/viajes-y-turismo/" width="500" height="300"></iframe>


        <h2>iFrames</h2>
        <p>Las mejores playas del mundo</p>
        <iframe src="https://www.semana.com/noticias/viajes/" width="500" height="300"></iframe>



    </section>

    <footer>
        ROSSEMBER ANDREY RESTREPO ALVAREZ
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```






