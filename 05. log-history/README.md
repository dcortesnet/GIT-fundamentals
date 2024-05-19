# Comandos para revisar el historial

### 1. `git log`

Se utiliza para mostrar el historial de confirmaciones (commits) en una rama específica. Este comando proporciona una lista detallada de los commits realizados en esa rama, incluyendo información como el hash del commit, el autor, la fecha y hora, y el mensaje asociado al commit. Su función específica depende de las opciones que se utilicen con él.

```bash
$ git log --oneline # Muestra un historial más conciso en una sola línea por cada commit.
$ git log --graph # Muestra un historial con un gráfico ASCII que representa las ramificaciones y fusiones en el repositorio.
$ git show [hash_commit] # Muestra los detalles de un commit específico, incluyendo los cambios realizados en ese commit.
```
