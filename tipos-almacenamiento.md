# Ficheros

## Autores. Alumnos que han participado en la elaboración.

- David González García
- Óscar Gaztelu Menéndez
- David Collados Blanco

## Origen. ¿Cuándo surgió? ¿Cómo se popularizó?

Los primeros ficheros informáticos fueron en tarjeta perforada en el siglo XIX (donde ya la máquina de Hollerith para el censo de 1890 funcionaba con ellas). Un fichero en tarjetas perforadas es un bloque de tarjetas que tienen perforaciones que representan los caracteres que componen la información del registro.
 
Después, a partir de principios de la década de 1950, fue la cinta magnética la que tomó el relevo… y esta vez para quedarse. Una cinta de 2.400 pies, la habitual a partir de los sesentas, grabada a 1600 ppi (phrames per inch, o caracteres por pulgada) podía almacenar unos 50 Mb de información… cuando los carísimos discos de la época podían almacenar quizá tres o cuatro.
 
En 1889, Herman Hollerith había desarrollado un sistema de tarjetas perforadas eléctricas y basado en la lógica de Boole, aplicándolo a la tabulacion en Estados Unidos. La máquina tenía un lector de tarjetas, un contador, un clasificador y un tabulador creado por el mismo. Así, en 1896, Hollerith crea la Tabulating Machine Company, con la que pretendía comercializar su máquina.

## Nivel de adopción

Los ficheros informáticos almacenan información según sea necesario, estos se adaptan a varias cosas, una de ellas pueden ser los logs.Los archivos log funcionan como el registro oficial de todas las actividades que ocurren dentro de un sistema informático. Cada vez que se ejecuta una operación, ya sea de forma manual o automática, se genera una entrada de texto en el archivo log correspondiente.
 
Por otro lado también se usan en bases de datos. Un fichero de base de datos contiene descripciones de cómo se van a presentar los datos de entrada a un programa desde el almacenamiento interno y cómo se van a presentar los datos de salida al almacenamiento interno desde un programa.
 
Por último aquí se puede ver la importancia que tienen los ficheros y como la gente se ha adaptado a ellos mediante encuestas, y aquí voy a mostrar alguna de ellas: un promedio de 69 % de usuarios de Argentina, Brasil y México, están más preocupados por perder sus archivos digitales que por extraviar sus objetos físicos.
 
Además, la mayoría de usuarios (86 %) de esos países saben lo que es un backup y una copia de respaldo, un 88 % efectivamente lo realiza y el 93 % cuenta con algún dispositivo físico o solución de almacenamiento en línea/en la nube.

## Descripción del funcionamiento del sistema de almacenamiento

Para almacenar los datos en ficheros de forma persistente, una de las cuestiones a tener en cuenta es que se requiere utilizar ciertos métodos para poner una limitación sobre cuándo empieza un elemento y cuándo acaba este elemento, cuándo empieza un campo de datos y cuándo acaba este campo de datos, o cuándo no hay más elementos en un fichero. De este modo, por ejemplo, si se necesita almacenar una cadena de longitud indefinida, una posible solución sería añadir un campo adicional para indicar la longitud de la cadena (en bytes) en el fichero.
 
La siguiente imagen muestra una forma de almacenar la información sobre fotos y autores en un único fichero. Podemos observar que inicialmente hay 4 bytes reservados para indicar en el fichero el número total de fotos que habrá almacenadas en el fichero, y a continuación estará la información de cada una de las fotos, incluyendo su información de autor. Para cada entero, habrá 4 bytes en el fichero para almacenarlo, pero habrá un campo adicional de 4 bytes para cada cadena que indicará la longitud en bytes de la cadena, para poder localizarla.
 
Existen diferentes formas de almacenar la misma información. Otra forma de almacenar la información disponible en el fichero, es la que se muestra en la siguiente figura. Aquí, la información se almacena dividida por autores. De esta forma, hay un campo inicial de 4 bytes, que indica el número total de autores almacenados, y a continuación la información de cada autor. Para cada autor, estarán los datos propios de cada autor, y cuando se termine la información sobre un autor, a continuación un número almacenado de 4 bytes, que indica el número total de fotos que han sido tomadas por este autor. Por último, está la información asociada a cada una de estas fotos.
 
