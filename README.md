<!DOCTYPE html>
<html lang="es">
<head>

        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Página con Rectángulo Verde Oscuro en la Parte Superior</title>
        <style>
            body {
                margin: 0;
                padding: 0;
            }
            .green-rectangle {
                background-color: #23594C; /* Verde oscuro */
                width: 100%;
                height: 20px; /* Altura del rectángulo */
            }
        </style>
    </head>

    <body>
        <div class="green-rectangle"></div>
        <!-- Aquí puedes agregar el resto del contenido de tu página -->
    </body>
    </html>

    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invitación de Matrimonio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background-color: #f3f7f3; /* Verde oscuro */
            color: #939292; /* Color del texto */
            font-family: Arial, sans-serif;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        #video-container {
            width: 100%;
            max-width: 800px;
            overflow: hidden;
            border-radius: 10px;
        }
        #video-container video {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .playlist-container {
            width: 100%;
            max-width: 800px;
            text-align: center;
            margin-top: 20px;
        }
        .playlist-container iframe {
            width: 100%;
            max-width: 400px;
            height: 400px;
            border: none;
            border-radius: 10px;
        }
        .image-container {
            text-align: center;
            margin-top: 20px;
        }
        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <p>¡Nos alegra compartir este momento especial contigo!</p>

    <!-- Video de Header -->
    <div id="video-container">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Centrado con Audio</title>
    <style>
        video {
            max-width: 80%;
            height: auto;
        }
    </style>
    <video controls autoplay>
        <source src="Invitacion.mp4" type="video/mp4">
    </video>
    </div>
    <!-- Imágenes centradas -->
    <div class="image-container">
        <h2>Galería de Fotos</h2>
        <img src="imagen1.jpg" alt="Imagen 1">
        <img src="imagen2.jpg" alt="Imagen 2">
        <!-- Agrega más imágenes según sea necesario -->
    </div>

    <!-- Playlist de Spotify -->
    <div class="playlist-container">
        <h2>Playlist de Spotify</h2>
        <iframe src="https://open.spotify.com/embed/playlist/xxxxxxxxxxxxxx" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
    </div>

    <!-- Footer -->
    <footer>
        <p>©️ 2024. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
