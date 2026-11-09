# Ruta Inglés Dev

Curso de inglés de A1 a C2 para hispanohablantes que quieren trabajar como ingenieros en sistemas en empresas internacionales.

El curso está publicado como artifact en claude.ai y solo puede abrirlo su dueño (ver `enlace.txt`).

## Qué incluye

- **Ruta MCER:** 6 niveles (A1–C2) de 8 unidades cada uno, con un examen para pasar de nivel.
- **Cada unidad:** explicación, gramática, vocabulario con audio, diálogo, ejercicios autocorregidos, escucha con dictado, práctica de pronunciación y una escritura que corrige el tutor IA.
- **Repaso:** repaso espaciado (sistema Leitner) del vocabulario y de los errores propios.
- **Conversar:** práctica de conversación escrita con un tutor IA, con correcciones.
- **Mi plan:** estimación de tiempos según las horas por semana.

Las 8 unidades de A1 están escritas a mano dentro del archivo. Desde A2, las lecciones las genera el tutor IA la primera vez que se abre cada unidad.

## Estructura

Todo el proyecto está en un único archivo, `curso-ingles.html`:

| Parte | Qué contiene |
|---|---|
| `<style>` | Diseño, colores y modo oscuro |
| `LEVELS` | El temario: niveles y unidades |
| `STATIC_LESSONS` | Las lecciones de A1 escritas a mano |
| `PRACTICE` | Escucha, dictado y pronunciación de A1 |
| `REFS` | Fichas de referencia (MCER y English Grammar Profile) |
| Resto del `<script>` | Lógica: progreso, repaso, tutor IA, exámenes y conversación |

## Cómo funciona

- **Tutor IA y guardado:** funcionan solo dentro de claude.ai, porque usan las capacidades del artifact (`sample`, `db` y `user`). El progreso de cada alumno se guarda en su cuenta, no en este repositorio.
- **Fuera de claude.ai:** si se abre el archivo en un navegador, las lecciones de A1 funcionan, pero no hay tutor IA y el progreso queda solo en ese navegador.
- **Publicar una nueva versión:** se publica `curso-ingles.html` en el mismo enlace del artifact.
