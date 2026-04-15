# PROMPT DE CORRECCIONES — PITCH DECK PROPER v2
## 4 correcciones específicas por slide

---

A continuación te indico con precisión qué cambiar en cada diapositiva del deck
que ya generaste. Mantén TODO lo que no se menciona exactamente igual.

---

## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## SLIDE 1 — COVER
## Dos correcciones
## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### CORRECCIÓN 1-A — Ampliar fila de stats (agregar Proper Rentas)

**Qué hay actualmente:**
Fila horizontal con 3 stats en naranja `#FF7B0F`:
`+1,000 inversionistas activos  |  +25% TIR anual promedio  |  +7% retorno anual flujo de caja`

**Qué debe quedar:**
Esa misma fila ahora tiene DOS grupos separados por un divisor visual claro.

**GRUPO IZQUIERDO — Proper Inversión** (mantener exactamente igual, naranja `#FF7B0F`):
```
+1,000               +25%                +7%
departamentos        TIR anual           retorno en
vendidos             promedio            flujo de caja
```
Números: 32pt, weight 800, naranja `#FF7B0F`
Labels: 11pt, `#8892AE`

**Divisor central:**
Línea vertical de 48px de alto, `rgba(255,255,255,0.2)`, 1px, con un pequeño espacio de 32px a cada lado

**GRUPO DERECHO — Proper Rentas** (NUEVO, color verde `#00C17A`):
```
+800                 USD 3.5MM           +2X
departamentos        en rentas           crecimiento
en gestión           pagadas/año         al año
```
Números: 32pt, weight 800, **verde `#00C17A`**
Labels: 11pt, `#8892AE`
Nota pequeña a la derecha del grupo: `B2B y B2C` (10pt, `rgba(255,255,255,0.35)`, italic)

**Regla del divisor entre grupos:**
Entre el GRUPO IZQUIERDO y el GRUPO DERECHO agrega un separador más prominente:
— Línea vertical de 60px, color `rgba(255,255,255,0.15)`, 2px de ancho
— O bien un pequeño label centrado vertical entre los dos grupos: `·` (punto grande, `rgba(255,255,255,0.3)`)

---

### CORRECCIÓN 1-B — Reemplazar sección "Respaldado por"

**Qué hay actualmente:**
Franja con texto `Respaldado por  HPC PADOVA · LAMEZCLADORA · PERÚPROPTECH`

**Eliminar completamente** esa franja.

**Reemplazar con esta nueva franja** en el mismo espacio (fondo `rgba(255,255,255,0.05)`, border-radius 12px, padding 14px 28px):

Texto izquierda: `Validado por` (11pt, weight 500, `#8892AE`)

Luego, en la misma línea horizontal, tres logos con saturación reducida al 20% (efecto casi-grayscale, opacity 60%):

**Logo 1 — ProInnóvate:**
URL: `https://www.gob.pe/rails/active_storage/representations/redirect/eyJfcmFpbHMiOnsiZGF0YSI6MTg1NjEzLCJwdXIiOiJibG9iX2lkIn19--8bb017cef8af25bc03dbe498b196016b3d2877d3/eyJfcmFpbHMiOnsiZGF0YSI6eyJmb3JtYXQiOiJwbmciLCJyZXNpemVfdG9fbGltaXQiOltudWxsLDQ4XX0sInB1ciI6InZhcmlhdGlvbiJ9fQ==--830247c4bafe7cadca50817d8559bf1a09e3aa28/Colores-cofinanciado_color.png`
Altura: 28px. Aplicar CSS: `filter: saturate(0.15) brightness(1.8)` para que se vea casi blanco/gris claro sobre el fondo oscuro.
Si la URL falla, escribir el texto `ProInnóvate` en 12pt, weight 600, `rgba(255,255,255,0.45)`

**Separador:** punto · color `rgba(255,255,255,0.2)`

**Logo 2 — UTEC:**
URL: `https://utec.edu.pe/sites/default/files/2023-09/logo_0.svg`
Altura: 24px. Aplicar CSS: `filter: brightness(10) saturate(0)` para que se vea blanco limpio sobre fondo navy.
Si la URL falla, escribir el texto `UTEC` en 12pt, weight 600, `rgba(255,255,255,0.45)`

