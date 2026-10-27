# Storyboard: Reel "Plan Fiestas con HIFU"

Publicación: jueves 5 de noviembre · Clínica estética, Quito

## 1. Overview

| Campo | Valor |
|---|---|
| Duración | 38 s (1140 frames) |
| Formato | 1080x1920 vertical, 30 fps |
| Voz | Locución en off de la especialista (voz cálida, tono bajo, ritmo ~2.5 palabras/s) + subtítulos palabra por palabra |
| Estilo | Editorial cálido y sereno. Luz de ventana, tonos crema/arena, movimientos lentos de cámara |
| Mood | Seguridad, calma, confianza. Nada de urgencia agresiva ni dramatismo |
| Segmento | Mujer 40-55, profesional, norte de Quito, con eventos de fin de año |
| Código reptil | Seguridad + trascendencia |
| Miedo a desactivar | Verse cansada o que se note que "se hizo algo" |

**Reglas de contenido (no negociables)**
- Sin antes y después, ni comparativas de rostro.
- Sin promesas de resultado: nada de "rejuvenece", "X años menos", "garantizado".
- Sin términos médicos íntimos ni imágenes del equipo apoyado sobre la piel.
- Que el cambio sea siempre "gradual y natural" y que la decisión sea de ella.

## 2. Arco narrativo

```
Gancho (0-10 s)    → Tensión suave: "empiezas tarde", pero sin culparla
Empatía (10-20 s)  → Validar el miedo a "verse hecha" y darle la vuelta
Razón (20-31.5 s)  → Metáfora de la casa + "empezar ahora = gradual"
CTA (31.5-38 s)    → Valoración gratis, escribir HIFU
```

El gancho debe funcionar en los primeros 3 s sin sonido: texto grande y rostro natural en pantalla desde el frame 0.

## 3. Audio

**Música**: piano suave con pads cálidos, ~78 BPM, sin letra. Volumen 14% bajo la voz, 28% en los silencios.
- 0-10 s: solo pad y notas espaciadas.
- 10-20 s: entra una segunda capa (cuerdas muy suaves) en el beat del segundo 10.
- 20-31.5 s: la música "abre" (más cuerpo) al llegar la metáfora de la casa.
- 31.5-38 s: resuelve en acorde mayor; fade-out de 1.5 s desde el segundo 36.5.
- Ducking de -8 dB siempre que hable la locución.

**Efectos de sonido (sutiles, 30-40%)**

| Tiempo | SFX | Propósito |
|---|---|---|
| 0.0 s | Respiración suave + room tone de baño/tocador | Intimidad inmediata |
| 1.5 s | Pasar de página de calendario (papel) | Marca "diciembre" |
| 5.0 s | Tick sordo de reloj, una sola vez | "Se trabaja con tiempo" |
| 11.0 s | Susurro de tela / pausa en silencio de 0.4 s | Peso emocional de "hecha" |
| 14.5 s | Pop suave (burbuja de mensaje) | Cumplido de la amiga |
| 17.0 s | Click suave de taza o carpeta sobre mesa | Entra a la consulta, escena de calma |
| 21.0 s | Whoosh bajo en la transición a la casa | Cambio a metáfora |
| 24.5 s | Chime cálido (capa profunda "se ilumina") | Foco en "capa profunda" |
| 28.5 s | Riser muy leve de 2 s | Anticipa el CTA |
| 32.5 s | Tecleo suave en celular | Escribe HIFU |
| 34.0 s | Pop de envío de mensaje | Acción completada |
| 35.0 s | Ding suave | Resolución |

## 4. Escenas

### Escena 1: Gancho A, el espejo (0.0-5.0 s, frames 0-150)

**Guion (voz)**: "Si quieres llegar a diciembre sintiéndote segura frente al espejo, la mayoría empieza tarde."

