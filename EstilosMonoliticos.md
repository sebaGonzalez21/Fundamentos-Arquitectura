### Estilos Monoliticos

* Es mas facil darle prioridad  a la eficiencia de las comunicaciones
* Son mas faciles de probar
* Curva de Aprendizaje son mas faciles, todas las piezas estan en el mismo lugar
* La capacidad de modificacion es mas facil
* La modularización es mas facil de romper, por lo que es mas facil no garantizar esa separacion a largo plazo.
* En usabilidad, es mas costoso, porque habria que respaldar toda la aplicacion y no pequeños microservicios
* Puede ser un desafio para el despliegue, porque habria que garantizar que toda la aplicacion o sistema se adapte a ese contecto especifico

## Estilos Distribuidos

* Es mas facil dar prioridad a la eficiencia de las comunicaciones
* Para hacer una prueba de principio a fin hay que tener todos los componentes disponibles.
* La curva de Aprendizaje es mas dificil, porque habia que entender todas las piezas de los componentes
* Al ser desplegadas independientemente, son versionadas independientemente, y estas variacion de serviones hace mas compleja su modificacion
* La modularidad es mas facil porque los componentes que son desplegados son independiente
* La disponibilidad se pueden tener multiples copias del sistema, por lo que este posible es mas barato
* La adaptabilidad es mas facil en el despliegue porque los componentes se despliegan independiente en multiples contextos
