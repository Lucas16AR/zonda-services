# Decisiones — División 1: Servicios

> Registro de decisiones tomadas en Semana 1 del plan operativo (snapshot sección 5).
> Fecha: 2026-06-30

---

## 1. Nombre comercial y dominio

**Descartados:** "Sigma Consultora" (ya existe) y "Andes Consultora" / "Andina Solutions" (dominios .com.ar ya registrados por terceros).

**Nombres comerciales CONFIRMADOS (División 1 — Servicios), dos marcas según línea de negocio:**

| Marca | Cubre |
|---|---|
| **Andex Consultora** | Consultora general PyME: auditoría digital express, web SEO, research de competencia, mantenimiento web mensual |
| **Nevado Solutions** | Vertical bodegas: Bodega Digital 360 (suscripción), auditoría digital bodega mendocina |

**Holding:** Quantix (engloba las 4 divisiones)

**Nombre comercial de la división (decidido 2026-07-02): Zonda Services.** Andex Consultora y Nevado Solutions quedan como submarcas/productos dentro de Zonda Services.

**Dominios — disponibles para registrar en nic.ar:**

| Dominio | Marca | Estado |
|---|---|---|
| andexconsultora.com.ar | Andex Consultora | Libre — pendiente de registro |
| nevadosolutions.com.ar | Nevado Solutions | Libre — pendiente de registro |

**Próxima acción (tuya):** registrar ambos dominios en nic.ar (~USD 15/año c/u). Avisame cuando estén registrados para tachar este pendiente.

---

## 2. Pasos para activar email profesional

Secuencia (de la sección 3.1/3.2 del manual operativo). Se repite por cada dominio (Andes y Andina), salvo que decidas arrancar con uno solo y sumar el segundo más adelante.

1. **Registrar el dominio elegido** (paso 1, debe estar resuelto primero).
2. **Elegir proveedor:**
   - Google Workspace básico (~USD 6/mes/casilla) — recomendado si ya usás Gmail/Drive/Calendar.
   - Zoho Mail (gratis hasta 5 usuarios, plan pago si necesitás más storage) — alternativa más económica, útil si vas a tener 2 dominios y querés bajar costo fijo.
3. **Verificar propiedad del dominio:** agregar el registro TXT que te da el proveedor en el panel de DNS de NIC.ar (o donde lo hayas registrado).
4. **Configurar registros MX** apuntando al proveedor elegido (Google o Zoho dan las instrucciones exactas al verificar).
5. **Crear la casilla principal de cada marca:** ej. `contacto@andexconsultora.com.ar` y `contacto@nevadosolutions.com.ar` (o `capi@...` si preferís tu nombre).
6. **Configurar firma profesional** por marca (nombre, rol, teléfono, link a LinkedIn).
7. **Probar envío/recepción** desde un email externo antes de usarlo con prospectos.

**Decisión pendiente:** Google Workspace vs Zoho — definir cuando los dominios estén confirmados. Con 2 marcas, Zoho puede convenir más por costo si arrancás sin clientes todavía.
**Decisión pendiente:** ¿arrancás con las dos marcas en paralelo desde semana 1, o priorizás Andes Consultora (servicios generales) y activás Andina Solutions cuando aparezca el primer prospecto de bodega?

---

## 3. Estructura de carpetas local — confirmada

Estructura creada dentro de `01-division-servicios/` (adaptada de snapshot sección 6):

```
01-division-servicios/
├── CLAUDE.md              # pendiente de redactar (contexto de la división)
├── skills/                 # onboarding-cliente-pyme.md, auditoria-digital-pyme.md, etc.
├── plantillas/             # contrato-servicios.md, propuesta-base.md, pdf-servicios-precios
├── clientes/               # una subcarpeta por cliente
├── prospectos/             # lista-20-iniciales.md (semana 2)
└── casos-exito/            # caso-demo-publico.md (semana 3)
```

Carpetas creadas y listas para usar. `CLAUDE.md` de la división queda pendiente para cuando definamos propósito/routing específico de Sigma Consultora.

---

## 4. Próximos pasos (Semana 1, según plan)

