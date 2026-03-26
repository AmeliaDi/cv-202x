s# Amelia Enora — Technical CV

Un currículum interactivo y orgánico, diseñado para reflejar la intersección entre código de bajo nivel, ciberseguridad y arte visual. 

Este proyecto es una carta de presentación interactiva construida con tecnologías web estándar y enriquecida con animaciones cinemáticas mediante GSAP.

## 🎨 Diseño y Animaciones

- **Estética Orgánica:** Colores tierra (crema, pergamino, arcilla), texturas sutiles de ruido de fondo ("grain") y curvas orgánicas generadas por SVG y CSS.
- **Tipografía:** Se combinan estilos Serif clásicos (`Cormorant Garamond`, `Libre Baskerville`) con Monoespaciados modernos (`DM Mono`) para acentuar el contraste entre la técnica rigorosa y el arte plástico.
- **Animaciones (GSAP):**
  - Efectos parallax al hacer scroll en `hero` y otras secciones.
  - Entradas escalonadas (`stagger`) al hacer scroll sobre tarjetas, certificaciones e ítems de experiencia para proveer una lectura fluida.
  - Uso intensivo del plugin `ScrollTrigger` para coordinar los puntos de entrada dinámicamente.

## 🛠️ Stack Tecnológico

- **Estructura y Lógica:** HTML5 Puro y JS Vanilla.
- **Estilos:** CSS3 Native Variables y Flexbox/Grid.
- **Animación:** GSAP + ScrollTrigger (vía CDN).
- **Hospedaje/Versionamiento:** Git / GitHub (`cv-202x`).

## 🚀 Despliegue

La página está lista para desplegarse estáticamente (por ejemplo, mediante GitHub Pages o Vercel) ya que no cuenta con un proceso de build (cero dependencias locales pesadas). 

```bash
# 1. Clonar el repositorio
git clone https://github.com/AmeliaDi/cv-202x.git

# 2. Abrir en tu navegador web
open index.html
```
