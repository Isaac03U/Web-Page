# Web-Page
Here are the updates about my Web Page

First, we started using a simple code in HTML to define title and start using the basics of HTML.

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página sobre Microcontroladores</title>
  
We start building our page using basic code 

As it was required for this assignment, my webpage must have an image, a video and a small paragraph about the topic I chose, so lets continue with the next part of the code:

<style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .portada {
            text-align: center;
            margin-top: 100px;
        }
        .resumen {
            margin: 50px;
        }
        .imagen {
            text-align: center;
        }
        .audio {
            text-align: center;
            margin-top: 50px;
        }
        .video {
            text-align: center;
            margin-top: 50px;
        }
    </style>
</head>
<body>

Here we defined the elements that my page will contain and also we defined the position that each one will have.

Now that we have the basics of our page, we can continue coding the features that we will allow in it: 

<!-- Resumen -->
<div class="resumen">
    <h2>¿Qué son los Microcontroladores?</h2>
    <p>Los microcontroladores son dispositivos electrónicos altamente integrados que combinan un procesador, memoria, periféricos de entrada/salida y otros componentes necesarios para ejecutar programas embebidos en un solo chip. Estos componentes están diseñados para realizar tareas específicas dentro de sistemas electrónicos, desde controlar electrodomésticos y dispositivos industriales hasta controlar sistemas de automóviles y dispositivos médicos.

Los microcontroladores son fundamentales en una amplia gama de aplicaciones debido a su capacidad para procesar datos en tiempo real y controlar dispositivos físicos de manera eficiente. Son utilizados en sistemas de control automático, sistemas de comunicación, sistemas de seguridad, dispositivos médicos, juguetes electrónicos, entre otros.

La programación de microcontroladores se realiza generalmente en lenguajes de programación de bajo nivel como C o ensamblador, y los programas se cargan directamente en la memoria del microcontrolador. Esto permite que los dispositivos controlados por microcontroladores realicen tareas específicas de manera autónoma, sin necesidad de intervención humana constante.</p>
</div>

<!-- Imagen de Microcontroladores -->
<div class="imagen">
    <img src="Micros.jpg" alt="Imagen de Microcontroladores" width="400">
</div>

<!-- Audio -->
<div class="audio">
    <h2>Audio sobre la creación de Microcontroladores</h2>
    <audio controls>
        <source src="ruta_del_audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
</div>

<!-- Video -->
<div class="video">
    <h2>Video sobre Microcontroladores</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/ruta_del_video" frameborder="0" allowfullscreen></iframe>
</div>

</body>
</html>

As we can see, it´s a simple but useful HTML web page that meets the requirements for this assignment.
