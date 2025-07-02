# ModaViva - Tienda de Ropa Online (Maqueta)

![Imagen de la página de inicio de ModaViva](https://images.unsplash.com/photo-1483985988355-763728e1935b?q=80&w=1200&auto=format&fit=crop)

Bienvenido a **ModaViva**, una maqueta de sitio web para una tienda de ropa online. Este proyecto es una demostración de una interfaz de usuario moderna y atractiva, construida como una Single Page Application (SPA) utilizando tecnologías web estándar.

## ✨ Características

- **Diseño de Página Única (SPA):** Navegación fluida entre secciones sin necesidad de recargar la página, gestionado con JavaScript.
- **Totalmente Responsivo:** Diseñado con **Tailwind CSS**, se adapta perfectamente a cualquier tamaño de pantalla, desde móviles hasta ordenadores de escritorio.
- **Paleta de Colores Personalizada:** Colores vibrantes y definidos directamente en la configuración de Tailwind para una identidad de marca consistente.
- **Listo para ser una PWA:** Incluye un archivo `manifest.json` básico que permite que el sitio sea "instalable" en dispositivos móviles y de escritorio.
- **Componentes Claros:** El código está organizado en secciones que simulan diferentes páginas (Inicio, Productos, Contacto, etc.).
- **Carga Diferida de Imágenes:** Utiliza el atributo `onerror` para mostrar imágenes de respaldo en caso de que la principal no se pueda cargar.

## 🛠️ Tecnologías Utilizadas

Este proyecto se ha construido utilizando únicamente tecnologías web front-end estándar, sin necesidad de dependencias complejas o procesos de compilación.

- **HTML5:** Para la estructura semántica del contenido.
- **CSS3:** Estilos personalizados que complementan a Tailwind.
- **Tailwind CSS v3:** Framework CSS "utility-first" para un diseño rápido y responsivo, cargado a través de CDN.
- **JavaScript (ES6+):** Para la lógica de la aplicación, como el enrutamiento de páginas y la interactividad.
- **Google Fonts:** Para la tipografía (familia "Inter").

## 🚀 Instalación y Uso

No se requiere ningún proceso de instalación o compilación. Para ver el proyecto en acción, simplemente sigue estos pasos:

1.  Clona o descarga este repositorio en tu máquina local.
2.  Abre el archivo `index.html` en tu navegador web preferido (como Google Chrome, Firefox o Edge).

Para una mejor experiencia de desarrollo (por ejemplo, para evitar problemas con CORS si en el futuro se añaden peticiones a APIs), se recomienda servir los archivos a través de un servidor local. Una forma sencilla de hacerlo es usando la extensión **Live Server** en Visual Studio Code.

## 📂 Estructura del Proyecto


/
├── index.html       # El único archivo HTML que contiene toda la estructura.
├── styles.css       # Hoja de estilos personalizada.
├── manifest.json    # Manifiesto de la Aplicación Web Progresiva (PWA).
└── README.md        # Este archivo.


## 🎨 Personalización

Puedes personalizar fácilmente el sitio:

-   **Colores y Fuentes:** Modifica el objeto `tailwind.config` dentro del `<script>` en `index.html` para cambiar la paleta de colores primarios, secundarios y la tipografía.
-   **Añadir Contenido:** Para añadir nuevas páginas o productos, simplemente duplica la estructura de una sección existente (`<div id="page-..." class="page-content">...</div>`) y actualiza el contenido. No olvides añadir un enlace correspondiente en la barra de navegación.

## 📄 Licencia

Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

_ModaViva &copy; 2025_
