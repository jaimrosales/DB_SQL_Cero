Curso de bade de datos SQL desde Cero

Que es una base de datos? es un ocnjunto de informacion Organizada, almacenada en un medio electronico

Caracteristicas
    -Versatilidad en la representacion de la informacion
    - Tiene que tener desempeno
    -Redundancia: En DB relacionales la redundancia es minima, en no relacionales no importa
    -simple
    integra: el dato debe ser consistente con el que se almacena, hashasta que el usuario decida cambiarlo
    -segura- debe dar diferentes permisos de edicinedicion que se otorguen a los usuarios
    -privacidad: debe guardar privacidad de acuerdo con los permisos asi deseados

Tipos de DB
    -Relaciones: permiten evitar redundancia, evitan repetir informacion,normalizacion  de datos con el objetivo de mantener la redundancia al minimo. Entre ellas sqlserver,potgres,MySQL,MariaDB, Oracle
    -No relacionales: permiten consultar grandes cantitades de datos de manera eficiente. Se permite la redundancia de datos con el objetivo de evitar los join
        Documentales:almacenan su informacion en archivos tipos json, MongoDB
        Clave-Valor: Redis
        Grafos: neo4j,Dgraph, utilizan la teroria de grafos para almacenar la informacion

Sistema gestor de base de datos
    Es un objeto que permite administrar todos los objetos de una base de datos, Bases de datos,tablas, usuarios, indices
        -Crear objetos(base de datos, tablas,usuarios)
        -Modificar
        -Registrar
        Actualizar
        -seleccionar
        -Borrar
        -Administrar privilegios