La elección para decidir una de las diferentes formas de almacenar la información en un fichero, depende de un análisis en el que se deben tener en cuenta las diferentes ventajas e inconvenientes, y existe un trade-off. En este sentido, hay que tener en cuenta qué solución ocupará más espacio en un fichero (en el caso presentado, la primera opción ocupará más espacio, porque la misma información de autor debe replicarse varias veces), o cuál será más eficaz para el tiempo de ejecución de las operaciones requeridas por la aplicación. Por ejemplo, si una aplicación requiere listar las fotos de un autor concreto muchas veces, entonces para esta operación será más efectiva la segunda elección, porque las fotos ya estarían ordenadas por autor, por lo que la aplicación no tendría que buscar foto a foto, sino que una vez localizado el autor toda la información estaría en posiciones consecutivas del fichero. Sin embargo, una aplicación que sólo requiriese listar todas las fotos del sistema con su información, sin ordenarlas por autor, entonces sería más efectiva la primera opción, porque para añadir una nueva foto, la aplicación puede hacerlo al final del fichero, sin necesidad de meter la foto en el fichero para agruparla con su autor.

## Ventajas e inconvenientes

### PROS

1. Sencillez:
- Fácil de implementar: Leer y escribir en archivos puede ser sencillo y requiere una configuración mínima.
- Sin software adicional: Puede utilizar el almacenamiento de archivos sin necesidad de un servidor de bases de datos.
Rendimiento para conjuntos de datos pequeños:
- Acceso rápido a archivos pequeños: Para pequeñas cantidades de datos, la E/S de archivos puede ser bastante rápida, especialmente si los datos ya están en memoria.
Portabilidad:
- Fácil de trasladar: los archivos pueden copiarse, trasladarse o compartirse fácilmente entre sistemas.
Coste:
- Sin costes de licencia: El uso del sistema de archivos evita los costes asociados a las licencias de bases de datos o a los servicios de bases de datos alojadas.
Menos gastos generales:
- Uso mínimo de recursos: Se puede acceder a los archivos con menos sobrecarga que con un sistema de gestión de bases de datos.

2. Escalabilidad:
- Degradación del rendimiento: A medida que crece la cantidad de datos, el acceso a los archivos puede volverse más lento y menos eficiente.
- Dificultad para gestionar grandes conjuntos de datos: La búsqueda y gestión de archivos de gran tamaño puede resultar engorrosa.
Problemas de concurrencia:
- Acceso concurrente limitado: Manejar múltiples operaciones de lectura/escritura simultáneamente puede llevar a la corrupción de datos o inconsistencias.
Falta de funciones avanzadas:
- Sin indexación integrada: La búsqueda en archivos puede ser lenta sin mecanismos de indexación.
- Sin transacciones: Los ficheros no admiten transacciones, lo que hace más difícil garantizar la integridad de los datos.
Redundancia de datos:
- Aumento de la duplicación: Sin un esquema estructurado, es fácil crear datos redundantes en diferentes archivos.
Copias de seguridad y recuperación:
- Procesos manuales: Las copias de seguridad y la recuperación de datos de archivos pueden ser más complejas y menos fiables en comparación con las bases de datos.

## Usos

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

## Tipos: Tipos de ficheros, bases de datos representativas, etc.

Los ficheros se pueden clasificar en varias categorías según su contenido y propósito. 

1. **Ficheros de texto**
Son archivos que contienen texto legible por humanos. Pueden ser simples, como los archivos .txt, o más complejos como los .csv, que contienen valores separados por comas. Estos archivos se utilizan para almacenar datos tubulares.

2. **Ficheros binarios**
Estos archivos contienen datos en un formato que no es legible directamente por humanos. Un ejemplo bastante común de fichero binario son las imágenes de formato .jpg.

3. **Ficheros de intercambio de datos**
Estos son formatos diseñados específicamente para facilitar la transferencia de datos entre diferentes sistemas o aplicaciones. Los ficheros XML son un ejemplo de fichero de intercambio de datos.

4. **Ficheros propietarios**
Son aquellos diseñados para ser utilizados con un software específico y no son fácilmente accesibles o editables por otros programas. Los archivos .psd (Adobe Photoshop) son considerados propietarios, ya que requieren el software correspondiente para abrirse y modificarse adecuadamente. 

## Casos de uso reales observados

- **Ficheros de extensión .exe**
Estos ficheros son generalmente utilizados para instalar aplicaciones en sistemas operativos Windows. Al hacer doble clic en este archivo, se inicia el proceso de instalación que copia los archivos necesarios al sistema y configura el software para su uso.

- **Ficheros de extensión json**
Los ficheros .json son utilizados para desarrollar aplicaciones web que intercambian información entre cliente y servidor. Un ejemplo sería una aplicación de clima. El servidor responde enviando un fichero .json que contiene datos como la temperatura, la humedad y las condiciones climáticas. La aplicación web analiza este fichero y presenta la información al usuario de manera visual.

- **Ficheros de extensión .word**
Son utilizados para crear y editar documentos en Microsoft Word. Un caso de uso común es la redacción de informes, propuestas o currículos. 
