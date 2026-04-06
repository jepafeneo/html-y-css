# Mi primer pagina

## Ejercicio

Crear un repositorio publico con las ramas main y dev

Crear el archico index.html en la rama dev, 
con la estructura basica de HTML y 
en el body que este el texto `<p>Hola, <nombre></p>`

## Comandos

Configuracion inicial

```shell
git config --global user.name "Jean Paul Ferreira"
git config --global user.email jp.ferreira@neoland.es
```

```shell
git config --local user.email jeanpaul@jepafe.net
```

Inicializa un repositorio y crea el .git

```shell
git init
```

Estado del repositorio

```shell
git status
```

Agregar archivo al Stage

```shell
git add <archivo>
```

Toma un foto del estado actual de repositorio

```shell
git commit -m "mensaje"
```

Muestra los logs

```shell
git log

git log --oneline --all
```

Enviar repositorio local al remote

```shell
git push <remote> <rama>
```

Actualizar repositorio local desde el remote

```shell
git pull <remote> <rama>
```

Actualizar informacion de la rama actual

```shell
git fetch
```

Si quiero hacer un merge, combinar ramas
Por ejemplo si estoy en main e incorporar los cambios de dev

```shell
git merge dev
```

Crear una rama

```shell
git checkout -b <new-branch>

git switch -c <new-branch>
```

Cambiar de rama

```shell
git checkout <branch-name>

git switch <branch-name>
```

Ver los remote

```shell
git remote -v
```

Agregar remote

```shell
git remote add origin https://...
```

Enviar datos

```shell
git push origin <branch-name>
```

Trae la información del remote

```shell
git fetch

git fetch --all
```

Trae los cambio del remote al local

```shell
git pull origin <branch-name>
```
