![Blend Text Tutorial](https://raw.githubusercontent.com/sergiecode/blend-text-css/master/blend%20text.jpg)

#   Tutorial para Blend Text en CSS

Este tutorial te guiará a través de los pasos necesarios para crear un efecto de "Blend Text" utilizando CSS. El efecto consiste en mezclar el texto con el fondo de una manera atractiva y creativa utilizando la propiedad `mix-blend-mode`. En este ejemplo, utilizaremos un archivo HTML y un archivo CSS para lograr este efecto.

## Archivos incluidos

Asegúrate de que tu proyecto tenga los siguientes archivos:

1.  **index.html**: Este archivo contendrá la estructura HTML básica y el contenido del efecto Blend Text.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Blend Text Tutorial</title>
</head>
<body>

    <div class="contenedor">
        <h2 class="texto">SERGIE CODE</h2>
    </div>
    
</body>
</html>

```

2.  **style.css**: En este archivo CSS, definiremos los estilos necesarios para lograr el efecto Blend Text.

```
.contenedor {
    margin: 50px;
    height: 366px;
    width: 593px;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-content: center;
    justify-content: center;
    align-items: center;
    background-image: url(background.png);
}

.texto {
    position: absolute;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 70px;
    font-weight: 900;
    background-color: white;
    padding: 0.5rem 1rem;
    mix-blend-mode: screen;
}
```

## Pasos

1.  Crea un archivo HTML llamado `index.html` y copia el contenido del código HTML proporcionado anteriormente.
    
2.  Crea un archivo CSS llamado `style.css` y copia el contenido del código CSS proporcionado anteriormente.
    
3.  Coloca una imagen de fondo que quieras usar en el mismo directorio que tus archivos HTML y CSS, y nómbrala `background.png`.
    
4.  Abre el archivo `index.html` en tu navegador web. Deberías ver el texto "SERGIE CODE" mezclado con la imagen de fondo de manera creativa.
    

## Explicación

-   Hemos utilizado la propiedad `mix-blend-mode` con el valor `screen` en la clase `.texto` para mezclar el texto con el fondo. Esto crea un efecto de fusión que hace que el texto se mezcle de manera visualmente atractiva con la imagen de fondo.
    
-   El texto tiene un fondo blanco semi-transparente creado con la propiedad `background-color` y el padding. Esto asegura que el texto sea visible y el efecto de mezcla sea más evidente.
