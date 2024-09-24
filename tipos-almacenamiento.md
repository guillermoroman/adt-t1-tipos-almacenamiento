# Tipos de almacenamiento
1. [Bases de datos NoSQL](## Bases de Datos NoSQL)



##  Bases de Datos NoSQL

### Origen

El origen de las bases de datos no relacionales se remonta a finales de la década de los 90, cuando Carlos Strozzi lo usó por primera vez para referirse a su base de código abierto la cual no ofrecía un lenguaje SQL. 

A pesar de esto, el término no adquirió popularidad hasta 2009 gracias a un empleado de la empresa Rackspace quien lo empleó para descubrir y distribuir una nueva generación de bases no relacionales.

## Nivel de Adopción

El motivo principal de que aumentara su empleabilidad fue ocasionado por la llegada del Big Data, con la necesidad de sistemas capaces de manejar cantidades grandes de información no estructurada (mensajes en redes sociales, imágenes, datos, etc). El sistema de las bases NoSQL resultó ser muy eficiente para gestionar esta clase de datos al ser más eficiente que las estructuras rígidas de las bases relacionales. 

## Ventajas

1. Son más flexibles para elaborar esquemas de información
2. Fácilmente escalables horizontalmente, utilizadas para trabajar con grandes volúmenes de información
3. Su rendimiento es alto debido a que se han preparado para trabajar con patrones y modelos de datos específicos
4. Gracias a sus API exclusivas y la proporción de modelos creados para gestionar los distintos tipos de datos se han convertido en un sistema de almacenamiento muy funcional

## Inconvenientes

1. Son incompatibles con las consultas realizadas en lenguaje SQL
2. No tienen un sistema estandarizado
3. No poseen el soporte que puede proporcionar una empresa comercial al ser de código abierto
4. Suelen tener problemas de compatibilidad dado que no comparten un estándar

## Descripción del Funcionamiento

Las bases de datos no relacionales se emplean para almacenar datos no estructurados, de los que no se tiene ninguna información predefinida. Sin embargo, también se pueden utilizar para el almacenamiento y gestión de datos estructurados. En el ejemplo de una base de datos en la que se almacenarán DVDs de películas, estos podrían almacenarse en cuanto al título, fecha de estreno, género y director. 

En el caso de las bases de datos no relacionales, cada registro de una película se almacena como un único documento JSON. Todas se almacenan en un solo documento, es decir, que este almacenamiento nos ayuda a tener mayor escalabilidad horizontal y un desarrollo más intuitivo.

## Tipos

### Clave-valor

En este tipo de bases de datos no relacionales almacena la información en pares formados por una clave y su correspondiente valor. La clave actúa como un identificador único, mientras que el valor contiene los datos asociados. Este modelo es ideal para aplicaciones que requieren rapidez y escalabilidad, como en el caso de videojuegos, dispositivos conectados al Internet de las Cosas (IoT) o sistemas de caché.

### Documentos

En este modelo, los datos se almacenan en forma de documentos, generalmente en formato JSON, lo que ofrece flexibilidad y permite manejar estructuras jerárquicas y semiestructuradas. Esto facilita a los desarrolladores el proceso de almacenamiento, gestión y consulta sin tener que ceñirse a un esquema rígido. Es comúnmente empleado en sistemas de gestión de contenidos y en la administración de perfiles de usuarios.

### Gráficos

Las bases de datos de gráficos están diseñadas para gestionar datos que tienen relaciones complejas. Las entidades se representan mediante nodos y las relaciones entre ellas se modelan con aristas. Este enfoque resulta especialmente útil en redes sociales, motores de recomendación y sistemas dedicados a la detección y prevención de fraudes.

### En memoria

Las bases de datos en memoria están pensadas para ofrecer respuestas extremadamente rápidas, con tiempos de acceso medidos en milisegundos. Son capaces de manejar grandes volúmenes de tráfico, lo que las convierte en una solución ideal para aplicaciones que requieren procesamiento en tiempo real, como clasificaciones en videojuegos o herramientas de análisis de datos en tiempo real.

## Usos

Las bases de datos NoSQL sobresalen en casos donde es necesario manejar una gran cantidad de usuarios distribuidos globalmente, brindando experiencias altamente personalizadas. Este tipo de aplicaciones interactivas se benefician de la flexibilidad y agilidad que ofrecen las bases de datos NoSQL.

Estas bases de datos priorizan la alta disponibilidad, proporcionan un rendimiento constante, escalan horizontalmente de manera rápida sin interrupciones y son capaces de gestionar grandes volúmenes de datos variados.

Estas características hacen que las bases de datos NoSQL sean ideales para aplicaciones que requieren alta escalabilidad, confiabilidad y disponibilidad continua.

Entre los casos de uso más comunes de NoSQL se encuentran:

- Aplicaciones web, IoT y móviles
- Aplicaciones web en tiempo real
- Personalización, recomendaciones y experiencias en tiempo real para los usuarios
- Gestión de inventarios y catálogos
- Detección de fraudes y autenticación de identidad
- Tecnología publicitaria

Illán Y Samuel.

## Ficheros

## Autores
Illán Y Samuel.
### Origen. ¿Cuándo surgió? ¿Cómo se popularizó?
Los primeros ficheros informáticos fueron en tarjeta perforada (ya la máquina de Hollerith para el censo de 1890 funcionaba con ellas). Un fichero en tarjetas perforadas es un bloque de tarjetas que tienen perforaciones que representan los caracteres que componen la información del registro. 
Los bloques de tarjetas se procesaban todos completos: se comenzaba a leer desde la primera tarjeta hasta alcanzar la última. Por tanto, si por algún motivo era necesario acceder exclusivamente a un registro, se debía leer secuencialmente todo el bloque, desde el principio, hasta llegar a él.

### Nivel de adopción.
Hoy en día los archivos son una parte esencial de nuestra vida diaria, tanto a nivel personal como profesional. Se utilizan en una variedad de contextos, desde la gestión de datos corporativos hasta el almacenamiento de fotografías y vídeos personales. La seguridad de los archivos y la protección de datos también se han convertido en temas importantes, con énfasis en el cifrado y la protección de datos.
En resumen, el uso de archivos ha aumentado y cambiado mucho a lo largo de la historia, según las necesidades tecnológicas y sociales de cada época.

### Descripción del funcionamiento del sistema de almacenamiento
La información se organiza en estructuras de datos, que pueden ser simples o complejas. Por ejemplo, un archivo de texto almacena caracteres en una matriz lineal, mientras que un archivo de base de datos puede contener tablas con filas y columnas.
En un dispositivo de almacenamiento, los archivos se organizan en un sistema de archivos. Este sistema gestiona cómo se almacenan y recuperan los archivos, asigna espacio en disco y mantiene una lista de archivos disponibles.
La información se puede codificar y comprimir para optimizar el espacio de almacenamiento. La compresión reduce el tamaño del archivo, lo que permite almacenar más datos en menos espacio.

### Ventajas e inconvenientes
Ventajas:
1. Homogeneización de documentos.
2. Ahorro de espacio físico y tiempo.
3. Mayor eficiencia en la gestión empresarial.
4. Resguardo seguro de documentos.
5. Eliminación de riesgos.

Desventajas:
1. Dificultad en el acceso a los datos.
2. Aislamiento de datos.
3. Anomalías en el acceso concurrente.
4. Problemas de integridad.

### Usos
Un fichero es un registro en el que se van a recoger y almacenar los datos que quieras guardar en él
Es un contenedor de información. La mayoría de los archivos que se utilizan contienen información en un formato determinado: un documento, una hoja de cálculo, un gráfico. El formato es la disposición de los datos dentro del archivo. El formato del archivo se conoce como tipo de datos.
Cuando el Gestor de archivos está en uno de sus modos de vista de iconos, puede identificar el tipo de datos de un archivo por el icono que se utiliza para representar el archivo. Cada tipo de datos tiene un icono diferente.

## Tipos: Tipos de ficheros, bases de datos representativas, etc.
Existen prácticamente infinitos tipos de ficheros pero los mas comunes son :
Texto: txt, md, rtf…
Ofimática: docx, xlsx, pptx, odt, ods, odp…
Imagen: jpg, gif, bmp, png, heic, webp…
Vídeo: avi, mov, mp4, mpeg, wmv…
Ejecución del sistema: exe, bat, dll, sys…
Audio: mp3, aac, ogg, wav, wma…
Archivo comprimido: zip, rar, tar…
Lectura: pdf, epub, azw, ibook…
Imagen de disco: iso, mds, img…

### Casos de uso reales observados (mínimo 3 ejemplos)
los casos de uso de ficheros describen situaciones específicas en las que se utilizan archivos para cumplir con ciertos objetivos, como almacenar, intercambiar o procesar información.
ejemplos:  Almacenamiento de Configuraciones, Exportación de Datos y Registro de Actividades


## Titulo: Bases de Datos Relacionales

### [Autores: Paula / Iván / Leire]

### [¿Qué es una base de datos relacional?]. 
Una base de datos relacional (RDB) es una forma de estructurar información en tablas, filas y columnas. Un RDB tiene la capacidad de establecer vínculos (o relaciones) entre información mediante la unión de tablas, lo que facilita la comprensión y la obtención de estadísticas sobre la relación entre varios datos. 

### [Diferencia entre bases de datos relacionales y no relacionales:] 

La principal diferencia entre las bases de datos relacionales y no relacionales (bases de datos NoSQL) es la forma en que se almacenan y organizan los datos. Las bases de datos no relacionales no almacenan datos de manera tabular y basada en reglas. En su lugar, almacenan datos como archivos individuales y no conectados, y se pueden usar para tipos de datos complejos y no estructurados, como documentos o archivos de rich media.

### [Origen:] 

Las bases de datos relacionales (RDBMS) surgieron en los años setenta y fueron concebidas para un dominio muy específico, que era la gestión de los datos tabulares, es decir, datos provenientes de formularios de papel y en los que se pudiesen aplicar operaciones CRUD (create, read, update, delete).  

En algunos casos, lo solucionaron prescindiendo de algunas características en favor de otras, por ejemplo: eliminando las constraints, desnormalizando los datos, desactivando la transaccionalidad para casos específicos de reporting, etc. Todos estos cambios dieron origen a las bases de datos NoSQL.    

Por otra parte, se buscaba mejorar algo que curiosamente se les da mal a las RDBMS, principalmente debido a que las consultas en las RDBMS son imperativas, a pesar de que en el modelo se definan las relaciones. Esto es una gran desventaja, ya que en algunos casos induce a que las consultas (query) sean complejas, difíciles de mantener y lentas. 

### [Nivel de adopción] 
Las bases de datos relacionales (RDBMS) son populares en la industria por su estructura en tablas y capacidad para mantener la integridad de los datos mediante relaciones entre tablas. Ejemplos comunes incluyen MySQL, PostgreSQL, Oracle y SQL Server, preferidos en entornos empresariales por su madurez y uso estandarizado de SQL.  

Además, cuentan con un ecosistema robusto de herramientas, amplia documentación y desarrolladores experimentados. Sin embargo, tienen limitaciones con datos no estructurados o grandes volúmenes de datos, donde las bases NoSQL son más eficientes. 

### [Funcionamiento del sistema de almacenamiento] 
Las bases de datos relacionales almacenan datos en tablas compuestas por filas (registros) y columnas (atributos). Las claves primarias identifican de manera única cada registro, mientras que las claves foráneas conectan tablas, referenciando claves primarias de otras tablas. Los usuarios interactúan con la base de datos mediante SQL para gestionar datos. 

Además, soportan transacciones, que son conjuntos de operaciones que deben completarse en su totalidad para mantener la consistencia e integridad de los datos. 

### [Ventajas e Inconvenientes:] 
1) **Ventajas:**
 El principal beneficio del modelo de base de datos relacional es que proporciona una manera intuitiva de representar datos y permite un acceso fácil a datos relacionados. 

