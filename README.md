# Bitácora de Seguimiento y Control - Proyecto Web ADSO

## 📄 Descripción del Proyecto
Este proyecto consiste en un sistema de seguimiento, control y documentación digital de actividades académicas para el programa de formación Análisis y Desarrollo de Software (ADSO) del SENA CIMI (Girón). El repositorio consolida las bitácoras semanales y diarias desarrolladas durante los meses de agosto y septiembre de 2026, sirviendo como un registro estructurado y accesible del progreso técnico y conceptual del equipo de trabajo.

## 👥 Información del Programa y Equipo
* **Programa de Formación:** Análisis y Desarrollo de Software (ADSO)
* **Ficha:** 3533582
* **Centro de Formación:** SENA CIMI - Girón
* **Líder de Equipo:** Juan Esteban Osorio Arévalo

## 📐 Estructura de las Vistas Desarrolladas
El proyecto está estructurado de forma jerárquica y modular en archivos HTML5 puro:

1. **Menú Principal / Dashboard (`index.html` en la raíz):**
   * Funciona como el índice general del proyecto.
   * Agrupa cronológicamente las entradas por mes (Agosto y Septiembre de 2026) y por semanas.
   * Proporciona acceso directo e intuitivo a cada uno de los registros diarios.

2. **Vista de Registro de Bitácora Semanal (`2026/mes/semanaX/index.html`):**
   * Presenta un resumen consolidado de los objetivos, actividades e hitos alcanzados durante una semana específica de formación.

3. **Vista de Detalle Diario (`2026/mes/semanaX/diaY-fecha/index.html`):**
   * Contiene el desglose detallado de las actividades realizadas en una jornada específica, documentando objetivos técnicos, evidencias, impedimentos resueltos y compromisos.

## 🗺️ Estructura del Menú Principal (`index.html`)
A continuación se detalla la estructura completa de navegación implementada en la raíz del proyecto:

### Agosto 2026
* **Semana 1**
  * Día 1: Inspección y Control de Bitácora (`2026/agosto/semana1/dia1-10-agosto/index.html`)
  * Día 2: Control e Inspección de Bitácora (`2026/agosto/semana1/dia2-14-agosto/index.html`)
* **Semana 2**
  * Día 1: Inspección y Control de Bitácora (`2026/agosto/semana2/dia1-21-agosto/index.html`)
* **Semana 3**
  * Día 1: Inspección y Control de Bitácora (`2026/agosto/semana3/dia1-24-agosto/index.html`)
  * Día 2: Control e Inspección de Bitácora (`2026/agosto/semana3/dia2-28-agosto/index.html`)

### Septiembre 2026
* **Semana 1**
  * Día 1: Inspección de Bitácora (`2026/septiembre/semana1/dia1-04-septiembre/index.html`)
* **Semana 2**
  * Día 1: Control e Inspección de Bitácora (`2026/septiembre/semana2/dia1-11-septiembre/index.html`)
  * Día 2: Se realizó una ruleta para la muestra del trabajo (`2026/septiembre/semana2/dia2-18-septiembre/index.html`)
* **Semana 3**
  * Día 1: Construir y validar documento HTML5 (`2026/septiembre/semana3/dia1-21-septiembre/index.html`)
  * Día 2: Construya en HTML las bitácoras vistas (`2026/septiembre/semana3/dia2-25-septiembre/index.html`)

## ♿ Prácticas de Semántica HTML5 y Accesibilidad Implementadas
Siguiendo los estándares de la W3C y las pautas de accesibilidad web, el proyecto implementa:

1. **Maquetación Semántica Estricta:**
   * Uso de etiquetas de estructura global: `<header>`, `<main>`, `<section>`, `<article>` y `<footer>`.
   * Delimitación explícita de áreas de navegación con el elemento `<nav>`.

2. **Jerarquía Correcta de Encabezados:**
   * Uso ordenado y secuencial de etiquetas de encabezado (`<h1>` a `<h4>`), garantizando que la estructura sea legible tanto para los usuarios como para los lectores de pantalla (evitando etiquetas no estándar como `<h7>`).

3. **Estándares de Rutas y Navegación Web:**
   * Implementación de rutas relativas puras con barras web (`/`) para asegurar la portabilidad del sitio entre distintos entornos y servidores web.

4. **Diseño Responsivo y Accesibilidad Móvil:**
   * Inclusión del metadato de adaptabilidad `<meta name="viewport" content="width=device-width, initial-scale=1.0">` en el `<head>` de todas las vistas.