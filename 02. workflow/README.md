# Comandos flujo de trabajo en Git

- `git add [archivo_o_directorio]`: Se utiliza para agregar cambios realizados en archivos al área de preparación (también conocida como el "index" o "staging area").

- `git commit -m "[Mensaje descriptivo del commit]"`: Se utiliza para confirmar los cambios realizados en el área de preparación (staging area) y genera una nueva instantánea agregandola en el historial del repositorio. Cada commit tiene un identificador único (hash) y un mensaje descriptivo que proporciona información sobre los cambios realizados.

- `git reset`: Se utiliza para deshacer cambios en el historial de commits y/o en el área de preparación (staging area). Su función específica depende de las opciones que se utilicen con él.

  - `git reset HEAD [archivo_o_directorio]`: Deshace un archivo que ya está en el área de preparación (staging area). Esto moverá el archivo de vuelta al directorio de trabajo y lo desvinculará del área de preparación.

  - `git reset --soft [hash_commit]`: Deshace commits mientras mantiene los cambios en el área de preparación y en el directorio de trabajo.

  - `git reset --hard  [hash_commit]`: Deshace commits y elimina los cambios tanto del área de preparación como del directorio de trabajo.
