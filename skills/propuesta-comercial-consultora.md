# Skill: propuesta-comercial-consultora

**Marcas:** Andex Consultora / Nevado Solutions · **Base de formato:** `plantillas/propuesta-base.md`

## Cuándo se activa

La tarea pide "propuesta comercial", o viene encadenada después de una auditoría (`auditoria-digital-pyme` o `auditoria-bodega-mendocina`). Convierte los hallazgos de la auditoría en una oferta formal lista para enviar al prospecto.

## Propósito

Transformar un diagnóstico en una decisión de compra fácil. La propuesta no repite la auditoría: la resume, propone la solución concreta con alcance y precio, y hace obvio el siguiente paso.

## Paso 0 — Datos que necesito antes de empezar

1. Auditoría previa (hallazgos) — es el insumo principal.
2. Marca que emite (Andex o Nevado) → define pie de página, dominio y catálogo de servicios.
3. Qué servicio(s) proponer. Si no está definido, lo recomiendo yo a partir de los hallazgos.
4. Nombre y datos del prospecto.

## Catálogo de servicios y precios (referencia)

| Servicio | Marca | Modalidad | Precio USD |
|---|---|---|---|
| Auditoría digital express | Andex | Único | 80-200 |
| Web SEO optimizada | Andex | Único + recurrencia | 800-1500 + 200-400/mes |
| Research de competencia | Andex | Único | 150-300 |
| Mantenimiento web mensual | Andex | Suscripción | 80-150/mes |
| Auditoría digital bodega | Nevado | Único | 300-600 |
| Bodega Digital 360 | Nevado | Suscripción | 400/mes |

## Proceso

1. **Resumen de hallazgos.** 3-4 líneas: el estado actual y la oportunidad principal, en lenguaje de negocio (plata/clientes), no técnico. Conecta con el dolor del cliente.
2. **Servicio propuesto.** Elegir el/los servicio(s) que resuelven los hallazgos prioritarios. Regla comercial: **empujar hacia al menos un servicio de suscripción** (mantenimiento mensual o Bodega Digital 360), porque la meta del trimestre es ≥1 cliente recurrente al cierre del mes 3. Alcance claro y acotado — qué incluye y qué no.
3. **Precio y modalidad.** Elegir un punto dentro del rango según tamaño del cliente y complejidad. Si conviene, ofrecer 2 opciones (una puntual, una con recurrencia) para anclar. Ser transparente con pago único vs mensual.
4. **Cronograma.** Plazos realistas de entrega por hito. No sobreprometer.
5. **Próximos pasos.** Máximo 3, el primero trivial de aceptar (confirmación por escrito). Bajar la fricción para el "sí".

## Formato de salida

Usar `plantillas/propuesta-base.md` como estructura. Ajustar marca, dominio y pie según Andex/Nevado. Salida lista para pasar a PDF.

## Guardrails

- **Revisión humana obligatoria** antes de enviar al cliente.
- No inventar hallazgos que no estén en la auditoría; la propuesta debe ser trazable al diagnóstico.
- No prometer resultados garantizados. Precio siempre dentro de los rangos del catálogo salvo decisión explícita de Capi.
- El dominio en el pie va como pendiente hasta que estén registrados (ver `decisiones.md`); mientras tanto usar solo el nombre de marca o el email/contacto disponible.
- Entregable va a `andex/clientes/[nombre]/` o `nevado/clientes/[nombre]/` según marca.

## Se alimenta de

- `auditoria-digital-pyme` / `auditoria-bodega-mendocina` (hallazgos previos).
