# Syncly Demo & Sign-up Form

Este proyecto es una página web simple que presenta un formulario de prueba y registro para **Syncly**, una herramienta colaborativa diseñada para equipos remotos. La página utiliza un diseño de dos paneles para promocionar la herramienta y capturar la información de los usuarios interesados en una demostración.

## Demo

* Puedes ver una demo en vivo [Aquí](https://itsuli19.github.io/Project-Sign-up-Form/).

## Características

* Diseño moderno de dos paneles (marketing a la izquierda, formulario a la derecha).
* Formulario de solicitud de demo con campos clave (Nombre Completo, Correo Electrónico de Trabajo, Nombre de la Empresa, Puesto/Rol, Mensaje).
* Validación básica de campos requeridos en HTML (`required`).
* Diseño responsive que se adapta a diferentes tamaños de pantalla (se apila verticalmente en dispositivos móviles).
* Uso de Variables CSS para facilitar la personalización del diseño y los colores.
* Tipografía consistente utilizando Google Fonts (Poppins, Roboto, Open Sans).
* Implementación de `normalize.css` para asegurar la consistencia del renderizado en diferentes navegadores.

## Tecnologías Utilizadas

* **HTML5:** Estructura semántica de la página.
* **CSS3:** Estilos y diseño, incluyendo Flexbox (layout principal), Grid (layout del formulario), y Variables CSS.
* **Normalize.css:** Reseteo de estilos CSS.
* **Google Fonts:** Tipografías personalizadas.

## Estructura del Proyecto
Project-Sign-up-Form/
├── assets/
│   └── images/
│       ├── icon.png  
│       └── hand.png  
├── css/
│   └── style.css     
└── index.html   

1.  Clona el repositorio en tu máquina local.
    ```bash
    git clone <https://github.com/ITSULI19/Project-Sign-up-Form#> 
    ```
2.  Navega a la carpeta del proyecto.
3.  Asegúrate de que la estructura de archivos sea correcta, incluyendo las imágenes en `assets/images/` (especialmente `hand.png` si quieres el fondo del panel izquierdo).
4.  Abre el archivo `index.html` en tu navegador web preferido.

¡Eso es todo! La página debería cargarse correctamente.

## Uso

El formulario permite a los usuarios interesados en Syncly solicitar una demostración. Los usuarios deben llenar los campos y hacer clic en el botón de envío.

**Nota:** Este es un proyecto front-end solamente. El formulario actual no tiene una funcionalidad de backend asociada para procesar y enviar los datos ingresados. Deberás implementar una solución de backend (usando JavaScript, un servicio de formularios, o un lenguaje de servidor como Node.js, Python, PHP, etc.) para manejar los datos del formulario.

## Personalización

Puedes personalizar fácilmente los estilos modificando las Variables CSS definidas en la sección `:root` del archivo `css/style.css`. Cambia colores, tipografías, espaciados y más para adaptar el diseño a tus necesidades.

## Notas y Posibles Mejoras

* El texto del botón de envío en el HTML es "Messege", que parece un error tipográfico y debería ser "Submit" o similar.
* La imagen `hand.png` es referenciada en el CSS para el fondo del panel izquierdo (`#izquierda`), pero no estaba listada en la estructura inicial. Asegúrate de añadir esta imagen en la ruta `assets/images/` si deseas que el fondo se muestre.
* Implementar validación de formulario más robusta con JavaScript.
* Integrar una solución de backend para procesar los datos del formulario (ej. enviar a un correo electrónico, guardar en una base de datos, conectar a un CRM).
* Añadir mensajes de éxito o error después del envío del formulario.