-Flexibilidad: Es fácil agregar, actualizar o borrar tablas, relaciones y hacer otros cambios a los datos cuando lo necesites sin cambiar la estructura general de la base de datos ni afectar las aplicaciones existentes. 

-Cumplimiento de ACID: Las bases de datos relacionales admiten el cumplimiento de ACID (atomicidad, coherencia, aislamiento y durabilidad) para garantizar la validez de los datos, sin importar si se producen errores, fallas o contratiempos de otro tipo. 

-Facilidad de uso: Es fácil ejecutar consultas complejas con SQL, lo que permite que incluso los usuarios no técnicos aprendan a interactuar con la base de datos. 

-Colaboración: Varias personas pueden operar y acceder a datos de manera simultánea. El bloqueo integrado impide el acceso simultáneo a los datos cuando se actualizan. 

-Seguridad Integrada: La seguridad basada en roles garantiza que el acceso a los datos esté limitado a usuarios específicos. 

-Normalización de Bases de Datos: Las bases de datos relacionales usan una técnica de diseño conocida como normalización que reduce la redundancia de los datos y mejora su integridad. 

2) **Inconvenientes:**
-Escalabilidad limitada: Las RDBMS suelen tener dificultades para escalar horizontalmente (añadir más servidores), lo que las hace menos eficientes en grandes volúmenes de datos distribuidos.

