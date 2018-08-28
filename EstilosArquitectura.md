### Estilos de Arquitectura

El Panorama Arquitectonico

* MVC
* FLAGS no es arquitectura de las tecnologias.

Desiciones arquitectonicas con proyectos con estructura de microservicios, es la tendencia para el equipo de desarrollo, los sacrificios que se hacen para realizarlo, patrones y estilos de arquitectura.

Se habla de algo generico, implementan diferentes arquitecturas, cliente servidor, sistema dns esta estructura define el estilo, habla del problema que resuelve arquitectonicamente, define algo generico que permite reutilizar a traves del software, nos permite restringir las desiciones tomadas, para beneficio estimado.

LLamado y Retorno:
Programa Principal y Subrutinas, el programa secuencialmente utilizaba la secuencia 1 por 1, funciones donde se modelaba bloque de codigo y luego se ejecutaba.

Flujo de Datos:
 - Lote Secuencial: Base de datos de venta archivos y aplicacion que procesa y da como salida otro set de archivos, sera procesado por otro proceso, entrada procesarla y devolver string de texto, sed remplaza y wc cuenta, proceso con salida clara y cuando existe string de entrada.

### Estilos centrados en datos

Pizarron:
Diferentes componente que interactuan con componente central, cada componente tiene como responsabilidad resivir algun dato y escribirlo al pizarron, puede tener logica cuando tiene datos necesario emite una salida, se espera el ok para luego dar como resultado que esto se reporte correctamente.

Centrado en datos:
Componentes y base de datos compartida, lo importante es que cualquiera de los componentes, deciden escribir a la bd, lo que el otro componente pueda leer, este puede implementar parte ip, en general se ve como componentes separados, dentro de algo monolitico, y verificar como compartir el recurso.

Sistema Expertos o Basado en Reglas:
Componente de tipo cliente se comunica con componente que tratara de inferir las reglas, verificara si es una regla o consulta, luego se comunica con tercero para ver la base de conocimientos.interaccion del sistema se genera base conocimientos en base a consultas que se sabe que ya es verdad, cada uno de estos estilos el dato tiene diferente forma.
