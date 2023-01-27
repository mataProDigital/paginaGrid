# paginaGrid
Pagina utilizando HTML, CSS y en especifico usando Grid
# Para agregar un icono fav a su página web, siga estos pasos:

1. Cree o encuentre una imagen que desee utilizar como icono fav. Asegúrese de que la imagen sea cuadrada y tenga un tamaño de al menos 16x16 píxeles.
2. Guarde la imagen en el formato .ico (ico es el formato recomendado para los favicon)
3. Suba la imagen a la raíz de su sitio web.
4. Agregue la siguiente línea de código en la sección head de cada página de su sitio web donde desea que se muestre el icono fav:

```html
Copy code
<link rel="shortcut icon" href="path/to/favicon.ico" type="image/x-icon">

```

1. reemplaza "path/to/favicon.ico" con la ruta correcta de tu imagen
2. Guarda y publica tus cambios y recarga tu pagina, veras tu nuevo icono fav.

Ten en cuenta que algunos navegadores pueden tomar un tiempo para mostrar el nuevo icono fav, así que es posible que necesite limpiar la caché de su navegador antes de ver los cambios.

## Opciones para obtener imágenes de 16x16:

1. Puedes crear tu propia imagen utilizando una herramienta de edición de imágenes como Adobe Photoshop, GIMP, o Paint.net.
2. Puedes descargar imágenes de sitios web gratuitos de recursos de imágenes, como Pixabay, Unsplash, o Pexels. Asegúrate de revisar los términos de uso antes de descargar cualquier imagen.
3. Puedes comprar imágenes en sitios web de venta de imágenes, como Shutterstock o iStock.
4. Puedes utilizar un generador de iconos, como IcoMoon o Flaticon, que te permiten crear iconos personalizados a partir de una variedad de fuentes.

## Opciones en línea para cambiar el tamaño de una imagen a 16x16 píxeles:

1. Online-Convert: Este sitio web le permite cambiar el tamaño de una imagen a 16x16 píxeles utilizando una variedad de formatos de entrada.
2. ResizeImage.net: Este sitio web le permite cambiar el tamaño de una imagen a 16x16 píxeles utilizando una variedad de formatos de entrada.
3. PicResize: Este sitio web le permite cambiar el tamaño de una imagen a 16x16 píxeles utilizando una variedad de formatos de entrada.
4. ResizeYourImage: Este sitio web le permite cambiar el tamaño de una imagen a 16x16 píxeles utilizando una variedad de formatos de entrada.

## Normalize.css

Normalize.css es una hoja de estilos CSS que se utiliza para normalizar los estilos predeterminados entre diferentes navegadores. Es recomendable utilizar Normalize.css en proyectos web para garantizar una presentación consistente de los elementos de la página en diferentes navegadores.

Normalize.css no es un sustituto para los estilos personalizados, sino una herramienta para ayudar a garantizar que los elementos básicos de la página se vean de manera similar en todos los navegadores. Es recomendable utilizarlo al principio de tu hoja de estilos, para que las reglas personalizadas puedan sobreescribir lo establecido por Normalize.

Además, algunas de las funcionalidades de Normalize.css son:

- Asegurar que todos los navegadores tienen los mismos valores predeterminados para elementos como headings, blockquotes, lists, etc.
- Mejorar la accesibilidad al hacer que algunos elementos sean más fáciles de usar con teclado.
- Proporcionar una base sólida para construir estilos personalizados.

En resumen, Normalize.css es una herramienta recomendable para garantizar una presentación consistente de los elementos de la página en diferentes navegadores, y proporciona una base sólida para construir estilos personalizados.

## Puedes utilizar Normalize.css en tu proyecto de varias maneras:

1. Descargando el archivo: Puedes descargar el archivo CSS de Normalize.css desde su sitio web oficial (**[https://necolas.github.io/normalize.css/](https://necolas.github.io/normalize.css/)**) y agregarlo a tu proyecto manualmente. Asegúrate de agregarlo al principio de tu hoja de estilos para que las reglas personalizadas puedan sobreescribirlo.
2. Utilizando un CDN: Puedes utilizar un Content Delivery Network (CDN) para cargar Normalize.css en tu proyecto. Un ejemplo de cómo hacerlo es agregando la siguiente línea de código en la sección head de tu archivo HTML:

```html
Copy code
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css">

```

1. A través de un administrador de paquetes: Si estás utilizando un administrador de paquetes como npm o yarn, puedes instalar Normalize.css como un paquete y agregarlo a tu proyecto. Ejemplo de cómo hacerlo en npm:

```
Copy code
npm install normalize.css

```

1. Utilizando un framework: Si estás utilizando un framework de front-end como Bootstrap o Foundation, ya incluyen una versión de normalize.css.

En cualquier caso, es importante que recuerdes agregarlo al principio de tu hoja de estilos para que las reglas personalizadas puedan sobreescribirlo.

## Existen varias alternativas a Normalize.css

1. Reset.css: Es una hoja de estilos CSS que se utiliza para reiniciar los valores predeterminados de los elementos de HTML. Es similar a Normalize.css, pero en lugar de normalizar los estilos, los reinicia completamente.
2. Sanitize.css: Es una hoja de estilos CSS que se utiliza para estandarizar los estilos predeterminados entre diferentes navegadores. Sanitize.css se enfoca en proporcionar una base sólida para construir estilos personalizados, al igual que Normalize.css
3. Base.css: Es una hoja de estilos CSS que se utiliza para establecer una serie de reglas básicas para los elementos de HTML. Se enfoca en proporcionar una base sólida para construir estilos personalizados, al igual que Normalize.css.
4. Normalizer.css: Es una hoja de estilos CSS que se utiliza para normalizar los estilos predeterminados entre diferentes navegadores. Es similar a Normalize.css, pero tiene un enfoque ligeramente diferente y se actualiza con menos frecuencia.
5. Eric Meyer's Reset CSS: Es una hoja de estilos CSS que se utiliza para reiniciar los valores predeterminados de los elementos de HTML. Es similar a Normalize.css pero con un enfoque más en el reset de los estilos.