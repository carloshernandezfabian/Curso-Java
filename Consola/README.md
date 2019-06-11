
#### Comandos Iniciales de consola
> Nota: tmux es un multiplexor de terminal para sistemas tipo Unix.

**El comando base es  Ctrl + b**

1. Comando para abrir tmux

```Shell
		tmux
```

2. Comando para ver el listado de terminales de tmux

```Shell
		tmux ls
```

![tmux-ls](Imagenes/tmux-ls.PNG)

3. Comando para re-ingresar a una terminal que esta abierta.

```Shell
		tmux attach-session -t [nombre de la sesion]
```

## Para poder movernos en la pantalla

```Shell
		Ctrl + b + tecla ([)
```
**para salir del buffer Esc**

## Para crear nuevas pestañas utilizamos el comando :

```Shell
		Ctrl + b + c
```

###### Comando para renombrar el nombre de la pestaña es ######

```Shell
		Ctrl + b + ,
```

###### Comando para recorrer las pestañas hacia adelante ######

```Shell
		Ctrl + b + n
```
###### Comando para recorrer las pestañas hacia atras ######

```Shell
		Ctrl + b + p
```
###### Comando para ir directamente a la pestaña ######

```Shell
		Ctrl + b + [# de pestaña]
```
###### Comando para cerrar una pestaña ######

```Shell
		Ctrl + b + &
```
