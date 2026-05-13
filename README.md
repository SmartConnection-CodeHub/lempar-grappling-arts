# LEMPAR Grappling Arts · Plan de inversión y proyección 3 años

**Cliente:** Claudio González León
**Marca:** LEMPAR Grappling Arts ([@lempar.grappling.arts](https://instagram.com/lempar.grappling.arts))
**Proyecto:** Plan de formalización, capitalización y escalamiento 2026-2028
**Confidencialidad:** Privado · datos financieros sensibles

---

## Contenido del repo

| Archivo | Propósito | Para quién |
|---|---|---|
| `propuesta.html` | Propuesta completa con 13 secciones + simulador interactivo | Claudio González (cliente) |
| `warroom.html` | Vista interna de la operación · 16 agentes SMC asignados + QA DATA-BW | Equipo Smart Connection |
| `assets/lempar-hero.mp4` | Video de hero · 8.4MB | Componente visual de la propuesta |

## Cómo abrir

```bash
open propuesta.html
```

O servir local con cualquier static server:

```bash
python3 -m http.server 8080
# Luego visitar http://localhost:8080/propuesta.html
```

## Capacidades destacadas

### Propuesta (cliente)

- **Simulador interactivo** · botón flotante brass abajo-derecha. Claudio puede editar 21 variables (universo, pagantes, ticket, ventas Y1-Y3, márgenes, CapEx, IVA, IDPC, equity socio). 45+ outputs se recalculan al instante.
- **Persistencia** · `localStorage` guarda los cambios entre visitas.
- **13 secciones** · Mapa · Contexto · Academia · Líneas de ingreso · Capital · Proyección · IVA · Pregunta central · Retiros lado a lado · Gastos (benchmark BJJ Chile) · Fondos públicos · RADAR · Pasos legales · Decisiones.
- **Mobile-first** · scroll horizontal con snap en cards · tipografía fluida `clamp()` · touch-friendly.
- **Branding** · negro + bone + brass + blood-red (paleta grappling/martial arts).

### War Room (interna SMC)

- **16 agentes asignados** (5 P1 críticos · 5 P2 importantes · 6 P3 apoyo).
- **DATA-BW QA financiero** · auditoría cuantitativa de la propuesta · 3 bugs detectados y corregidos.
- **Timeline 4 semanas** · sprints coordinados por PM con orquestación de Cerebro.

## Variables clave de la propuesta

| Variable | Valor base |
|---|---|
| Universo alumnos | 48 |
| Pagantes activos | 20 |
| Ticket mensual | $40.000 CLP |
| Ingreso real / mes | $800.000 CLP |
| Anual real | $9.6M CLP |
| CapEx propuesto | $8.000.000 CLP |
| Ventas Y1 / Y2 / Y3 | $7.37M / $14M / $21M |
| Margen Y1 / Y2 / Y3 | 23% / 47% / 53% |
| Retiros Claudio 3Y solo | $8.314.950 |
| Retiros Claudio 3Y con socio 50% | $4.157.475 |
| Diferencia 3 años | **$4.157.475** |

## Pregunta central

**¿Capitalizar $8M aceptando inversionista 50/50, o ir solo vía Sercotec Capital Semilla ($3.5M) + BancoEstado PYME ($4.5M)?**

La propuesta argumenta que la segunda alternativa es preferible: mismo capital, sin entregar control, mismos números, retiros 2× mayores a 3 años.

## Estructura recomendada (próximos pasos)

1. Decidir modelo capitalización (recomendado: Sercotec + préstamo)
2. Constituir SpA LEMPAR Grappling Arts
3. Inicio actividades SII · régimen 14D N°3
4. Cuenta corriente PYME BancoEstado
5. Registro marca INAPI (clases 25 · 28 · 41)
6. Postular Sercotec próxima convocatoria
7. Abrir 2do horario mes 9-12

---

**Creado:** 2026-05-13
**Última actualización:** 2026-05-13
**Equipo SMC:** Cerebro · DATA-BW · PRM · Functional-Lead · Compliance · Controller · Business Development · Frontend · PM · RADAR · Procurement · Supply-Chain · Portavoz · Video&Img · Innovation-Lab · Hoku
