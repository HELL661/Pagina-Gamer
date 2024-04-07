Pagina-Gamer
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Untitled Page</title>
<meta name="generator" content="WYSIWYG Web Builder 16 - http://www.wysiwygwebbuilder.com">
<link href="Juegos.css" rel="stylesheet">
<link href="Entrar.css" rel="stylesheet">
<style>
    /* Estilos CSS del primer documento */
    /* Agrega estilos CSS adicionales para hacer la página receptiva */
    @media screen and (max-width: 767px) {
        /* Estilos para pantallas de hasta 767px de ancho (Dispositivos móviles) */
        #wb_Heading1 {
            left: 50px;
            width: auto;
            font-size: 20px;
        }
        #wb_Heading2 {
            left: 20px;
            width: auto;
            font-size: 24px;
        }
        #wb_Text1 {
            left: 20px;
            width: auto;
            font-size: 14px;
        }
        #wb_Image3 {
            display: none; /* Ocultar la imagen en la esquina superior derecha */
        }
    }

    @media screen and (min-width: 768px) and (max-width: 991px) {
        /* Estilos para pantallas de 768px a 991px de ancho (Tabletas) */
        #wb_Heading1 {
            left: 100px;
            width: auto;
            font-size: 28px;
        }
    }

    @media screen and (min-width: 992px) and (max-width: 1199px) {
        /* Estilos para pantallas de 992px a 1199px de ancho (Tabletas y dispositivos de escritorio más pequeños) */
        #wb_Heading1 {
            left: 200px;
            width: auto;
            font-size: 32px;
        }
    }

    @media screen and (min-width: 1200px) {
        /* Estilos para pantallas de 1200px en adelante (Dispositivos de escritorio) */
        #wb_Heading1 {
            left: 300px;
            width: auto;
            font-size: 36px;
        }
    }

    /* Estilos CSS del segundo documento */
    div#container {
        width: 1354px;
        position: relative;
        margin: 0 auto 0 auto;
        text-align: left;
    }
    body:before {
        content: "";
        position: fixed;
        left: 0;
        top: 0;
        right: 0;
        bottom: 0;
        z-index: -1;
        background: radial-gradient(circle, #9370DB 0%, #000000 100%);
    }
    body {
        background-color: #9370DB;
        color: #000000;
        font-family: Arial;
        font-weight: normal;
        font-size: 13px;
        line-height: 1.1875;
        margin: 0;
        text-align: center;
    }
    a {
        color: #0000FF;
        text-decoration: underline;
    }
    a:visited {
        color: #800080;
    }
    a:active {
        color: #FF0000;
    }
    a:hover {
        color: #0000FF;
        text-decoration: underline;
    }
    input:focus, textarea:focus, select:focus {
        outline: none;
    }
    #wb_Image1 {
        vertical-align: top;
    }
    #Image1 {
        border: 0px solid #000000;
        padding: 0;
        margin: 0;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
    }
    #Button1 {
        box-sizing: border-box;
        line-height: 61px;
        text-decoration: none;
        vertical-align: top;
        border: 1px solid #7FFFD4;
        border-radius: 4px;
        background-color: #7FFFD4;
        background-image: none;
        color: #000000;
        font-family: Georgia;
        font-weight: normal;
        font-style: normal;
        font-size: 19px;
        padding: 1px 6px 1px 6px;
        text-align: center;
        -webkit-appearance: none;
        margin: 0;
    }
    #wb_Image2 {
        vertical-align: top;
    }
    #Image2 {
        border: 0px solid #000000;
        padding: 0;
        -webkit-transform: rotate(90deg);
        transform: rotate(90deg);
        -webkit-transform-origin: 50% 50%;
        transform-origin: 50% 50%;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
    }
    #wb_Image3 {
        vertical-align: top;
    }
    #Image3 {
        border: 0px solid #000000;
        padding: 0;
        margin: 0;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
    }
</style>
</head>
<body>
<div id="container">
    <div id="wb_Image1" style="position:absolute;left:266px;top:104px;width:844px;height:575px;z-index:0;">
        <img src="images/pc1.gif" id="Image1" alt="">
    </div>
    <a id="Button1" href="./Bienvenida-.html" style="position:absolute;left:606px;top:842px;width:165px;height:65px;z-index:1;">GO!!</a>
    <div id="wb_Image2" style="position:absolute;left:633px;top:698px;width:111px;height:128px;z-index:2;">
        <img src="images/right-arrow.gif" id="Image2" alt="">
    </div>
    <div id="wb_Image3" style="position:absolute;left:266px;top:104px;width:854px;height:575px;z-index:3;">
        <img src="images/Marco.gif" id="Image3" alt="">
    </div>
</div>

<script>
    // Agregar evento onClick al botón para mostrar una alerta
    document.getElementById("Button1").addEventListener("click", function() {
        alert("Let's go!!");
    });
</script>

</body>
</html>