**Separador:** punto ·

**Logo 3 — ASEI:**
URL: `https://asei.com.pe/wp-content/uploads/2023/10/LogoVertical_ASEI_original.png`
Altura: 28px. Aplicar CSS: `filter: saturate(0) brightness(2)` para efecto gris claro/blanco.
Si la URL falla, escribir el texto `ASEI` en 12pt, weight 600, `rgba(255,255,255,0.45)`

**Instrucción de fallback para los 3 logos:**
Si no puedes cargar las imágenes por restricciones de red, usa texto en su lugar:
`ProInnóvate  ·  UTEC  ·  ASEI`
Todo en 12pt, weight 600, `rgba(255,255,255,0.45)`, espaciado uniforme.
En ese caso, al texto "ProInnóvate" dale color `rgba(255,180,0,0.5)` (referencia al color dorado/naranja de su logo), "UTEC" en `rgba(0,191,255,0.5)` (referencia a su azul cielo), "ASEI" en `rgba(255,255,255,0.45)`.

---

## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## SLIDE 4 — ECOSISTEMA
## Una corrección
## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### CORRECCIÓN 4-A — Card 04: Proper Rentas → Property Management

**Qué hay actualmente en Card 04:**
- Ícono llave en círculo azul `#EBF0FC`
- Número de paso: `04`
- Título: `Proper Rentas`
- Cuerpo: `Conseguimos el inquilino, cobramos la renta y administramos todo. Tú solo recibes el depósito cada mes.`
- Chip: `Plataforma 100% digital`

**Qué debe quedar en Card 04:**
- Ícono llave en círculo **verde** `#00C17A` (cambiar color del círculo de azul a verde)
- Número de paso: `04` (mantener)
- Título: **`Property Management con Proper Rentas`**
  (mantener 20pt, weight 800, `#0F172A`)
- Cuerpo: mantener exactamente igual
- Chip: cambiar fondo a `rgba(0,193,122,0.12)`, texto `#00965F`: `Plataforma 100% digital`

**Nota:** El color verde `#00C17A` es el color de marca de Proper Rentas. Debe diferenciarse visualmente de las cards naranjas (01 y 03) y de la azul (02), marcando que es una unidad de negocio distinta.

---

## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## SLIDE 5 — TRACCIÓN
## Una corrección (rediseño de la columna izquierda)
## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### CORRECCIÓN 5-A — Separar métricas en dos negocios

**Qué hay actualmente:**
Columna izquierda con grid 2×3 mezclado, todos los números en naranja, badge "TRACCIÓN REAL" arriba y título "Números que hablan solos."

**La columna derecha (proyectos Perseo/Orue/Prolongación) NO CAMBIA.**

**Qué debe quedar en la columna izquierda:**

Eliminar el grid 2×3 actual completamente. Reemplazar con esta estructura:

---

**Badge superior:** `TRACCIÓN REAL` (mantener igual)

**Título:** `Dos negocios.` (40pt, ExtraBold, `#0F172A`, letter-spacing -1.5px)
`Un ecosistema.` (40pt, ExtraBold, `#0F172A`)

Subtítulo (13pt, `#4B5574`):
`Proper Inversión y Proper Rentas operan de forma`
`integrada, con métricas independientes.`

Espacio: 24px

---

**BLOQUE 1 — PROPER INVERSIÓN**
Card contenedora: fondo blanco, border-radius 16px, padding 20px 24px, sombra suave, borde izquierdo 4px sólido naranja `#FF7B0F`

Label de sección (dentro de la card):
`🏠 PROPER INVERSIÓN` (10pt, weight 700, `#FF7B0F`, uppercase, letter-spacing 1.5px)

Grid interno 1×3 horizontal (tres stats en fila):

Stat 1:
`+1,000` (32pt, weight 800, `#FF7B0F`)
`departamentos vendidos` (11pt, `#4B5574`)
`~ USD 100MM` (10pt, weight 600, `#8892AE`)

Separador: línea vertical 1px `#EBF0FC`

Stat 2:
`+20` (32pt, weight 800, `#FF7B0F`)
`desarrolladores inmobiliarios` (11pt, `#4B5574`)
`en la plataforma` (10pt, `#8892AE`)

Separador: línea vertical 1px `#EBF0FC`

