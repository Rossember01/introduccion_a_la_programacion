<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


# Actividad: Creando mi primer sitio web

Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

Index o página de inicio
Acerca
Contacto

# solución

### index

```html
<!DOCTYPE html>

<head>
    
    <title>Mi primer sitio web</title>
</head>
<body>

    <header>
        <h1>Mi sitio web</h1>
    </header>
    
    <nav>
        <a href="acerca.html">acerca</a>
        <a href="contacto.html">contacto</a>
        </nav>

        <main>
            <p>Bienvenidos a mi sitio sobre empresas xyz</p>
            <p>Aqui encontraran información sobre nuestros servicios y productos</p>
        </main>

        <footer>
            <p>Copyright 2023 Rossember Restrepo</p>
            <P>rossember01@gmail.com</P>
        </footer>
</body>
```

### Acerca

```html
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Sobre nosotros</title>
</head>

<body>
    

<header>
    <h1>Sobre nosotros</h1>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="contacto.html">contacto</a>
    </nav>

    <section>

        <h2>Historia</h2>
        <P>Fundada en 2010</P>

        <article>
            <h3>Misión</h3>
            <P>Ofrecer alimentos saludables y de calidad que satisfagan a los consumidores </P>

            <h3>Visión</h3>
            <p>Estar siempre a la vanguardia en la industria de alimentos</p>
        </article>
        
    </section>

    <footer>
        <p>Copyright 2023 - Rossember Restrepo</p>
    </footer>

</body>

</html>

```

### Contacto

```html
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Contacto</title>
</head>

<body>
    
    <header>
        <h1>Contacto</h1>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="acerca.html">acerca</a>
    </nav>

    <main>

        <form>
            <label for="Nombre">Nombre:</label>
            <input type="text" id="Nombre"><br>

            <label for="Email">Email:</label>
            <input type="Email" id="Email"><br>

            <label for="Mensaje">Mensaje:</label>
            <textarea id="Mensaje"></textarea><br>

            <input type="Submit" value="Enviar">
        </form>

        <aside>
            <h3>Ubicación</h3>
            <p>Calle falsa 123</p>
        </aside>

    </main>

    <footer>
        <p>Copyright 2023 - Rossember Restrepo</p>
    </footer>

</body>

</html>
```






