# Reglas de Trabajo: Canal YouTube (Pulso PolÃ­tico)

## 0. Identidad del Canal: Formato Faceless
- **Pulso PolÃ­tico es un canal SIN ROSTRO.** Todo el contenido visual depende del montaje, memes y B-Roll.
- **Acotaciones 100% Vocales:** En los guiones de locuciÃ³n estÃ¡ **PROHIBIDO** incluir instrucciones fÃ­sicas (ej. "mira a la cÃ¡mara", "levanta el dedo"). Toda instrucciÃ³n en cursiva debe ser estrictamente sonora (ej. tono, velocidad, pausas, silencios, volumen).

Este archivo define las reglas obligatorias de empaque, tÃ­tulos y miniaturas aprendidas de la metodologÃ­a vidIQ y las preferencias del canal.

## 1. Regla de Oro: Complementariedad TÃ­tulo-Miniatura
- **Nunca duplicar informaciÃ³n:** Si el tÃ­tulo dice un dato o marco (polÃ­tico, temporal, temÃ¡tico), la miniatura **no** lo repite con sinÃ³nimos. Se reparten el trabajo.
- **Desglose del TÃ­tulo:**
  - Marco temÃ¡tico / polÃ­tico -> TÃ­tulo.
  - Urgencia temporal -> TÃ­tulo.
  - InterÃ©s personal / Consecuencia ("cÃ³mo te afecta / vacÃ­a tu bolsillo") -> **Hueco para la miniatura**.
- **ContradicciÃ³n / Quiebre de expectativa:** Generar conflicto cognitivo. Si el tÃ­tulo insinÃºa un culpable obvio, la miniatura le da la vuelta (ej. *"NO FUE EL GOBIERNO"*).

## 2. ComposiciÃ³n de Miniaturas (CTR Alto)
- **Objeto protagÃ³nico:** Elementos tangibles cotidianos (recibos, facturas, tickets con precios en rojo) que materialicen el impacto en el bolsillo.
- **Causalidad grÃ¡fica:** Mostrar el vÃ­nculo entre la causa macro (mapa tÃ©rmico del ocÃ©ano PacÃ­fico) y el efecto local (la boleta/ticket).
- **Rostros:** Rostro con la expresiÃ³n adecuada (ej. resignaciÃ³n o incredulidad), ubicado a un costado y mirando al objeto central, sin robarle el protagonismo al objeto.
- **Textos:** MÃ¡ximo 3 a 4 palabras, alto contraste (blanco con reborde negro o acento amarillo/rojo), legibles en celular.

## 3. OptimizaciÃ³n Mobile de TÃ­tulos
- **Front-loading:** Colocar el beneficio o dolor directo ("vacÃ­a tu bolsillo") en los primeros 45 caracteres antes del corte en feed mÃ³vil.
- **Sin palabras muertas:** Eliminar prefijos genÃ©ricos como `"Clima:"` o etiquetas vacÃ­as al inicio.

## 4. Reglas de InteracciÃ³n y ModificaciÃ³n del Repositorio
- **AprobaciÃ³n Previa Obligatoria:** Nunca actualizar, crear ni sobreescribir archivos en los repositorios o carpetas locales de forma automÃ¡tica.
- **Propuesta por Chat:** Toda modificaciÃ³n, guion, idea o ajuste de cÃ³digo debe ser propuesto y discutido en el chat primero. Solo se ejecutarÃ¡n los cambios en el sistema local cuando el usuario dÃ© una orden explÃ­cita para hacerlo.

## 6. Sistema de Archivos y OrganizaciÃ³n de Carpetas

### Estructura CanÃ³nica del Repositorio
```
canal YOUTUBE/
â”œâ”€â”€ 01_guiones/
â”‚   â”œâ”€â”€ _plantillas/          â† SOLO instrucciones, formatos y plantillas reutilizables
â”‚   â””â”€â”€ EP##_NOMBRE_TEMA/     â† Una carpeta por episodio con TODOS sus archivos
â”œâ”€â”€ 02_miniaturas/
â”‚   â”œâ”€â”€ _plantillas/          â† SOLO instrucciones de diseÃ±o y guÃ­as de CTR
â”‚   â””â”€â”€ EP##_NOMBRE_TEMA/     â† Ideas e imÃ¡genes de miniaturas por episodio
â”œâ”€â”€ 03_titulos/
â”‚   â””â”€â”€ _plantillas/          â† SOLO instrucciones de tÃ­tulos y guÃ­as de SEO
â”œâ”€â”€ _formacion/               â† Entrenamiento, tesis y ejercicios del gimnasio de Ã¡ngulos
â”œâ”€â”€ TAREAS_PENDIENTES.md
â””â”€â”€ GEMINI.md
```

### Reglas Obligatorias de OrganizaciÃ³n
- **`_plantillas/`** contiene ÃšNICAMENTE instrucciones, formatos y guÃ­as reutilizables. Nunca contenido creado para un episodio especÃ­fico.
- **Carpetas de episodio** (`EP##_NOMBRE/`) contienen ÃšNICAMENTE los archivos de producciÃ³n de ese episodio. Nunca instrucciones generales.
- **Nunca crear archivos sueltos** en la raÃ­z de `01_guiones/`, `02_miniaturas/` o `03_titulos/`. Todo va dentro de una subcarpeta.
- **ConvenciÃ³n de nombres de archivos:** `EP##_TIPO_DOCUMENTO.ext` (ej: `EP03_TEXTO_NARRADOR.md`)

### Formatos de Entrega y Contenido por Documento
| Documento | Formatos obligatorios | Contenido Obligatorio |
|-----------|----------------------|-----------------------|
| Guion completo | `.md` | Todo integrado (Narrador + Etiquetas `[VISUAL]` + Notas). |
| Texto para el narrador | `.docx` y `.md` | **100% LIMPIO (Teleprompter).** Solo el texto a leer + indicaciones de tono. Debe incluir la Leyenda de Lectura. **PROHIBIDO** incluir etiquetas visuales. Ver matriz. |
| Indicaciones editor | `.md` | Minuto a minuto visual: b-roll, grÃ¡ficos, memes y SEO. |
| Instrucciones / plantillas | `.md` | Reglas de formato. |

### Paquete Completo por Episodio
Todo episodio debe tener estos archivos antes de ir a producciÃ³n:
1. `EP##_GUION_[TEMA].md` â€” El guion general con la narrativa y la capa visual integradas.
2. `EP##_TEXTO_NARRADOR.docx` â€” **(CRÃTICO)** Documento Word 100% limpio para el teleprompter. **OBLIGATORIO:** Consultar `01_guiones/_plantillas/FORMATO_NARRADOR_MATRIZ.md` antes de crearlo para asegurar el formato y la leyenda correctos en el primer intento.
3. `EP##_TEXTO_NARRADOR.md` â€” VersiÃ³n Markdown del texto limpio.
4. `EP##_INDICACIONES_NARRADOR.md` â€” Tono, ritmo y emociones por secciÃ³n.
5. `EP##_INDICACIONES_EDITOR.md` â€” Archivo exclusivo para el editor (recursos visuales + SEO).

## 7. Uso de vidIQ y CrÃ©ditos
- **LÃ­mite por defecto:** Siempre utilizar las opciones o herramientas de vidIQ que consuman 10 crÃ©ditos.
- **AutorizaciÃ³n:** Para utilizar opciones de 25 crÃ©ditos (o superiores) se debe pausar la tarea y pedir autorizaciÃ³n explÃ­cita al usuario en el chat.

