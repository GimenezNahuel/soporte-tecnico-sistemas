# Caso #SYS-03: Interrupción Masiva del Servicio de Impresión Corporativo (`INC0012870`)

* **Categoría:** Infraestructura de Servidores / Gestión de Incidentes[cite: 20, 21, 22, 24]
* **Prioridad:** Alto[cite: 24]

## Contexto y Problema
La usuaria `Dorothy Martinez` (Legal, Piso 2) reporta que ninguna impresora de la oficina funciona y todas figuran desconectadas en distintos pisos, afectando contratos y presentaciones[cite: 24].

## Procedimiento y Resolución
1. Contacto por **Chat de la empresa** para confirmar la revisión del ticket `INC0012870`[cite: 19].
2. Revisión en **Sala de servidores** (`DC01`, `DC02`, `FILESERV01` y `EXCH01` en *Online*), detectando el servidor de impresión **`PRINT01`** en estado *Degraded* con alto consumo de recursos (CPU 95%, memoria 90%)[cite: 20].
3. Ejecución de **Reiniciar** sobre `PRINT01`[cite: 21].
4. Comprobación del estado *Online* del nodo y validación por chat con la usuaria de que el servicio volvió a operar[cite: 22].

## Resultado
Servicio de impresión restablecido en la sala de servidores y confirmado por la usuaria para cerrar `INC0012870`[cite: 22, 24].