**Plano**: medio, ligeramente contrapicado, mujer de ~45 años frente a un espejo de tocador. Luz lateral de ventana, blusa crema. Expresión tranquila, mirada al espejo (no a cámara). Rostro natural, sin maquillaje evidente.

**Elementos en pantalla**
- Texto principal (frames 6-40): "Llegar a diciembre segura frente al espejo", Poppins 800, 78 px, blanco crema `#FFF8F0`, 3 líneas, zona segura superior (y ≈ 260 px). Sombra suave.
- Palabra "segura" resaltada en dorado `#C9A66B` (frame 22).
- Calendario (frames 45-70): hoja de "NOVIEMBRE" que se pasa a "DICIEMBRE" con eventos pequeños (cena de empresa, fotos familiares) en la esquina inferior derecha, 220 px de ancho.
- Subtítulos palabra por palabra (WordByWordCaption) en el tercio inferior, fuera de la zona de UI de Reels (margen inferior 380 px).

**Animación**
- Cámara: push-in lento de 100% a 106% (interpolate, easeOut).
- Texto: slideUp con spring (damping 14, stiffness 120), stagger de 6 frames por línea.
- Calendario: rotación 3D leve al pasar hoja, 20 frames.

**Timing**
- 0-6: rostro entra con fade desde crema (0→1). El gancho ya es legible a los 0.5 s.
- 6-40: aparece el titular.
- 45-70: pasa la hoja del calendario.
- 70-130: hold con push-in.
- 130-150: texto sale (fade + 10 px hacia arriba, más rápido que la entrada).

**Foco**: titular → "segura" dorada → calendario.
**Transición**: corte con match de movimiento hacia plano detalle del calendario.

---

### Escena 2: Gancho B, "no es culpa tuya" (5.0-10.0 s, frames 150-300)

**Guion**: "No es culpa tuya: nadie te contó que el colágeno se trabaja con tiempo."

**Plano**: plano detalle de manos hojeando una agenda abierta en noviembre/diciembre; fondo desenfocado de ventana. Alterna a plano corto de ella sonriendo levemente (alivio).

**Elementos**
- Texto grande (frame 160): "No es culpa tuya" Poppins 700, 84 px, centrado. Subtexto (frame 195): "nadie te contó que el colágeno se trabaja con tiempo" 44 px, 80% opacidad.
- Línea de tiempo minimalista (frames 210-285): una línea fina dorada que crece de izquierda a derecha entre "HOY" y "DIC". Sin porcentajes ni cifras.

**Animación**
- "No es culpa tuya" aparece con blur→nítido (12→0 px, 14 frames).
- Línea de tiempo se dibuja con `interpolate` (easeInOut), 60 frames.
- Cámara: paneo horizontal lento de la agenda, 3% de desplazamiento.

**Audio**: tick de reloj en 5.0 s, silencio de la música por 0.3 s antes de "No es culpa tuya" y vuelve el pad en 5.3 s.
**Foco**: "No es culpa tuya" (sensación de alivio) → línea de tiempo.
**Transición**: crossfade de 10 frames hacia la escena 3.

---

### Escena 3: Empatía A, el miedo (10.0-13.5 s, frames 300-405)

**Guion**: "Es normal que te preocupe verte distinta o 'hecha'."

**Plano**: primer plano medio de ella mirándose al espejo, ligera inclinación de cabeza; toca suavemente su mejilla con la yema de los dedos (sin dispositivo ni gesto clínico). Luz un poco más fría y baja de contraste, para dar un matiz de duda.

**Elementos**
- Texto: "verte distinta" (frame 310) y "hecha" (frame 340) entre comillas, Playfair Display 600 itálica, 72 px.
- Las comillas de "hecha" se desvanecen y la palabra baja a 40% de opacidad al finalizar la frase, para sugerir que se suelta ese miedo.

