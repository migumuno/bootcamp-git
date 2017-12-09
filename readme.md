#Preguntas Ejercicio 1

* ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Utilicé *git reset --hard HEAD~1* por que era necesario retroceder un commit (HEAD~1) y perder los cambios realizados en el working copy (--hard).

* ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Utilicé primero *git reset [hash_del_commit]* para comprobar qué ocurría y movió HEAD al commit perdido pero el working copy no recuperó el archivo.
Finalmente, utilicé *git reset --hard [hash_del_commit]* y movió HEAD al commit perdido y también recuperó los archivos dejando todo como estaba.

* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causó ningún conflicto ya que hizo un merge fast-forward.

* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, se produjo un conflicto en el archivo git-nuestro.md, tenían diferente contenido en la rama styled y htmlify. Resolví el conflicto manteniendo
el contenido que tenía la rama styled.

* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?


* ¿Qué comando o comandos utilizaste en el paso 25?

* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

* ¿Qué comando o comandos utilizaste en el paso 27?

* ¿Qué comando o comandos utilizaste en el paso 28?

* ¿Qué comando o comandos utilizaste en el paso 29?

* ¿Qué comando o comandos utilizaste en el paso 30?

* ¿Qué comando o comandos usaste en el paso 32?

* ¿Qué comando o comandos usaste en el punto 33?
