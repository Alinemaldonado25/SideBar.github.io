# Introducción
**Sidenav o barra lateral**  
Es un elemento de diseño web muy común que se utiliza para la navegación principal de un sitio o aplicación. Es una barra de navegación vertical, que generalmente se encuentra en el lado izquierdo, aunque en algunos casos puede estar a la derecha de la pantalla. Contiene enlaces a secciones o funcionalidades del sitio.

Es útil para organizar y presentar información adicional, como menús de navegación, opciones de configuración, publicidad o contenido relacionado. Se usa en sitios web, como blogs, tiendas online, paneles de control y también en aplicaciones móviles, en especial en aquellas que requieren una navegación más compleja.

## Tipos de sidenav:
- **Fijo**: siempre visible en la pantalla.
- **Colapsable o desplegable**: se oculta y se despliega al hacer click en un botón.
- **Emergente**: aparece cuando el usuario realiza una acción específica.
- **Responsivo**: se adapta al tamaño de la pantalla, cambiando su diseño y comportamiento. Se adapta a todos los dispositivos.

Los sidenav pueden ser con texto, con iconos (requiere que los iconos sean fácilmente reconocibles, se usa especialmente en diseños minimalistas) y con submenús.

### ¿Para qué sirve?
- Facilita el acceso a diferentes secciones de un sitio o aplicación, en especial si estos tienen mucho contenido.
- Agrupa elementos relacionados, evitando que la pantalla se vea saturada.
- Destaca elementos importantes, como menús o llamadas a la acción.
- Permite a los usuarios acceder rápidamente a sus configuraciones o preferencias, personalizando su experiencia.

### Beneficios:
- Hace que el sitio sea más fácil de navegar y explorar.
- Ofrece una interfaz más organizada y atractiva.
- Invita a los usuarios a explorar más opciones y contenido.
- Permite a los usuarios encontrar lo que desean más rápidamente.

---

# Detalles del Proyecto

El proyecto sobre **Barra lateral o Side Navigation** puede ser minimizado para que solo se muestren los iconos. Cuenta con un interruptor para habilitar o deshabilitar el modo oscuro. Es completamente responsivo, tanto en vertical como en horizontal, para adaptarse a cualquier tipo de dispositivo. Cuando se muestra de forma vertical, la barra se oculta y en su lugar se muestra un botón flotante. Al hacer clic en él, se puede ocultar o mostrar la barra lateral.

## Herramientas Utilizadas
- **Google Fonts** (tipo de letra)
- **Ionicons** (iconos)

### Estructura Responsiva
La barra lateral se divide en 3 secciones:
1. Nombre de la página junto con el botón.
2. Menú.
3. Línea y modo oscuro.

---

## HTML
**HTML** es el lenguaje principal utilizado para crear y estructurar el contenido en la web. No es un lenguaje de programación como tal, sino de marcado. Permite organizar el contenido mediante etiquetas para que los navegadores puedan mostrar correctamente textos, imágenes, enlaces, y otros elementos visuales en una página web.

En este proyecto se utiliza HTML5, indicado por `<!DOCTYPE html>`. La página está configurada en español (`<html lang="es">`) y dentro del bloque `<head>`, se incluye la codificación de caracteres (UTF-8) y una etiqueta de viewport para hacer la página adaptable a diferentes dispositivos.

---

## CSS
Para los estilos, utilizamos **Google Fonts** para elegir la tipografía, y las variables CSS para definir colores tanto en modo claro como en modo oscuro, lo que facilita cambiar el tema de la página.

### Diseño Responsivo
Usamos el selector universal para aplicar un estilo base a todos los elementos, incluyendo márgenes, rellenos, y tipo de letra. Se definieron estilos específicos para el cuerpo de la página, la barra lateral, el menú de navegación y el switch para el modo oscuro. Se agregaron estilos específicos para pantallas más pequeñas usando `@media`.

---

## JavaScript
En **JavaScript**, se crean variables y constantes para manipular la barra lateral, los botones y el switch del modo oscuro. Se utilizan métodos como `getElementById()`, `querySelector()`, y `addEventListener()` para añadir interactividad al proyecto.

### Funcionalidad del Menú
El botón del menú cambia entre mostrar y ocultar la barra lateral. Además, el switch de modo oscuro permite alternar entre los dos modos de visualización (claro y oscuro).

---

### Consideraciones Responsivas
El diseño se adapta automáticamente a pantallas pequeñas, mostrando solo un botón flotante para el menú cuando la pantalla es inferior a 600px de ancho. También se ajusta el contenido del main cuando la barra lateral se minimiza.

---
