# Skill: auditoria-digital-pyme

**Marca:** Andex Consultora · **Producto:** Auditoría digital express · **Precio:** USD 80-200 (pago único)

## Cuándo se activa

La tarea menciona "auditoría" + un negocio genérico (retail, gastronomía, turismo, hotelería, servicios profesionales, etc.) que **no** sea bodega/vitivinícola. Si es bodega → usar `auditoria-bodega-mendocina`.

## Propósito

Producir una auditoría digital express: un diagnóstico corto y accionable del estado digital de una PyME. Es el producto de entrada de Andex: barato, rápido de entregar, y diseñado para **abrir la puerta a la venta** de web SEO o mantenimiento mensual.

## Paso 0 — Datos que necesito antes de empezar

Si falta alguno, pedírselo al usuario (Capi) antes de generar el informe:

1. Nombre del negocio y rubro.
2. Ciudad / zona de operación (clave para SEO local).
3. URL de la web (si tiene) y links de redes (Instagram, Facebook, Google Business).
4. 2-3 competidores directos conocidos (si Capi los tiene; si no, los identifico yo).
5. Objetivo del cliente si se conoce (más reservas, más ventas online, más visibilidad local, etc.).

## Proceso

1. **Web actual.** ¿Existe? ¿Carga rápido? ¿Es responsive (móvil)? ¿Tiene llamada a la acción clara (WhatsApp, reserva, compra)? ¿Datos de contacto visibles? Si no tiene web, señalarlo como oportunidad #1.
2. **Google Business Profile / Maps.** ¿Está reclamado? ¿Datos completos (horario, teléfono, fotos)? ¿Reseñas? ¿Responde reseñas? Es el mayor driver de clientes locales y suele estar abandonado.
3. **SEO local básico.** ¿Aparece al buscar "[rubro] + [ciudad]"? ¿Título/descripción de la web tienen la ciudad y el servicio? Coherencia de NAP (nombre, dirección, teléfono) en la web y Google.
4. **Redes sociales.** ¿Cuáles usa? ¿Frecuencia de publicación? ¿Bio con link y contacto? ¿Coherencia de marca? No cantidad de seguidores por sí sola, sino uso comercial real.
5. **Benchmark de competencia.** Comparación rápida con 2-3 competidores directos: qué tienen ellos que el cliente no (web, ecommerce, Google, contenido). Sirve para crear urgencia sin inventar.
6. **Priorización.** 3-5 recomendaciones ordenadas por impacto/esfuerzo. Cada una con: qué hacer, por qué importa (en plata o clientes), y esfuerzo estimado (bajo/medio/alto).

## Formato de salida

Informe de 1-2 páginas, tono claro y sin jerga técnica, orientado a dueño de PyME:

```
# Auditoría digital express — [Negocio]
Andex Consultora · [fecha]

## Resumen ejecutivo
[3-4 líneas: dónde está parado hoy y la oportunidad más grande]

## Diagnóstico
1. Web
2. Google Business / Maps
3. SEO local
4. Redes sociales
5. Comparación con competencia

(cada punto: estado actual → semáforo 🔴🟡🟢 → comentario breve)

## Recomendaciones priorizadas
| # | Acción | Impacto | Esfuerzo |
|---|--------|---------|----------|

## Próximo paso sugerido
[Gancho hacia web SEO o mantenimiento mensual — sin ser agresivo]
```

## Guardrails

- **Revisión humana obligatoria** antes de entregar al cliente (human-in-the-loop, sección 5.7 del manual).
- No prometer resultados garantizados ("vas a duplicar ventas") — hablar de oportunidades e impacto estimado.
- El semáforo debe ser honesto: si algo está bien, decirlo. Un informe que es todo rojo pierde credibilidad.
- Entregable va a `andex/clientes/[nombre-cliente]/`.
- El objetivo comercial es real pero secundario: primero valor genuino, después el gancho.

## Encadena con

- `propuesta-comercial-consultora` — para convertir los hallazgos en oferta formal.
