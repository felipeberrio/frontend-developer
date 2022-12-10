# Proyecto frontend developer
Proyecto del curso practivo de frontend developer de Platzi
> Imagenes de: https://drive.google.com/drive/folders/1EqPBh8LR0TJIi3zJCwPxl8W9h8Mc82GS
> Maquetado: https://scene.zeplin.io/project/60afeeed20af1378ed046538
> Figma: https://www.figma.com/files/recent?fuid=1144810407156046225

> Metodologías de diseño https://polaris.shopify.com/design/design

1. Creamos nuestro index.html y en estilos creamos la fuente de nuestros colores incluido los que trae por base CSS por si algúna libreria que traemos nos llega a cambiar este nombre, e importamos las tipografias.

2. Agregamos las diferentes ventanas de la aplicación

3. Declaramos las variables en común para cada hoja de estilos de Css en cada una de las ventanas de la app
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;500;700&display=swap');
        :root{
            --white: #FFFFFF;
            --black: #000000;
            --dark: #232830;
            --very-light-pink: #C7C7C7;
            --text-input-field: #F7F7F7;
            --hospital-green: #ACD9B2;
            --sm: 14px;
            --md: 16px;
            --lg: 18px;
        }

        body{
        margin: 0;
        font-family: 'Quicksand', sans-serif;
        }
    </style>

4. Para este ejercicio se crearon todas las ventanas con sus estilos incluidos, pero mejor practica es separarlos en un archivo css además de que ninguna página tiene funcionalidad, únicamente frontend y maqueteado