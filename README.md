# S06 · El caso del pliego fantasma (IDC)

Guía de trabajo interactiva de una sola página (HTML estático, sin compilación) para la **Sesión 06** de la unidad didáctica **"Producción y publicación de piezas gráficas"** del **IDC Diseño & Comunicación – Instituto de Educación Superior Público**. Docente: **Mg. Mario Quiroz Martínez**.

La sesión se plantea como un **caso de misterio**. Don Aurelio, jefe de taller de la Litografía Kolb (ficticia), encerró la orden de producción en una caja fuerte. El estudiante la abre con un código de 4 dígitos que va reuniendo al resolver pistas técnicas sobre preparación de archivos e impresión offset.

---

## 📚 Objetivo de aprendizaje

Al finalizar la sesión 06, el estudiante será capaz de **preparar archivos gráficos según requerimientos técnicos específicos**. Para eso verifica y ajusta el archivo de presentación de su cuadro de medios y canales (formato, resolución, tamaño, legibilidad, nomenclatura y completitud) y lo expone ante la clase. Además, aplica los fundamentos del proceso de impresión offset (plancha, entintado, cuatricromía, pliego, tiraje, imposición y acabados) para **calcular el aprovechamiento de un pliego**, considerando el margen de pinza, el sangrado de la pieza y las dos orientaciones posibles, a fin de determinar la disposición más eficiente para un encargo real.

---

## 🧭 Flujo de la actividad (7 estaciones)

Cada estación se desbloquea al completar la anterior. Las pistas 1 a 4 forman el código de la caja fuerte: **4 · 5 · 9 · 6**.

| Estación | Enigma | Contenido técnico | Pista |
|---|---|---|---|
| **1 · La escena del taller** | Hipótesis inicial + mensaje cifrado (A = 3) | Activación: “MIDE LA PINZA” | — |
| **2 · El archivo sospechoso** | 6 evidencias: ¿cumple o no cumple? + tarjetas volteables | Los 6 requisitos de una presentación | **4** fallas |
| **A · Tu archivo** | Lista de cotejo + validador de nombre | Revisión del archivo propio y guion de exposición (4 + 1 min) | — |
| **B · Los testigos** | 8 operarios describen el proceso sin decir el término | Plancha, entintado, cuatricromía, pliego, tiraje, imposición, acabados, pinza | **5** planchas (4/1) |
| **3 · La orden manchada** | Reconstruir 5 cálculos borrados | Área útil, sangrado, orientación A y B, pliegos con demasía | **9** piezas |
| **4 · El cuaderno revuelto** | 5 anagramas + acertijo + caja fuerte | PINZA, PLANCHA, SANGRADO, IMPOSICIÓN, TIRAJE | **6** letras |
| **5 · Tu primera orden** | Encargos reales y cierre del caso | Encargo 2 (tarjetas), encargo 3 (pieza propia), reflexión, ticket, rúbrica | — |

Al abrir la caja fuerte se revela la causa del misterio: el archivo llegó sin revisar y el volante se montó sin girar, con 8 piezas por pliego en lugar de 9. Esa diferencia significó **43 pliegos perdidos**. La guía compara esa causa con la hipótesis inicial del estudiante.

### Datos de referencia del caso

| Cálculo | Valor |
|---|---|
| Pliego / pinza | 70 × 100 cm / 1.5 cm → área útil 100 × 68.5 cm |
| Volante A4 con sangrado 3 mm | 21.6 × 30.3 cm |
| Orientación A (normal) | 4 × 2 = **8** piezas → 394 pliegos |
| Orientación B (girada 90°) | 3 × 3 = **9** piezas → **351** pliegos (3 000 ej. + 5 %) |
| Encargo 2 · tarjeta 9 × 5.5 en ½ pliego 50 × 70, pinza 1 cm | A: 7 × 8 = **56** · B: 11 × 5 = 55 |

---

## ✨ Funcionalidades principales

