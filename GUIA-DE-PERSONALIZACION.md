# Guía de personalización

## Publicación rápida

1. Crea un repositorio público cuyo nombre sea exactamente tu usuario de GitHub: `USUARIO/USUARIO`.
2. Copia `README.md`, `assets/` y `.github/` en la raíz del repositorio.
3. En `README.md`, usa **Buscar y reemplazar** con todos los marcadores de la sección inicial `CONFIGURACIÓN`.
4. Elimina botones, tecnologías o proyectos que no apliquen.
5. Ejecuta manualmente el flujo **Generar animación de contribuciones** desde la pestaña **Actions**. La rama `output` aparecerá al terminar.
6. Revisa el perfil en escritorio y móvil antes de compartirlo.

## Banner

El archivo `assets/banner-cyberpunk.webp` ya está optimizado para web y no contiene texto. El nombre y las frases se muestran con HTML y un SVG de escritura, así que puedes personalizarlos sin editar la imagen.

Para reemplazar el banner sin tocar el diseño:

1. Genera una imagen horizontal de proporción cercana a 3:1.
2. Expórtala como WebP, preferiblemente por debajo de 1 MB.
3. Sustituye `assets/banner-cyberpunk.webp` conservando exactamente el mismo nombre.

### Prompt utilizado para el recurso

> Crea una escena cyberpunk original para un perfil profesional de GitHub: estudiante de desarrollo visto de espaldas frente a una ciudad digital, una ruta luminosa de nodos como metáfora de aprendizaje, remolinos abstractos de datos, fragmentos de código, viñetas diagonales, semitono sutil y aberración RGB moderada. Paleta #050510, #090A1A, #FF1744, #FF2BD6, #7C3AED, #00D9FF y #EAF7FF. Composición panorámica 3:1, profesional, oscura y legible. Sin texto, logotipos, marcas de agua, personajes reconocibles, uniformes, emblemas o símbolos de franquicias.

## Integraciones

- `readme-typing-svg`: texto de escritura del encabezado.
- `github-readme-stats`: estadísticas y lenguajes de repositorios públicos.
- `github-readme-streak-stats`: racha de contribuciones.
- `github-readme-activity-graph`: gráfico de actividad reciente.
- `Platane/snk`: SVG animado generado dentro de tu propio repositorio.
- `komarev.com/ghpvc`: contador de visitas opcional.

Las tarjetas de terceros pueden tener límites de uso temporales. La animación `snk` queda alojada en tu propio repositorio y no depende de un renderizado público en cada visita.

## Lista de verificación

- No queda ningún marcador entre corchetes.
- Solo aparecen tecnologías que realmente estudias o utilizas.
- Los tres proyectos apuntan a repositorios reales.
- Los estados de proyecto son `planeado`, `en desarrollo` o `terminado`.
- Los enlaces de GitHub, LinkedIn, correo y portafolio funcionan.
- No hay datos privados.
- Todas las imágenes conservan su texto alternativo.
- El flujo de contribuciones tiene permiso `contents: write`.
