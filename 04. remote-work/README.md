# Comandos para trabajar con el repositorio remoto

### 1. `git remote`

Se utiliza para conectarnos con un servidor Git remoto. Su función específica depende de las opciones que se utilicen con él.

```bash
git remote add [nombre_origen] [url_origen] # Este comando se utiliza para conectar y agregar un nuevo repositorio remoto a nuestro entorno de trabajo.
git remote set-url [nombre_origen] [nueva_url_origen] #  Se utiliza para cambiar la URL asociada con un repositorio remoto existente.
git remote remove [nombre_origen] # Elimina la conexión a un repositorio remoto.
git remote -v #  Este comando muestra las URLs de los repositorios remotos configurados actualmente en tu proyecto.
```

### 2. `git fetch`

Se utiliza para recuperar cambios desde un repositorio remoto sin fusionar esos cambios en tu rama actual. Básicamente, actualiza tu repositorio local con la información más reciente del repositorio remoto, pero no realiza cambios en tu trabajo actual

```bash
git fetch [nombre_origen]
```

### 3. `git pull`

Es un comando en Git que combina dos operaciones, realiza un "git fetch" para obtener los cambios del repositorio remoto y luego realiza un "git merge" para fusionar esos cambios en la rama actual.

```bash
git pull [nombre_origen] [nombre_rama_remota]
```

### 4. `git push`

Es un comando en Git que se utiliza para enviar los cambios confirmados en tu rama local a un repositorio remoto.

```bash
git push [nombre_origen] [nombre_rama_local]
```