### Gamificación y retroalimentación positiva
- **Narrativa de misterio** con mensaje cifrado, evidencias, testigos, cuaderno de anagramas y caja fuerte con pista por cada dígito.
- **Libreta de pistas** en la barra superior: los dígitos encontrados se llenan en tiempo real.
- **Puntaje** de 234 puntos máximos: menos puntos por intento (100 % → 60 % → 30 %), nunca cero.
- **Rangos:** Aprendiz de taller → Ayudante de preprensa → Preprensista → Jefe de producción → Detective de imprenta.
- **Rachas** de aciertos (3, 5 y 8) con mensaje propio.
- **Elogio en cada acierto** con el porqué, chispas y el nombre del estudiante.
- **Error productivo:** el panel muestra pausa, pista, dato clave, contexto y reintento. Detecta errores típicos: restar la pinza dos veces, sumar el sangrado una sola vez, no redondear hacia arriba.

### Mecánicas interactivas
- Mensaje cifrado por desplazamiento.
- Clasificación de evidencias (cumple / no cumple).
- Tarjetas de definición volteables.
- Emparejamiento testigo ↔ término (tocar y tocar, operable con teclado).
- Simulador de cálculo paso a paso con detección de errores frecuentes.
- **Calculadora de montaje** que dibuja las dos orientaciones con pinza y sangrado.
- Anagramas con “volver a mezclar” y ayuda tras dos intentos.
- Caja fuerte de 4 dígitos con retroalimentación por dígito.

### Registro, informe y seguimiento
- **Ficha del detective:** nombres, apellidos y **correo electrónico** con validación en vivo.
- **Autoguardado** en el navegador después de cada acción, con la opción **▶ Continuar mi caso** al volver y el botón **Borrar guardado**.
- **Informe de desempeño en PDF** (jsPDF) y **Markdown**, disponible en la Estación 5 y en 🧭 Ayuda en cualquier momento. Incluye datos y correo, puntaje, nivel, rango, tiempo, sello, fortalezas, temas para seguir practicando, tablas por estación y por reto, reflexiones e historial de respuestas.
- **Constancia** imprimible al cerrar el caso.
- **Envío en tiempo real al docente** mediante `envio-resultados.js` (ver más abajo).

### Transversal
- 🗺️ **Mapa del caso** en ventana modal, con el estado de cada estación.
- 🧭 **Ayuda y avance**, con puntaje, estaciones, consejo del taller y descarga del informe.
- 📖 **Glosario** de 25 términos con buscador que ignora tildes.
- Branding IDC: azul `#0072b9`, amarillo `#f3a100`, grises, logo institucional y pie del docente.
- Accesible: foco visible, `aria-live` en la retroalimentación, modales con foco atrapado y Esc, respeta `prefers-reduced-motion` y no tiene scroll horizontal en el celular.

---

## 📡 Datos que se envían al docente

Al abrir la guía desde el servidor, `envio-resultados.js` envía el estado:

- cada **45 s**, si hubo cambios;
- en un **latido** cada **20 s**, para mostrar quién está conectado;
- al cerrar la pestaña;
- con el botón **📤 Enviar resultados al docente**.

| Campo de `state` | Contenido | Uso en el panel `/docente` |
|---|---|---|
| `student` | `nombres`, `apellidos`, `email` | Identificación del estudiante |
| `score` | Puntaje acumulado (máx. 234) | Columna **Puntaje** |
| `answers` | Un registro por reto: estación, intentos, última respuesta, correcto, puntos | Columna **Progreso** |
| `current` | Estaciones superadas (0–7) | **Paso actual** |
| `startTs` / `endTs` | Inicio y cierre del caso | **Tiempo en la tarea** |
| `historial` | Cada intento con hora, reto, respuesta y resultado | Informe `.md` |
| `buildMD()` | Informe de desempeño completo | Botón **Ver informe** |

Los resultados se guardan en `resultados/tarea-06/`, con un `.json` y un `.md` por estudiante.

Si la guía se abre con doble clic (`file://`), **no envía nada**. Funciona igual, guarda el avance y genera los informes, y el estudiante puede entregar su PDF.

El diagrama del flujo de datos está en [`../../diagramas/flujo-datos-s06.html`](../../diagramas/flujo-datos-s06.html).

