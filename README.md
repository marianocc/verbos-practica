# 📚 Práctica de verbos regulares

Herramienta interactiva para practicar la conjugación de verbos regulares en español. Pensada para alumnos de ELE (Español como Lengua Extranjera) y sus profesores.

**[→ Abrir la aplicación](https://TU-USUARIO.github.io/verbos-practica/)**

![screenshot](screenshot.png)

## Características

### Para alumnos
- Conjugación de verbos regulares (-ar, -er, -ir)
- Indicativo, subjuntivo e imperativo
- Tiempos simples y compuestos (haber + participio)
- Variantes -ra / -se del subjuntivo
- Modo estricto de acentos (habló ≠ hablo) o relajado
- Sistema de pistas progresivas
- Botones de acentos (á, é, í, ó, ú, ñ, ü) para teclados sin ellos
- Racha, puntuación y porcentaje de acierto en tiempo real
- Historial de errores recientes

### Para profesores
- Panel de seguimiento con datos de todos los alumnos
- Tabla ordenable: sesiones, preguntas, % de acierto, mejor racha
- Detalle expandible por alumno con historial de sesiones y errores frecuentes
- Vista de "Verbos difíciles" — qué verbos y tiempos fallan más
- Exportación a CSV
- Los datos se guardan en localStorage del navegador

## Uso

### Opción 1: GitHub Pages (recomendada)

1. Haz fork de este repositorio
2. Ve a **Settings → Pages**
3. En **Source**, selecciona `main` branch y `/ (root)`
4. Tu app estará en `https://tu-usuario.github.io/verbos-practica/`

### Opción 2: Local

Abre `index.html` directamente en el navegador. No necesita servidor ni conexión a internet.

### Opción 3: Chromebook / aula

Descarga `index.html` y ábrelo en Chrome. Funciona completamente offline.

## Atajos de teclado

| Atajo | Acción |
|-------|--------|
| `Enter` | Comprobar respuesta / Siguiente pregunta |
| `Ctrl+Enter` | Siguiente pregunta |
| `Ctrl+H` | Mostrar pista |

## Notas técnicas

- Un solo archivo HTML, sin dependencias externas (salvo Google Fonts)
- Los datos se guardan en `localStorage` bajo la clave `verbos_progress_v2`
- Funciona offline (las fuentes se degradan a system-ui si no hay conexión)
- Compatible con Chrome, Firefox, Safari y Edge

## Licencia

MIT
