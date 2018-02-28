# Práctica GIT - Respuestas

### Roig Daras, Paula

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

git reset --hard HEAD~1

Porque es el comando que sirve para deshacer el último commit, quedandose en el anterior, y que además elimina todo lo modificado, es decir que elimina lo que hay en el working copy hasta el último commit.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

git reflog y git reset --hard 027deb9

Porque aunque el último commit hubiese desaparecido y hubiese perdido toda la información, con git reflog puedes ver como el historial de los pasos que has ido haciendo y los commits por donde te has movido y localizar el commit donde quieres estar y con git reset--hard vuelves al commit que deseas y mantienes el working copy que había.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

Si, la rama "styled" no puede absorber a "master", ya que es su madre, es decir, esta rama ya esta fusionada con su anterior, ya que además estan en linea, y la rama "styled" va por delante lo que quiere decir que además de estar actualizada con la anterior, va en cabeza.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Si, ya que estas dos ramas tiene en común un mismo commit, es decir una misma versión del archivo, que después se ha tomado, y en cada rama ha sido modificado de una forma. Y al intentar hacer el merge, no se puede ya que es el mismo archivo , pero modifcado de diferentes formás, entonces debemos o seleccionar una de las dos, o modificarlo en común. 

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No, ya que la rama "Master" esta detrás de la rama "Styled" y por tanto al estar detras y en linea, absorbe todo hasta donde llega styled. Se produce FAST-FORWARD. Teniendo ahora toda la información de todos los commits en ella.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

git graph

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si, ya que la rama "Title" esta creada en el ultimo commit, es decir que se queda por delante de la rama "Master", de la cual es una rama hija,  y que además estan en linea y aún no estan ramificadas.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

git reset HEAD~1

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

git status  y  git checkout -- .\don-quijote.md

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

git branch -d title y git branch -D title

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

git reflog y  git reset --hard 7447017

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

git reflog y git reset --hard 0bed926

--

**13. ¿Qué comando o comandos usaste en el punto 33?**

git reflog y git reset --hard 458f06a

--