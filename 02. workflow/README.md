# Comandos flujo de trabajo en Git

### 1. `git add`

Se utiliza para agregar cambios realizados en archivos al área de preparación (también conocida como el "index" o "staging area").

```bash
git add [archivo_o_directorio]
git add *
```

### 2. `git commit`

Se utiliza para confirmar los cambios realizados en el área de preparación (staging area) y genera una nueva instantánea agregandola en el historial del repositorio. Cada commit tiene un identificador único (hash) y un mensaje descriptivo que proporciona información sobre los cambios realizados.

```bash
git commit -m "[Mensaje descriptivo del commit]"
```

### 3. `git reset`

Se utiliza para deshacer cambios en el historial de commits y/o en el área de preparación (staging area). Su función específica depende de las opciones que se utilicen con él.

- git reset HEAD: Deshace un archivo que ya está en el área de preparación (staging area). Esto moverá el archivo de vuelta al directorio de trabajo y lo desvinculará del área de preparación.

```bash
git reset HEAD [archivo_o_directorio]
```

- git reset --soft: Deshace commits mientras mantiene los cambios en el área de preparación y en el directorio de trabajo.

```bash
git reset --soft [hash_commit]
```

- git reset --hard: Deshace commits y elimina los cambios tanto del área de preparación como del directorio de trabajo.

```bash
git reset --hard  [hash_commit]
```
