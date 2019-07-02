# CamelCase

#### ¿Qué es CamelCase? ####

Es un estilo de escritura, que se aplica a frases o palabras compuestas. EL nombre se debe a que las mayúsculas a lo largo de una palabra en CamelCase se asemejan a las jorobas de un camello.

Este tipo de escritura, se caracteriza por que las palabras van unidas entre sí y sin espacios.

Existen dos tipos de CamelCase:

#### Upper CamelCase ####

Cuando la primera letra de cada una de las palabras es mayúscula.

Ejemplos:
- Google
- PayPal
- SanDisk
- Microsoft

#### Lower CamelCase ####

Cuando la primera letra de cada una de las palabras es minúscula.

Ejemplos :
- amazon
- adidas
- intel
- visa
- iPhone

# Modificadores de Acceso

Los modidificadores de acceso, son elementos del lenguaje que se colocan delante de la definición de variables locales, datos miembro, métodos o clases, que alteran o condicionan el significado del elemento.

Los modificadores de acceso permiten al diseñador de una clase, determinar quien accede a los datos y métodos de una clase.

Declaración para una Variable :

```Shell
[modificador] tipo_variable nombre;
```
Declaración para un Método :

```Shell
[modificador] tipo_retorno nombre_metodo;
```

#### Tipos de modificadores de acceso ####

* __*public*__

Todos pueden acceder o ver al elemento, es decir usarlo o asignarlo, si es un método todos pueden invocarlo.

* __*private*__

Cuando un método o atributo (variable) es declarada como private, su uso queda restringido al interior de la misma clase, no siendo visible para el resto.

> Una clase no puede ser private, sólo atributos y métodos.

* __*protected*__

Un método o atributo definido como protected es visible para las clases que se encuentren en el mismo paquete y para cualquier subclase de esta, aun que este en otro paquete. Este modificador es utilizado normalmente para herencias.

* __*default*__

Si no le asignamos ningun modificador de acceso al elemento (variable, método, clase) java asigna uno denominado "por defecto" el cual permite la visibilidad de los elementos.

![modificadores de acceso](Imagenes/Acceso.png)