- [ ] Confirmar dominio disponible en nic.ar — **pospuesto** (2026-07-03): sin presupuesto por ahora, se retoma más adelante
- [ ] Comprar dominio + activar email profesional — **pospuesto** (2026-07-03), depende del punto anterior
- [x] Activar Claude Pro — confirmado activo (2026-07-03)
- [x] Setup de GitHub — **decidido (2026-07-03): un solo repo para toda la división, nombre `zonda-services`**, no uno por marca (Andex/Nevado comparten skills, plantillas y flujo; separar no se justifica hasta que una marca tenga producto de software propio)
- [ ] Redactar `CLAUDE.md` de la división (cuando el nombre/dominio estén 100% confirmados) — nota: el CLAUDE.md ya fue redactado con nombre confirmado (Zonda Services); dominio sigue pendiente

## 5. Estructura del repo `zonda-services` (decidida 2026-07-03)

```
zonda-services/
├── skills/              (compartidas: auditoria-digital-pyme, auditoria-bodega-mendocina, propuesta-comercial-consultora)
├── plantillas/
├── andex/                clientes, casos, contenido específico Andex Consultora
├── nevado/                clientes, casos, contenido específico Nevado Solutions
└── casos-exito/           incluirá los 3 simulacros de Semana 3: bodega, PyME de productos, hotel/cabañas
```

**Alcance de negocio confirmado (2026-07-03):** Zonda Services no se limita a bodegas. Bodegas (Nevado Solutions) es la vertical prioritaria por volumen monetario, pero Andex Consultora apunta a negocios en general (retail, gastronomía, turismo, hotelería, etc.). Los simulacros de Semana 3 deben reflejar esa diversidad, no solo el caso bodega.

## 6. Skills operativas redactadas (2026-07-04)

Tarea de Semana 2 completada. Las tres skills dejaron de ser placeholder y quedaron como playbooks operativos:

- [x] `skills/auditoria-digital-pyme.md` (Andex) — datos requeridos, proceso de 6 pasos, formato de informe, guardrails, encadena con propuesta.
- [x] `skills/auditoria-bodega-mendocina.md` (Nevado) — incluye enoturismo, venta directa/club de vino, research de competencia en paralelo y guardrail regulatorio (nada de asesoramiento financiero).
- [x] `skills/propuesta-comercial-consultora.md` — catálogo de precios, empuje a suscripción (meta ≥1 cliente recurrente al cierre del trimestre), usa `plantillas/propuesta-base.md`.

**Pendiente Semana 2/3:** workflow `web-pyme-seo-argentina` (texto SEO) y los 3 simulacros de Semana 3 en `casos-exito/` (bodega, PyME de productos, hotel/cabañas).

## 7. Estado del proyecto al 2026-07-04

Constancia de cierre de jornada. Se retoma cuando se defina con cowork el próximo paso.

**Hecho hoy:**
- Repo movido de ubicación local: pasó de colgar de `Quantix/` a `Quantix/01-division-servicios/zonda-services` (un nivel más profundo).
- Se corrigió la ruta relativa rota que quedó tras el movimiento: en `CLAUDE.md`, la referencia al snapshot del holding pasó de `../00-comando-central/...` a `../../00-comando-central/...`. Verificado que resuelve.
- Revisado el repo completo: sin rutas absolutas hardcodeadas y con el git remote (`origin` → GitHub `Lucas16AR/zonda-services`) intacto.
- Cambios commiteados y pusheados a `master` (commit `1defd9a`).

**Estado general:** repo sano y sincronizado con GitHub. Semana 1–2 del plan de 90 días avanzadas: nombre comercial confirmado (Zonda Services), CLAUDE.md redactado, estructura de carpetas creada, 3 skills operativas redactadas. Sin clientes todavía (fase de setup).

**Pendientes abiertos (sin cambios hoy):**
- Dominios en nic.ar (`andexconsultora.com.ar`, `nevadosolutions.com.ar`) — pospuestos por presupuesto.
- Email profesional (Google Workspace vs Zoho) — depende de los dominios.
- Workflow `web-pyme-seo-argentina` y los 3 simulacros de Semana 3 en `casos-exito/`.

**Próximo paso:** a definir con cowork qué se prioriza. Trabajo en pausa hasta esa definición.
