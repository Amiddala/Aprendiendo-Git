# **CURSO GIT**

A traves de este repositorio, estoy documentando mi aprendizaje sobre Git

## Clase 1: Introducción a Git
### Concepto básico:
Git es un sistema de control de versiones distribuido que permite rastrear cambios en archivos y coordinar el trabajo entre múltiples personas en proyectos de software.

### Comandos:
- `git init`: Inicializa un repositorio Git en un directorio.
- `git add <archivo>`: Agrega un archivo al área de preparación.
- `git commit -m "Mensaje"`: Guarda los cambios en el repositorio.

## States y Commits
### Concepto básico:

- **Directorio de trabajo:** Es el espacio donde trabajas con tus archivos y realizas cambios.
- **Área de preparación (Staging Area):** Es donde seleccionas los cambios que quieres incluir en tu próximo commit.
- **Repositorio:** Es donde Git guarda los commits, que son instantáneas de los cambios guardados en el repositorio. Cada commit tiene un mensaje asociado que describe los cambios realizados.

### Comandos:

- `git status`: Muestra el estado actual del repositorio. Te indica qué archivos han sido modificados, agregados o eliminados, y si están en el área de preparación o no.
- `git log`: Muestra el historial de commits. Proporciona una lista detallada de todos los commits realizados en el repositorio, incluyendo el autor, la fecha y el mensaje asociado a cada commit.
- `git diff`: Muestra las diferencias entre versiones. Puedes usar este comando para ver las diferencias entre el directorio de trabajo y el área de preparación, entre el área de preparación y el último commit, o entre dos commits específicos.

## Clase 2: Ramas, Merge y Conflictos

### Concepto básico
Las ramas en Git permiten trabajar en paralelo en diferentes funcionalidades o correcciones de errores. Cada rama representa una línea independiente de desarrollo. Merge combina cambios de diferentes ramas, y los conflictos ocurren cuando hay cambios contradictorios que deben resolverse manualmente.

### Comandos
- `git branch <nombre_rama>`: Crea una nueva rama con el nombre especificado.
- `git checkout <nombre_rama>`: Cambia a una rama específica.
- `git merge <nombre_rama>`: Combina los cambios de una rama en otra. Esto fusiona los cambios de la rama especificada en la rama actual. Si hay conflictos, Git pausará el proceso de fusión y requerirá que los resuelvas manualmente.

### Uso avanzado
- `git branch -d <nombre_rama>`: Elimina una rama después de que sus cambios se han fusionado correctamente en otra rama.
- `git branch -D <nombre_rama>`: Elimina una rama incluso si sus cambios no se han fusionado en otra rama (se pierden los cambios no fusionados).
- `git merge --abort`: Cancela el proceso de fusión en caso de conflicto y restaura el estado antes de la fusión.
- `git merge --no-ff <nombre_rama>`: Realiza un merge "no fast-forward", creando un nuevo commit de merge incluso si Git podría hacerlo automáticamente.

### Estrategias de fusión
- **Fusión Regular (Fast-forward)**: Git avanza la rama actual para fusionarla con la rama especificada si no hay conflictos.
- **Fusión de "Merge commit"**: Git crea un nuevo commit de fusión para combinar cambios, incluso si no hay conflictos.
- **Resolución de conflictos**: Cuando hay conflictos, Git requiere intervención manual para resolverlos antes de completar la fusión.

### Recursos adicionales
- [Documentación oficial de Git](https://git-scm.com/doc)
- [Tutorial de ramas en Git](https://www.atlassian.com/git/tutorials/using-branches)
- [Resolución de conflictos en Git](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/merge-conflicts)
