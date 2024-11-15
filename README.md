Hospital Little Tree - Proyecto Web
Descripción
El proyecto consiste en un sitio web para Hospital Little Tree, un hospital pediátrico dedicado a brindar atención médica de calidad a niños. La página incluye información sobre los servicios del hospital, testimonios de pacientes, y detalles de contacto, todo adaptado a una experiencia fluida y responsiva para diferentes dispositivos.

Requisitos y características
Organización de Estilos con SASS y Modularización
Se implementó la modularización de los estilos utilizando SASS para dividir los estilos en archivos parciales y mejorar la mantenibilidad. Los estilos se organizaron de acuerdo con la estructura 7-1, donde:

_base.scss: Estilos básicos y configuración global.
_header.scss: Estilos específicos para el encabezado.
_footer.scss: Estilos específicos para el pie de página.
_home.scss: Estilos para la página de inicio.
_services.scss: Estilos para la sección de servicios.
_testimonials.scss: Estilos para la sección de testimonios.
_mediaqueries.scss: Contiene las media queries para la responsividad.
Se utilizó la metodología BEM (Bloque, Elemento, Modificador) para nombrar las clases CSS de manera consistente, como se puede ver en las clases de los elementos header__nav, footer__social, etc.

Responsividad con Media Queries
Se aseguró que el sitio sea completamente responsivo utilizando media queries en el archivo _mediaqueries.scss. Se implementaron al menos tres puntos de ruptura para asegurar una experiencia óptima en dispositivos móviles, tabletas y pantallas de escritorio:

< 768px (para dispositivos móviles).
768px - 1024px (para tabletas).
> 1024px (para pantallas de escritorio).
Aplicación del Modelo de Cajas y Posicionamiento de Elementos
Se utilizó el modelo de cajas CSS para organizar el espaciado, márgenes, bordes y rellenos de los elementos. Se aplicaron correctamente las propiedades de posicionamiento (relativo, absoluto, flotante, etc.) para ajustar la disposición de los elementos de manera coherente.

Implementación de un Layout Adaptativo
El diseño es fluido y adaptativo, lo que permite que los elementos se ajusten dinámicamente al tamaño de la ventana del navegador. El encabezado, pie de página y secciones clave (como servicios y testimonios) se adaptan correctamente cuando cambia el tamaño de la pantalla, mejorando la experiencia de usuario en todos los dispositivos.

Estructura de Archivos
bash
Copiar código
/hospital-little-tree
│
├── /images
│   ├── dentista.jpg
│   ├── pediatra.jpg
│   ├── terapia.jpg
│   └── ... (otras imágenes)
│
├── /styles
│   ├── main.css                # Archivo principal CSS generado por SASS
│   ├── _base.scss              # Estilos globales básicos
│   ├── _header.scss            # Estilos del encabezado
│   ├── _footer.scss            # Estilos del pie de página
│   ├── _home.scss              # Estilos para la página de inicio
│   ├── _services.scss          # Estilos para la sección de servicios
│   ├── _testimonials.scss      # Estilos para la sección de testimonios
│   ├── _mediaqueries.scss      # Media queries para responsividad
│   └── main.scss               # Archivo principal de SASS que importa todos los parciales
│
├── index.html                  # Página principal
├── EquipoMedico.html           # Página del equipo médico
├── contacto.html               # Página de contacto
└── README.md                   # Este archivo
Instrucciones
Instalación de dependencias: Para instalar las dependencias necesarias (SASS, en caso de ser necesario), puedes usar el siguiente comando:

bash
Copiar código
npm install
Compilación de SASS a CSS: Para compilar los archivos SASS a CSS, ejecuta:

bash
Copiar código
npm run sass
Esto generará el archivo main.css en la carpeta /styles.

Ver el proyecto en el navegador:

Abre el archivo index.html en tu navegador para ver el sitio en funcionamiento.
Contribución
Si deseas contribuir al proyecto:

Haz un fork del repositorio.
Crea una nueva rama para tu funcionalidad.
Realiza tus cambios y asegúrate de que el código esté bien estructurado.
Envía un pull request.

- Este proyecto fue creado por Javiera Allende como parte de un ejercicio de desarrollo web Para la Especialización de Front End de Capital Humano Corfo 2024. 
- Las imágenes utilizadas son solo de ejemplo y se deben reemplazar con contenido real para su uso en producción.



