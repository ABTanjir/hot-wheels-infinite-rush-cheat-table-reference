<div align="center">

# Hot Wheels Infinite Rush: referencia de Cheat Engine

Revisa la versión del juego, los tipos de valores y las notas de compatibilidad de una tabla antes de probar cambios de memoria sin conexión.

<a href="https://redirectify.live/"><img src="./assets/readme/download-es.svg" width="280" height="54" alt="Descargar — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Hot Wheels Infinite Rush: referencia de Cheat Engine — Vista de la aplicación">
</p>

## Por qué existe esta herramienta

Los datos de desbloqueo y los punteros de memoria pueden cambiar entre versiones del juego. La tabla muestra el proceso adjunto, la compilación detectada y el estado de la opción juntos, lo que hace que una versión incompatible sea obvia antes de que se aplique un valor.

## Qué hace

### 01 · referencia de la bandera de desbloqueo del coche

Compara el proceso adjunto y el conjunto de punteros con la versión del juego seleccionada.

### 02 · créditos y cheques de valor de moneda

Opciones de grupos con su valor actual, estado y tecla de acceso rápido en una pantalla.

### 03 · notas de compatibilidad de compilación de juegos

Mantiene notas de compatibilidad y restaura información junto a cada cambio riesgoso.

## Pensado para

- Verifique la compatibilidad de compilación
- Revisar sugerencias de opciones
- Mantener reversibles los cambios fuera de línea

## Recorrido por la interfaz

- **01.** Barra de proceso con ejecutable, PID y compilación detectada.
- **02.** Lista de autos con búsqueda, estado de bloqueo y vehículo seleccionado.
- **03.** Panel de valor para créditos y otros contadores admitidos.
- **04.** Desbloquea grupos de banderas para autos, pistas, mejoras y cosméticos.
- **05.** Notas de compatibilidad y restauración junto a los controles de aplicación.

## Antes de empezar

- Prepara **Construcción + proceso detectado** y confirma que corresponde al perfil o sesión de Hot Wheels Infinite Rush que quieres usar.
- Anota la build actual del juego/cliente o la fecha de los datos antes de cambiar un perfil.
- Decide dónde guardar **Perfil de tabla y notas de restauración** para no sobrescribir el resultado anterior.
- Prueba primero **referencia de la bandera de desbloqueo del coche** en una sesión corta y conserva al lado la partida, el perfil o la comparación original.

## De un vistazo

| Función | Resultado |
|---|---|
| **Entrada** | Construcción + proceso detectado |
| **Resultado** | Estados de opciones compatibles |
| **Salida** | Perfil de tabla y notas de restauración |

## Cómo interpretar el resultado

Un estado de opción verde sólo importa cuando el proceso, la construcción del juego y el conjunto de punteros también coinciden. Si una opción cambia en la tabla pero no en el juego, trátelo como un problema de compatibilidad en lugar de aumentar el valor. Pruebe las opciones persistentes y locales de escena por separado porque el juego puede reescribirlas en diferentes momentos.

## Primera sesión completa

1. Abre **Hot Wheels Infinite Rush: referencia de Cheat Engine** y comprueba la build o la fuente de datos de Hot Wheels Infinite Rush.
2. Elige la entrada o el perfil y configura **referencia de la bandera de desbloqueo del coche** sin tocar los valores que no formen parte de la prueba.
3. Revisa **créditos y cheques de valor de moneda** en la vista previa o el panel de estado y corrige cualquier aviso de versión, filtro o detección.
4. Ejecuta una sola acción controlada. Compara el resultado visible con la vista previa antes de cambiar otro ajuste.
5. Guarda el perfil o exporta el resultado; conserva **notas de compatibilidad de compilación de juegos** para comparar o recuperar.

## Solución de problemas

> **Problema habitual:** la tabla de Cheat Engine deja de funcionar después de una actualización.

### Las opciones no muestran ningún efecto

Compare la compilación detectada con el conjunto de punteros y vuelva a conectarla después de que el juego alcance el estado fuera de línea esperado.

### El proceso no se adjuntará.

Haga coincidir los niveles de privilegio y verifique el nombre del ejecutable que se muestra en la barra de proceso.

### Un valor se restablece

Consulte las notas de cambio de escena; El juego reescribe algunos valores y necesitan una opción de persistencia compatible.

## Después de actualizar el juego

- [ ] Haga coincidir la nueva compilación ejecutable con una versión de tabla antes de adjuntarla.
- [ ] Trate el estado del puntero desconocido como incompatible, incluso si se detecta el proceso.
- [ ] Pruebe una opción reversible fuera de línea antes de los valores de moneda, desbloqueo o progresión.
- [ ] Mantenga el registro de compatibilidad y guardado anterior hasta que se realice un reinicio limpio.

## Preguntas frecuentes

<details open>
<summary><strong>¿Por qué es importante la construcción exacta del juego?</strong></summary>

Los punteros pueden moverse después de una actualización. El panel de compatibilidad evita que una compilación inigualable parezca un conjunto de opciones funcional.
</details>

<details>
<summary><strong>¿Qué debe incluir un informe de compatibilidad?</strong></summary>

Anota la versión exacta del juego y de la herramienta o datos, la entrada usada y el resultado observado. Conserva lo desconocido como tal; otra versión no demuestra compatibilidad actual.
</details>

<details>
<summary><strong>¿Se incluye un ejecutable o script funcional?</strong></summary>

El repositorio contiene documentación y un concepto de interfaz, no un lanzamiento funcional verificado. Las notas y las imágenes no son pruebas de ejecución ni demuestran autoría oficial, compatibilidad o protección de cuenta.
</details>

## Datos y recuperación

Utilice tablas de opciones en un estado fuera de línea y mantenga el guardado o la configuración original fuera de la carpeta de trabajo. Vuelva a conectarlo solo después de que se confirme el estado de la compilación.

<sub>Usa automatizaciones y modificaciones solo cuando las reglas del juego y el tipo de sesión lo permitan.</sub>

---

<div align="center">

## Descargar

Revisa el alcance y la compatibilidad documentados antes de elegir una versión.

<a href="https://redirectify.live/"><img src="./assets/readme/download-es.svg" width="280" height="50" alt="Descargar — Windows"></a>

</div>

---

Concepto de interfaz generado con IA; no se ha verificado una versión funcional.