-Consultas complejas y lentas: Las consultas SQL pueden volverse muy complejas y difíciles de mantener, especialmente con datos altamente relacionados. Esto puede afectar el rendimiento.

-Rigidez en el esquema: El esquema de una base de datos relacional es rígido y estructurado, lo que hace que sea complicado modificar la estructura de las tablas cuando cambian los requisitos del negocio o de la aplicación.

-Altos costos de transacciones: Aunque las RDBMS soportan transacciones ACID (Atomicidad, Consistencia, Aislamiento, Durabilidad), mantener estas propiedades puede ser costoso en términos de rendimiento, especialmente en grandes volúmenes de datos.

-Ineficiencia con datos no estructurados: Las RDBMS no son adecuadas para gestionar datos no estructurados o semi-estructurados como documentos, imágenes, videos o grandes conjuntos de datos sin un formato claro.

-Sobrecarga de administración: La necesidad de mantener la integridad referencial, constraints, y otras características propias de las RDBMS puede generar sobrecarga de administración y más tiempo de desarrollo. 

### [Usos:]
se usan para rastrear inventarios, procesar transacciones de comercio electrónico, administrar cantidades enormes y esenciales de información de clientes y mucho más. 

### [Tipos:] 
-Oracle: Almacena y facilita el manejo de grandes cantidades de información relacionada entre sí.
-My SQL: Permite almacenar, organizar y recuperar datos de manera eficiente.
-PostgreSQL: Código abierto, altamente estable, que proporciona soporte a diferentes funciones de SQL.
-DB2:  Base de datos nativa de cloud creada para impulsar transacciones de baja latencia, análisis en tiempo real y aplicaciones de IA a escala

### [Casos de uso reales observados:]  

- Sistema de cajero automatico 

- Sistema de facturacion en el aeropuerto 

- Sistema de gestion de usuarios  

## Ficheros

### Autores. Alumnos que han participado en la elaboración.

- David González García
- Óscar Gaztelu Menéndez
- David Collados Blanco

### Origen. ¿Cuándo surgió? ¿Cómo se popularizó?

Los primeros ficheros informáticos fueron en tarjeta perforada en el siglo XIX (donde ya la máquina de Hollerith para el censo de 1890 funcionaba con ellas). Un fichero en tarjetas perforadas es un bloque de tarjetas que tienen perforaciones que representan los caracteres que componen la información del registro.
 
Después, a partir de principios de la década de 1950, fue la cinta magnética la que tomó el relevo… y esta vez para quedarse. Una cinta de 2.400 pies, la habitual a partir de los sesentas, grabada a 1600 ppi (phrames per inch, o caracteres por pulgada) podía almacenar unos 50 Mb de información… cuando los carísimos discos de la época podían almacenar quizá tres o cuatro.
 
En 1889, Herman Hollerith había desarrollado un sistema de tarjetas perforadas eléctricas y basado en la lógica de Boole, aplicándolo a la tabulacion en Estados Unidos. La máquina tenía un lector de tarjetas, un contador, un clasificador y un tabulador creado por el mismo. Así, en 1896, Hollerith crea la Tabulating Machine Company, con la que pretendía comercializar su máquina.

### Nivel de adopción

Los ficheros informáticos almacenan información según sea necesario, estos se adaptan a varias cosas, una de ellas pueden ser los logs.Los archivos log funcionan como el registro oficial de todas las actividades que ocurren dentro de un sistema informático. Cada vez que se ejecuta una operación, ya sea de forma manual o automática, se genera una entrada de texto en el archivo log correspondiente.
 
