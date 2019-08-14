# Patrón arquitectónico Broker

El patrón arquitectónico Broker es utilizado para la implementación de sistemas de software distribuidos con componentes desacoplados.

Funciona como un intermediario entre el cliente y el servidor encargado de realizar la coordinación de mensajes, solicitudes, respuestas etc.

![enter image description here](http://www.dossier-andreas.net/software_architecture/broker.jpg)

La arquitectura broker tiene como objetivo poner un intermediario entre los clientes y el servidor o múltiples de estos, tiene  el objetivo de gestionar el envío de información o la ejecución de tareas, al tener esta arquitectura permite a una aplicion tener funciones desacopladas y descentralizadas lo que facilita la escalabilidad y la seguridad del sistema informático.

![enter image description here](https://i.imgur.com/lBkzoPV.jpg)

La interior imagen muestra como interactuan los diferentes actores implicados en  la petición a un servidor utilizando el patrón Broker, se observa como el Broker funciona como intermediario entre entre el cliente y el servidor, la operación que aquí se esta ejecutando es la búsqueda de un servidor, esto es un ejemplo del por que un broker protege al servidor, ya que el cliente no esta conectado directamente, ademas que en algunas aplicaciones el broker ayuda a encontrar los servidores menos congestionados.

**Ventajas:**
- Servidores invisibles para los clientes.
- Escalabilidad del Software.
- Facil implementacion de nuevos servicios.
- Portabilidad del Sistema.

**Desventajas:**
- Disminución del rendimiento de las conexiones
- Baja tolerancia a errores
- Compleja Depuración
- 

**CORBA**

Common Object Request Broker Architecture (CORBA): es un estándar definido por el grupo de gestión de objetos (OMG) que permite el funcionamiento conjunto de componentes de software escritos en distintos lenguajes informáticos y que se ejecutan en distintos sistemas.

CORBA fue el primer producto propuesto por OMG. Su objetivo es ayudar a reducir la complejidad, disminuir los costes y acelerar la introducción de nuevas aplicaciones informáticas, promoviendo la teoría y la práctica de la tecnología de objetos en los sistemas distribuidos.

Es una tecnología que oculta la programación a bajo nivel de aplicaciones distribuidas. No obstante también brinda al programador una tecnología orientada a objetos; las funciones objetos y estos objetos pueden estar en diferentes máquinas, pero el programador accederá a ellos a través de funciones normales dentro de su programa.

CORBA es más que una especificación multiplataforma, también define servicios habitualmente necesarios como seguridad y transacciones. Y así este no es un sistema operativo en sí, en realidad es un middleware.


## Ejemplos de código

En los siguientes links se dejan dos Ejemplos donde se implementa el patrón de diseño Broker.

https://github.com/Huracan311/Broker


**Links Consultados**

https://www.ibm.com/support/knowledgecenter/es/SSMKHH_9.0.0/com.ibm.etools.mft.doc/bc22400_.htm
https://www.grimm-jaud.de/index.php/private-vortraege/27-broker-pattern
https://ff.tu-sofia.bg/~bogi/knigi/SE/Wiley%20-%20Pattern-Oriented%20Software%20Architecture%20-%20Volume%201,%20A%20System%20of%20Patterns.pdf



