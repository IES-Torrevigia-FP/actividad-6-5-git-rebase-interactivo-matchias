 Reflexión Actividad 6.5

 Para qué sirve git rebase -i?

Sirve para ordenar y limpiar los commits. Puedes cambiar mensajes, juntar varios commits en uno o cambiar el orden.

Básicamente, te ayuda a que el historial no sea un caos con mensajes tipo "wip" o "arreglo", sino que quede más claro y profesional.

 Ejemplos de uso

 reword
Para cambiar el mensaje de un commit.
Ejemplo: cambiar "wip" por algo que se entienda mejor.

squash
Para juntar varios commits en uno solo.
Ejemplo: si has hecho muchos cambios pequeños, los unes en uno más limpio.

 drop
Para borrar un commit.
Ejemplo: si has añadido algo que no sirve o te has equivocado.

 Riesgos de usar git rebase -i

El problema es que cambia el historial. Si ya has subido los commits a internet (GitHub), puedes liarla y crear conflictos.

Por eso es mejor usarlo solo antes de hacer push o en ramas que solo usas tú.