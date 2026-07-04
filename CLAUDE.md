# CLAUDE.md — División 1: Zonda Services (Quantix)

## Propósito

**Nombre comercial de la división (decidido 2026-07-02): Zonda Services.**

División de servicios del holding Quantix. Es el corazón operativo: la única división que genera caja desde el mes 1. Financia el desarrollo del resto de las divisiones (Productos financieros, Atuel Insights, Productización).

Opera con dos submarcas/productos:

- **Andex Consultora** — consultora general para PyMEs: auditoría digital express, web SEO, research de competencia, mantenimiento web mensual.
- **Nevado Solutions** — vertical bodegas mendocinas: Bodega Digital 360 (suscripción premium), auditoría digital bodega mendocina.

Dominios: `andexconsultora.com.ar` y `nevadosolutions.com.ar` (en proceso de registro, ver `decisiones.md`).

## Estado actual

Prioridad #1 absoluta del holding. Semana 1 del plan de 90 días en curso (ver snapshot sección 5). Sin clientes todavía — fase de setup de identidad y herramientas.

## Servicios / productos que incluye

| Servicio | Marca | Modalidad | Precio (USD) |
|---|---|---|---|
| Auditoría digital express | Andex | Pago único | 80-200 |
| Web SEO optimizada | Andex | Único + recurrencia | 800-1500 + 200-400/mes |
| Research de competencia | Andex | Pago único | 150-300 |
| Mantenimiento web mensual | Andex | Suscripción | 80-150/mes |
| Auditoría digital bodega | Nevado | Pago único | 300-600 |
| Bodega Digital 360 | Nevado | Suscripción | 400/mes |
| Ebook lead magnet | Ambas (captación) | Gratis | — |

## Métricas de éxito esperadas (trimestre 1)

- Mes 1: 0-1 clientes, USD 0-500
- Mes 2: 1-2 clientes, USD 500-1500
- Mes 3: 3-5 clientes, USD 1500-3500
- Al menos 1 cliente en suscripción mensual al cierre del mes 3

## Reglas de routing

- Tarea menciona "auditoría" + cliente genérico → activar (futura) skill `auditoria-digital-pyme`
- Tarea menciona "auditoría" + bodega/vitivinícola → activar (futura) skill `auditoria-bodega-mendocina` + research de competencia en paralelo
- Pide "propuesta comercial" → activar (futura) skill `propuesta-comercial-consultora`
- Requiere texto SEO → activar (futura) workflow `web-pyme-seo-argentina`
- Cualquier output de cliente → pasa por revisión humana antes de salir (human-in-the-loop, sección 5.7 del manual)

Las skills todavía no están escritas — son la tarea de Semana 2 del plan. Esta sección se actualiza cuando existan.

## Decisiones pendientes

- Google Workspace vs Zoho para email profesional (ver `decisiones.md`)
- Arrancar Andex y Nevado en paralelo desde semana 1, o priorizar Andex y activar Nevado con el primer prospecto de bodega
- Vertical principal definitivo (bodegas u otro) — se decide con datos del trimestre 1

## Stack técnico

- Claude Pro (activo)
- GitHub (repo pendiente de crear — ver `decisiones.md`)
- WordPress + Elementor Pro + Envato Elements (para webs de clientes)
- Google Workspace o Zoho (a definir, para email)
- NotebookLM (transcripción de audios de onboarding de clientes)

## Reglas de uso

- Esta conversación = esta división. No mezclar con Atuel Insights, Productos o Productización.
- Outputs de clientes van a `clientes/[nombre-cliente]/`, no a la raíz.
- Decisiones de negocio (nombres, dominios, pricing) se registran en `decisiones.md`, no solo en el chat.

---

*Ver `decisiones.md` para el detalle de decisiones tomadas y `../00-comando-central/snapshot-holding-2026.md` sección 5 para el plan completo de 90 días.*
