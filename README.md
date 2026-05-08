# Reglamento IA IDC 2026 – Infografía interactiva

Infografía web interactiva sobre el **Reglamento de Uso Responsable de Inteligencia Artificial** del IDC, desarrollada en un único archivo HTML. El recurso presenta el marco AIAS, la aplicación por carreras, los lineamientos para titulación, estadísticas visuales, un simulador de declaración de uso de IA, una lista de verificación ética y el régimen disciplinario.[file:1]

## Descripción general

Este proyecto fue diseñado como una pieza informativa e interactiva orientada a estudiantes y docentes de las carreras de diseño del IDC. El documento integra contenido normativo, navegación por secciones, componentes accesibles y herramientas de apoyo para declarar el uso de IA conforme al Artículo 9 del reglamento.[file:1]

La página incorpora una estructura institucional con identidad visual IDC, encabezado fijo, navegación sticky con scrollspy, secciones temáticas y pie de página con firma institucional. También incluye metadatos que identifican el recurso como una “Infografía interactiva del Reglamento de Uso Responsable de Inteligencia Artificial - IDC 2026”.[file:1]

## Contenido principal

La infografía organiza la información en las siguientes secciones:[file:1]

- Hero o portada con síntesis visual del reglamento y cifras destacadas.[file:1]
- Marco AIAS revisado con niveles de uso de IA presentados en pestañas accesibles.[file:1]
- Aplicación por carrera profesional para Comunicación Audiovisual, Diseño Publicitario, Diseño de Interiores y Diseño de Modas.[file:1]
- Criterios para titulación TAP y ESP mediante bloques comparativos.[file:1]
- Estadísticas visuales con gráficos SVG y barras animadas.[file:1]
- Simulador de declaración de uso de IA con validación reactiva y texto autogenerado.[file:1]
- Lista de verificación ética con persistencia de progreso mediante `localStorage`.[file:1]
- Régimen disciplinario con clasificación de faltas leves, graves y muy graves.[file:1]

## Características técnicas

El proyecto está construido como un archivo HTML autónomo con estilos CSS y comportamiento JavaScript embebidos. Usa tipografías DM Sans, Manrope y DM Mono, una paleta institucional basada en colores IDC y un sistema de variables CSS para facilitar mantenimiento y consistencia visual.[file:1]

Entre sus funcionalidades destacan el indicador de progreso de lectura, scrollspy con `IntersectionObserver`, pestañas accesibles con atributos ARIA, validación de formulario en `blur`, notificaciones tipo toast, efecto ripple en botones y almacenamiento local del checklist ético.[file:1]

Además, el documento contempla criterios de accesibilidad como `skip link`, foco visible, respeto a `prefers-reduced-motion`, objetivos táctiles mínimos y navegación por teclado. También incorpora estilos de impresión para ocultar elementos interactivos no necesarios al imprimir.[file:1]

## Estructura del archivo

El proyecto se distribuye actualmente como un solo archivo principal:[file:1]

```text
.
├── Reglamento_IA_IDC_Infografia.html
└── README.md
```

## Uso

1. Descargue o clone este repositorio.
2. Abra `Reglamento_IA_IDC_Infografia.html` en cualquier navegador moderno.
3. Navegue por las secciones desde la barra superior o mediante desplazamiento vertical.[file:1]
4. Use `Alt + S` para saltar rápidamente al simulador, según el atajo definido en el script.[file:1]
5. Complete el formulario para generar una declaración de uso de IA y copie el resultado si es necesario.[file:1]

## Requisitos

- Navegador web moderno con soporte para HTML5, CSS variables y JavaScript ES6.[file:1]
- Conexión a Internet para cargar tipografías desde Google Fonts, si no están en caché.[file:1]

## Autoría institucional

El documento identifica como autor a **Mg. Mario Quiroz Martínez** y lo vincula con la Jefatura de la Unidad de Investigación del IDC. En el pie de página también se consigna la versión `v3.0 mayo 2026` como documento institucional.[file:1]