Stat 3:
`25% / 7%` (32pt, weight 800, `#FF7B0F`)
`TIR anual / flujo de caja` (11pt, `#4B5574`)
`retorno promedio` (10pt, `#8892AE`)

---

Espacio: 16px

---

**BLOQUE 2 — PROPER RENTAS**
Card contenedora: fondo blanco, border-radius 16px, padding 20px 24px, sombra suave, borde izquierdo 4px sólido verde `#00C17A`

Label de sección:
`🔑 PROPER RENTAS` (10pt, weight 700, `#00C17A`, uppercase, letter-spacing 1.5px)

Grid interno 1×3 horizontal:

Stat 1:
`+800` (32pt, weight 800, `#00C17A`)
`departamentos en gestión` (11pt, `#4B5574`)
`B2B y B2C` (10pt, `#8892AE`)

Separador: línea vertical 1px `#EBF0FC`

Stat 2:
`USD 3.5MM` (32pt, weight 800, `#00C17A`)
`en rentas pagadas` (11pt, `#4B5574`)
`cada año` (10pt, `#8892AE`)

Separador: línea vertical 1px `#EBF0FC`

Stat 3:
`+2X` (32pt, weight 800, `#00C17A`)
`crecimiento` (11pt, `#4B5574`)
`año a año` (10pt, `#8892AE`)

---

**Nota de pie** (fuera de las cards, 11pt, `#8892AE`, italic):
`5 años de operación · Lima, Perú`

---

## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## SLIDE 6 — MODELO & MERCADO
## Una corrección
## ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

### CORRECCIÓN 6-A — Actualizar card de competencia

**Qué hay actualmente** en la card navy (esquina inferior derecha de la columna de mercado):
```
🌐  Sin competidor regional directo en inversión inmobiliaria retail.
    Capitalizarme opera solo en Perú y Colombia a menor escala.
```

**Eliminar ese texto.**

**Reemplazar con este contenido** (misma card, mismo estilo visual, mismo fondo navy `#162040`, mismo borde-radius):

Ícono globo naranja (mantener)

Título de la card (15pt, weight 700, blanco):
`Referentes por país, sin escala regional:`

Luego tres líneas de texto (14pt, Regular, `#8892AE`):

Línea 1: punto bullet naranja `•` + `Capitalizarme y Assetplan` (blanco, weight 600) + ` en Chile`
Línea 2: punto bullet naranja `•` + `LaHaus` (blanco, weight 600) + ` en Colombia y México`
Línea 3: punto bullet naranja `•` + `Quinto Andar` (blanco, weight 600) + ` en Brasil`

Línea final (14pt, weight 700, naranja `#FF7B0F`, con pequeño espacio superior):
`Ninguno opera a escala LATAM. Proper lo hace.`

---

## RESUMEN DE CAMBIOS

| Slide | Qué cambia |
|-------|-----------|
| **1** | Stats: agrega grupo verde (Proper Rentas) a la derecha de los stats naranja |
| **1** | Footer: "Respaldado por" → "Validado por" con logos ProInnóvate, UTEC, ASEI desaturados |
| **4** | Card 04: título "Property Management con Proper Rentas" + círculo ícono verde |
| **5** | Grid de métricas → dos cards separadas: Proper Inversión (naranja) + Proper Rentas (verde) |
| **6** | Card competencia: lista con Capitalizarme/Assetplan, LaHaus, Quinto Andar por país |

## LO QUE NO CAMBIA
Slides 2, 3 y 7 permanecen exactamente igual.
Columna derecha de Slide 5 (proyectos Perseo/Orue/Prolongación) permanece exactamente igual.
Tabla Sin Proper / Con Proper de Slide 6 permanece exactamente igual.
Todo el sistema de diseño (fuentes, colores base, márgenes, logo) permanece exactamente igual.

## COLOR NUEVO: PROPER RENTAS
`#00C17A` — Verde esmeralda (color de marca Proper Rentas)
`#00965F` — Verde oscuro (variante para chips y estados activos)
`rgba(0,193,122,0.12)` — Verde suave para fondos de chips
Este verde fue elegido para armonizar con el navy `#162040` y el naranja `#FF7B0F`
sin crear conflicto visual. Es vibrante, moderno y diferenciador.
