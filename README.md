# Guía Completa de Comandos de GitHub

Este archivo contiene una lista de los comandos de GitHub más utilizados junto con su explicación detallada. Es una referencia rápida para gestionar repositorios, colaborar en proyectos y manejar tu flujo de trabajo en GitHub.

---

## Comandos Básicos de Git

1. **`git init`**  
   Inicializa un repositorio vacío en el directorio actual. Esto crea una carpeta `.git` que contiene la información del repositorio.

2. **`git clone <url>`**  
   Clona un repositorio existente desde una URL (por ejemplo, un repositorio en GitHub).

3. **`git add <archivo>`**  
   Añade un archivo específico al área de preparación (staging area), para que esté listo para ser confirmado en el commit.

4. **`git commit -m "<mensaje>"`**  
   Realiza un commit con un mensaje descriptivo que explique los cambios realizados.

5. **`git status`**  
   Muestra el estado del repositorio, incluyendo archivos modificados, añadidos y sin seguimiento.

6. **`git log`**  
   Muestra el historial de commits del repositorio.

7. **`git diff`**  
   Muestra las diferencias entre los archivos actuales y los cambios sin confirmar (unstaged changes).

8. **`git reset <archivo>`**  
   Elimina un archivo del área de preparación (staging area), pero sin borrar los cambios locales.

---

## Comandos de GitHub

1. **`git remote add origin <url>`**  
   Conecta tu repositorio local con el repositorio remoto en GitHub.

2. **`git push origin <branch>`**  
   Empuja los commits de tu rama local hacia la rama remota en GitHub.

3. **`git pull origin <branch>`**  
   Trae los cambios de la rama remota y los fusiona con tu rama local.

4. **`git fetch`**  
   Obtiene las últimas actualizaciones del repositorio remoto sin hacer un merge con tu rama local.

5. **`git remote -v`**  
   Muestra las URL de los repositorios remotos asociados al repositorio local.

6. **`git push --force`**  
   Fuerza la actualización del repositorio remoto (destruye el historial previo en el remoto y lo reemplaza).

7. **`git branch -a`**  
   Muestra todas las ramas disponibles, tanto locales como remotas.

---

## Comandos de Colaboración

1. **`git fork`**  
   Crea una copia personal de un repositorio en tu cuenta de GitHub. Esto te permite realizar cambios sin afectar el repositorio original.

2. **`git pull request`**  
   Inicia una solicitud de cambios para que un repositorio propietario revise y acepte tus contribuciones.

3. **`git merge`**  
   Combina los cambios de una rama a otra (por ejemplo, fusionar `feature` en `main`).

4. **`git rebase <branch>`**  
   Reaplica los commits de la rama actual sobre la base de otra rama, lo que puede ayudar a mantener un historial más limpio.

5. **`git cherry-pick <commit>`**  
   Aplica un commit específico de otra rama a la rama actual.

---

## Comandos de Gestión de Branches

1. **`git branch <nombre-de-rama>`**  
   Crea una nueva rama en tu repositorio local.

2. **`git checkout <nombre-de-rama>`**  
   Cambia a la rama especificada.

3. **`git branch -d <nombre-de-rama>`**  
   Elimina una rama local que ya no es necesaria.

4. **`git checkout -b <nombre-de-rama>`**  
   Crea una nueva rama y cambia a ella en un solo comando.

5. **`git merge <rama>`**  
   Fusiona los cambios de la rama especificada a la rama actual.

---

## Comandos de Fetch, Pull y Push

1. **`git push`**  
   Sube tus cambios locales a tu repositorio remoto en GitHub.

2. **`git fetch`**  
   Trae todos los cambios desde el repositorio remoto, pero no los fusiona con tu rama local.

3. **`git pull`**  
   Trae y fusiona los cambios del repositorio remoto con tu rama local.

4. **`git push --all`**  
   Empuja todas las ramas locales hacia el repositorio remoto.

5. **`git push --tags`**  
   Empuja todas las etiquetas (tags) locales al repositorio remoto.

---

## Otros Comandos Útiles

1. **`git tag <tag>`**  
   Crea una etiqueta (tag) en el commit actual. Las etiquetas se utilizan para marcar puntos importantes en la historia del proyecto (como versiones).

2. **`git stash`**  
   Guarda temporalmente los cambios no confirmados (commits) para que puedas trabajar en otra cosa y luego recuperarlos más tarde.

3. **`git stash apply`**  
   Recupera los cambios que guardaste previamente con `git stash`.

4. **`git clean -fd`**  
   Elimina los archivos no rastreados (no versionados) en tu directorio de trabajo.

---

## Conclusión

Este es solo un resumen de los comandos más utilizados en Git y GitHub. Con esta guía podrás gestionar repositorios, colaborar con otros desarrolladores, y mantener tu proyecto en GitHub de manera eficiente. Si tienes dudas o necesitas más información, consulta la [documentación oficial de Git](https://git-scm.com/doc) o la [documentación oficial de GitHub](https://docs.github.com/).
