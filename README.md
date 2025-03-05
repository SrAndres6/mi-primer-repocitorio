andres garcia
en resumen aprendido que git y github es un programa muy grande y utilizado en el mundo, por su complejidad y variedad de datos, archivos y comandos, anque sea um programa muy grande.

### 1. **`git init`**
   - **Función**: Crea un nuevo repositorio vacío en el directorio actual. Se utiliza al comenzar un proyecto en Git.

### 2. **`git clone [url]`**
   - **Función**: Clona un repositorio remoto en tu máquina local. Se utiliza para obtener una copia de un repositorio.

### 3. **`git status`**
   - **Función**: Muestra el estado actual del repositorio, es decir, qué archivos han sido modificados, añadidos, eliminados o están listos para ser comiteados.

### 4. **`git add [archivo]`**
   - **Función**: Agrega un archivo o cambios específicos al área de "staging" para prepararlos para el próximo commit.

### 5. **`git commit -m "mensaje"`**
   - **Función**: Guarda los cambios del área de "staging" en el historial del repositorio con un mensaje descriptivo.

### 6. **`git push`**
   - **Función**: Envía los cambios locales a un repositorio remoto, actualizando la rama remota.

### 7. **`git pull`**
   - **Función**: Obtiene y fusiona los cambios de un repositorio remoto en la rama actual de tu repositorio local.

### 8. **`git fetch`**
   - **Función**: Descarga cambios desde un repositorio remoto, pero no los fusiona con la rama actual.

### 9. **`git merge [rama]`**
   - **Función**: Combina los cambios de otra rama en la rama actual. Es útil para integrar el trabajo de diferentes ramas.

### 10. **`git branch`**
   - **Función**: Muestra las ramas existentes en el repositorio o crea una nueva rama si se le da un nombre de rama después del comando.

### 11. **`git checkout [rama]`**
   - **Función**: Cambia a la rama especificada. También puede utilizarse para restaurar archivos a su versión anterior.

### 12. **`git log`**
   - **Función**: Muestra el historial de commits en el repositorio, mostrando información sobre cada commit (fecha, autor, mensaje, etc.).

### 13. **`git diff`**
   - **Función**: Muestra las diferencias entre archivos modificados y el último commit, o entre dos commits diferentes.

### 14. **`git reset [archivo]`**
   - **Función**: Elimina un archivo del área de "staging", pero mantiene los cambios en el archivo.

### 15. **`git reset --hard`**
   - **Función**: Restaura el repositorio a un estado anterior, eliminando todos los cambios no comprometidos (cuidado con este comando, ya que los cambios no se pueden recuperar).

### 16. **`git remote -v`**
   - **Función**: Muestra las URL de los repositorios remotos asociados con tu repositorio local.

### 17. **`git config --global user.name "Tu Nombre"`**
   - **Función**: Configura tu nombre de usuario globalmente para que se utilice en todos los repositorios locales de Git.

### 18. **`git config --global user.email "tuemail@dominio.com"`**
   - **Función**: Configura tu correo electrónico globalmente para los commits.

### 19. **`git stash`**
   - **Función**: Guarda temporalmente los cambios no comprometidos en un "stash" para que puedas trabajar en otra cosa sin perder tu trabajo.

### 20. **`git stash pop`**
   - **Función**: Recupera los cambios guardados con `git stash` y los aplica nuevamente al repositorio.

### 21. **`git tag`**
   - **Función**: Marca puntos específicos en el historial del repositorio, típicamente para crear versiones o hitos.

### 22. **`git rebase [rama]`**
   - **Función**: Reaplica los cambios de la rama actual sobre otra rama. Es útil para mantener un historial limpio.

### 23. **`git cherry-pick [commit]`**
   - **Función**: Aplica los cambios de un commit específico a la rama actual.

### 24. **`git rm [archivo]`**
   - **Función**: Elimina un archivo del repositorio y del área de trabajo.

### 25. **`git revert [commit]`**
   - **Función**: Crea un nuevo commit que revierte los cambios de un commit específico.

### 26. **`git clean -f`**
   - **Función**: Elimina archivos no rastreados (archivos que no han sido añadidos con `git add`).

### 27. **`git show [commit]`**
   - **Función**: Muestra detalles sobre un commit específico, como los cambios que hizo y los archivos modificados.
