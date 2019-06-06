### Java
Java es un lenguaje de programación multiplataforma, orientado a objetos, diseñado para que los desarrolladores puedan crear una sola vez sus programas y se ejecuten en cualquier plataforma.

**El modelo orientado a objetos, es mas proximo a nuestra comprensión de la realidad.**

###### JDK (Java Development Kit)

Conjunto de herramientas (librerias y programas) que nos permiten compilar , ejecutar y generar documentación en java.

Las variables de entorno, mas importantes son:

**javac :** es el compilador de java, encargado de convertir nuestro codigo fuente (.java) en bytecode (.class) el cual posteriormente sera interpretado y ejecutado con la JVM.

**java :** es el interprete de java.

**java doc :** genera la documentación de las clases.

**Appletviewer :** es un visor de applet para generar sus vistas previas.

**.jar :** se utiliza para manipular ficheros, un fichero (.jar) es una colección de clases java y otros ficheros empaquetados en uno solo.

**javah :** es un fichero de cabecera, para escribir metodos nativos.

**javap :** se utiliza para descompilar archivos.

###### JRE (Java Runtime Enviroment)

Es la implentación de la maquina virtual de java, actua como un intermediario entre el sistema y java.

El JRE esta compuesto por dos importantes areas, la primera son las clases que conforman el API de java y la segunda es la JVM.

**El API** son todas las clases que componen el ambiente java y que al momento de ser utilizadas desde la aplicación podrán ser ejecutadas y/o interpretadas por la JVM.

**La JVM** es un componente de software que actua justamente como una maquina virtual o un espacio virtual de memoria, donde se ejecutan las aplicaciones java.

La JVM es el programa que interpreta el codigo java,mientras que las librerias de clases estándar son las que implementan el API de java, ambas deben ser consistentes entre sí.
