# Comandos de preparación de ambiente

### 1. `git clone`

Se utiliza para clonar un repositorio existente. Este comando copia un repositorio Git completo, incluidos todos los archivos, historial y configuraciones, desde un repositorio remoto a tu máquina local.

```bash
git clone [url_repositorio]
```

### 2. `git init`

Se utiliza para iniciar un nuevo repositorio Git en el directorio actual. Git crea un nuevo subdirectorio dentro del directorio actual que contendrá la estructura de control de versiones de Git. Este subdirectorio se llama .git y es donde Git almacena toda la información necesaria para gestionar las versiones de tu proyecto.

```bash
git init
```

### 3. `git config`

Se utiliza para configurar y gestionar las opciones de configuración del sistema, del usuario y del proyecto. Permite establecer información como el nombre de usuario, la dirección de correo electrónico, el editor preferido, y muchas otras configuraciones que afectan el comportamiento de Git.

```bash
git config user.name "[tu_username]"
git config user.email "[tu_correo]"
git config --list # List config
```
