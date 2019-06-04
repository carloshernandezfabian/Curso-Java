# Git

#### Comandos Iniciales

1. El comando que sirve para clonar repositorios en local es :
```Shell
git clone https://github.com/carloshernandezfabian/Curso-Java.git

```
2. El siguiente comando sirve para ver el estado en el que esta el repositorio :
```Shell
git status
```
#### Comandos para subir cambios al servidor

1. Primero verificamos el estado en el que esta el repositorio:
```Shell
git status
```

2. Agregamos los archivos que fueron modificados
```Shell
git add [nombre completo del archivo]
```

2.1 si deseamos agregar todos los archivos utilizamos el siguiente comando

```Shell
git add .
```

3. Una vez agrgados los archivos hacemos commit

```Shell
git commit -m "mensaje"
```
4. Despues del commit ya se puede hcaer **push** al servidor

```Shell
git push origin [nombre de la rama]
```
#### Archivos de configuracion de repositorio

+ En el archivo **.gitignore** Agregamos el nombre de los archivos que deseamos ignorar, para que no se suban al repositorio. 

+ En la carpeta **.git** se encuentran las configuraciones de nuestro repositorio localmente, y dentro de el hay un archivo que se llama **config** que contiene el **origin**, que es hacia donde apunta nuestro repositorio, por ejemplo:
```Shell
[remote "origin"]
	url = https://github.com/carloshernandezfabian/Curso-Java.git
	fetch = +refs/heads/*:refs/remotes/origin/*
```
