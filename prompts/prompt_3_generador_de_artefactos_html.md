# Prompt 03: Generador de Artefactos Interactivos en HTML5/JS

**Propósito:** Este prompt instruye a la IA para codificar un único archivo HTML autocontenido con diseño moderno, componentes interactivos, retroalimentación pedagógica inmediata y persistencia de progreso en `localStorage`.

---

## 📋 Copiar y Pegar en Gemini / ChatGPT

```text
Actúa como un Desarrollador Web EdTech Senior experto en HTML5, Tailwind CSS y JavaScript interactivo.

Tu tarea es crear un **Artefacto Educativo Interactivo Monolítico (un solo archivo .html)** para la siguiente materia y tema:

- **Materia:** [Materia]
- **Tema del Artefacto:** [Tema o Ejercicio]
- **Objetivo Práctico:** [Objetivo que el alumno debe demostrar]
- **Instrucciones Pedagógicas:** [Describir qué debe calcular, simular o resolver el estudiante]

---

### REQUISITOS TÉCNICOS Y PEDAGÓGICOS OBLIGATORIOS:

1. **ESTRUCTURA MONOLÍTICA:** Todo el código HTML, CSS (usa CDN de Tailwind CSS `https://cdn.tailwindcss.com`) y JavaScript debe residir en un ÚNICO archivo `.html`. Sin archivos externos adicionales.
2. **DISEÑO UI/UX:**
   * Utiliza una interfaz moderna, limpia, responsiva (mobile-first) con Tailwind CSS.
   * Encabezado claro con el nombre del curso, título del ejercicio e instrucciones sencillas.
3. **MECÁNICA INTERACTIVA:**
   * Incluye elementos de entrada (inputs numéricos, sliders de rango, botones de opción o campos de texto según el tema).
   * Genera visualizaciones inmediatas o cálculos en tiempo real cuando el alumno modifique valores o envíe sus respuestas.
4. **RETROALIMENTACIÓN PEDAGÓGICA AUTOMÁTICA (Scaffolding):**
   * No limites la respuesta a "Correcto/Incorrecto".
   * Proporciona explicaciones conceptuales automáticas cuando el alumno cometa un error.
   * Incluye un botón de "💡 Obtener Pista" si el estudiante se atasca.
5. **PERSISTENCIA Y SEGUIMIENTO (`localStorage`):**
   * Guarda el número de intentos y el mejor puntaje obtenido en `localStorage`.
   * Incluye una opción para que el alumno copie o descargue un "Reporte de Desempeño" en texto plano para enviarlo al docente.

Genera el código HTML completo y listo para guardar como archivo `.html`.
```