**Animación**: tipografía con fade + escala 0.96→1 (spring suave, damping 200). Cámara estática con micro-respiración de 0.5%.
**Audio**: pausa de 0.4 s antes de "hecha" (SFX tela). Música baja a 8%.
**Foco**: rostro → palabra "hecha".
**Transición**: corte seco al plano de la amiga.

---

### Escena 4: Empatía B, el cumplido (13.5-17.0 s, frames 405-510)

**Guion**: "La idea es lo contrario: que te digan qué descansada te ves."

**Plano**: dos mujeres en un café/evento de oficina, luz cálida, bokeh dorado al fondo. La amiga se dirige a ella con una sonrisa. Cámara sobre el hombro, ella responde con una sonrisa relajada.

**Elementos**
- Burbuja de mensaje sobre la amiga (frame 440), estilo tipografía suave, con el texto "¡Qué descansada te ves!", fondo `#FFFFFF` al 92%, radio 28 px.
- Texto de apoyo: "lo contrario" en dorado (frame 410).
- Partículas bokeh (ParticleField, 20 partículas, `rgba(201,166,107,0.35)`, velocidad 0.3).

**Animación**: burbuja con spring (damping 14), entra con escala 0.8→1 y leve rotación -2°→0. Cámara con dolly-in del 3%.
**Audio**: pop suave al aparecer la burbuja (14.5 s); sube un poco el ambiente de oficina/café (20%).
**Foco**: burbuja → sonrisa de ella.
**Transición**: match cut por color cálido hacia la consulta.

---

### Escena 5: Empatía C, "te explicamos todo" (17.0-20.0 s, frames 510-600)

**Guion**: "Y antes de hacer cualquier cosa, te explicamos todo."

**Plano**: consulta luminosa. La especialista (bata blanca discreta, sin equipo a la vista) frente a la paciente, con una tablet o carpeta de opciones abierta sobre el escritorio. Contacto visual, gestos abiertos. Planos de 2 personas en 3/4.

**Elementos**
- Texto (frame 520): "Antes de hacer cualquier cosa, te explicamos todo" en 2 líneas, Poppins 700, 64 px.
- Icono de check dorado al lado de "te explicamos todo" (frame 560).

**Animación**: texto slideLeft suave; check con spring (stiffness 180). Cámara estática, rack focus de la mano de la especialista a su rostro (12 frames).
**Audio**: click de carpeta, ambiente de consulta muy bajo.
**Foco**: especialista → check.
**Transición**: whoosh y *wipe* vertical cálido (crema) hacia la metáfora.

**Nota para el rodaje (neurotip)**: grabar a la especialista diciendo en cámara la frase de cabina *"Me contaste que quieres verte natural; empecemos por ahí"*, con contacto visual y tono bajo. Úsala como b-roll sin audio o como escena opcional de 1.5 s.

---

### Escena 6: Razón A, la casa (20.0-27.5 s, frames 600-825)

**Guion**: "El HIFU trabaja en la capa profunda que sostiene el rostro, como reforzar los cimientos de una casa sin tocar la pintura."

**Visual**: motion graphics en 2D sobre fondo crema `#F6EFE6`. Una casa en corte lateral estilizada (líneas finas, sin realismo).
- Capa superior = "pintura": fachada de color suave (`#E8C9B0`).
- Capa inferior = "cimientos": bloques base en gris cálido `#B9A99A`.

**Animación detallada**
- 600-640: la fachada aparece con un trazo de línea (stroke dashoffset).
- 640-700: el texto "capa profunda" (Poppins 800, 70 px) aparece sobre los cimientos; los bloques se iluminan en dorado `#C9A66B` uno a uno (stagger 6 frames).
- 700-780: la cámara hace un *tilt* hacia abajo hasta los cimientos mientras la fachada se mantiene intacta; etiqueta "sin tocar la pintura" aparece con fade en la fachada.
- 780-825: pull-back para mostrar la casa completa, tranquila y estable.