---

## 🗂️ Archivos

| Archivo | Ubicación | Para qué sirve |
|---|---|---|
| `index.html` | `servidor-nas/tareas/tarea-06/` | **Versión que se publica en el NAS.** Incluye `<script src="/envio-resultados.js">` |
| `README.md` | `servidor-nas/tareas/tarea-06/` | Este documento |
| `tareas.json` | `servidor-nas/tareas/` | Nombre visible: “S06 · El caso del pliego fantasma” |
| `guia-s06-caso-pliego.src.html` | `Proyectos/` | **Versión editable** (con el marcador `__IDC_LOGO__`) |
| `guia-s06-caso-pliego.html` | `Proyectos/` | Copia local, para abrir con doble clic |
| `construir-guia-s06.js` | `Proyectos/` | Regenera la copia local y `tarea-06/index.html` |
| `ejemplo-informe-s06.pdf` | `Proyectos/` | Ejemplo del informe (estudiante ficticia) |
| `flujo-datos-s06.html` / `.json` | `servidor-nas/diagramas/` | Diagrama archify del flujo de datos y su especificación |

---

## 🚀 Publicar en el NAS

1. Copia la carpeta `tarea-06` y el archivo `tareas.json` a `\\192.168.0.101\docker\idc-servidor\tareas\`.
2. Comprueba que el proyecto **aplicativos-idc** está en marcha en Docker (UGOS Pro). El servidor relee `tareas.json` cada 30 s, así que no hace falta reiniciarlo.
3. Comparte la dirección con los estudiantes:

| Quién | Dirección |
|---|---|
| Red del instituto o de casa | `http://192.168.0.101:8091/tarea-06/` |
| Desde cualquier lugar | `https://aplicativos-idc.<tu-red>.ts.net/tarea-06/` |
| Lista de tareas | `https://aplicativos-idc.<tu-red>.ts.net/tareas` |
| Panel del docente | `https://aplicativos-idc.<tu-red>.ts.net/docente` |

No uses `file://192.168.0.101/...`: abre el archivo sin pasar por el servidor y las respuestas no llegan al panel.

También hay una copia en línea: https://claude.ai/artifact/CjXzRMXAeK5R312VvEzFcM. Es privada: hay que compartirla desde **Share** y no envía datos al NAS.

---

## ✏️ Editar la guía

1. Edita `Proyectos/guia-s06-caso-pliego.src.html`. El contenido está en arreglos de datos dentro del `<script>`:

   | Arreglo | Contenido |
   |---|---|
   | `EVID` | Evidencias del archivo sospechoso |
   | `FLIPS` | Tarjetas con los requisitos |
   | `CHECKS` | Lista de cotejo |
   | `TESTS` | Declaraciones de los testigos |
   | `SIM` | Pasos del cálculo, con sus pistas y errores típicos |
   | `ANAG` | Anagramas |
   | `GLOSSARY` | Glosario |
   | `TIPS` | Consejos del taller |
   | `ITEMS` | Puntaje por reto |
   | `ITEM_INFO` | Nombres de cada reto en el informe |

2. Regenera desde la carpeta `Proyectos`:
   ```bash
   node construir-guia-s06.js
   ```
3. Vuelve a copiar `tarea-06/index.html` al NAS.

Si cambias un valor del caso (pliego, pinza, tiraje), actualiza también `CODE`, las respuestas de `SIM`, la carta de la caja fuerte y la tabla de referencia de este README.

---

## 🔒 Privacidad

- La guía pide solo nombre, apellidos y correo, para identificar el informe.
- El avance se guarda en el navegador del estudiante con la clave `s06-pliego-registro-v1`. Se borra con **Borrar guardado** o con **Empezar de nuevo**.
- Los datos solo salen del navegador hacia el servidor del NAS del docente, por HTTPS con Tailscale Funnel. No se envían a terceros.
- En una computadora compartida, el estudiante debe usar **Borrar guardado** al terminar.

---

**Mg. Mario Quiroz Martínez** · Docente · Unidad didáctica: Producción y publicación de piezas gráficas · Semana 6
