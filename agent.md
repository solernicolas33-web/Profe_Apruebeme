# Agent Instructions: Cartel "Profe Apruébeme"

## Objetivo
Generar y mantener una aplicación web estática de archivo único (`index.html`) diseñada para ser desplegada directamente en Vercel sin dependencias ni pasos de compilación.

## Especificaciones de Desarrollo
- **Estructura:** Todo el código debe estar estrictamente contenido dentro de un único archivo `index.html`. Usar etiquetas `<style>` para CSS en el `<head>`.
- **Diseño Responsivo:** Utilizar Flexbox/Grid y la función `clamp()` en CSS para asegurar que tanto el texto como los elementos visuales se adapten a cualquier tamaño de pantalla (móvil, tablet, desktop) sin generar scroll barras innecesarias.
- **Estética Visual:**
  - Tema oscuro limpio (fondo `#0f172a`, texto principal `#f8fafc`).
  - Tipografía en negrita, mayúsculas y bien contrastada para el texto "PROFE APRUÉBEME".
  - Corazón gigante en color rojo (`#ef4444`) centrado con animación CSS tipo latido (`@keyframes pulse`) y sombra con resplandor (`drop-shadow`).
- **Compatibilidad Vercel:** Mantener la estructura como HTML5 estándar estático (*zero-config*).

## Reglas de Modificación
- No crear archivos `.css` o `.js` separados a menos que se indique explícitamente.
- Garantizar que cualquier cambio preserve el rendimiento y la simetría del centrado.