Por otro lado también se usan en bases de datos. Un fichero de base de datos contiene descripciones de cómo se van a presentar los datos de entrada a un programa desde el almacenamiento interno y cómo se van a presentar los datos de salida al almacenamiento interno desde un programa.
 
Por último aquí se puede ver la importancia que tienen los ficheros y como la gente se ha adaptado a ellos mediante encuestas, y aquí voy a mostrar alguna de ellas: un promedio de 69 % de usuarios de Argentina, Brasil y México, están más preocupados por perder sus archivos digitales que por extraviar sus objetos físicos.
 
Además, la mayoría de usuarios (86 %) de esos países saben lo que es un backup y una copia de respaldo, un 88 % efectivamente lo realiza y el 93 % cuenta con algún dispositivo físico o solución de almacenamiento en línea/en la nube.

### Descripción del funcionamiento del sistema de almacenamiento

[text](https://www.it.uc3m.es/pbasanta/asng/course_notes/data_modeling_data_storage_en.html)

Para almacenar los datos en ficheros de forma persistente, una de las cuestiones a tener en cuenta es que se requiere utilizar ciertos métodos para poner una limitación sobre cuándo empieza un elemento y cuándo acaba este elemento, cuándo empieza un campo de datos y cuándo acaba este campo de datos, o cuándo no hay más elementos en un fichero. De este modo, por ejemplo, si se necesita almacenar una cadena de longitud indefinida, una posible solución sería añadir un campo adicional para indicar la longitud de la cadena (en bytes) en el fichero.
 
La siguiente imagen muestra una forma de almacenar la información sobre fotos y autores en un único fichero. Podemos observar que inicialmente hay 4 bytes reservados para indicar en el fichero el número total de fotos que habrá almacenadas en el fichero, y a continuación estará la información de cada una de las fotos, incluyendo su información de autor. Para cada entero, habrá 4 bytes en el fichero para almacenarlo, pero habrá un campo adicional de 4 bytes para cada cadena que indicará la longitud en bytes de la cadena, para poder localizarla.
 
Existen diferentes formas de almacenar la misma información. Otra forma de almacenar la información disponible en el fichero, es la que se muestra en la siguiente figura. Aquí, la información se almacena dividida por autores. De esta forma, hay un campo inicial de 4 bytes, que indica el número total de autores almacenados, y a continuación la información de cada autor. Para cada autor, estarán los datos propios de cada autor, y cuando se termine la información sobre un autor, a continuación un número almacenado de 4 bytes, que indica el número total de fotos que han sido tomadas por este autor. Por último, está la información asociada a cada una de estas fotos.
 
La elección para decidir una de las diferentes formas de almacenar la información en un fichero, depende de un análisis en el que se deben tener en cuenta las diferentes ventajas e inconvenientes, y existe un trade-off. En este sentido, hay que tener en cuenta qué solución ocupará más espacio en un fichero (en el caso presentado, la primera opción ocupará más espacio, porque la misma información de autor debe replicarse varias veces), o cuál será más eficaz para el tiempo de ejecución de las operaciones requeridas por la aplicación. Por ejemplo, si una aplicación requiere listar las fotos de un autor concreto muchas veces, entonces para esta operación será más efectiva la segunda elección, porque las fotos ya estarían ordenadas por autor, por lo que la aplicación no tendría que buscar foto a foto, sino que una vez localizado el autor toda la información estaría en posiciones consecutivas del fichero. Sin embargo, una aplicación que sólo requiriese listar todas las fotos del sistema con su información, sin ordenarlas por autor, entonces sería más efectiva la primera opción, porque para añadir una nueva foto, la aplicación puede hacerlo al final del fichero, sin necesidad de meter la foto en el fichero para agruparla con su autor.

### Ventajas e inconvenientes

### Ventajas

1. **Sencillez**
- Fácil de implementar: Leer y escribir en archivos puede ser sencillo y requiere una configuración mínima.
- Sin software adicional: Puede utilizar el almacenamiento de archivos sin necesidad de un servidor de bases de datos.

2. **Rendimiento para conjuntos de datos pequeños**
- Acceso rápido a archivos pequeños: Para pequeñas cantidades de datos, la E/S de archivos puede ser bastante rápida, especialmente si los datos ya están en memoria.

3. **Portabilidad**
- Fácil de trasladar: los archivos pueden copiarse, trasladarse o compartirse fácilmente entre sistemas.

4. **Coste**
- Sin costes de licencia: El uso del sistema de archivos evita los costes asociados a las licencias de bases de datos o a los servicios de bases de datos alojadas.

5. **Menos gastos generales**
- Uso mínimo de recursos: Se puede acceder a los archivos con menos sobrecarga que con un sistema de gestión de bases de datos.

### Desventajas

1. **Escalabilidad**
- Degradación del rendimiento: A medida que crece la cantidad de datos, el acceso a los archivos puede volverse más lento y menos eficiente.
- Dificultad para gestionar grandes conjuntos de datos: La búsqueda y gestión de archivos de gran tamaño puede resultar engorrosa.

2. **Problemas de concurrencia**
- Acceso concurrente limitado: Manejar múltiples operaciones de lectura/escritura simultáneamente puede llevar a la corrupción de datos o inconsistencias.

3. **Falta de funciones avanzadas**
- Sin indexación integrada: La búsqueda en archivos puede ser lenta sin mecanismos de indexación.
- Sin transacciones: Los ficheros no admiten transacciones, lo que hace más difícil garantizar la integridad de los datos.

4. **Redundancia de datos**
- Aumento de la duplicación: Sin un esquema estructurado, es fácil crear datos redundantes en diferentes archivos.

5. **Copias de seguridad y recuperación**
- Procesos manuales: Las copias de seguridad y la recuperación de datos de archivos pueden ser más complejas y menos fiables en comparación con las bases de datos.

### Usos

Los ficheros son fundamentales en el mundo digital y tienen una amplia variedad de usos.

1. **Almacenamiento de datos**
Los ficheros se utilizan para almacenar datos de manera organizada. Esto incluye documentos de texto, hojas de cálculo y bases de datos. Podemos guardar información de manera permanente o temporal.

2. **Intercambio de información** 
Este es el uso de los ficheros de intercambio de datos. Estos comunican diferentes usuarios y sistemas.

3. **Configuración de software**
Muchos programas utilizan ficheros de configuración para almacenar preferencias y ajustes del usuario.

4. **Almacenamiento multimedia**
Los ficheros de imagen, audio y video son esenciales para el almacenamiento y la reproducción de contenido multimedia.

5. **Desarrollo de software**
Los ficheros son utilizados para almacenar código fuente, bibliotecas y recursos necesarios para construir aplicaciones.

6. **Respaldo y recuperación**
Para realizar una copia de seguridad, necesitamos una gran cantidad de ficheros. Estos permiten que la información pueda ser recuperada en caso de pérdida o daño.

7. **Registro de actividades**
Los ficheros de registro (logs) son utilizados por sistemas y aplicaciones para registrar eventos y actividades.

8. **Interacción con bases de datos**
Los ficheros también se utilizan para importar y exportar datos en las bases de datos. Formatos como SQL y XML son comunes para este propósito.

### Tipos: Tipos de ficheros, bases de datos representativas, etc.

Los ficheros se pueden clasificar en varias categorías según su contenido y propósito. 

1. **Ficheros de texto**
Son archivos que contienen texto legible por humanos. Pueden ser simples, como los archivos .txt, o más complejos como los .csv, que contienen valores separados por comas. Estos archivos se utilizan para almacenar datos tubulares.

2. **Ficheros binarios**
Estos archivos contienen datos en un formato que no es legible directamente por humanos. Un ejemplo bastante común de fichero binario son las imágenes de formato .jpg.

3. **Ficheros de intercambio de datos**
Estos son formatos diseñados específicamente para facilitar la transferencia de datos entre diferentes sistemas o aplicaciones. Los ficheros XML son un ejemplo de fichero de intercambio de datos.

4. **Ficheros propietarios**
Son aquellos diseñados para ser utilizados con un software específico y no son fácilmente accesibles o editables por otros programas. Los archivos .psd (Adobe Photoshop) son considerados propietarios, ya que requieren el software correspondiente para abrirse y modificarse adecuadamente. 

### Casos de uso reales observados

- **Ficheros de extensión .exe**
Estos ficheros son generalmente utilizados para instalar aplicaciones en sistemas operativos Windows. Al hacer doble clic en este archivo, se inicia el proceso de instalación que copia los archivos necesarios al sistema y configura el software para su uso.

- **Ficheros de extensión json**
Los ficheros .json son utilizados para desarrollar aplicaciones web que intercambian información entre cliente y servidor. Un ejemplo sería una aplicación de clima. El servidor responde enviando un fichero .json que contiene datos como la temperatura, la humedad y las condiciones climáticas. La aplicación web analiza este fichero y presenta la información al usuario de manera visual.

- **Ficheros de extensión .word**
Son utilizados para crear y editar documentos en Microsoft Word. Un caso de uso común es la redacción de informes, propuestas o currículos. 

## Bases de datos no relacionales
### Alumnos que han participado
`Miguel Fernández Vallés y Jorge Fresno Menéndez`
### Origen. ¿Cuándo surgió? ¿Cómo se popularizó?
Surgen como respuesta a las limitaciones que tienen las bases de datos relacionales. Se crean en 1998, no por una empresa o entidad particular si no por diferentes empresas como Google, Amazon, Facebook... y creadores de grandes proyectos open source como MongoDB, Cassandra... solucionando las carencias de las RDBMS.

Comenzaron a ganar relevancia a mediados de la década de 2000, impulsadas por la necesidad de almacenar y procesar grandes volúmenes de datos generados por aplicaciones web 2.0, redes sociales y el Internet de las Cosas (IoT).

### Nivel de adopción
Aunque las bases de datos más usadas siguen siendo las relacionales, las bases de datos no relacionales han aumentado su uso hasta situar a MongoDB como la quinta base de datos más usada. Muchas empresas de todos los tamaños las utilizan para diversas aplicaciones, desde startups hasta grandes corporaciones. La elección de una base de datos NoSQL depende de las necesidades específicas de cada proyecto, como el tipo de datos, el volumen, la frecuencia de acceso y los requisitos de rendimiento.

Estas son las bases de datos más usadas, donde podemos ver a MongoDB en el quinto lugar:
![Bases más usadas](https://learnsql.es/blog/las-bases-de-datos-mas-populares-en-2023/most-popular-databases-2023-3.webp)

### Descripción del funcionamiento del sistema de almacenamiento
En lugar de utilizar tablas y relaciones con las bases de datos relacionales, emplean modelos de datos más flexibles como:

- ***Clave-Valor***: Cada dato se almacena como un par único de clave y valor. Por ejemplo una simple lista de compras donde cada ítem (clave) tiene asociado un valor (cantidad).
- ***Documentos***: Los documentos almacenan datos en un formato similar a JSON, lo que permite estructuras anidadas y flexibles. Esto significa que puedes tener objetos dentro de objetos, creando estructuras de datos más complejas y representativas de la información real.
- ***Columnas***: A diferencia de las bases de datos relacionales que organizan los datos en filas y columnas, las bases de datos de columnas invierten esta lógica. Los datos se organizan en columnas, y cada columna puede tener diferentes tipos de datos.
- ***Gráficos***: Los datos se representan como nodos (entidades) y relaciones (conexiones) entre ellos. Esto permite modelar datos con relaciones complejas y jerárquicas.

### Ventajas e incovenientes
**Ventajas**
1. *Escalabilidad*: Gracias a su escalabilidad horizontal frente a la vertical de las relacionales, en lugar de aumentar la potencial del servidor, puedes agregar más servidores para aumentar la carga de trabajo.
2. *Flexibilidad*: No se limitan a un esquema rígido, permitiendo adaptarse fácilmente a los cambios en datos y nuevos tipos de información.
3. *Rendimiento optimizado*: Al diseñarse para un tipo específico de trabajo, pueden ofrecer un rendimiento superior en ciertas operaciones, como lecturas y escrituras de alta velocidad.
4.  *Economía*: No se necesitan servidores con gran cantidad de recursos para operar.

**Desventajas**
1. *Madurez*: Algunas bases de datos NoSQL aún están en desarrollo y pueden carecer de algunas características o funcionalidades.
2. *Falta de estándares*: : No se tiene un criterio plenamente definido, variando el lenguaje según el tipo de base de datos que se vaya a utilizar.
3. *Complejidad*: La gestión es más compleja que en una base de datos relacional.
4. *Herramientas GUI:*  La mayoría de las bases de datos NoSQL no contienen una interfaz gráfica. Requiere conocimiento especial para poder ejecutarlas.

### Usos
Una base de datos NoSQL es la mejor opción para gestionar datos indeterminados, no relacionados o que cambian rápidamente. Pueden usarse para aplicaciones que cumplan:
+ Necesidad de esquemas flexibles que permitan un desarrollo más rápido e iterativo.
+ Realizar consultas complejas y uniones entre tablas.
+ Exigencia de un escalado horizontal mediante la fragmentación de los servidores.
+ Alto nivel de integridad de los datos y transacciones ACID (atomicidad, coherencia, aislamiento y durabilidad).

### Tipos
#### Bases de datos clave-valor
Son las más sencillas de todas y almacenan datos en una organización de pares de clave y valor. Son las que permiten más altas velocidades en la lectura y escritura de datos y se usan principalmente en sistemas de almacenamiento en caché.

![Clave-valor](https://www.certia.net/wp-content/uploads/2021/03/Clave_Valor.jpg)
#### Bases de datos de documentos
Las bases de datos de documentos almacenan datos en colecciones, siendo los elementos de cada una de esas colecciones documentos que contienen pares clave/valor. Además de también tener un identificador único para cada documento, los campos de los que consta este documento sí son transparentes para el sistema de administración.

![Documentos](https://www.certia.net/wp-content/uploads/2021/03/Documento-JSON.jpg)
#### Bases de datos de columnas anchas
Están pensadas para requerir menos consultas a la hora de recuperar datos puesto que guardan todos los datos relacionados en “grupos”, teniendo cada familia de columnas un conjunto de columnas con una relación lógica entre ellas.

![Columnas](https://www.certia.net/wp-content/uploads/2021/03/Familia-columnas.jpg)
#### Bases de datos orientadas a grafos
Están compuestas por documentos que se relacionan entre sí y que permiten representar relaciones complejas entre los datos y así realizar consultas eficientes a través de los nodos y aristas analizando sus relaciones.

![Grafos](https://www.certia.net/wp-content/uploads/2021/03/Grafos.png)

### Casos de uso reales observados
1. **Redes sociales**

![Redes](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQKrFhY-ljA-u7J5IMWeTv8zmpBx4PP9nQMw&s)

Facebook utiliza Cassandra para manejar los datos generados por usuarios como comentarios, likes, publicaciones...X utiliza también Cassandra y Storm para procesar en tiempo real los tweets y construir un índice de búsqueda invertido.

2. **Comercio electrónico**

![Comercio](https://brandemia.org/contenido/subidas/2022/11/logo-amazon-2000-actualidad-1024x576.png)

Utiliza DynamoDB para almacenar información de productos, pedidos, recomendaciones y datos de clientes en tiempo real. Esto les permite ofrecer una experiencia de compra personalizada y escalable.

3. **Juegos en Línea**

![Juego](https://brand.riotgames.com/static/a91000434ed683358004b85c95d43ce0/8a20a/lol-logo.png)

Riot Games emplea Cassandra para manejar la gran cantidad de datos generados por League of Legends, como estadísticas de partidas, perfiles de jugadores y chat.

Blizzard Entertainment utiliza MongoDB para almacenar datos de los jugadores, como personajes, inventario y progreso en el juego.

4. **Plataformas de streaming**

![Netflix](https://m.media-amazon.com/images/I/51LGj5--KsL.png)

Netflix emplea Cassandra para almacenar datos de usuarios, como historial de visualización, calificaciones y recomendaciones. También utiliza Elasticsearch para realizar búsquedas de contenido.

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

- Caso 1: Gestión de Usuarios en una Aplicación Web
   - Cada usuario es un objeto con atributos como nombre, email, contraseña y métodos como actualizarPerfil() o verificarContraseña(). Los usuarios administradores heredan de la clase Usuario, añadiendo métodos para gestionar permisos y otros usuarios.

- Caso 2: Sistema de Gestión de Proyectos de Software
  - Los proyectos se representan como objetos que contienen otros objetos, como tareas, archivos y colaboradores. Cada proyecto tiene atributos como nombre, fecha de entrega, y métodos como agregarTarea() o asignarColaborador(). 

- Caso 3: Gestión de Recursos Multimedia en un Servidor
  - Los proyectos se representan como objetos que contienen otros objetos, como tareas, archivos y colaboradores. Cada proyecto tiene atributos como nombre, fecha de entrega, y métodos como agregarTarea() o asignarColaborador().


## Bases de Datos Orientadas a Objetos (BDOO)

### Autores
* Luis Iturrioz López
* David Fernández Suco

### Origen y Popularización
El origen se remonta a la década de los 70 con los primeros lenguajes de programación orientados a objetos, pero el término “base de datos orientado a objetos” no nació hasta el 85. La popularización se dio en parte por el aumento de aplicaciones que requerían manejar datos complejos, como gráficos, multimedia y sistemas CAD. Además, la proliferación de lenguajes de programación orientados a objetos, como C++ y Java, facilitó su adopción.

### Nivel de Adopción
La adopción es limitada, aunque tiene ciertos nichos donde son populares, como cuando se trabaja con datos complejos, pero en general distan bastante de estar adoptadas a gran escala. 

### Descripción del funcionamiento del sistema de almacenamiento
Funcionan agrupando en paquetes relacionados la información, estos paquetes son objetos que almacenan la información, a diferencia de otras bases de datos que guardan su información en filas y columnas. Las BDOO emplean lenguajes de programación y se pueden aplicar métodos, clases y subclases.

### Ventajas e inconvenientes
* **Ventajas:**
    * Mayor capacidad de modelado: Representan el mundo real de forma más intuitiva 
    * Flexibilidad: Permiten adaptarse a cambios en los requisitos de una aplicación
    * Manejo de datos complejos: Son ideales para gestionar datos de gran tamaño y complejidad. 
    * Integración con lenguajes orientados a objetos: La integración con lenguajes como Java o C++ es más natural 
    * Reutilización de código: Al permitir la creación de clases y jerarquías de clases, se promueve la reutilización de código. 
* **Inconvenientes:**
    * Complejidad: Requiere un mayor conocimiento y experiencia por parte de los desarrolladores. 
    * Madurez: Las BDOO aún no están tan maduras como las bases de datos relacionales, lo que puede implicar una menor disponibilidad de herramientas y soporte. 
    * Rendimiento: En algunos casos, el rendimiento de las BDOO puede ser inferior al de las bases de datos relacionales, especialmente en consultas complejas
    * Falta de un estándar universal: No existe un estándar universal para las BDOO, lo que dificulta la portabilidad de las aplicaciones entre diferentes sistemas.
    * Costo: Las licencias de los sistemas de gestión de bases de datos orientados a objetos suelen ser más costosas que las de los sistemas relacionales.

### Usos
* Modelado de datos complejos: Son ideales para representar entidades del mundo real con sus atributos y relaciones de manera intuitiva.  
* Gestión de datos multimedia: Gracias a su capacidad para almacenar objetos complejos, son excelentes para manejar imágenes, videos, audio y otros tipos de datos multimedia.
* Gestión de información geográfica (GIS): Los sistemas GIS utilizan BDOO para modelar entidades geográficas como puntos, líneas y polígonos, así como sus atributos y relaciones espaciales. 
* Aplicaciones CAD/CAM: En el diseño asistido por computadora (CAD) y la fabricación asistida por computadora (CAM), permiten representar de forma precisa objetos tridimensionales y sus relaciones geométricas. 
* Inteligencia artificial: Son útiles en aplicaciones de inteligencia artificial, como sistemas expertos y redes neuronales, para representar el conocimiento y los datos de manera estructurada. 

### Tipos
* **BDOO Puras:**
    * Definición: Implementan de forma completa los conceptos de la programación orientada a objetos, como la herencia, el polimorfismo y la encapsulación.
    * Características: Ofrecen un alto nivel de abstracción y una estrecha integración con los lenguajes de programación orientados a objetos.
* **BDOO Híbridas:**
    * Definición: Combinan características de las bases de datos relacionales y orientaadas a objetos.
    * Características: Ofrecen un equilibrio entre la flexibilidad de las BDOO y la eficiencia de las bases de datos relacionales.
* **Objetos-Relacionales:**
    * Definición: Son una evolución de las bases de datos relacionales que añaden soporte para tipos de datos complejos y objetos.
    * Características: Permiten almacenar y manipular tanto datos estructurados como no estructurados, ofreciendo una mayor flexibilidad.

### Casos de uso reales
* **CATIA (CAD)** utiliza BDOO para gestionar la información de los diseños, desde piezas individuales hasta ensamblajes completos. Esto facilita la creación de configuraciones, variantes y la gestión del ciclo de vida del producto.
* **ArcGIS (GIS)** utiliza BDOO para almacenar y gestionar la información geográfica. Por ejemplo, un río puede ser representado como un objeto con atributos como longitud, caudal y calidad del agua, y relacionado con otros objetos como puentes o ciudades.
* **BioJava (Bioinformática)** utiliza BDOO para representar secuencias de proteínas, estructuras 3D y vías metabólicas. Esto facilita el análisis y la comparación de datos biológicos. 



# Trabajo Tema 1 ADT
## Documentos XML
## Mario Sanchez, Guillermo Muñiz, Rubén Arias

### Descripción del funcionamiento del sistema de almacenamiento
Los sistemas de almacenamiento XML no son bases de datos relacionales tradicionales. En lugar de almacenar datos en tablas con filas y columnas, utilizan documentos XML para representar la información. Estos documentos tienen una estructura jerárquica definida por etiquetas, lo que permite organizar los datos de forma lógica y flexible.

**Ventajas:**
* Flexibilidad
* Legibilidad
* Independencia
* Extensibilidad
* Autodescriptivo

**Desventajas:**
* Verbosidad
* Complejidad
* Falta de estandarización
* Rendimiento

**Usos:**
* Intercambio de datos
* Configuración de aplicaciones
* Almacenamiento de datos heterogéneos
* Generación de informes
* Web service


**XML: Un lenguaje de marcado extensible y su evolución**

**Introducción:** XML, o Extensible Markup Language, es un lenguaje de marcado diseñado para almacenar datos de manera estructurada. Su simplicidad y flexibilidad lo han convertido en una herramienta fundamental en el mundo de la informática.

**Objetivo:** En este trabajo exploraremos el origen, surgimiento, popularización y nivel de adopción de los archivos XML.

## Origen y Surgimiento

* **SGML:** XML tiene sus raíces en el Standard Generalized Markup Language (SGML), un lenguaje de marcado muy poderoso pero complejo.
* **Nacimiento de XML:** El Consorcio World Wide Web (W3C) desarrolló XML con el objetivo de crear un lenguaje más simple y flexible que SGML. La primera versión de XML se publicó en 1998.

## Popularización

* **Factores Clave:**
    * **Simplicidad:** Sintaxis clara y fácil de aprender.
    * **Extensibilidad:** Permite crear lenguajes de marcado personalizados.
    * **Independencia de Plataforma:** Funciona en cualquier sistema operativo.
* **Aplicaciones Iniciales:**
    * **Configuración de Aplicaciones:** XML se utilizó ampliamente para configurar aplicaciones de manera flexible.
    * **Intercambio de Datos:** Protocolos como SOAP adoptaron XML para la comunicación entre sistemas.

## Nivel de Adopción Actual

* **Ámbitos de Aplicación:**
    * **Desarrollo Web:** XML sigue siendo utilizado en la creación de sitios web dinámicos.
    * **Integración de Sistemas:** XML es fundamental en la comunicación entre diferentes sistemas.
    * **Gestión de Contenidos:** Muchos CMS utilizan XML para almacenar y gestionar contenido.
* **Alternativas:**
    * **JSON:** Un formato más ligero y popular en el desarrollo web moderno.
    * **YAML:** Otra alternativa con una sintaxis más concisa.
* **Tendencias Futuras:**
    * A pesar de la competencia, XML sigue siendo relevante debido a su estructura sólida y capacidad de representar datos complejos.


### Casos de uso reales observados (mínimo 3 ejemplos)

1. **Ejemplo: Datos meteorológicos**
    * Servicios web como aquellos que exponen datos meteorológicos suelen utilizar XML para encapsular los datos y permitir que otras aplicaciones los consuman.

<weatherdata>
    <location>
        <city>Madrid</city>
        <country>España</country>
    </location>
    <current_condition>
        <temperature value="25" unit="C"/>
        <humidity value="60" />
    </current_condition>
</weatherdata>

2. **Ejemplo: Estructura de un artículo en un CMS**
    * Muchos sistemas de gestión de contenidos (CMS) utilizan XML para almacenar la estructura y el contenido de un sitio web.


<article>
    <title>Mi primer artículo</title>
    <author>Juan Pérez</author>
    <date>2023-11-20</date>
    <body>
        <paragraph>Este es el contenido del artículo.</paragraph>
        <image src="imagen.jpg" alt="Imagen descriptiva"/>
    </body>
</article>

3. **Ejemplo: Configuración de un editor de texto**
    * Muchos editores de texto y entornos de desarrollo integrados (IDEs) utilizan archivos XML para almacenar preferencias del usuario como tamaño de fuente, esquemas de color y atajos de teclado.


<preferences>
    <font-size>12</font-size>
    <theme>dark</theme>
    <keybindings>
        <save>Ctrl+S</save>
        <undo>Ctrl+Z</undo>
    </keybindings>
</preferences>

## Tipos: Tipos de ficheros, bases de datos representativas

### Tipos de ficheros
1. Ficheros XML sencillos: Documentos estructurados con etiquetas que representan la jerarquía de datos. Pueden ser usados para almacenar información de manera estructurada.
 
2. XML Schema (XSD): Esquemas XML que definen la estructura y restricciones de un documento XML. Se utilizan para validar que un archivo XML siga una estructura y formato específico.
 
3. DTD (Document Type Definition): Similar al XSD, pero con una sintaxis diferente. Se usa para validar la estructura de los documentos XML.
 
4. Ficheros RSS/ATOM: Son tipos de documentos XML utilizados en la sindicación de contenido, por ejemplo, en fuentes de noticias o blogs.
 
 
### Bases de Datos Representativas con XML
 
1. Base de datos XML nativa: Son bases de datos que almacenan directamente documentos XML y permiten consultas usando lenguajes como XPath o XQuery.

2. Bases de datos relacionales con soporte XML: Algunas bases de datos relacionales ofrecen soporte para almacenar y consultar datos XML, aunque no son nativas de XML.


### Casos de Uso Reales de XML
1. Intercambio de Datos en Aplicaciones B2B.
 
2. Servicios Web.
 
3. Sindicadores de contenido: Los archivos RSS (Rich Site Summary) o Atom, que son versiones especializadas de XML, se utilizan para sindicar contenido. Plataformas de noticias, como BBC News, y blogs utilizan RSS en XML para actualizar a sus usuarios sobre contenido nuevo.
