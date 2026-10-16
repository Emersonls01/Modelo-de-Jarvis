# Jarvis para Consultoría — Guía de inicio (sin saber programar)

## Qué es este kit
Una carpeta llamada `Modelo-de-Jarvis` con todo lo que Jarvis necesita para trabajar:
- `CLAUDE.md` — quién es Jarvis y los límites que nunca cruza. Claude Code lo lee solo al abrir la carpeta.
- `LEEME.md` — esta guía.
- `README.md` — portada corta del repositorio en GitHub; remite a esta guía.
- `.claude/skills/arquitecto-ia/` — la skill de evaluación (puede estar oculta en Windows; es normal).
- `sistema/` — aprendizaje de errores y plantilla del reporte al Centro de Control.
- `clientes/_plantilla/` — se copia automáticamente por cada cliente nuevo.

La carpeta vive en tu repositorio de GitHub `emersonls01/modelo-de-jarvis`. Puedes abrir a Jarvis de dos formas: en la web (opción A) o en la app de Windows (opción B).

## Paso a paso

### 1. Elige dónde trabajar
- **Opción A — Web (claude.ai/code):** no hay que instalar nada. Jarvis trabaja en la nube con una copia de tu repositorio de GitHub.
  - Importante: al cerrar la sesión, los archivos nuevos se pierden si no se guardaron en GitHub. Al terminar cada bloque de trabajo, Jarvis te pide aprobación para guardarlos ahí.
- **Opción B — App de escritorio en tu PC con Windows:** los archivos quedan en tu computadora. La MacBook Pro 2013 con Big Sur es demasiado antigua para estas herramientas; usa la PC con Windows.

Si usas la opción A, salta directo al paso 5.

### 2. (Opción B) Instala la app de escritorio de Claude
1. Descarga el instalador para Windows: https://claude.ai/api/desktop/win32/x64/setup/latest/redirect
2. Ábrelo e inicia sesión con tu cuenta de Claude (ya tienes plan de pago, es requisito).
3. La app ya incluye Claude Code: no hay que instalar nada por terminal.

### 3. (Opción B, recomendado) Instala Git para Windows
Descarga desde https://git-scm.com/downloads/win y acepta todo con "Next". Le da a Claude Code mejores herramientas internas y permite bajar la carpeta desde GitHub. No tienes que usarlo tú.

### 4. (Opción B) Coloca la carpeta
1. Baja la carpeta `Modelo-de-Jarvis` desde GitHub (Jarvis te puede guiar) o descomprímela si la tienes en .zip.
2. Muévela a `Documentos` (o donde prefieras, que no se mueva después).

### 5. Abre Jarvis
- **Opción A:** entra a claude.ai/code y abre una sesión sobre el repositorio `emersonls01/modelo-de-jarvis`.
- **Opción B:** en la app de Claude, entra a la pestaña **Code** y selecciona la carpeta `Modelo-de-Jarvis` como carpeta de trabajo.

Escribe tu primer mensaje:
> Hola Jarvis, lee CLAUDE.md y LEEME.md y confírmame en un checklist que todo está en su lugar.

### 6. Prueba la skill con un cliente piloto
> nuevo mapa Comfort Services

Jarvis crea `clientes/Comfort-Services/` y empieza con la fase F0, una pregunta a la vez.

### 7. Antes de una reunión con un cliente
1. `nuevo mapa [Cliente]`
2. Copia los archivos del cliente (organigrama, manuales) dentro de `clientes/[Cliente]/`. En la opción A, súbelos al chat y Jarvis los guarda en esa carpeta.
3. Opcional: `encuesta [área]` para que los referentes llenen sus tareas antes de la reunión.

### 8. Durante la reunión
1. Pide el consentimiento de grabación al inicio (Florida exige el de todas las partes) y graba con Zoom.
2. Escribe `modo reunión`. Pregunta lo que necesites, por ejemplo: "¿cuántas personas tiene el organigrama?". Jarvis responde corto y cita la fuente.

### 9. Después de la reunión
1. Descarga la transcripción de Zoom y ponla en la carpeta del cliente (en la opción A, súbela al chat).
2. `cargar transcripción` → Jarvis la vuelca al registro.
3. `genera mapa` → entregables en `clientes/[Cliente]/entregables/`.
4. `reporte CC` → bloque de reporte para el Centro de Control.
5. En la opción A: aprueba que Jarvis guarde todo en GitHub antes de cerrar.

## Cómo corregir a Jarvis
Escribe `error: [lo que hizo mal]`. Jarvis registra el error, propone la causa y la solución, y te pide un "si" antes de crear una regla nueva. Revisa con `errores abiertos` y `revisar reglas`.

## Permisos
Claude Code te pedirá permiso antes de crear o cambiar archivos. Al principio, lee cada pedido y aprueba. Si algo no te queda claro, pregunta: "¿qué vas a hacer exactamente?".

## Rutinas
Todavía no hay ninguna. Las definimos cuando estemos trabajando (tanto la web como la app de escritorio permiten tareas programadas).

## Si algo falla
Copia el mensaje de error y pégalo en el chat de Jarvis o en tu proyecto de Claude "Jarvis Para Consultoría".
