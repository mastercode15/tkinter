# tkinter
Metodos en tkinter
label:
La sintaxis para crear los label es la siguiente:
nombre_del_label = Label( contenedor, text=“ ”)

pack:
El método pack() es un tipo de posicionamiento para los widgets que ajusta todo los elementos acomodándolos entre sí, para luego hacer la ventana raíz tan grande para contener todos estos elementos. Por ejemplo en el código anterior al ejecutar vemos que la ventana raíz se ajusta al tamaño del frame.

Este método también tiene opciones de configuración como son fill, expand, side, entre otros. Para utilizarlos dentro del método pack, entre paréntesis colocamos los parámetros a configurar, por ejemplo.

Parámetros	                        Valores
mi_Frame.pack(fill=”valor”)	      ‘x’, ‘y’, ‘both’, ‘none’
mi_Frame.pack(expand=”valor”)   	  0, 1, “True”, “False”
mi_Frame.pack(side=”valor”)	      ‘left’, ‘right’, ‘top’, ‘bottom’

para tener en claro los widgets que se van a usar ingrese al siguiente link:
https://guia-tkinter.readthedocs.io/es/develop/chapters/6-widgets/6.1-Intro.html

Todos los ejercicios que se explican a continuacion importan la libreria tkinter

ejercicio1:
el ejercicio1 crea una ventana y dentro de esta se el texto "Hola Mundo"
para esto se usa la funcion label que significa etiqueta en español

ejercicio2:
En este ejercicio se crea una variable (whatever_you_do) donde se almacena un mensaje,
este mensaje es almacenado en una variable llamada msg que usa el metodo mesage para almacenar el mensaje
posteriromente se usa el metodo config para editar el texto como por ejemplo su color de fondo, su tipo de letra, su tamaño,su color,etc.
finalmense se usa el metodo pack para crear el mensaje

ejercicio3:
En este ejercicio crea dos botones, uno denominado "SALIR"y el otro "ENTRAR"
Para ello se crea una clase app que contendra dos funciones
una funcion que crea ños botones y la otra que imprime el mensaje cuando se hace clic en boton entrar
cuando se hace clic en el boton entrar se imprime el mensaje "Estamos aprendiendo a usar Tkinter!"

ejercicio4:
En este ejercicio se crea una ventana donde se imprime un mensaje que dice "Escoga un lenguaje de programacion"
el programa nos permite escoger 1 de las dos opciones, en la opcion donde se haga clic se marcara

ejercicio5:
En este ejercicio al igual que el ejercico4 imprime un mensaje que dice "escoja un lenguaje de programacion"
asi mismo, en la opcion en la que se haga clic se marcará
a diferencia del ejercicio4 este programa, cada vez que se selecciona una opcion diferente se imprime el numero de la opcion en consola
esto lo hace creando una lista donde se le asigna a cada una de las opciones un número
finalmente se usa un bucle for que verifica la opcion seleccionada e imprime el numero que se le asigno a esa opción

ejercicio6:
Este ejercicio es bastante similar al ejercicio5 porque realiza la misma función
la unica diferencia es que al hacer clic en las opciones, estas se marcan como si fueran un boton

ejercicio7:
En este ejercico aparecen 2 opciones con sus respectivos chekbox
Este programa permite marcar las dos opciones o unicamente una de ellas

ejercicio8:
Este ejercicio es similar al ejercico7
Ya que asi mismo nos da a escoger dos opciones con sus respectivos checkbox cada una
A difeferncia del ejercicio7 en este programa se implementan 2 botones
el boton Quit para salir 
y el boton show
que mestra en consola la opcion y si se seleccionó imprime el numero 1 y si no se selecciono imprimer el numero 0

ejercicio 9:
En este ejercico se cran dos etiquetas una denominada "primer nombre" y otra denominada "apellido"
cada una de estas etiquetas posee un cuadro de texto a su lado
en este caudro de texto se permite escribir lo que el usuario desee ya que es como un tipo de variable String

ejercicio10:
Este ejercicio es similar el ejercicio 9
Ya que asi mismo implementa 2 etiquetas, una de nombre y otra de apellido
A diferencia del ejercicio 9 este programa implementa 2 botones
el boton Quit para salir 
y el boton show,el cual permite mostrar en consola las dos etiquetas con el texto escrito que puede escribir el usuario en los respectivos cuadros de texto
