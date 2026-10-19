# Portafolio: Entorno Interactivo de Realidad Aumentada en Química

Portafolio web interactivo del proyecto de investigación-creación **"Desarrollo, implementación y evaluación de un entorno interactivo de Realidad Aumentada en prácticas educomunicativas en la enseñanza de funciones inorgánicas"** (estudiantes de grado 8° y 9° del Colegio Calasanz Bogotá).

- **Autor:** Manuel Alejandro Gómez Cortés
- **Programa:** Maestría en Comunicación - Educación, Universidad Distrital Francisco José de Caldas

## Tecnologías

- HTML / CSS (glassmorphism, diseño responsive)
- [Three.js](https://threejs.org/) `0.160.0` — gráficos 3D con shaders personalizados (sol procedural, moléculas, cristales, redes, etc.)
- [GSAP](https://gsap.com/) `3.12.5` — animaciones y transiciones entre escenas
- Post-procesado con `UnrealBloomPass`

## Uso

Al ser un sitio estático, basta con abrir `index.html` en un navegador moderno. Las dependencias (Three.js y GSAP) se cargan vía CDN mediante un *import map*, por lo que se requiere conexión a internet.

```bash
# Opcional: servirlo localmente
python3 -m http.server 8000
# luego abre http://localhost:8000
```

> Navega haciendo scroll e interactúa con los objetos 3D moviendo el puntero sobre ellos.
