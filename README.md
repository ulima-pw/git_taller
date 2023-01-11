# Taller guiado de GIT

## Trabajo en Equipo

- Formar equipos de 3 a 4 integrantes.
- Cada integrante debe tener una cuenta github.

### Comando a utilizar

Hacer que repositorio local apunte a repositorio remoto.

```
$ git remote add <etiqueta> <url_repo_git>
```

Enviar cambios (commits) a repositorio remoto

```
$ git push <etiqueta> master
```

Traer ultimo commit de repositorio remoteo

```
$ git pull <etiqueta> master
```

Creación de un nuevo branch

```
$ git checkout -b <nombre_branch>
```

Posicionarse en un branch creado anteriormente

```
$ git checkout <nombre_branch_existente>
```

Integración entre branches. Primero encontrarse en el branch destino

```
$ git merge <branch_origen>
```

*Nota:* En caso de conflicto, resolver el conflicto de forma manual y
luego commitear y pushear los cambios.

### Actividades

1. Solución de conflictos manuales y automático.s

2. Creación de branches para trabajo en equipo.

3. Realización de pull request.

### Recursos

- https://www.markdownguide.org/basic-syntax/
