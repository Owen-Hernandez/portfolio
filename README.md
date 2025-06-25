# portofolio-v2

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Notas
```
App.vue
Archivo raíz de la aplicación Vue. Es el componente principal donde se estructura la navegación y se incluye el router-view, que sirve como contenedor dinámico para las páginas (views).

Contenido importante:
Navbar (menú superior):
Ubicado dentro del <nav>, incluye enlaces (<router-link>) a rutas como:

/ → Inicio

/about → Acerca de

/portfolio → Portafolio

/blog → Blog

Footer (menú inferior para móviles):
Aparece solo en pantallas pequeñas (md:hidden) y contiene los mismos enlaces de navegación que el navbar.

Redirección personalizada:
El botón de título bagasRakha(); en el navbar redirige a la página de inicio con un método redirectToInicio().

<router-view />:
Este componente sirve para mostrar el contenido de la vista correspondiente según la ruta activa. Ejemplo: si estás en /about, carga el contenido del componente asociado a esa ruta.

Cosas que se pueden editar en App.vue:
Texto de los enlaces del menú:
Se puede cambiar el texto visible como "About" por "Acerca de" directamente en los <router-link>.

Enlaces o rutas nuevas:
Se pueden agregar más <router-link> si se agregan nuevas páginas en el proyecto.

Estilos del scroll y cuerpo:
En la sección <style> están los estilos globales, incluido el estilo del scroll personalizado y fondo oscuro.

📁 /views
Esta carpeta contiene las vistas o páginas principales del sitio web. Cada una se carga dentro del <router-view /> del App.vue según la URL.

Ejemplos de vistas comunes:
Home.vue → Ruta / (Inicio)

About.vue → Ruta /about (Acerca de)

Portfolio.vue → Ruta /portfolio

Blog.vue → Ruta /blog

Estas vistas son archivos .vue completos que definen lo que se muestra cuando se visita cada sección del sitio.


PARA AGREGAR IMAGENES EN EL APARTADO DE PORTOFLIO SE DEBE COPIAR LAS IMAGENES A LAS 2 RUTAS:
C:\Users\OWEN\Desktop\portfolio\public\img
C:\Users\OWEN\Desktop\portfolio\dist\img