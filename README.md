<img width="1366" height="643" alt="Captura de pantalla 2026-09-19 214114" src="https://github.com/user-attachments/assets/4a845384-9f24-4937-8572-6e40859e0694" />
# Personal Finance Dashboard - Offline Web App

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)


---

## Sobre el Proyecto:

Una Single Page Application (SPA) minimalista desarrollada para la gestión de finanzas personales. Diseñada bajo una arquitectura Offline-First, esta aplicación permite a los usuarios registrar, editar y analizar sus gastos en tiempo real sin necesidad de conexión a internet ni bases de datos externas, garantizando cero latencia y máxima privacidad de los datos.

Este proyecto fue desarrollado para demostrar fundamentos sólidos en el desarrollo Frontend sin depender de frameworks pesados, aplicando buenas prácticas de manipulación del DOM y diseño responsivo.

---

## Características Principales:

- Gestión de Estado Local: Operaciones CRUD (Crear, Leer, Actualizar, Eliminar) gestionadas de forma síncrona mediante la API de localStorage.

- Dashboard Analítico: Integración con Chart.js para la renderización de gráficos dinámicos que muestran la distribución del gasto (mensual, semanal o anual) calculando porcentajes al vuelo.

- UI/UX Adaptativa: Diseño Mobile-First con soporte nativo para múltiples temas (Light, Dark, Accent) utilizando variables nativas de CSS (Custom Properties).

- Gestión de Zonas Horarias: Lógica implementada en JavaScript para manejar correctamente las fechas según el huso horario local del cliente.

- Validación y Manejo de Errores: Formularios protegidos y notificaciones UI (Toasts y Modales) personalizadas sin usar alertas del navegador por defecto.

---

## Stack Tecnológico:

- Frontend: HTML5 semántico, CSS3 (Flexbox, Grid, CSS Variables), Vanilla JavaScript (ES6+).
- Librerías: Chart.js (Data Visualization).
- Almacenamiento: Web Storage API (localStorage).
- Despliegue: Netlify / GitHub Pages.

---

## Decisiones Técnicas y Arquitectura:

- Vanilla JS vs Frameworks: Se eligió usar JavaScript puro para maximizar el rendimiento de la aplicación y demostrar un dominio profundo del DOM, Event Listeners y manipulación de arrays/objetos.

- Offline-First Architecture: En lugar de depender de un BaaS (Backend as a Service) que requiere latencia de red, se implementó almacenamiento persistente en el navegador. Esto asegura que la aplicación cargue de manera instantánea y funcione incluso en zonas sin cobertura móvil (ideal para registrar gastos sobre la marcha).

- Escalabilidad Visual: La implementación de temas oscuros/claros no se hizo duplicando código, sino mediante la alteración dinámica de la raíz del DOM (:root) con variables CSS, haciendo que agregar nuevos temas en el futuro tome solo un par de líneas de código.

---

## Capturas de Pantalla:

<img width="683" height="323" alt="Captura de pantalla 2026-09-19 214114" src="https://github.com/user-attachments/assets/4a845384-9f24-4937-8572-6e40859e0694" />
<img width="683" height="323" alt="Captura de pantalla 2026-09-19 213811" src="https://github.com/user-attachments/assets/68aba4c9-f5ef-44ce-8368-395a44a30fbf" />
<img width="683" height="323" alt="Captura de pantalla 2026-09-19 213721" src="https://github.com/user-attachments/assets/669e1aa7-2cdb-41bf-a012-9b960d42beb0" />

---

## Autor:

Magbis Mizraim Santiago López
- Universidad Politécnica de Altamira (Ingeniería / Desarrollo Web)
- LinkedIn: [Tu_Enlace_De_LinkedIn]
- Portafolio: [Tu_Enlace_De_Portafolio_o_GitHub]
