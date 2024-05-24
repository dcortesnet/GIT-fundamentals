# Comandos para gestionar ramas

### 1. `git branch`

Se utiliza para listar, crear y manipular ramas en tu repositorio. Su función específica depende de las opciones que se utilicen con él. Este comando por defecto lista todas las ramas presentes en tu repositorio local. La rama actual estará marcada con un asterisco (\*).

```bash
$ git branch [nombre_de_la_rama] # Este comando crea una nueva rama en tu repositorio, pero no cambia automáticamente a esa rama.
$ git branch -m [nombre_viejo_rama] [nombre_nuevo_rama] # Este renombra una rama.
$ git branch -d [nombre_de_la_rama] # Este comando elimina una rama.
```

### 2. `git checkout`

El comando git checkout tiene múltiples usos, entre los cuales destacan el cambio de ramas de trabajo y el cambio a commits específicos.

```bash
$ git checkout [nombre_de_la_rama] # Cambiarnos de rama
$ git checkout [commit_hash] # Cambiarnos de commit
```

### 3. `git merge`

Se utiliza en Git para combinar cambios de una rama en otra. La idea principal es fusionar el trabajo realizado en una rama con el trabajo de otra, creando un nuevo commit que representa la combinación de ambas líneas de desarrollo. Ten en cuenta que puedes enfrentarte a conflictos que deberás resolver manualmente si se producen cambios en las mismas líneas de código.

```bash
$ git merge [nombre_de_la_rama]
```
