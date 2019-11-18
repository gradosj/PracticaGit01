- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	git reset --hard HEAD~1. Se utilizó porque queremos perder los cambios en la working. si lo utilizasemos sin "Head", los cambios en la working se mantendrian. 
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	git reset --hard d60c351. Vuelvo al commit original para que vuelvan a estar disponibles mis ficheros en la working.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	No, indica que todo está actualizado, en la rama que nos encontramos tenemos una version posterior, por lo que la rama master no se absorbe. 
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	Si, estamos indicando que se abosrva una rama con un fichero que tiene modificadas las mismas lineas de codigo. 
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	No causó conflicto, la rama styled tenia modificaciones sobre el fichero de la rama master.
- ¿Qué comando o comandos utilizaste en el paso 25?
	git log --graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	Si, podria ser, pues queremos abosrver todos los cambios de esa rama
- ¿Qué comando o comandos utilizaste en el paso 27?
	git reset HEAD~1
- ¿Qué comando o comandos utilizaste en el paso 28?
	git restore git-nuestro.md
- ¿Qué comando o comandos utilizaste en el paso 29?
	git branch -D
- ¿Qué comando o comandos utilizaste en el paso 30?
	git reset --hard 9611f66
- ¿Qué comando o comandos usaste en el paso 32?
	git reset --hard dae5224a1e22360e58a3acd8de9af4875ff5f3d5
- ¿Qué comando o comandos usaste en el punto 33?
	git reset --hard 9611f66