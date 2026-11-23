# Caso #SYS-02: Pérdida de Acceso a Unidad Compartida en Trabajo Remoto (`INC0012847`)

* **Categoría:** Conectividad Remota / Acceso a Recursos de Red[cite: 8, 11, 12]
* **Prioridad:** Alto[cite: 8]

## Contexto y Problema
La usuaria `Sarah Mitchell` (Marketing, trabajo remoto) reporta el error *"No se encontró la ruta de red"* al intentar abrir la unidad compartida de Marketing, mientras que Internet y correo funcionan con normalidad[cite: 8].

## Procedimiento y Resolución
1. Conexión por **Escritorio remoto** al equipo `SD1066`[cite: 10].
2. Verificación del **Cliente VPN** corporativo (`vpn.corp.local:443`, `IKEv2/IPSec`), detectando el estado *Desconectado* / túnel *Inactivo*[cite: 11].
3. Activación de la conexión VPN hasta dejar el túnel en estado *Conectado*[cite: 12].

## Resultado
Túnel VPN restablecido hacia la red corporativa y ticket (`INC0012847`) listo para cierre con notas de resolución[cite: 7, 8, 12].
