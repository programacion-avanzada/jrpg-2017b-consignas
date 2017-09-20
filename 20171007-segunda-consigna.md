# Trabajo Práctico - segunda entrega

En esta entrega vamos a implementar dos funcionalidades conjuntas: la evolución de los atributos de los personajes conforme avanzan de nivel, y la existencia de enemigos en el escenario.

## Metodología de trabajo

### Evolución de atributos

Como en todo juego de estrategia, queremos que los atributos tales como fuerza y defensa puedan modificarse a lo largo del tiempo acorde al nivel del personaje.
Esto debería reflejar los puntos obtenidos y asignados por el jugador, conforme su selección.
Deberá poder reiniciarse la asignación y reasignarse los puntos cada vez que se avanza de nivel.

Por ejemplo, si el jugador avanza de nivel 1 a nivel 2, y obtiene 3 puntos, debería poder asignarlos todos a fuerza, todos a defensa, o elegir dónde hacerlo. Al pasar de nivel 2 a nivel 3, debería poder asignar los nuevos 3 puntos, o reasignar los 6 que ya obtuvo.

### Enemigos en el escenario

Deseamos que aparezcan enemigos en ciertas zonas no visitadas del escenario, y que al acercarse a ellos comiencen una batalla con el jugador. La misma no deberá ser demasiado inteligente, sino simplemente una seguidilla de ataques hasta ganarle o ser derrotados.

No deberán aparecer enemigos espontáneamente en una zona visible del mapa, para evitar el efecto "generación espontanea". Adicionalmente, no deberá haber más de 10 enemigos al mismo tiempo.

Se aclara que los enemigos deberán ser vistos y pueden combatir con cualquiera de los jugadores conectados al mapa. Sin embargo, una vez que entablan combate con uno, no pueden hacerlo con nadie más al mismo tiempo.

Por último, al ser derrotados, los enemigos desaparecen del mapa.

## Forma y fecha de entrega

Siempre se trabajará sobre los repositorios de GitHub. El Trabajo Práctico se tomará automáticamente de sus repositorios el día 7 de Octubre de 2017, a las 8:00 AM (dos horas antes del primer turno del Taller).