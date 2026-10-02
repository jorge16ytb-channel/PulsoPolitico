# Instrucciones de Producción: Formato del Guion

Este documento define el estándar de presentación de guiones para Pulso Político. Todo guion debe seguir este formato antes de pasar a producción.

---

## 1. Encabezado Obligatorio

Todo guion comienza con un bloque de metadatos:

```
# Título del video

**Título:** [Título exacto del video]
**Miniatura:** [Texto que aparece en la miniatura]
**Keywords principales:** [3 a 5 palabras clave separadas por coma]
```

---

## 2. Índice de Ayudas al Narrador

Inmediatamente después del encabezado, antes del guion, se incluye este índice fijo:

```
## ÍNDICE DE AYUDAS AL NARRADOR

- **Negrita** = Énfasis. Cargar esa palabra con peso, bajar el tono o pausar justo después.
- *Cursiva* = Chiste o ironía. Livianar el tono, casi como si lo dijeras entre dientes con una sonrisa.
- ***Negrita + cursiva*** = Emoción adicional marcada en el texto. Indica qué sentimiento sembrar 
  en ese momento exacto (ej: ***indignación***, ***asombro***). Solo aparece cuando es necesario 
  cambiar de emoción base.
```

---

## 3. Estructura de Secciones

Cada sección del guion sigue este patrón:

```
## NOMBRE DE SECCIÓN
*(Tiempo estimado de inicio – tiempo estimado de fin)*

**TÍTULO INTERNO DE LA SECCIÓN** (en mayúsculas, negrita)
[Texto del narrador con las ayudas de formato correspondientes]
```

**Regla:** El título interno de la sección va pegado al párrafo que lo sigue, en la misma sección. No se crea un bloque separado para el título solo.

---

## 4. Secciones Obligatorias

Todo guion debe incluir, en este orden:

| N° | Sección | Tiempo estimado |
|----|---------|----------------|
| 1 | GANCHO | 0:00 – 0:25 |
| 2 | DUDA TEMPRANA (CTA temprano) | 0:25 – 0:45 |
| 3 | Desarrollo (tantas sub-secciones como requiera la tesis) | 0:45 – 4:00 |
| 4 | CIERRE Y LLAMADO A LA ACCIÓN | Últimos 30–60 segundos |

---

## 5. Reglas del Texto del Guion

- **Sin saludos al inicio.** El guion arranca con la primera oración del gancho, sin "hola", "bienvenidos", ni presentación del canal.
- **Un solo CTA al final.** La suscripción y la pregunta para comentarios van únicamente en la sección de Cierre. No se repiten en otro momento del guion.
- **Una tesis por video.** Si el guion intenta demostrar más de una idea principal, debe dividirse en dos videos.
- **Máximo 3 tipos de ayuda al narrador.** Negrita, cursiva y negrita+cursiva. No se inventan otros formatos sin actualizar el índice.

---

## 6. Indicaciones para el Editor

Las indicaciones visuales para el editor se escriben como bloques de cita (`>`) inmediatamente después del fragmento de narración al que corresponden:

```
> **[EDITOR]**: Descripción de la imagen, b-roll, gráfico o efecto requerido en este momento.
> Incluir referencia de tiempo si es relevante.
```

---

## 7. Archivos del Paquete de Producción

Cada episodio se entrega con estos archivos en la carpeta `01_guiones/`:

| Archivo | Contenido |
|---------|-----------|
| `EP##_GUION_[TEMA].md` | Guion completo con ayudas al narrador y al editor |
| `EP##_TEXTO_NARRADOR.md` | Solo el texto que lee el narrador, sin indicaciones ni formato de ayudas |
| `EP##_INDICACIONES_NARRADOR.md` | Documento separado con sugerencias generales de tono, ritmo y actuación |
| `EP##_INDICACIONES_EDITOR.md` | Documento separado con todas las indicaciones visuales consolidadas por sección |

---
