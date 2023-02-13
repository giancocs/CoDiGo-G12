# Primer dia con Git y Github

lista de comandos git

* para poder ver la version de git ejecutamos en nuestyra terminal:

```bash
git --version
git -v
```
* para configurar el correo y nombre (solo la primera vez en mi maquina)

```bash
git config --global user.email "adrianlucianno1@gmail.com"
git config --global user.name "giancocs"
```

* para ver la configuracion de git:

```bash
git config --list
```

* para inicializar nuestro repositorio en git:

```bash
git init
```

* para ver el estado de nuestros cambios:

```bash
git status
```

* para preparar nuestros archivos para la zona de stage (prepararlos para la commit)

```bash
git add .
git add nombredelarchivo.extension
```

* crear el registro de los comandos realizados:

```bash
git commit -m "comentario corto y conciso"
```

* para ver uan linea de tiempo de los commits que hemos realizado:

```bash
git log
```

* para poder ver el detalle de un commit en especifico:

```bash
git show id-de-commit
```




