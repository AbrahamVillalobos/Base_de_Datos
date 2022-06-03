7. Triggers en SQL


1.- Qué es in TRIGGER?

Un trigger o disparador es un script que se usa en lenguaje de programación SQL, en especial en bases de datos como MySQL o PostgreSQL. Consiste en una serie de reglas predefinidas que se asocian a una tabla. Estas reglas se aplican a la base de datos cuando se realizan determinadas operaciones en la tabla, por ejemplo, al añadir, actualizar o eliminar registros.


2.- Cuál es la función de un TRIGGER?

La principal función de los trigger es contribuir a mejorar la gestión de la base de datos. Gracias a ellos muchas operaciones se pueden realizar de forma automática, sin necesidad de intervención humana, lo que permite ahorrar mucho tiempo.


3.- Cuando se puede usar un TRIGGER?

Los trigger se puede ejecutar cuando el usuario realizar alguna acción relacionada con añadir, actualizar o eliminar información de una tabla. Es decir, al usar los comandos INSERT, UPDATE o DELETE.


4.- Cuáles son los dos escenarios de uso de un TRIGGER?

El primero es cuando no podemos intervenir en el código fuente de la aplicación que trabaja sobre la base de datos sobre la que queremos actuar o reaccionar a sus eventos.

El segundo es cuando a pesar de disponer del código, éste pertenece a un software desarrollado por terceros y existe una probabilidad relativamente alta de aplicar actualizaciones o instalar pluggins, y hemos decidido modificar el código fuente lo menos posible para facilitar este tipo de tareas.