**Reglas**: no mostrar una cara con capas anatómicas ni láminas médicas. Todo es metáfora.
**Audio**: whoosh de entrada (21.0 s); chime cálido en 24.5 s cuando los cimientos se iluminan. Música en su punto más abierto.
**Foco**: cimientos dorados → "capa profunda".
**Transición**: la casa se desvanece y entra la línea de tiempo.

---

### Escena 7: Razón B, empezar ahora (27.5-31.5 s, frames 825-945)

**Guion**: "Empezar ahora le da tiempo al cambio para ser gradual y natural."

**Visual**: calendario de noviembre-diciembre en vista plana, con tres hitos pequeños (eventos de fin de año) y una curva suave que asciende con suavidad, sin números ni porcentajes.
- Etiquetas: "HOY" (frame 830), "Fiestas" (frame 900).
- Texto principal: "gradual y natural" Playfair Display 700, 76 px (frame 850), con "natural" subrayado dorado dibujado a mano.
- Pequeño plano de ella en la calle con abrigo, relajada, en un inserto de 1 s (frames 900-930), sin primeros planos del rostro que sugieran "resultado".

**Animación**: curva dibujada con easeInOut (60 frames); subrayado con trazo (18 frames); calendario con parallax leve.
**Audio**: riser muy suave desde 28.5 s.
**Foco**: "gradual y natural" → "HOY".
**Transición**: la curva se transforma en la burbuja de mensaje del CTA (match cut de forma).

---

### Escena 8: CTA, valoración gratis (31.5-35.0 s, frames 945-1050)

**Guion**: "Tu valoración es gratis: escríbenos HIFU."

**Visual**: fondo crema. Interfaz de mensajería genérica (sin marcas de terceros) con un campo de texto donde se teclea la palabra **HIFU**. Debajo, botón "Enviar mensaje" en dorado.
- Titular (frame 950): "Tu valoración es gratis" Poppins 800, 80 px, color `#3B2F2A`.
- Palabra clave (frame 985-1010): "HIFU" tecleada en mayúsculas, Poppins 800, 110 px, resaltada en una píldora dorada.
- Subtexto (frame 1015): "Sin compromiso".

**Animación**: titular con scale-in (spring); tecleo con TypewriterText, 3 frames por letra; botón con pulso suave (escala 1→1.04, 2 ciclos).
**Audio**: tecleo en 32.5 s, pop de envío en 34.0 s, ding suave a 35.0 s.
**Foco**: "HIFU" → botón.
**Transición**: fade a end card.

---

### Escena 9: End card (35.0-38.0 s, frames 1050-1140)

**Visual**: fondo crema con textura sutil. Logo de la clínica centrado (sustituir por logo real), debajo: "Valoración gratis · Shyris y República, Quito". Flecha o icono discreto de mensaje.
**Animación**: logo con fade + escala 0.95→1 (20 frames); texto de ubicación a 8 frames de diferencia.
**Audio**: música resuelve en acorde mayor, fade-out desde 36.5 s (1.5 s).
**Hold**: 2 s completos sin movimiento para que se lea.

## 5. Especificaciones técnicas (Remotion)

**Composición**: `PlanFiestasHIFU`, 1080x1920, 30 fps, 1140 frames. Registrar en `src/Root.tsx`.

**Estructura sugerida**
```
<AbsoluteFill>
  <Series>
    <Series.Sequence durationInFrames={150}> <Scene1Mirror/> </Series.Sequence>
    <Series.Sequence durationInFrames={150}> <Scene2NoEsCulpa/> </Series.Sequence>
    <Series.Sequence durationInFrames={105}> <Scene3Miedo/> </Series.Sequence>
    <Series.Sequence durationInFrames={105}> <Scene4Cumplido/> </Series.Sequence>
    <Series.Sequence durationInFrames={90}>  <Scene5Explicamos/> </Series.Sequence>
    <Series.Sequence durationInFrames={225}> <Scene6Casa/> </Series.Sequence>
    <Series.Sequence durationInFrames={120}> <Scene7Gradual/> </Series.Sequence>
    <Series.Sequence durationInFrames={105}> <Scene8CTA/> </Series.Sequence>
    <Series.Sequence durationInFrames={90}>  <Scene9EndCard/> </Series.Sequence>
  </Series>
  <CaptionOverlay .../>   {/* subtítulos palabra por palabra */}
  <AudioTrack .../>       {/* música con ducking */}
</AbsoluteFill>
```
Total: 150+150+105+105+90+225+120+105+90 = **1140** frames.

