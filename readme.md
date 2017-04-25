# Preguntas

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

`git reset --hard HEAD~1`
Para deshacer el último commit y hard para perder los cambios del working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

`git reflog`para buscar el commit dónde agregué el estilo
`git reset --hard 267e948` para volver el HEAD a este commit

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No casusó ningún conflicto porque la branch ´styled´ se creó después de que este archivo fuera modificado en la rama master.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 

Si, porque el mismo archivo ´git-nuestro.md´ fue modificado en mismas líneas en las dos ramas.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 

No, en master no se modificó el mismo archivo, es un ff merge.

- ¿Qué comando o comandos utilizaste en el paso 25?

`git log --graph --decorate --pretty=oneline` Para ver todos los commits claros en una línea y con el nombre de la branch de c/ commit.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

Si, porque están en la misma lista, solo tendría que mover el HEAD al commit dónde se agregó el título.

- ¿Qué comando o comandos utilizaste en el paso 27?

`git reset HEAD~1`

- ¿Qué comando o comandos utilizaste en el paso 28? 

`git checkout git-nuestro.md`

- ¿Qué comando o comandos utilizaste en el paso 29? 

`git branch -D title`

- ¿Qué comando o comandos utilizaste en el paso 30? 

`git reflog`  `git checkout 25942b6` `git branch title` `git checkout master` `git merge title`

- ¿Qué comando o comandos usaste en el paso 32?

`git log` `git checkout fa5812..` (inicial)

- ¿Qué comando o comandos usaste en el punto 33?

`git reflog` `git checkout 25942b6
