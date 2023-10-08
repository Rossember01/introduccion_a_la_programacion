<!-- No borrar o modificar -->
[Inicio](./index.md)

# Sesión 8 

# Actividad: Aplicando estilos con selectores CSS

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

# Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>

 Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"


Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"


Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un <div>
- Centrar el contenido de la sección <section>


# Solución

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ACTIVIDAD8</title>
    <style>
        h1 {
            color: red;

        }

        p {
            color: blue;
        }

        div p {
            color: grey;

        }

        .grande {
            font-size: 80px;
        }

        section {
            text-align: center;
        }

        .destacado {
            color: green;
        }

        #principal {
            color: yellow;
        }
    </style>






</head>


<h1 class="grande">f1</h1>


<body>

    <section>
        <br>
        <h1 style="box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.301);">Red Bull</h1>
        <div>
            <p>
                Checo Pérez: Suzuka debería ser una gran pista para nosotros
                Sergio Pérez señaló que, internamente, en Red Bull tienen una idea de qué ha salido mal en el GP de
                Singapur,
                una suerte que no esperan se repita en Japón.
        </div>
        </p>
        <br>
        <h1 id="principal">Ferrari</h1>
        <p>
            Sainz: Debilidades de Ferrari no han cambiado pese a ganar en Singapur
            Carlos Sainz ha advertido de que los puntos débiles del coche de Ferrari siguen siendo los mismos a pesar de
            su
            victoria en el Gran Premio de Singapur de Fórmula 1.

        </p>
        <br>
        <h1 class="destacado">Aston Martin</h1>
        <p>
            Alonso y Aston Martin encuentran explicación a baja de rendimiento
            Fernando Alonso dice que está "menos preocupado" por la falta de ritmo de Aston Martin en el Gran Premio de
            Singapur de Fórmula 1 después de descubrir lo mucho que le ralentizó: una cubierta de suspensión dañada.

        </p>

        <img src="https://hips.hearstapps.com/hmg-prod/images/collage-f1-2022-1645179257.jpg" width="500" height="300"
            style="border: 1px solid black;">
    </section>
</body>
<br>
<br>

<footer style="box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.301)">
    <p>Así queda el campeonato 2023 de la F1 tras la carrera del GP de Singapur, con Max Verstappen al frente con 374
        puntos, en segundo el mexicano Sergio "Checo" Pérez, con 233, y tercero está Lewis Hamilton, con 180 unidades.
        Entre los equipos lidera Red Bull con 597 puntos, seguido de Mercedes con 289 unidades.</p>
</footer>


</html>


```



