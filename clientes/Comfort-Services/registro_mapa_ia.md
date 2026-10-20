# Registro maestro — Comfort Services

Versión: v10 · 20-10-2026 · Fase actual: F2

## Empresa
- Nombre: Comfort Services FL LLC — VERIFICADO (dicho por el cliente: Emerson, CEO, 16-10-2026)
- CEO: Emerson (también es el consultor de este mapa; decide, acepta, verifica y ajusta todo lo de Comfort Services) — VERIFICADO (dicho por el cliente: Emerson, CEO, 16-10-2026)
- Rubro: climatización comercial (aire acondicionado y calefacción); participa en licitaciones — VERIFICADO (dicho por el cliente: Emerson, CEO, 16-10-2026)
- Tamaño (personas): 4 empleados en Florida — VERIFICADO (dicho por el cliente: Emerson, CEO, 16-10-2026)
- Composición: 2 técnicos, 1 administrador(a) y el CEO (Emerson), que también trabaja como gerente de operaciones — VERIFICADO (dicho por el cliente: Emerson, CEO, 18-10-2026)
- Ubicación: Florida (ciudad no indicada) — VERIFICADO (dicho por el cliente: Emerson, CEO, 16-10-2026)
- Objetivo de transformación con IA: un agente que apoye al CEO en todo el proceso, en sus diferentes tareas — VERIFICADO (dicho por el cliente: Emerson, CEO, 18-10-2026)
- Restricciones — VERIFICADO como base inicial ajustable (aprobado por el cliente: Emerson, CEO, 18-10-2026; propuesto por Jarvis):
  - Presupuesto: bajo, menos de US$200 al mes en herramientas de IA para empezar.
  - Datos delicados: finanzas (QuickBooks) y datos de clientes (Gmail). La IA consulta; no envía, paga ni borra nada sin aprobación del CEO.
  - Normas: licencias y permisos de climatización en Florida, a respetar en cotizaciones y licitaciones.
  - Plazo: primer resultado en 30 a 60 días.
- Software actual general: Gmail, QuickBooks, WhatsApp y Excel, entre otros (lista incompleta) — VERIFICADO (dicho por el cliente: Emerson, CEO, 18-10-2026)
- Consentimiento de grabación de reuniones: pendiente

## Áreas
| ID | Área | Referente | Estado | Dato |
|---|---|---|---|---|
| A1 | Dirección (decisiones, metas, contratación, licencias y permisos) | Emerson (CEO) | confirmada | VERIFICADO (aprobado por el CEO, 18-10-2026; propuesto por Jarvis) |
| A2 | Ventas y licitaciones (oportunidades, visitas, cotizaciones, ofertas, seguimiento) | Emerson | confirmada | VERIFICADO (aprobado por el CEO, 18-10-2026; propuesto por Jarvis) |
| A3 | Operaciones en obra (agenda de trabajos, instalación, mantenimiento, reportes) | Emerson (gerente de operaciones) + 2 técnicos + administrador(a) | confirmada | VERIFICADO (aprobado por el CEO, 18-10-2026; propuesto por Jarvis) |
| A4 | Administración y finanzas (facturación, cobranzas, pagos, QuickBooks) | Emerson | confirmada | VERIFICADO (aprobado por el CEO, 18-10-2026; propuesto por Jarvis) |
| A5 | Compras y clientes (equipos y repuestos, proveedores, atención y seguimiento a clientes) | Emerson (compras) + administrador(a) (visitas a clientes) | confirmada | VERIFICADO (aprobado por el CEO, 18-10-2026; propuesto por Jarvis) |

## Intercambios entre áreas
Estado: VERIFICADO como base inicial ajustable (aprobado por el CEO, 20-10-2026; propuesto por Jarvis; el canal es ASUMIDO)

| De | A | Qué información | Por dónde |
|---|---|---|---|
| A2 Ventas | A3 Operaciones | Trabajo ganado: alcance, dirección, fecha, equipos | WhatsApp / Excel |
| A2 Ventas | A4 Administración | Cotización aprobada para facturar (anticipo o total) | Gmail / Excel |
| A3 Operaciones | A5 Compras | Equipos y repuestos que hacen falta | WhatsApp |
| A3 Operaciones | A4 Administración | Trabajo terminado: reporte, horas, materiales usados | WhatsApp / fotos |
| A4 Administración | A1 Dirección | Cobranzas pendientes, pagos y caja | QuickBooks |
| A5 Clientes | A2 Ventas | Pedidos nuevos y mantenimientos que vuelven a tocar | Gmail / teléfono |

## Tareas por área
Inventario inicial de tareas del CEO (entrevista, 20-10-2026). Que Emerson hace cada tarea: VERIFICADO (dicho por el cliente: Emerson, CEO). ⭐ = de las que más tiempo le quitan (VERIFICADO). 🔴 CRÍTICA = las más críticas para el negocio según el CEO (VERIFICADO, 20-10-2026); entran al desglose de F3 aunque no sean ⭐. El área asignada a las tareas nuevas es ASUMIDO. El desglose detallado (formato de `clientes/_plantilla/registro_mapa_ia.md`) se hace en F3 para las tareas candidatas.

