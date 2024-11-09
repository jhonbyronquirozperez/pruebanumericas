# Documentación de la Prueba Técnica - Página Web E-learning

## Descripción General
Esta prueba técnica consiste en crear una página web enfocada en el **E-learning**, utilizando únicamente **Bootstrap** y **HTML**. La página debe ser completamente **responsiva** y funcionar correctamente en dispositivos de diferentes tamaños. Además, se debe organizar el código de forma clara y estructurada, con una correcta nomenclatura de archivos.

## Instrucciones

### Estructura de la Página

1. **Archivo principal**: Se debe crear un archivo `index.html`.
2. **Estructura HTML básica**: Se debe incluir la estructura básica de HTML y vincular el CDN de Bootstrap en la sección `<head>` del documento.
3. **Vinculación del CDN de Bootstrap**: 
    - Incluir la versión de Bootstrap 5 o superior a través de un CDN.

### Navbar (Barra de navegación)

1. **Barra fija**: La barra de navegación debe estar fija en la parte superior de la página.
2. **Elementos en la barra**: Incluir los siguientes enlaces:
   - **Inicio**
   - **Servicios**
   - **Portfolio**
   - **Contacto**
3. **Logotipo**: El logotipo debe estar en la barra de navegación.
4. **Menú hamburguesa**: El menú de navegación debe colapsar en un botón de menú (hamburguesa) cuando la pantalla tenga un ancho menor a 768px.

### Sección de Encabezado (Hero)

1. **Sección Hero**: Crear una sección con un fondo de imagen.
2. **Texto de bienvenida**: El texto debe estar centrado tanto vertical como horizontalmente dentro de la sección Hero.
3. **Diseño responsivo**: Usar las clases de alineación y diseño responsivo de Bootstrap para asegurarse de que el texto sea visible y bien distribuido en todos los dispositivos.

### Sección de Servicios

1. **Número de columnas**: Crear una sección que contenga al menos tres columnas.
2. **Contenido de cada columna**: Cada columna debe contener:
   - Un icono (puede usarse Bootstrap Icons o Font Awesome)
   - Un título
   - Una breve descripción del servicio
3. **Sistema de rejilla**: Utilizar el sistema de rejilla de Bootstrap para garantizar que las columnas se apilen en dispositivos móviles y se expandan en dispositivos de escritorio.

### Sección de Portfolio

1. **Galería de imágenes**: Crear una galería con al menos seis imágenes organizadas en filas y columnas utilizando el sistema de rejilla de Bootstrap.
2. **Responsividad**: Las imágenes deben ajustarse automáticamente al tamaño de la pantalla.
3. **Modal**: Al hacer clic en cualquier imagen, esta debe abrirse en un modal usando el componente Modal de Bootstrap.

### Formulario de Contacto

1. **Campos del formulario**: Crear una sección de "Contacto" con un formulario que contenga:
   - Campo de **Nombre**
   - Campo de **Correo electrónico** (con validación)
   - Campo de **Mensaje**
   - Botón de **Enviar**
2. **Responsividad**: Utilizar las clases de Bootstrap para asegurarse de que el formulario sea responsivo.
3. **Validación**: Asegurarse de que el campo de correo electrónico tenga validación de formato y que el formulario se vea bien tanto en pantallas grandes como pequeñas.

### Pie de Página (Footer)

1. **Contenido del pie de página**:
   - Información de **copyright**
   - Enlaces a **redes sociales**
2. **Iconos de redes sociales**: Usar iconos de Bootstrap o Font Awesome para los enlaces a redes sociales.

### Extras (Opcional)

1. **Efectos de Hover**: Añadir efectos de hover en botones y enlaces usando las utilidades de Bootstrap.
2. **Tooltip**: Agregar tooltips a los iconos de redes sociales.
3. **Scrollspy**: Implementar Scrollspy de Bootstrap para que la barra de navegación resalte la sección activa mientras se hace scroll.

## Entregables

1. **Archivo ZIP**: Un archivo comprimido (.zip) que contenga:
   - El archivo `index.html`.
   - Una carpeta con las imágenes usadas (si es necesario).
2. **Instrucciones básicas de uso**:
   - Incluir la versión de Bootstrap utilizada y cómo abrir el archivo en un navegador.

## Evaluación

El trabajo será evaluado según los siguientes criterios:

- **Uso adecuado de las clases de Bootstrap**: El uso correcto de las clases de Bootstrap para diseño responsivo y otros componentes.
- **Estructura y organización del código**: Código limpio, bien organizado y bien documentado.
- **Diseño responsivo**: La página debe verse bien en diferentes dispositivos, desde móviles hasta escritorios.
- **Creatividad y estética**: El diseño debe ser atractivo, profesional y adecuado para una página de E-learning.
