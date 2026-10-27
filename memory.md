# Project Memory & Context

## Resumen del Proyecto
- **Nombre:** Cartel "Profe Apruébeme"
- **Tecnologías:** HTML5, CSS3 (Vanilla, inline `<style>`)
- **Plataforma de Despliegue:** Vercel (Sitio Estático / Zero Config)
- **Estado del Proyecto:** Inicial / Prototipo de una sola página

## Arquitectura y Archivos
- `index.html`: Único punto de entrada del proyecto. Contiene la estructura, estilos CSS y animaciones del cartel centrado.
- `agent.md`: Instrucciones de comportamiento para el agente de IA en este repositorio.
- `memory.md`: Registro de contexto, requisitos y decisiones técnicas del proyecto.

## Requisitos Clave
1. **Contenido:** Texto destacado "PROFE APRUÉBEME" junto a un corazón rojo de gran tamaño.
2. **Animaciones:** Animación de latido continua en el corazón mediante CSS.
3. **Despliegue:** Preparado para despliegue directo con `npx vercel` o vinculación con repositorio de GitHub.

## Historial de Decisiones
- Se optó por una arquitectura de archivo único (`single-file HTML`) para eliminar complejidad de empaquetadores (Vite, Webpack) y permitir deploys instantáneos en Vercel.
