Realización de actividad para practicar HTML y CSS en parejas:

Actividad: Creación de una página de perfil personal

Desarrollar una página de perfil personal que incluya información básica, una imagen de perfil y un diseño estilizado utilizando HTML y CSS.

Detalles:
- La página debe contener al menos una imagen, un encabezado, un párrafo de texto y un enlace a redes sociales.
- Cada pareja de programadores/as trabajará en diferentes partes de la página: uno se encargará del diseño y estilos (CSS), y el otro de la estructura y contenido (HTML).
- Utilizarán un sistema de control de versiones para coordinar y combinar sus contribuciones.

Pasos:

Preparación:
1. Decidir quién será responsable del HTML y quién del CSS.
   
Desarrollo:
   
Pareja 1 - Estructura y Contenido (HTML):
1. Crea un nuevo repositorio de Git y comparte el enlace con tu pareja.
2. En la rama main sólo debe de estar el archivo Readme.md
3. Crea la rama dev.
4. Crea un archivo `index.html` en la rama dev.
5. Crea una rama de trabajo por ejemplo: ramaHTML
6. Diseña la estructura básica de la página, incluyendo un encabezado, una imagen de perfil, un párrafo de texto y un enlace a redes sociales.
7. Agrega contenido de ejemplo para cada sección.
8. Realiza un commit con tu implementación y haz un push a la ramaHTML.
9. Haz un merge a la dev cuando el trabajo esté terminado.
10. Por último haz un merge a la main.

Pareja 2 - Diseño y Estilos (CSS):
1. Clona el repositorio creado por tu pareja.
2. Crear un archivo `styles.css`
3. Crea una rama de trabajo, por ejemplo ramaCSS.
4. Implementa estilos para la página utilizando CSS. Puedes experimentar con colores, fuentes, tamaños y márgenes para hacer que la página se vea atractiva.
5. Aplica estilos a la imagen de perfil, encabezado, párrafo de texto y enlace a redes sociales.
6. Realiza un commit con tu implementación y haz un push a la ramaCSS.
8. Haz un merge a la dev cuando el trabajo esté terminado.
9. Por último haz un merge a la main. 

Integración:
1. Ambos revisan el trabajo del otro/a para asegurarse de que se integren correctamente HTML y CSS.
2. Uno de vosotros fusionará las ramas (`main`) y resolverá cualquier conflicto si es necesario.
3. Tenéis que verificar que la página se vea y funcione correctamente en un navegador web.
4. Realizar un último commit para documentar la integración y hagan un push final al repositorio.

Conclusión:

En un readme.md tenéis que documentar los pasos que habéis seguido y contestar a estas preguntas. 

Reflexión sobre el proceso:
- ¿Cómo fue la colaboración utilizando control de versiones en el desarrollo web?
- ¿Qué desafíos encontrasteis al trabajar en diferentes partes de la página?
- ¿Qué aprendieron sobre la importancia de la separación entre HTML y CSS?

Ejemplo Práctico:

Supongamos que la pareja 1 crea la siguiente estructura HTML:


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil Personal</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Nombre Apellido</h1>
        <img src="profile.jpg" alt="Foto de perfil">
    </header>
    <main>
        <p>Soy un desarrollador web apasionado por la tecnología...</p>
        <a href="#">Sígueme en Instagram</a>
    </main>
    <footer>
        <p>&copy; 2025 - Todos los derechos reservados</p>
    </footer>
</body>
</html>


Y la pareja 2 aplica estilos CSS como este:


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f3f3f3;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
}

main {
    padding: 20px;
}

img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    display: block;
    margin: 0 auto 20px;
}

a {
    color: #333;
    text-decoration: none;
    background-color: #fff;
    padding: 10px 20px;
    border-radius: 5px;
}

a:hover {
    background-color: #999;
    color: #fff;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

