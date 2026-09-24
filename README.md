<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Under Night In Birth Sys Celes - Argentina</title>
    <!-- Enlace a Font Awesome para los iconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        /* --- Definición de fuentes --- */
        /* Constantia es una fuente de Windows, usamos una alternativa similar si no está */
        @font-face {
            font-family: 'Constantia';
            src: local('Constantia'), local('Georgia'), local('Times New Roman');
        }

        /* FOT-NewCezanne es una fuente japonesa, usamos una alternativa sans-serif */
        @font-face {
            font-family: 'FOT-NewCezanne';
            src: local('FOT-NewCezanne'), local('Yu Gothic'), local('Meiryo'), local('MS PGothic'), local('sans-serif');
        }

        /* --- Estilos generales --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            /* Fondo: Reemplaza 'fondo.jpg' con el nombre de tu archivo de fondo */
            background-image: url('fondo.jpg');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-family: 'FOT-NewCezanne', 'Yu Gothic', 'Meiryo', sans-serif;
            color: #ffffff;
            text-align: center;
            padding: 20px;
        }

        /* --- Contenedor principal --- */
        .container {
            max-width: 900px;
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 30px;
            padding: 40px 20px;
            /* Fondo semitransparente para que el texto se lea mejor */
            background-color: rgba(0, 0, 0, 0.4);
            border-radius: 15px;
            backdrop-filter: blur(3px);
        }

        /* --- Logo principal --- */
        /* Reemplaza 'logo.png' con el nombre de tu archivo de logo */
        .logo {
            max-width: 400px;
            width: 80%;
            height: auto;
            display: block;
            margin: 0 auto;
        }

        /* --- Título de la página --- */
        h1 {
            font-family: 'Constantia', 'Georgia', 'Times New Roman', serif;
            font-size: 2.5rem;
            font-weight: bold;
            color: #ffffff; /* Texto blanco */
            /* Relleno púrpura: usamos text-shadow para simular un borde/relleno */
            text-shadow: 
                2px 2px 0 #800080,
                -2px -2px 0 #800080,
                2px -2px 0 #800080,
                -2px 2px 0 #800080,
                0 0 10px #9b59b6,
                0 0 20px #8e44ad;
            letter-spacing: 2px;
            text-transform: uppercase;
            line-height: 1.3;
        }

        /* --- Relleno celeste para "Argentina" --- */
        h1 .argentina {
            color: #ffffff;
            text-shadow: 
                2px 2px 0 #0025CE,
                -2px -2px 0 #0025CE,
                2px -2px 0 #0025CE,
                -2px 2px 0 #0025CE,
                0 0 10px #A8D0F0,
                0 0 20px #0025CE;
        }

        /* --- Descripción debajo del título --- */
        .descripcion {
            font-family: 'FOT-NewCezanne', 'Yu Gothic', 'Meiryo', sans-serif;
            font-size: 1.2rem;
            color: #ffffff;
            text-shadow: 
                1px 1px 0 #800080,
                -1px -1px 0 #800080,
                1px -1px 0 #800080,
                -1px 1px 0 #800080,
                0 0 8px rgba(155, 89, 182, 0.8);
            max-width: 650px;
            margin: 0 auto;
            line-height: 1.5;
            letter-spacing: 0.5px;
        }

        /* --- Contenedor de iconos de redes sociales --- */
        .social-links {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 10px;
        }

        /* --- Estilo de cada enlace/icono --- */
        .social-links a {
            color: #ffffff;
            font-size: 3rem;
            text-decoration: none;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background-color: rgba(128, 0, 128, 0.6); /* Fondo púrpura semitransparente */
            border: 2px solid #ffffff;
            box-shadow: 0 4px 15px rgba(128, 0, 128, 0.5);
        }

        /* --- Efecto al pasar el mouse --- */
        .social-links a:hover {
            transform: scale(1.15) translateY(-5px);
            background-color: #800080; /* Púrpura sólido */
            box-shadow: 0 8px 25px rgba(155, 89, 182, 0.8);
            color: #ffffff;
        }

        /* --- Ajustes responsivos --- */
        @media (max-width: 600px) {
            h1 {
                font-size: 1.8rem;
            }
            .descripcion {
                font-size: 0.9rem;
                padding: 0 10px;
            }
            .social-links a {
                font-size: 2.2rem;
                width: 60px;
                height: 60px;
            }
            .logo {
                max-width: 250px;
            }
            .container {
                padding: 20px 10px;
            }
        }

        /* --- Instrucciones para las imágenes --- */
        .image-instructions {
            margin-top: 20px;
            font-size: 0.8rem;
            color: #cccccc;
            background-color: rgba(0,0,0,0.5);
            padding: 10px;
            border-radius: 8px;
            max-width: 500px;
        }
        .image-instructions code {
            background-color: #333;
            padding: 2px 6px;
            border-radius: 4px;
            color: #ffcc00;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Logo Principal -->
        <!-- Reemplaza 'logo.png' con la ruta de tu imagen de logo -->
        <img src="logo.png" alt="Under Night In Birth Sys Celes - Argentina" class="logo">

        <!-- Título -->
        <h1>Under Night In Birth Sys Celes  <span class="argentina">Argentina</span></h1>

        <!-- Descripción -->
        <p class="descripcion">
            Comunidad argentina de Under Night In-Birth enfocándose en torneos, exhibiciones, eventos y más.
        </p>

        <!-- Enlaces con iconos (solo se ven los iconos) -->
        <div class="social-links">
            <!-- Discord -->
            <a href="https://discord.gg/jA4W3WnQVP" target="_blank" rel="noopener noreferrer" title="Discord">
                <i class="fab fa-discord"></i>
            </a>
            <!-- Twitch -->
            <a href="https://www.twitch.tv/uniargentina" target="_blank" rel="noopener noreferrer" title="Twitch">
                <i class="fab fa-twitch"></i>
            </a>
            <!-- Twitter / X -->
            <a href="https://x.com/UnderNightARG" target="_blank" rel="noopener noreferrer" title="Twitter / X">
                <i class="fab fa-twitter"></i>
                <!-- Si prefieres el icono de X en vez del pajarito, reemplaza la línea de arriba por:
                <i class="fa-brands fa-x-twitter"></i> -->
            </a>
            <!-- YouTube -->
            <a href="https://www.youtube.com/@UnderNightArgentina" target="_blank" rel="noopener noreferrer" title="YouTube">
                <i class="fab fa-youtube"></i>
            </a>
        </div>

   
</body>
</html>
