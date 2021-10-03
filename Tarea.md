1º : Definicion de las relaciones y 5 ejemplos de c/u (uno a uno / uno a muchos / muchos a muchos)

(Uno a uno)
Este mismo permite que un solo registro de una tabla se relacione con un unico registro de otra.

EJEMPLOS:

Estudiantes ----  Informacion de contacto.

Persona Fisica ----- Licencia de conducir.

Persona fisica ----- DNI-

auto ------- patente.

vehiculo --- N° Chasis.




(Uno a muchos)
En este otro caso. Un registro de una tabla se puede asociar a uno o varios registros de otra. La relacion en su para a ser una tabla intermedia entre estas dos, Contando como minimo tres datos: una clave primaria (PK) y dos claves Foraneas (FK)


EJEMPLOS:

Cliente ---- pedidos

domicilio ------ codigo postal

Nº celular ------ Codigo de area





(muchos a muchos)
Cuando llamamos a una relacion " Muchos a muchos " nos referiamos a que varios registros de una tabla se asocian a varios registros de otra.


EJEMPLOS:

Estudiantes ---------- carreras

Clientes ------- productos

club de futbol --- Hinchas 



2º : Investigar que es un SGBD (cuales son los mas famosos)

SGBD (sistema de gestion de bases de datos) : es un conjunto de programas que permite el almacenamiento, modificacion y extraccion de la informacion que se encuentra en una base de datos.

siendo algunos ejemplos de estos mismos: Oracle, DB2, MySQL, MS SQL Server..


3º : En que se diferencian las relaciones y las no relacionales

Las bases de datos relacionales se basan en la organización de la información en partes pequeñas que se integran mediante identificadores; a diferencia de las bases de datos no relacionales que, como su nombre lo indica, no tienen un identificador que sirva para relacionar dos o más conjuntos de datos.
