# Simulador Educativo: El Funcionamiento de la Web

Este es un recurso educativo interactivo diseñado para explicar de forma clara, visual y accesible los procesos técnicos que ocurren cuando se ingresa una URL en el navegador.

## 🚀 Framework Utilizado
* **Tailwind CSS (v3 a través de Play CDN):** Enfoque *Utility-First* para garantizar un desarrollo ágil, limpio y responsivo sin alterar hojas de estilo locales.

## 🛠️ Características del Proyecto
* **Maquetación Semántica HTML5:** Uso estricto de etiquetas estructurales (`<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>`).
* **Diseño Responsivo:** Adaptabilidad total en dispositivos móviles, tablets y escritorios mediante grids y flexbox nativos de Tailwind.
* **Componentes Enriquecidos:** Incorporación de barras de navegación fijas, tarjetas (cards) informativas, alertas de estado, badges visuales, tablas de datos y formularios estilizados.

## 📂 Páginas del Simulador
1. **Inicio (`index.html`):** Anatomía de una URL.
2. **Solicitud HTTP (`http.html`):** Métodos GET y POST.
3. **Servidor Web (`servidor.html`):** Procesamiento y encabezados de respuesta.
4. **Renderizado HTML5 (`renderizado.html`):** El proceso del motor del navegador.
5. **Ejemplo Práctico (`ejemplo.html`):** Códigos de estado y formulario de retroalimentación.

## ♿ Anexo: Mini-Checklist Interna de Accesibilidad Aplicada
* [x] **Ratio de Contraste de Color:** Legibilidad óptima con texto oscuro sobre fondo claro (`bg-slate-50`) y contraste inverso en la cabecera.
* [x] **Estados de Enfoque Visibles:** Anillos de enfoque explícitos con `focus:ring-2` para navegación fluida por teclado.
* [x] **Marcadores Semánticos:** Estructura limpia organizada mediante bloques semánticos nativos de HTML5.
* [x] **Textos Alternativos:** Atributo `alt` detallado en todas las imágenes pedagógicas del simulador.
* [x] **Identificación de Página Activa:** Implementación del atributo `aria-current="page"` para marcar la sección en uso.
* [x] **Formulario Accesible:** Uso de `<fieldset>` y `<legend>` para agrupar de forma lógica los controles de opción.