### A1 — Dirección
| Código | Tarea | Quién | Origen |
|---|---|---|---|
| 1.1 | Revisar caja, cobranzas y pagos con el administrador(a) | Emerson | lista propuesta, confirmada |
| 1.2 | Mantener licencias, seguros y permisos al día | Emerson | lista propuesta, confirmada |
| 1.3 | Responder correos de clientes y proveedores (también A5) | Emerson | lista propuesta, confirmada |

### A2 — Ventas y licitaciones
| Código | Tarea | Quién | Origen |
|---|---|---|---|
| 2.1 | Buscar y revisar licitaciones u oportunidades nuevas | Emerson | lista propuesta, confirmada |
| 2.2 | ⭐ Preparar cotizaciones y ofertas (cálculos en Excel) | Emerson | lista propuesta, confirmada |
| 2.3 | Visitas técnicas para medir o evaluar antes de cotizar | Emerson | lista propuesta, confirmada |
| 2.4 | Seguimiento a cotizaciones enviadas | Emerson | lista propuesta, confirmada |

### A3 — Operaciones en obra
| Código | Tarea | Quién | Origen |
|---|---|---|---|
| 3.1 | ⭐ Armar la agenda semanal de los técnicos | Emerson | lista propuesta, confirmada |
| 3.2 | ⭐ Coordinar con los técnicos por WhatsApp durante el día | Emerson | lista propuesta, confirmada |
| 3.3 | Revisar reportes y fotos de trabajos terminados | Emerson | lista propuesta, confirmada |
| 3.4 | Valuaciones de trabajos (área ASUMIDA; enlaza con A4 para facturar) | Emerson | agregada por el CEO |
| 3.5 | 🔴 CRÍTICA · Servicio de unidades (equipos de climatización) | Administrador(a) | dicho por el CEO, 20-10-2026 |
| 3.6 | 🔴 CRÍTICA · Mantenimiento y servicio | Administrador(a) | dicho por el CEO, 20-10-2026 |

### A4 — Administración y finanzas
| Código | Tarea | Quién | Origen |
|---|---|---|---|
| 4.1 | Elaborar facturas | Emerson | agregada por el CEO |
| 4.2 | Seguimiento de pagos (cobranzas) | Emerson | agregada por el CEO |
| 4.3 | Balance de caja | Emerson | agregada por el CEO |

### A5 — Compras y clientes
| Código | Tarea | Quién | Origen |
|---|---|---|---|
| 5.1 | 🔴 CRÍTICA · Visitas a clientes | Administrador(a) | dicho por el CEO, 20-10-2026 |

Tareas de los 2 técnicos: pendiente de levantar.

## Pendientes
- Organigrama: primer borrador = tabla de Áreas (18-10-2026). Falta convertirlo en documento visual cuando el CEO lo pida. Pedido por el CEO, 16-10-2026.
- Software: completar la lista ("entre otras"). Confirmar si usan Google Drive y BidCore — ASUMIDO por Jarvis, no confirmado.

## Anomalías
- AN-01 [RESUELTA] (20-10-2026): en F1 el responsable de A4 Administración y finanzas es el administrador(a), pero el CEO dice que él elabora facturas, hace seguimiento de pagos y el balance de caja. Falta aclarar quién hace qué en A4.
  - Avance 20-10-2026: el CEO aclara que el administrador(a) hace servicio de unidades, visitas a clientes, mantenimiento y servicio (VERIFICADO), es decir, trabajo de campo y no administrativo. Propuesta de Jarvis (ASUMIDO, pendiente de aprobación): A4 pasa a responsable Emerson; el administrador(a) se suma a A3 y A5. Pendiente: quién hace las compras.
  - Resuelta 20-10-2026: el CEO aprueba el ajuste. A4 = Emerson; A3 suma al administrador(a); A5 = Emerson (compras) + administrador(a) (visitas a clientes). VERIFICADO (aprobado por el CEO, 20-10-2026).

## Historial de versiones
| Versión | Fecha | Cambio |
|---|---|---|
| v0 | 16-10-2026 | Creación desde plantilla |
| v1 | 16-10-2026 | F0: nombre, CEO, rubro y ubicación (estado) confirmados por el CEO |
| v2 | 16-10-2026 | F0: tamaño (4 empleados); organigrama agregado a pendientes |
| v3 | 18-10-2026 | F0: composición del equipo y objetivo de IA |
| v4 | 18-10-2026 | F0: software actual (parcial) |
| v5 | 18-10-2026 | F0 cerrada: restricciones como base inicial ajustable; pasa a F1 |
| v6 | 18-10-2026 | F1: 5 áreas y responsables confirmados (borrador de organigrama) |
| v7 | 20-10-2026 | F1 cerrada: 6 intercambios entre áreas como base ajustable; pasa a F2 |
| v8 | 20-10-2026 | F2: inventario inicial de 14 tareas del CEO (3 ⭐); anomalía AN-01 |
| v9 | 20-10-2026 | F2: tareas del administrador(a) (trabajo de campo); avance en AN-01 |
| v10 | 20-10-2026 | F1 ajustada (responsables A3, A4, A5); AN-01 resuelta; tareas de campo marcadas como críticas |
