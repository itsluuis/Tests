# Plan de Aprendizaje y Bitácora de Progreso: Apple iPhone 15 Pro Clone

> **Documento de Contexto y Continuidad:** Este archivo guarda el estado completo del curso para que cualquier sesión o chat pueda continuar exactamente donde quedamos sin perder el hilo.

---

## 1. Información General y Referencias
* **Proyecto:** Réplica de alta fidelidad del sitio web del iPhone 15 Pro de Apple con gráficos 3D y animaciones de scroll.
* **Fuente de Estudio:** Video *"Master Creative Frontend in 2 Hours with React, Three.js & GSAP"* por **JavaScript Mastery** (ID de YouTube: `DEeaT6FxEws`).
* **Tecnologías Clave:** React 18, Vite, Tailwind CSS v3, GSAP (GreenSock) + ScrollTrigger, Three.js, React Three Fiber (R3F), React Three Drei.
* **Metodología de Tutoría (Skill `tutor`):**
  1. Breve introducción conceptual del módulo.
  2. Presentación del desafío con pistas.
  3. Propuesta de solución y código por parte del estudiante.
  4. Evaluación crítica y pedagógica (nivel universitario) de la propuesta.
  5. Ajustes y comprobaciones en vivo.
  6. **Compuerta de Satisfacción:** El estudiante debe confirmar explícitamente estar satisfecho antes de avanzar.

---

## 2. Mapa de Módulos del Curso

### [Módulo 0] Fundamentos de Arquitectura y Entorno de Trabajo
* **Estado:** 🟢 *Completado y validado por el estudiante.*
* **Objetivos:**
  * Configuración de bundler con Vite y React 18.
  * Análisis de compatibilidad entre Three.js / React Three Fiber y versiones de React.
  * Configuración de Tailwind CSS con paleta y extensiones oficiales de Apple.
  * Organización de la carpeta `public` (geometrías 3D `.glb`, videos en alta definición, SVGs).
  * Desacoplamiento de constantes y abstracción de utilidades de animación.
  * Servidor local de desarrollo (`npm run dev`) en puerto 5173.

### [Módulo 1] La Navbar y la Estética Minimalista de Apple
* **Estado:** 🟡 *En progreso.*
* **Objetivos:**
  * Estructura semántica de `<header>` y `<nav>`.
  * Efecto Glassmorphism con clases de Tailwind (`backdrop-blur`, opacidades de fondo).
  * Diseño responsive: visualización en desktop vs. colapso a solo iconos esenciales en móvil.
  * Microinteracciones en hover de los enlaces de navegación.

### [Módulo 2] Hero Section y Carrusel de Video con GSAP
* **Estado:** ⚪ *Pendiente*
* **Objetivos:**
  * Hook `useGSAP` para animaciones declarativas seguras en el ciclo de vida de React.
  * Carga condicional y responsiva de medios (videos específicos para mobile vs. desktop según ancho de ventana).
  * Sincronización de eventos de video (`onPlay`, `onLoadedMetadata`, `onEnded`).
  * Barra de progreso sincronizada con el tiempo transcurrido del video.

### [Módulo 3] Modelado 3D Interactivo con Three.js y React Three Fiber
* **Estado:** ⚪ *Pendiente*
* **Objetivos:**
  * Arquitectura de una escena WebGL: Escena (`<Canvas>`), Cámara de perspectiva (`PerspectiveCamera`), y Luces (`ambientLight`, `directionalLight`).
  * Conversión de modelos 3D (`scene.glb`) a componentes React mediante `gltfjsx`.
  * Manejo de la interacción táctil y del cursor mediante `OrbitControls`.
  * Estado reactivo para alternar modelos (6.1" Pro vs. 6.7" Pro Max) y materiales/colores de titanio.

### [Módulo 4] Storytelling, Parallax y Diseño Bento
* **Estado:** ⚪ *Pendiente*
* **Objetivos:**
  * Integración profunda del plugin `ScrollTrigger` de GSAP.
  * Efecto de expansión de video con scroll (revelado progresivo de marcos).
  * Maquetación en cuadrícula moderna tipo *Bento Box*.
  * Animaciones de texto escalonadas (*stagger*).

### [Módulo 5] Sección de Rendimiento (Chip A17 Pro) y Footer
* **Estado:** ⚪ *Pendiente*
* **Objetivos:**
  * Efecto cinemático de zoom-in hacia la arquitectura del procesador A17 Pro.
  * Animación de estadísticas de hardware con contadores fluidos.
  * Maquetación del Footer corporativo de Apple con enlaces legales y selectores de país.

### [Módulo 6] Despliegue en Producción y Portafolio Propio
* **Estado:** ⚪ *Pendiente*
* **Objetivos:**
  * Control de versiones con Git y repositorio en GitHub.
  * Despliegue continuo en Vercel con dominio personalizado gratuito.
  * Estrategias para reemplazar el iPhone por otros productos en 3D (audífonos, consolas, relojes) adaptando el diseño a un estilo propio.
