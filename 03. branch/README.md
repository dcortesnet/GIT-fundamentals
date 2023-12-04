# Comandos para trabajar con ramas

- `git branch`: Se utiliza para listar, crear y manipular ramas en tu repositorio. Su función específica depende de las opciones que se utilicen con él.

  - Ejemplo: `git branch`: Este comando lista todas las ramas presentes en tu repositorio local. La rama actual estará marcada con un asterisco (\*).
  - Ejemplo: `git branch [nombre_de_la_rama]`: Este comando crea una nueva rama en tu repositorio, pero no cambia automáticamente a esa rama.
  - Ejemplo: `git branch -m [nombre_viejo_rama] [nombre_nuevo_rama]`: Este comando renombrar una rama.
  - Ejemplo: `git branch -d [nombre_de_la_rama]`: Este comando elimina una rama.

- `git checkout`: Se utiliza para cambiar entre ramas.

  - Ejemplo: `git checkout [nombre_de_la_rama]`: Este comando cambia de rama de trabajo.

- `git merge`: Se utiliza en Git para combinar cambios de una rama en otra. La idea principal es fusionar el trabajo realizado en una rama con el trabajo de otra, creando un nuevo commit que representa la combinación de ambas líneas de desarrollo. Ten en cuenta que puedes enfrentarte a conflictos que deberás resolver manualmente si se producen cambios en las mismas líneas de código.
  - Ejemplo: `git merge [nombre_de_la_rama]`: Fusiona dos ramas, la actual con la especificada.
