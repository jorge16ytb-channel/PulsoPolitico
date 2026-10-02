# Reglas de Trabajo: Canal YouTube (Pulso Político)

Este archivo define las reglas obligatorias de empaque, títulos y miniaturas aprendidas de la metodología vidIQ y las preferencias del canal.

## 1. Regla de Oro: Complementariedad Título-Miniatura
- **Nunca duplicar información:** Si el título dice un dato o marco (político, temporal, temático), la miniatura **no** lo repite con sinónimos. Se reparten el trabajo.
- **Desglose del Título:**
  - Marco temático / político -> Título.
  - Urgencia temporal -> Título.
  - Interés personal / Consecuencia ("cómo te afecta / vacía tu bolsillo") -> **Hueco para la miniatura**.
- **Contradicción / Quiebre de expectativa:** Generar conflicto cognitivo. Si el título insinúa un culpable obvio, la miniatura le da la vuelta (ej. *"NO FUE EL GOBIERNO"*).

## 2. Composición de Miniaturas (CTR Alto)
- **Objeto protagónico:** Elementos tangibles cotidianos (recibos, facturas, tickets con precios en rojo) que materialicen el impacto en el bolsillo.
- **Causalidad gráfica:** Mostrar el vínculo entre la causa macro (mapa térmico del océano Pacífico) y el efecto local (la boleta/ticket).
- **Rostros:** Rostro con la expresión adecuada (ej. resignación o incredulidad), ubicado a un costado y mirando al objeto central, sin robarle el protagonismo al objeto.
- **Textos:** Máximo 3 a 4 palabras, alto contraste (blanco con reborde negro o acento amarillo/rojo), legibles en celular.

## 3. Optimización Mobile de Títulos
- **Front-loading:** Colocar el beneficio o dolor directo ("vacía tu bolsillo") en los primeros 45 caracteres antes del corte en feed móvil.
- **Sin palabras muertas:** Eliminar prefijos genéricos como `"Clima:"` o etiquetas vacías al inicio.

## 4. Reglas de Interacción y Modificación del Repositorio
- **Aprobación Previa Obligatoria:** Nunca actualizar, crear ni sobreescribir archivos en los repositorios o carpetas locales de forma automática.
- **Propuesta por Chat:** Toda modificación, guion, idea o ajuste de código debe ser propuesto y discutido en el chat primero. Solo se ejecutarán los cambios en el sistema local cuando el usuario dé una orden explícita para hacerlo.

## 5. Sistema de Archivos y Organización de Carpetas

### Estructura Canónica del Repositorio
```
canal YOUTUBE/
├── 01_guiones/
│   ├── _plantillas/          ← SOLO instrucciones, formatos y plantillas reutilizables
│   └── EP##_NOMBRE_TEMA/     ← Una carpeta por episodio con TODOS sus archivos
├── 02_miniaturas/
│   ├── _plantillas/          ← SOLO instrucciones de diseño y guías de CTR
│   └── EP##_NOMBRE_TEMA/     ← Ideas e imágenes de miniaturas por episodio
├── 03_titulos/
│   └── _plantillas/          ← SOLO instrucciones de títulos y guías de SEO
├── _formacion/               ← Entrenamiento, tesis y ejercicios del gimnasio de ángulos
├── TAREAS_PENDIENTES.md
└── GEMINI.md
```

### Reglas Obligatorias de Organización
- **`_plantillas/`** contiene ÚNICAMENTE instrucciones, formatos y guías reutilizables. Nunca contenido creado para un episodio específico.
- **Carpetas de episodio** (`EP##_NOMBRE/`) contienen ÚNICAMENTE los archivos de producción de ese episodio. Nunca instrucciones generales.
- **Nunca crear archivos sueltos** en la raíz de `01_guiones/`, `02_miniaturas/` o `03_titulos/`. Todo va dentro de una subcarpeta.
- **Convención de nombres de archivos:** `EP##_TIPO_DOCUMENTO.ext` (ej: `EP03_TEXTO_NARRADOR.md`)

### Formatos de Entrega por Tipo de Documento
| Documento | Formatos obligatorios |
|-----------|----------------------|
| Texto para el narrador | `.md` + `.docx` (con negrita/cursiva aplicadas) |
| Guion completo | `.md` |
| Indicaciones narrador | `.md` |
| Indicaciones editor | `.md` |
| Instrucciones / plantillas | `.md` |

### Paquete Completo por Episodio
Todo episodio debe tener estos archivos antes de ir a producción:
1. `EP##_GUION_[TEMA].md` — guion con ayudas integradas
2. `EP##_TEXTO_NARRADOR.md` — solo texto con formato de actuación
3. `EP##_TEXTO_NARRADOR.docx` — ídem en Word para teleprompter/imprimir
4. `EP##_INDICACIONES_NARRADOR.md` — tono, ritmo y emociones por sección
5. `EP##_INDICACIONES_EDITOR.md` — b-roll, gráficos y música por sección
