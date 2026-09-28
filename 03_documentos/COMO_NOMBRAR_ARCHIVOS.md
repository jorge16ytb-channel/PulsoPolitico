# Cómo nombrar archivos nuevos

Idea general: el mismo ID de video se usa en el guion, en la miniatura y en la fila correspondiente del "Registro de cambios y métricas". Así todo lo de un mismo video queda enlazado.

## ID de video

Usar dos dígitos (01, 02, 03...) para que ordene bien alfabéticamente incluso pasando de 9 a 10. Es el mismo número que ya se usa en "GUION_1", "GUION_2", etc. — de acá en adelante, escribirlo con dos dígitos: GUION_01, GUION_02...

## Guiones (01_guiones/)

Mantener el patrón que ya se usa:

`{AUTOR}_-_GUION_{NN}_-_{TÍTULO_EN_MAYÚSCULAS_CON_GUIONES_BAJOS}.docx`

Ejemplo: `JORGE_SENTIS_-_GUION_05_-_TÍTULO_DEL_VIDEO.docx`

Nota: en los archivos actuales el autor aparece a veces como "JORGE_SENTIS" y a veces como "JORGEN_SENTIS" — conviene fijar una sola forma de acá en adelante.

## Miniaturas (03_miniaturas/)

- Miniatura original de un video: `mini-{NN}_v1.png`
- Si se prueba una segunda miniatura para el mismo video (por bajo CTR u otro motivo): `mini-{NN}_v2.png`, y así sucesivamente.
- El número de versión (`v1`, `v2`...) es el mismo que se anota en la columna "N° de versión" del Registro de cambios y métricas, para poder cruzar la miniatura usada con el resultado que dio.

Nota: en los archivos actuales hay inconsistencia de formato — "mini-1.png", "mini-2.png", "mini-3.png" (con guion) pero "mini 4.png" (con espacio). De acá en adelante usar siempre guion y dos dígitos.

## Video final (04_video/), si se archiva acá

`{NN}_{título-corto-en-minúsculas-con-guiones}.mp4`

Ejemplo: `05_titulo-del-video.mp4`

## Investigación vidIQ (02_investigacion_vidiq/)

Una subcarpeta por video, nombrada `{NN}_{título-corto}`, con los archivos de vidIQ y del video base adentro (sin renombrar los exports de vidIQ, para no perder trazabilidad del dato original).
