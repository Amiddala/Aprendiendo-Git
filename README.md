# **CURSO GIT**
<A traves de este repositorio, estoy documentando mi aprendizaje sobre Git


## Clase 1 :Introducción a Git
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