**Componentes del proyecto a reutilizar**: `VideoClip`, `FitImage`, `AnimatedTitle`, `WordByWordCaption` / `CaptionOverlay`, `ParticleField`, `TypewriterText`, `AudioTrack`, `SafeArea`.

**Paleta**

| Uso | Hex |
|---|---|
| Fondo crema | `#F6EFE6` |
| Texto claro | `#FFF8F0` |
| Texto oscuro | `#3B2F2A` |
| Dorado de acento | `#C9A66B` |
| Piel/rosa suave | `#E8C9B0` |
| Gris cálido | `#B9A99A` |

**Tipografía**: Poppins (titulares y CTA), Playfair Display (palabras clave emotivas). Cargar con `loadGoogleFont`.

**Springs**: entradas de texto `damping 14, stiffness 120`; elementos suaves `damping 200`; botón/check `stiffness 180`.

**Zonas seguras (Reels)**: dejar libres 250 px arriba y 380 px abajo para la interfaz; subtítulos a ~y=1380-1480.

**Subtítulos**: siempre activos (mucho consumo sin sonido). Resaltar en dorado la palabra activa. Máx. 3-4 palabras por línea.

**Assets necesarios**
- Rodaje: mujer 40-55 años en tocador/espejo; amiga en entorno social; consulta con especialista (sin equipo a la vista); calle con abrigo. Todo con luz natural cálida.
- Locución en off grabada por la especialista.
- Música instrumental con licencia y los SFX de la tabla.
- Logo de la clínica en PNG transparente.

## 6. Cumplimiento y riesgos

- **Segmentación por atributos personales**: el gancho habla de sentimientos ("verte cansada"). Para el anuncio pagado conviene formular en positivo ("llegar segura") y evitar afirmar que la persona tiene un problema. El texto actual ya va por ahí.
- **Sin resultados**: "gradual y natural" describe el enfoque, no promete un resultado. Mantener el aviso "Los resultados varían" si la plataforma o la normativa lo piden.
- **Sin antes y después**: el cumplido de la amiga es una escena ilustrativa y no debe usarse como testimonio de un tratamiento.
- **Modelos**: usar autorización de imagen firmada de las personas que aparezcan.
- **Música y logo**: confirmar licencias.

## 7. Checklist de calidad

- [x] Gancho visible y comprensible en 3 s, también sin audio
- [x] Jerarquía visual clara en cada escena
- [x] Ritmo: ninguna escena supera 7.5 s sin cambio visual
- [x] Audio de apoyo con ducking en voz
- [x] Arco: gancho → empatía → razón → CTA
- [x] CTA único y claro (escribir HIFU)
- [x] Sin antes/después ni promesas

## 8. Relación con las ideas 2 y 3

- **Idea 2 (anuncio de mensajes)**: usará una versión de 15-20 s de este reel. Propuesta de cortes: escenas 1 (recortada a 3 s con gancho "Antes de gastar en un tratamiento, conversa con quien lo va a hacer"), 5, 6 abreviada, 8 y 9. Se puede desarrollar su storyboard aparte.
- **Idea 3 (recorrido de WhatsApp)**: el mensaje llegó cortado en "el precio, el dolor y la duda de no saber por dónde empezar". Falta el resto del guion.
