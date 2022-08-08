# Git and GitHub course

<img src="https://cliparting.com/wp-content/uploads/2017/09/Superman-clipart-3.jpeg"/>

## Primeros comandos de git

version de git: `git --version`

git help: `git help`

salir de la consola git: `:q`

## Configurar git

- `$ git config --global user.name "Fernando Herrera"`

- `$ git config --global user.email "fernandoherrera@hola.com"`

El correo electronico puede ser un email general que no esta siendo utilizado en github

Para ver los cambios que acabamos de hacer en la configuracion, escribimos:

- `$ git config --global -e`

**Inicaliza el repositorio (proyecto) git:**

`$ git init`

**Informacion sobre los commits, ramas en las que nos encontramos, etc**

`$ git status`

**Añadir archivos**

`$ git add <nombre archivo>`

`$git add .` añade todos los archivos
