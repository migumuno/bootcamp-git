# Preguntas Ejercicio 1

* ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilicé **git reset --hard HEAD~1** por que era necesario retroceder un commit (HEAD~1) y perder los cambios realizados en el working copy (--hard).

* ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Utilicé primero **git reset [hash_del_commit]** para comprobar qué ocurría y movió HEAD al commit perdido pero el working copy no recuperó el archivo.
Finalmente, utilicé **git reset --hard [hash_del_commit]** y movió HEAD al commit perdido y también recuperó los archivos dejando todo como estaba.

* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causó ningún conflicto ya que no había ninguna diferencia con la rama master.

* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, se produjo un conflicto en el archivo git-nuestro.md, tenían diferente contenido en la rama styled y htmlify. Resolví el conflicto manteniendo
el contenido que tenía la rama styled.

* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No causó ningún conflicto ya que hizo un merge fast-forward.

* ¿Qué comando o comandos utilizaste en el paso 25?
Utilicé el comando **git graph** para mostrar el dibujo ya que ya tenía predefinido un alias para el comando 
**git log --graph --pretty=oneline --decorate**.

* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, ya que estaban alineadas las ramas title y master, se podía hacer un movimiento de puntero simplemente.

* ¿Qué comando o comandos utilizaste en el paso 27?
Utilicé el comando **git reflog** para ver el historial y el identificador y el comando **git reset [hash_del_commit]** para deshacer el merge
ya que había hecho un commit entre medias cambiando el archivo readme.md.

* ¿Qué comando o comandos utilizaste en el paso 28?
Utilicé el comando **git checkout -- git-nuestro.md** para descartar los cambios del working copy.

* ¿Qué comando o comandos utilizaste en el paso 29?
Utilicé el comando **git branch -D title** para eliminar la rama title.

* ¿Qué comando o comandos utilizaste en el paso 30?
Utilicé el comando **git reflog** para ver el historial y el identificador y el comando **git reset [hash_del_commit]** para deshacer el merge

* ¿Qué comando o comandos usaste en el paso 32?
Utilicé el comando **git reflog** para ver el historial de commits y buscar el hash del commit inicial y después usé el comando
**git checkout [hash_del_commit]** para desplazar el puntero hasta el.

* ¿Qué comando o comandos usaste en el punto 33?
Utilicé el comando **git reflog** para ver el historial de commits y buscar el hash del commit final y después usé el comando
**git checkout [hash_del_commit]** para desplazar el puntero hasta el. Después tuve que hacer un **git checkout master** para
volver a la rama master.

**En el último paso ponía Ir al tag htmlify y así lo hice pero para finalizar volví a la rama master para que el archivo readme.md con las
respuestas a las preguntas quedase visible. Aunque esto quedó registrado en el reflog así que ya lo sabréis jeje.**
