**1. [Points on Line — CF 251A](https://codeforces.com/contest/251/problem/A)**
Buscan el segmento de longitud dada con más puntos adentro. `check` es directo con `lower_bound`/`upper_bound` sobre las posiciones ordenadas — buen puente entre lo clásico y lo "sobre la respuesta".

**2. [String Game — CF 778A](https://codeforces.com/problemset/problem/778/A)**
Buscan el mínimo prefijo de eliminaciones tal que la palabra deje de ser subsecuencia del texto. `check(x)` = "¿sigue siendo subsecuencia después de sacar las primeras x letras marcadas?" — chequeo lineal, monotonía bien obvia.

**3. [Cartons of Milk — CF 767D](https://codeforces.com/contest/767/problem/D)**
Simulación con binary search para encontrar cuántos cartones se pueden tomar antes de que se venzan. Buen ejercicio para que vean el patrón aplicado a una simulación de eventos, sin ser complicado.

Sugerencia de orden: 251A primero (el `check` es casi mecánico), después 778A (empiezan a escribir su propio `check`), y 767D como cierre (mezcla la idea con lógica de simulación).

Mismo comentario que antes: confirmá el rating/tag en el problemset, ya que vienen de la lista de terceros y no de una consulta directa mía al sistema de tags de Codeforces.
