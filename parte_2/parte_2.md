Parte 2. Comprensión del flujo colaborativo

Responde esta parte en el documento parte_2/parte_2.md. Incluye en cada punto el planteamiento y tu
explicación.

1. Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos: Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier operación que consideres necesaria.
Yo considero que lo primero que yo haría es un Fork para tener el proyecto en mi cuenta de GitHub, luego realizaría el comando Clone con la URL para  así tenerlo en mi computadora, para no modificar dentro del proyecto original, crearía una rama (Branch) para trabajar en mis cambios y así empiezo, ya cuando termine de modificar el o los archivos, realizo el comando Commit para guardar los cambios y el Push para subirlos a GitHub. Luego en Github hago un Pull Request para pedir al propiettario o mi colaborador a que revise mis cambios, si es correcto lo que hice y todo está bien, se hace el Merge y los cambios se realizan al proyecto original.

2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta y explica la diferencia entre Fork y Clone. Yo considero que es correcta, porqeue hay dos puntos que se parecen mucho en el sentido de que ayudan a copiar el proyecto y es el Clone y el Fork, pero Clone si permite copiar el proyecto de GitHub localmente, en este caso a mi computadora para poder trabajar en él desde ahí.

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte del repositorio original? ¿Qué debe ocurrir para incorporarlos? Según yo no, todavía no pueden los cambios formar parte del repositorio original, ya que se necesita de un Pull Request para pedir que revisen los cambios y entonces si están bien y el propietario los acepta hace un Merge para agregarlos al proyecto original.

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear otro Pull Request y qué ocurre cuando realizas nuevamente push. Primero sería ver lo que se me pidió y según lo que yo entendí, no es tan necesario crear otro Pull Request, ya que se pueden generar los cambios en la misma rama y después hacer Commit y un Push otra vez, para que los nuevos cambios aparezcan en el Pull Request que ya estaba abierto para que el propietario los pueda revisar nuevamente.

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no contiene los cambios. Explica por qué sucede y qué operación debe realizarse. Tengo en tendido que es porque los cambios se hicieron en GitHub y para actualizarlos en la computadora se necesita de usar un comando llamado: git pull.

6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull. Para este caso creo que es más recomendable usar Sync Fork de GitHub, ya que éste sirve para actualizar mi Fork con los cambios que se hicieron en el repositorio original, mientras que git pull se usa en mi computadora para traer cambios desde GitHub a mi proyecto local.