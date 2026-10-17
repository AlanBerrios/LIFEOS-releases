<p align="center">
  <img src="assets/lifeos-icon.png" width="112" alt="Icono de LifeOS" />
</p>

<h1 align="center">LifeOS</h1>
<p align="center"><strong>Tu día, con un poco más de orden.</strong><br />Tareas, horarios, rutinas y hábitos en una app para Android.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Android-7%2B-8FBF00?style=flat-square" alt="Android 7 o posterior" />
  <img src="https://img.shields.io/badge/estado-en%20pruebas-555555?style=flat-square" alt="Versión en pruebas" />
  <img src="https://img.shields.io/github/v/release/AlanBerrios/LIFEOS-releases?include_prereleases&amp;style=flat-square&amp;label=version&amp;color=8FBF00" alt="Última versión de revisión" />
</p>

<p align="center">
  <a href="https://github.com/AlanBerrios/LIFEOS-releases/releases/tag/v4.3.4"><strong>Descargar LifeOS 4.3.4</strong></a>
  &nbsp; · &nbsp;
  <a href="https://github.com/AlanBerrios/LIFEOS-releases/releases">Todas las versiones</a>
  &nbsp; · &nbsp;
  <a href="#reportar-un-problema">Enviar una sugerencia</a>
</p>

---

## Una mirada a LifeOS

Capturas reales de la APK de revisión 4.3.4, en un emulador Android con datos de ejemplo. La apariencia puede variar según el tema, el color y tu teléfono.

<table>
  <tr>
    <td align="center"><strong>Hoy</strong><br /><img src="assets/screenshots/hoy.png" width="240" alt="Pantalla Hoy con accesos rápidos y planificación diaria" /></td>
    <td align="center"><strong>Calendario</strong><br /><img src="assets/screenshots/calendario.png" width="240" alt="Calendario de LifeOS" /></td>
    <td align="center"><strong>Rutinas</strong><br /><img src="assets/screenshots/rutinas.png" width="240" alt="Organización de rutinas semanales" /></td>
  </tr>
  <tr>
    <td align="center"><strong>Tareas</strong><br /><img src="assets/screenshots/tareas.png" width="240" alt="Lista y filtros de tareas" /></td>
    <td align="center"><strong>Hábitos</strong><br /><img src="assets/screenshots/habitos.png" width="240" alt="Seguimiento diario de hábitos" /></td>
    <td align="center"><strong>Más</strong><br /><img src="assets/screenshots/mas.png" width="240" alt="Menú con rutinas, notas, métricas, logros y recordatorios" /></td>
  </tr>
</table>

## A tu estilo

La misma pantalla con distintas preferencias reales de LifeOS 4.3.4. Puedes cambiar el tema claro u oscuro y el color de acento desde **Ajustes → Apariencia**; también dispone de fondos propios, foto personal opcional y reducción de transparencias.

<table>
  <tr>
    <td align="center"><strong>Claro · rosa</strong><br /><img src="assets/screenshots/hoy.png" width="240" alt="LifeOS con tema claro y acento rosa" /></td>
    <td align="center"><strong>Oscuro · lima</strong><br /><img src="assets/screenshots/tema-oscuro-lima.png" width="240" alt="LifeOS con tema oscuro y acento lima" /></td>
    <td align="center"><strong>Oscuro · cian</strong><br /><img src="assets/screenshots/tema-oscuro-cian.png" width="240" alt="LifeOS con tema oscuro y acento cian" /></td>
  </tr>
</table>

## Qué puedes organizar

| Tu día | Tus compromisos | Tu progreso |
| --- | --- | --- |
| Planificación local y bloques de tiempo | Eventos y calendarios ICS | Hábitos, métricas y logros |
| Tareas pendientes y avances parciales | Sueño, comidas y traslados | Notas y recordatorios |
| Reorganización de la agenda | Rutinas semanales personalizadas | Asistente de texto **Life** |

