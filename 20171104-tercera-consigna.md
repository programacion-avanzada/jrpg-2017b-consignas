# Trabajo Práctico - tercera entrega

En esta entrega vamos a mejorar la estructura de los tres proyectos. Habrá sugerencias puntuales, y generales. Se espera que hagan su mejor esfuerzo, y no lo mínimo para "zafar".

## Metodología de trabajo

### Cambios genéricos

* Utilizando la herramienta gradle, con la configuración actual, se piden bajar a menos de 100 las incidencias de checkstyle de los 3 proyectos.

* Se pide seguir la convención de uso de paquetes. Adapten los existentes para ello.

### Evolución del dominio

* Debemos volver a tener excelentes pruebas. Mantener el porcentaje de cobertura del dominio por encima del 95%.

* Revisaremos la documentación existente para ver si concuerda con la realidad. Adicionalmente, corregiremos las faltas ortográficas y de redacción.

### Evolución del cliente

* El puerto en el que corre el juego debe ser configurable por medio de un archivo de propiedades.


* Hay sentencias if que deberían reemplazarse por un mejor despacho condicional en `estados.EstadoJuego.getMundo()`, `entidades.Entidad.getFrame()`, `entidades.Entidad.getFrameAnimacionActual()`, `juego.Pantalla.Pantalla(...).new KeyAdapter() {...}.keyReleased(KeyEvent)`. Por supuesto, no estamos hablando de incorporar `switch`.

* Es una mala práctica devolver valores `null`, como lo hacen estos métodos: `mensajeria.Paquete.getObjeto(String)` y `mensajeria.Paquete.getObjetoSet(String, int)`

* Los siguientes métodos devuelven los literales `true` y `false`, y eso podría evitarse utilizando una variable bien aplicada, o utilizando la condición inicial: `entidades.Entidad.estanEnDiagonal(Nodo, Nodo)`, `interfaz.MenuInfoPersonaje.clickEnBoton(int, int)`, `interfaz.MenuInfoPersonaje.clickEnCerrar(int, int)`, `interfaz.MenuInfoPersonaje.clickEnMenu(int, int)`, `dominio.*.habilidad1(Personaje, Peleable)`, `dominio.*.habilidad2(Personaje, Peleable)`

### Evolución del servidor

Elementos a mejorar:

* El método `servidor.Servidor.mensajeAAll(int)` tiene un condicional bastante sucio.

* Los métodos de la clase `servidor.Conector` y el método `servidor.Servidor.mensajeAUsuario(PaqueteMensaje)` tienen condicionales y retornos redundantes.

* Verificar la pertinencia y necesidad del archivo `/jrpg-2017a-servidor/wereable positions.txt`

* Reemplazaremos la persistencia, para comenzar a utilizar Hibernate.

## Forma y fecha de entrega

Siempre se trabajará sobre los repositorios de GitHub. El Trabajo Práctico se tomará automáticamente de sus repositorios el día 4 de Noviembre de 2017, a las 8:00 AM (dos horas antes del primer turno del Taller).