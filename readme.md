#Respuestas Practica

**11- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

git reset --hard HEAD~1

para mover los punteros styled y head a la posicion anterior en misma rama.
reset hard para modificar los archivos en el working copy y que coincidan con los de ese commit 

**12- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

git reflog para identificar el commit al que quiero ir
git reset --hard 4aa090e para mover los punteros a ese commit y cambiar los archivos del working 
area

**13- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

Ningun conflicto porque los cambios de Master ya estaban contenidos en Styled (estan en la misma 
linea)

**19- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Si. Causo conflicto porque cada los archivos git-nuestro.md de cada una de las 2 ramas habian 
sido modificados en las mismas lineas.

**21- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No causo conflicto porque fue un merge fast-forward.

**25- ¿Qué comando o comandos utilizaste en el paso 25?**

git log --graph

**26- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si. Porque master esta en la misma linea que title. Master no contiene ningun cambio que no este 
incluido en title.

**27- ¿Qué comando o comandos utilizaste en el paso 27?**

git reset HEAD~1

**28- ¿Qué comando o comandos utilizaste en el paso 28?**

git checkout git-nuestro.md

**29- ¿Qué comando o comandos utilizaste en el paso 29?**

git branch -D title

**30- ¿Qué comando o comandos utilizaste en el paso 30?**

git reset --hard HEAD@{1}

**32- ¿Qué comando o comandos usaste en el paso 32?**

git reset --hard HEAD~3

**33- ¿Qué comando o comandos usaste en el punto 33?**

git reset --hard HEAD@{1}

##-----------FIN DE RESPUESTAS------------

**Diego Alvarado**
