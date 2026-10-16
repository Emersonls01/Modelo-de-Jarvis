# Jarvis para Consultoría — Guía de inicio (sin saber programar)

## Qué es este kit
Una carpeta con todo lo que Jarvis necesita para trabajar:
- `CLAUDE.md` — quién es Jarvis y los límites que nunca cruza. Claude Code lo lee solo al abrir la carpeta.
- `.claude/skills/arquitecto-ia/` — la skill de evaluación (puede estar oculta en Windows; es normal).
- `sistema/` — aprendizaje de errores y plantilla del reporte al Centro de Control.
- `clientes/_plantilla/` — se copia automáticamente por cada cliente nuevo.

## Paso a paso

### 1. Usa la PC con Windows
La MacBook Pro 2013 con Big Sur es demasiado antigua para estas herramientas. Trabaja desde la PC con Windows.

### 2. Instala la app de escritorio de Claude
1. Descarga el instalador para Windows: https://claude.ai/api/desktop/win32/x64/setup/latest/redirect
2. Ábrelo e inicia sesión con tu cuenta de Claude (ya tienes plan de pago, es requisito).
3. La app ya incluye Claude Code: no hay que instalar nada por terminal.

### 3. (Recomendado) Instala Git para Windows
Descarga desde https://git-scm.com/downloads/win y acepta todo con "Next". Le da a Claude Code mejores herramientas internas. No tienes que usarlo tú.

### 4. Coloca la carpeta
1. Descomprime `Jarvis-Consultoria.zip`.
2. Mueve la carpeta `Jarvis-Consultoria` a `Documentos` (o donde prefieras, que no se mueva después).

### 5. Abre Jarvis
1. En la app de Claude, entra a la pestaña **Code**.
2. Selecciona la carpeta `Jarvis-Consultoria` como carpeta de trabajo.
3. Escribe tu primer mensaje:
   > Hola Jarvis, lee CLAUDE.md y LEEME.md y confírmame en un checklist que todo está en su lugar.

### 6. Prueba la skill con un cliente piloto
> nuevo mapa Comfort Services

Jarvis crea `clientes/Comfort-Services/` y empieza con la fase F0, una pregunta a la vez.

### 7. Antes de una reunión con un cliente
1. `nuevo mapa [Cliente]`
2. Copia los archivos del cliente (organigrama, manuales) dentro de `clientes/[Cliente]/`.
3. Opcional: `encuesta [área]` para que los referentes llenen sus tareas antes de la reunión.

### 8. Durante la reunión
1. Pide el consentimiento de grabación al inicio (Florida exige el de todas las partes) y graba con Zoom.
2. Escribe `modo reunión`. Pregunta lo que necesites, por ejemplo: "¿cuántas personas tiene el organigrama?". Jarvis responde corto y cita la fuente.

### 9. Después de la reunión
1. Descarga la transcripción de Zoom y ponla en la carpeta del cliente.
2. `cargar transcripción` → Jarvis la vuelca al registro.
3. `genera mapa` → entregables en `clientes/[Cliente]/entregables/`.
4. `reporte CC` → bloque de reporte para el Centro de Control.

## Cómo corregir a Jarvis
Escribe `error: [lo que hizo mal]`. Jarvis registra el error, propone la causa y la solución, y te pide un "si" antes de crear una regla nueva. Revisa con `errores abiertos` y `revisar reglas`.

## Permisos
Claude Code te pedirá permiso antes de crear o cambiar archivos. Al principio, lee cada pedido y aprueba. Si algo no te queda claro, pregunta: "¿qué vas a hacer exactamente?".

## Rutinas
Todavía no hay ninguna. Las definimos cuando estemos trabajando (la app de escritorio permite tareas programadas).

## Si algo falla
Copia el mensaje de error y pégalo en el chat de Jarvis o en tu proyecto de Claude "Jarvis Para Consultoría".