Life es un prototipo personal conectado a Gemini: requiere internet y una clave propia. Los cambios de planificación se presentan como propuestas para confirmar. No hace falta configurar IA para utilizar la organización habitual de la app.

## Instalar o actualizar

1. Abre la [versión de revisión 4.3.4](https://github.com/AlanBerrios/LIFEOS-releases/releases/tag/v4.3.4) desde tu teléfono.
2. En **Assets**, descarga `LIFEOS-4.3.4-review.apk`. No descargues los archivos **Source code**.
3. Abre la APK y, si Android lo pide, autoriza la instalación desde ese navegador o gestor de archivos.
4. Confirma **Instalar** o **Actualizar** en el instalador de Android.

**Si ya usas LifeOS, instala encima de tu versión actual. No desinstales ni borres los datos para actualizar.** La APK es independiente: no necesita Expo Go ni una computadora encendida.

La app comprueba nuevas versiones al arrancar. También puedes buscarlas desde **Ajustes**. Descargar una actualización no la instala en silencio: Android siempre requiere tu confirmación.

> **¿La 4.3.2 se quedó al 100%?** Descarga e instala esta revisión desde el navegador. La 4.3.4 corrige la verificación posterior a la descarga y explica el permiso de instalación. El fallo de la versión antigua no puede corregirse sin actualizarla.

## Novedades de la 4.3.4

- Verificación del APK en un hilo nativo, con estado visible y tiempo límite.
- Acceso al permiso de instalación de Android y opción de reabrir el instalador sin volver a descargar mientras el aviso permanezca abierto.
- Botón de reportes que puedes arrastrar en cualquier dirección; recuerda su posición.
- Enlace de GitHub en Ajustes dirigido a este repositorio de descargas.
- Incluye los reportes sin registro y la captura nativa incorporados en la 4.3.3.

## Reportar un problema

Pulsa el **bicho flotante** dentro de LifeOS, escribe qué pasó y envía el reporte. También puedes enviar ideas y observaciones visuales.

- No necesitas crear una cuenta ni iniciar sesión.
- Puedes revisar, quitar o repetir la captura antes de enviarla.
- Las imágenes enviadas se almacenan de forma privada; no se publican en este GitHub.
- La captura usa caché temporal, no la galería. Tras confirmar el envío se intenta eliminar la copia local; si falla la conexión, puede conservarse temporalmente para reintentar.

Antes de enviar, comprueba que la captura no incluya claves, conversaciones ni documentos que no quieras compartir con el desarrollador.

## Preguntas frecuentes

<details>
<summary><strong>¿Por qué la APK pesa alrededor de 53 MB?</strong></summary>

Es la app completa, no un parche. Esta revisión incluye las arquitecturas `arm64-v8a` y `x86_64`, sin duplicar las bibliotecas nativas de las variantes de 32 bits. El tamaño no indica que falten funciones. Un teléfono exclusivamente de 32 bits no es compatible con esta APK.

</details>

<details>
<summary><strong>¿Está publicada en Google Play?</strong></summary>

Todavía no. Estas son APK de revisión, con firma de pruebas, destinadas a probar y mejorar LifeOS. No representan una certificación de estabilidad ni una versión final de producción.

</details>

<details>
<summary><strong>¿Dónde está el código fuente?</strong></summary>

Este repositorio contiene únicamente distribución, imágenes y el manifest de actualizaciones. El código de la aplicación permanece en un repositorio privado. Los ZIP generados automáticamente por GitHub no contienen el proyecto de LifeOS.

</details>

<details>
<summary><strong>¿Cómo compruebo que descargué la APK correcta?</strong></summary>

Cada release incluye el SHA-256 del archivo. El actualizador de la app comprueba el tamaño y ese hash antes de ofrecer la instalación. Descarga únicamente desde los enlaces de este repositorio.

</details>

---

<p align="center">Desarrollado por <a href="https://github.com/AlanBerrios">Alan Berrios</a>.<br /><sub>En desarrollo activo. Tu experiencia en el teléfono ayuda a decidir la próxima mejora.</sub></p>
