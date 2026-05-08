# Reglamento IA IDC 2026 – Infografía interactiva

Infografía web interactiva sobre el **Reglamento de Uso Responsable de Inteligencia Artificial** del IDC, desarrollada en un único archivo HTML. El recurso presenta el marco AIAS, la aplicación por carreras, los lineamientos para titulación, estadísticas visuales, un simulador de declaración de uso de IA, una lista de verificación ética y el régimen disciplinario.

## Descripción general

Este proyecto fue diseñado como una pieza informativa e interactiva orientada a estudiantes y docentes de las carreras de diseño del IDC. El documento integra contenido normativo, navegación por secciones, componentes accesibles y herramientas de apoyo para declarar el uso de IA conforme al Artículo 9 del reglamento.

La página incorpora una estructura institucional con identidad visual IDC, encabezado fijo, navegación sticky con scrollspy, secciones temáticas y pie de página con firma institucional. También incluye metadatos que identifican el recurso como una “Infografía interactiva del Reglamento de Uso Responsable de Inteligencia Artificial - IDC 2026”.

## Contenido principal

La infografía organiza la información en las siguientes secciones:

- Hero o portada con síntesis visual del reglamento y cifras destacadas.
- Marco AIAS revisado con niveles de uso de IA presentados en pestañas accesibles.
- Aplicación por carrera profesional para Comunicación Audiovisual, Diseño Publicitario, Diseño de Interiores y Diseño de Modas.
- Criterios para titulación TAP y ESP mediante bloques comparativos.
- Estadísticas visuales con gráficos SVG y barras animadas.
- Simulador de declaración de uso de IA con validación reactiva y texto autogenerado.
- Lista de verificación ética con persistencia de progreso mediante `localStorage`.
- Régimen disciplinario con clasificación de faltas leves, graves y muy graves.

## Características técnicas

El proyecto está construido como un archivo HTML autónomo con estilos CSS y comportamiento JavaScript embebidos. Usa tipografías DM Sans, Manrope y DM Mono, una paleta institucional basada en colores IDC y un sistema de variables CSS para facilitar mantenimiento y consistencia visual.

Entre sus funcionalidades destacan el indicador de progreso de lectura, scrollspy con `IntersectionObserver`, pestañas accesibles con atributos ARIA, validación de formulario en `blur`, notificaciones tipo toast, efecto ripple en botones y almacenamiento local del checklist ético.

Además, el documento contempla criterios de accesibilidad como `skip link`, foco visible, respeto a `prefers-reduced-motion`, objetivos táctiles mínimos y navegación por teclado. También incorpora estilos de impresión para ocultar elementos interactivos no necesarios al imprimir.

## Estructura del archivo

El proyecto se distribuye actualmente como un solo archivo principal:

```text
.
├── Reglamento_IA_IDC_Infografia.html
└── README.md
```

## Uso

1. Descargue o clone este repositorio.
2. Abra `Reglamento_IA_IDC_Infografia.html` en cualquier navegador moderno.
3. Navegue por las secciones desde la barra superior o mediante desplazamiento vertical.
4. Use `Alt + S` para saltar rápidamente al simulador, según el atajo definido en el script.
5. Complete el formulario para generar una declaración de uso de IA y copie el resultado si es necesario.

## Requisitos

- Navegador web moderno con soporte para HTML5, CSS variables y JavaScript ES6.
- Conexión a Internet para cargar tipografías desde Google Fonts, si no están en caché.

## Autoría institucional

El documento identifica como autor a **Mg. Mario Quiroz Martínez** y lo vincula con la Jefatura de la Unidad de Investigación del IDC. En el pie de página también se consigna la versión `v3.0 mayo 2026` como documento institucional.
