# Tipos de almacenamiento


## TAREA 1 | TEMA DEL GRUPO | BASE DE DATOS DE OBJETOS
 
### Autores: 
Carmen y Judith
 
### Origen, ¿Cuándo surgió? ¿Cómo se popularizó?:

Las bases de datos de objetos surgieron en la década de 1960, gracias a los esfuerzos de Kristen Nygaard y Ole-Johan Dahl, pioneros en el desarrollo de sistemas informáticos. Su objetivo era crear un software que replicara fielmente los objetos físicos en un entorno digital, lo que llevó a la creación del lenguaje de programación Simula-67. 
La popularización de las bases de datos de objetos se produjo en los años 80, impulsada por Alan Kay y Xerox. Utilizando Simula-67 como base, desarrollaron Smalltalk, un lenguaje que eventualmente influyó en la creación de C++. 
En la actualidad, las bases de datos de objetos están recuperando relevancia debido a la creciente demanda de aplicaciones que emplean lenguajes de programación orientados a objetos y al apoyo de las comunidades de software libre y POO. 


### Nivel de adopción:

El uso de las bases de datos orientadas a objetos es relativamente limitado en comparación con las bases de datos relacionales. Su aplicación se centra principalmente en áreas que manejan grandes volúmenes de datos complejos y requieren una representación precisa de objetos del mundo real, como en ingeniería y diseño. 
 
### Descripción del funcionamiento del sistema de almacenamiento:

En términos generales, estas bases de datos utilizan la programación orientada a objetos para almacenar y gestionar datos. 

Componentes y Funcionamiento: 

-  Almacenamiento de Objetos 

   - En lugar de utilizar tablas, las bases de datos orientadas a objetos almacenan los datos en forma de objetos, que son instancias de clases con propiedades y métodos definidos. 

- Integridad de Datos 

  - Implementan mecanismos para asegurar la integridad de los datos, como la gestión de transacciones, control de concurrencia y recuperación ante fallos. 

- Persistencia de Objetos 

  - Los objetos creados bajo este modelo pueden ser almacenados directamente en la base de datos sin necesidad de convertirlos a otro formato, como filas o columnas. 

- Consultas 

  - A diferencia de las bases de datos relacionales, estas utilizan lenguajes de consulta orientados a objetos, que permiten realizar consultas complejas sobre los objetos y sus relaciones. 

 
### Ventajas e inconvenientes:

- Ventajas
  - Son perfectas para trabajar con lenguajes de programación orientados a objetos, facilitando su integración en la base de datos.
  - Permiten manipular conjuntos de datos complejos de manera rápida y eficiente.
  - Cada objeto tiene un identificador único asignado.
  - Las transacciones ACID se completan sólo cuando no hay conflictos entre los datos.
  - Cuentan con un sistema de memoria caché que agiliza su uso.
  - Son capaces de manejar grandes volúmenes de datos.

 - Desventajas
   - Su uso no está muy extendido.
   - Si no están bien optimizadas, pueden ser menos eficientes que las bases de datos relacionales.
   - No tienen estándares claros y definidos.
   - Existe poca documentación disponible.
   - Tienen una curva de aprendizaje pronunciada. 
 
### Usos:

La utilización de las bases de datos orientadas a objetos se limita a áreas muy específicas, como la ingeniería, las telecomunicaciones y la biología molecular, porque permiten una manipulación y visualización de datos mucho más sencilla y directa. 

En resumen, su uso se centra en el almacenamiento y manejo de datos muy complejos y/o voluminosos, permitiendo establecer relaciones directas entre los datos, sin necesidad de distribuirlos en tablas como en las bases de datos tradicionales. 
 
### Tipos: Tipos de ficheros, bases de datos representativas, etc:

- Ficheros de objetos puros
   - Almacenan objetos completos, incluyendo sus atributos y métodos

 - Ficheros de objetos relacionales
   - Combinan las caracteristicas de diferentes modelos de bases de datos y pueden manejar tanto datos estructurados como no esctructurados

- Bases de Datos Representativas
  - Db4o
     - Base de datos orientada a objetos, ideal para Java y .NET.
  - ObjectDB
     -  Optimizada para aplicaciones Java.
  - Versant Object Database
     - Ofrece gran rendimiento y escalabilidad, utilizada en aplicaciones empresariales.
  - GemStone/S
     - Soporta Smalltalk, adecuada para aplicaciones críticas. 

### Casos de uso reales observados:

Tienda de material deportivo: En una base de datos de objetos, cada artículo se guarda con sus atributos y métodos. Por ejemplo, unos patines azules, tanto para niños como para adultos. Los patines pertenecen a la clase <patines>, donde también podemos incluir patines de otros colores. La clase patines es una subcategoría de “productos deportivos con ruedas” y puede extenderse según sea necesario. Al acceder mediante el código identificador único del objeto, obtenemos todos sus métodos y atributos. 

Sistema de información geográfica: Los datos geográficos pueden representarse como objetos. Por ejemplo, un objeto “Ciudad” con atributos como “nombre, población y ubicación”, donde “ubicación” puede ser un objeto geográfico. Las bases de datos orientadas a objetos permiten almacenar y manipular estos datos espaciales de manera más directa que en una base de datos relacional. 

Gestión de contenidos multimedia: Este caso puede abordarse de diversas maneras, similar a los anteriores. Por ejemplo, un objeto “Video” podría tener

