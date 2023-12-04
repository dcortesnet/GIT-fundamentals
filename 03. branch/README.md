# Comandos para trabajar con ramas

- `git branch`: Se utiliza para listar, crear y manipular ramas en tu repositorio. Su función específica depende de las opciones que se utilicen con él.

  - `git branch`: Este comando lista todas las ramas presentes en tu repositorio local. La rama actual estará marcada con un asterisco (\*).
  - `git branch [nombre_de_la_rama]`: Este comando crea una nueva rama en tu repositorio, pero no cambia automáticamente a esa rama.
  - `git branch -m [nombre_viejo_rama] [nombre_nuevo_rama]`: Este comando renombrar una rama.
  - `git branch -d [nombre_de_la_rama]`: Este comando elimina una rama.

- `git checkout [nombre_de_la_rama]`: Se utiliza para cambiar entre ramas. Este comando cambia de rama de trabajo.

- `git merge [nombre_de_la_rama]`: Se utiliza en Git para combinar cambios de una rama en otra. La idea principal es fusionar el trabajo realizado en una rama con el trabajo de otra, creando un nuevo commit que representa la combinación de ambas líneas de desarrollo. Ten en cuenta que puedes enfrentarte a conflictos que deberás resolver manualmente si se producen cambios en las mismas líneas de código.
