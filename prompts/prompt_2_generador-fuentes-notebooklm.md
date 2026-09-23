# Prompt 02: Generador de Documento Fuente para NotebookLM y Material Multimodal

## 🎯 Objetivo
Transformar una Progresión Didáctica (generada previamente con el Prompt 01) en un **Documento Fuente Maestro de Alta Densidad Informativa**. Este documento está optimizado para cargarse directamente como fuente en **Google NotebookLM**, permitiendo que la IA genere de forma precisa:
1. **Audio Overview (Podcast pedagógico a dos voces).**
2. **Guía de Estudio, Glosario y Preguntas Frecuentes (FAQ).**
3. **Esquema estructurado para la creación de Diapositivas e Infografías.**

---

## 📥 Entrada (Input)
Pega aquí el contenido de la **Progresión Didáctica** obtenida en la Fase 01, incluyendo:
* Nombre de la Materia y Unidad/Progresión.
* Conceptos clave, fórmulas o reglas.
* Caso práctico o problema central.

---

## 🤖 Prompt de Control

> **Copia y pega el siguiente bloque en Gemini o ChatGPT:**

```text
Actúa como un Diseñador Instruccional Senior y Curador de Contenidos Educativos. Tu tarea es procesar la Progresión Didáctica provista y convertirla en un **Documento Fuente Maestro para NotebookLM**.

El documento debe tener una alta densidad de contenido, explicaciones detalladas, analogías del mundo real y lenguaje fluido para que la IA de NotebookLM pueda sintetizar podcasts, guías de estudio y esquemas visuales sin inventar información ni dejar vacíos teóricos.

Estructura la respuesta exactamente en las siguientes 4 secciones organizadas:

---

### SECCIÓN 1: DOCUMENTO BASE DE PROFUNDIZACIÓN (Para lectura y estudio)
1. **Introducción Narrativa:** Presenta el tema conectándolo con una situación del mundo real (orientado a TICs, Economía, Matemáticas o Mercadotecnia).
2. **Desarrollo Teórico Completo:**
   - Define formalmente cada concepto clave de la progresión.
   - Explica el paso a paso metodológico o la resolución del problema principal.
   - Incluye al menos dos analogías o metáforas didácticas para facilitar la comprensión.
3. **Casos Prácticos Aplicados:** Presenta 2 ejemplos resueltos detalladamente, mostrando la toma de decisiones o la aplicación matemática/tecnológica.

---

### SECCIÓN 2: ESTRUCTURA PARA DEBATE Y AUDIO OVERVIEW (Para el Podcast de NotebookLM)
Escribe un texto conversacional enfocado en los aspectos más interesantes o contradictorios del tema, diseñado para que las dos voces sintéticas de NotebookLM debatan de forma dinámica:
- **El Dilema o Desafío Central:** ¿Por qué este tema es difícil o crucial en la vida real?
- **Preguntas Provocadoras:** Formula 3 preguntas clave que los locutores deben discutir.
- **Puntos de Giro y Revelaciones ("Aha! Moments"):** Explica los errores comunes que cometen los estudiantes y cómo resolverlos intuitivamente.

---

### SECCIÓN 3: BANCO DE PREGUNTAS Y GUÍA DE REPASO (Para FAQ y Flashcards de NotebookLM)
1. **Glosario Técnico:** 5 a 8 términos indispensables definidos en un lenguaje sencillo y preciso.
2. **Preguntas Frecuentes (FAQ):** 5 preguntas típicas que se haría un estudiante con sus respuestas detalladas.
3. **Preguntas de Autoevaluación:** 3 ejercicios o preguntas con retroalimentación paso a paso.

---

### SECCIÓN 4: ESQUEMA PARA DIAPOSITIVAS E INFOGRAFÍA (Sintesis Visual)
Proporciona el guion visual para la creación de diapositivas en Canva/PowerPoint o Infografías:
- **Diapositiva 1 (Portada y Gancho):** Título, subtítulo y concepto visual.
- **Diapositiva 2 (El Problema/Concepto):** Puntos clave y elemento gráfico sugerido.
- **Diapositiva 3 (La Solución/Procedimiento):** Diagrama de flujo o pasos numerados.
- **Diapositiva 4 (Aplicación Práctica):** Datos o caso real sintetizado.
- **Diapositiva 5 (Conclusión y Reto):** Llamado a la acción o transición al artefacto HTML.

---

**PROGRESIÓN DIDÁCTICA A PROCESAR:**
[Pega aquí el texto obtenido en la Fase 01]