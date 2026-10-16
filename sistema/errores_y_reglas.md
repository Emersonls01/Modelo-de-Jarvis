# Aprendizaje de errores y reglas — Jarvis Consultoría

Versión: v2 · 16-10-2026

## Principio
Cada error termina en una de tres salidas: **regla**, **ajuste de la skill** o **descarte**. Nunca en una lista que solo crece.

## Ciclo de 6 pasos
1. **Capturar** — Emerson corrige (`error: …`) o el agente detecta una contradicción. Se registra al momento.
2. **Clasificar** — tipo: dato inventado / pregunta innecesaria / cálculo / formato / criterio de negocio. Severidad: crítico / alto / menor.
3. **Causa raíz** — una línea: faltaba instrucción, era ambigua, no revisó la fuente…
4. **Proponer solución** — corrección puntual / regla nueva o ajustada / cambio en la skill.
5. **Aprobar** — lo menor lo corrige el agente y avisa; reglas nuevas y cambios a la skill requieren "si" de Emerson.
6. **Verificar** — en los siguientes usos el agente confirma que la regla funcionó. Dos usos correctos seguidos → error cerrado.

## Reglas de higiene
- Tope de **10 errores abiertos**. Al llegar al tope, se cierran errores antes de seguir acumulando.
- Error repetido 2 veces → se convierte en regla obligatoriamente.
- Cada 10 reglas, el agente propone fusionar las que se pisan.
- Regla sin aplicarse en 90 días → se propone su retiro.
- Dos niveles: errores de **método** (aquí) y errores de un **cliente** (`clientes/<cliente>/errores_cliente.md`).

## Formato de la ficha
```
E-## | fecha | tipo | severidad
Qué pasó: (1 línea)
Causa: (1 línea)
Solución: corrección / R-## / cambio en skill
Estado: abierto → en prueba → cerrado (usos correctos: 0/2)
```

## Errores abiertos
(ninguno)

## Errores cerrados
(ninguno)

## Reglas activas
| ID | Regla | Origen | Fecha | Último uso |
|---|---|---|---|---|
| R-01 | Cada vez que pida aprobación a Emerson, incluir mi sugerencia o recomendación (qué haría yo y por qué), para que él solo confirme o cambie. | Instrucción directa de Emerson | 16-10-2026 | 16-10-2026 |

## Reglas retiradas
(ninguna)
