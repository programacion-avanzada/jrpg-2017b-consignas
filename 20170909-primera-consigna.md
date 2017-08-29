# Trabajo Práctico - primera entrega

Se deberá dejar el proyecto (en sus tres módulos) funcionando en sus computadoras. Asimismo se deberá revisar toda documentación incluida con el código, y actualizarla.

## Metodología de trabajo

Por ser el primer trabajo práctico, será más simple porque demanda la organización de los grupos. Detallaremos a continuación los pasos necesarios para poder trabajar correctamente:

1. Formar grupos de 5 a 8 personas. Este grupo se mantendrá durante la cursada del taller. La flexibilidad cubre casos en los que haya abandonos, o que sean impares, etc. Utilicen dicha flexibilidad con sabiduría.

2. Escoger un nombre para el grupo. Dicho nombre se utilizará de ahora y hasta la finalización de la cursada para referirse al grupo completo. Mantengan la compostura, sin por eso ser necesariamente demasiado estructurados.

3. Crear una organización (con plan gratuito) en GitHub con dicho nombre. Eso se hace [desde esta página](https://github.com/organizations/new), y debe hacerlo *sólamente un integrante por equipo*. Ese integrante será el _dueño_ de la organización, momentáneamente.

4. Garantizar el acceso a la organización al resto de los integrantes del grupo. Eso se hace desde una dirección similar a esta, suponiendo que la organizacion se llamase "los-magios": `https://github.com/orgs/los-magios/people`.

5. Hacer el fork de los repositorios suministrados por la cátedra *en el GitHub de la organización*. Esto se hace desde estos enlaces:

* [Dominio](https://github.com/programacion-avanzada/jrpg-2017b-dominio)
* [Cliente](https://github.com/programacion-avanzada/jrpg-2017b-cliente)
* [Servidor](https://github.com/programacion-avanzada/jrpg-2017b-servidor)

Allí donde deben presionar el botón "Fork" que tiene un contador, en la parte superior derecha de la pantalla.  
**Nota:** Es muy importante que lo hagan a nombre de la organización, y no a nombre de sus usuarios individuales. Si se equivocan, lo pueden borrar e intentar nuevamente.

6. Habilitar los _issues_ en cada repositorio recientemente "forkeado". Esto lo usaremos desde la cátedra, y se hace desde una dirección similar a esta: `https://github.com/los-magios/jrpg-2017b-dominio/settings`, chequeando la casilla "Issues".

7. Sacar una captura de pantalla de los resúmenes de Repositorios y Personas de la organización, y enviarla a los docentes. Las direcciones de estos resúmenes son similares a estas:
	* Repositorios: `https://github.com/los-magios`
	* Personas: `https://github.com/orgs/los-magios/people`

8. Cuando quieran importar cada proyecto en Eclipse, [lean el README](https://github.com/programacion-avanzada/jrpg-2017b-dominio/blob/master/README.md) ya que necesitarán hacer algunos ajustes en su workspace. Encontrarán un README.md en cada proyecto.

## Actualización de documentación

Deberán editar cada archivo README.md para que incluya los nombres de los integrantes del grupo, así como también el correcto enlace a TravisCI (ver línea superior de cada README.md).

## Configuración de TravisCI

1. Sacar una cuenta en [Travis CI](https://travis-ci.org/). Se identifican con su cuenta de GitHub.
2. Ingresar a [su perfil en Travis CI](https://travis-ci.org/profile) y verificar que la organización que crearon es visible. Si NO fuera visible, diríjanse [aqui](https://github.com/settings/connections/applications/f244293c729d5066cf27) y otórguenle acceso a la organización haciendo clic en el botón _"Grant access"_ que figura junto al nombre de su organización, en el listado.
3. Una vez que verificaron el acceso, [vuelvan a Travis CI](https://travis-ci.org/profile) y luego de seleccionar en el menú de la izquierda su organización, habiliten el repositorio del grupo para integración contínua. Esto se hace mediante el interruptor correspondiente en el listado. Si NO apareciera, es cuestión de esperar unos minutos hasta que sí lo haga, refrescando la pantalla cada cierto tiempo.
4. Si todo funcionó correctamente, en una dirección similar a `https://travis-ci.org/programacion-avanzada/jrpg-2017b-dominio`, pero con el nombre de su grupo en lugar de `programacion-avanzada` encontrarán el historial de construcciones de esta pieza de software.
5. Repitan esos pasos para los otros dos repositorios.
6. Durante la próxima clase veremos cómo trabajar con esta herramienta. Sin embargo, los alentamos a intentar leer los detalles de cada trabajo construído en la herramienta.

## Forma y fecha de entrega

Siempre se trabajará sobre los repositorios de GitHub. El Trabajo Práctico se tomará automáticamente de sus repositorios el día 9 de Septiembre de 2017, a las 8:00 AM (dos horas antes del primer turno del Taller).