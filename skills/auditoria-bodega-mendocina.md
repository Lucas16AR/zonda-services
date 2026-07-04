# Skill: auditoria-bodega-mendocina

**Marca:** Nevado Solutions · **Producto:** Auditoría digital bodega · **Precio:** USD 300-600 (pago único)

## Cuándo se activa

La tarea menciona "auditoría" + una bodega o negocio vitivinícola. Se activa **junto con research de competencia en paralelo** (regla de routing del CLAUDE.md). Producto de entrada de Nevado Solutions; base para vender **Bodega Digital 360** (suscripción USD 400/mes).

## Propósito

Auditoría digital especializada para bodegas mendocinas. Ticket más alto que la de PyME genérica porque el rubro tiene canales propios (enoturismo, club de vino, ecommerce de vino, exportación) y márgenes que justifican la inversión.

## Paso 0 — Datos que necesito antes de empezar

1. Nombre de la bodega, valle/zona (Luján de Cuyo, Valle de Uco, Maipú, San Rafael, etc.).
2. Web / tienda online (si vende vino online) y redes (Instagram es el canal rey del rubro).
3. ¿Hace enoturismo? (visitas, degustaciones, restaurante, alojamiento).
4. ¿Tiene club de vino o venta directa a consumidor?
5. ¿Exporta o apunta solo a mercado interno?
6. 2-3 bodegas comparables de la misma zona/segmento para el research.

## Proceso

1. **Web / ecommerce.** ¿Vende online? ¿Carrito funcional, medios de pago, envíos? ¿Ficha de producto por etiqueta/varietal? Si no vende online, es la oportunidad de mayor impacto económico.
2. **Google Business / Maps.** Crítico para enoturismo: horarios de visita, reservas, fotos, reseñas de turistas (muchas en inglés/portugués). Estado y respuesta a reseñas.
3. **Instagram y redes.** Es el escaparate del rubro. Calidad visual, frecuencia, uso de contenido de enoturismo, reels de vendimia/degustación, link a reservas/tienda en bio, coherencia de marca.
4. **Enoturismo.** ¿Se puede reservar una visita online? ¿Está en plataformas (TripAdvisor, agencias, Winerist, etc.)? ¿Idiomas? El turista extranjero es alto valor.
5. **Venta directa / club de vino.** ¿Existe suscripción de vino? ¿Newsletter? ¿Base de clientes propia? La venta directa es el mayor margen del rubro.
6. **Research de competencia (en paralelo).** 2-3 bodegas comparables de la misma zona/segmento: qué canales dominan, qué hacen mejor, dónde hay hueco. Este research se entrega como sección del informe.
7. **Priorización.** 3-5 recomendaciones por impacto/esfuerzo, con foco en los canales de mayor margen (venta directa, enoturismo, ecommerce).

## Formato de salida

Informe entregable (2-3 páginas, más presentable que el de PyME por el ticket):

```
# Auditoría digital — Bodega [Nombre]
Nevado Solutions · [valle] · [fecha]

## Resumen ejecutivo
## Diagnóstico
1. Web / ecommerce
2. Google Business / enoturismo
3. Instagram y redes
4. Venta directa / club de vino
5. Research de competencia ([bodega A], [bodega B], [bodega C])
## Recomendaciones priorizadas (tabla impacto/esfuerzo)
## Próximo paso: Bodega Digital 360
```

## Guardrails

- **Riesgo regulatorio:** esto es exclusivamente digital/marketing. **No** incluir recomendaciones de inversión, asesoramiento financiero, ni proyecciones de rentabilidad de la bodega como negocio. Hablar de canales digitales, no de finanzas.
- No dar consejo sobre publicidad de alcohol que contradiga regulación (no apuntar a menores, etc.) — mantener recomendaciones dentro de buenas prácticas del rubro.
- **Revisión humana obligatoria** antes de entregar.
- Entregable va a `nevado/clientes/[nombre-bodega]/`.
- Honestidad en el diagnóstico: el semáforo rojo/amarillo/verde debe reflejar la realidad.

## Encadena con

- `propuesta-comercial-consultora` — para presentar Bodega Digital 360 como oferta formal.
