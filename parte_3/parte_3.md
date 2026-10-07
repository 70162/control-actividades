Parte 3. Interpretación de comandos

Responde esta parte en el documento parte_3/parte_3.md. Incluye cada planteamiento y su explicación.

1. Analiza
git status
git add README.md
git commit -m "Actualiza documentación"
git push
Explica qué ocurre en cada instrucción:
git status sirve para revisar el estado del proyecto y ver si hubo modificaciones en los archivos.
git add README.md prepara o agrega el archivo README.md para guardarlo en Git.
git commit -m "Actualiza documentación" guarda ese cambio que se hizo en el historial y se le pone un nombre.
git push sube los cambios que se hicieron en mi computadora a GitHub.

2. Identifica qué falta
Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push
Indica qué operación falta y explica su función: Faltaría un git commit para que se pueda guardar ese cambio.

Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local
Indica qué operación utilizarías y explica por qué: Yo condsireo que sería un Clone, con el comando de git clonne, para que pueda copiar el proyecto y tabajarlo desde mi repositorio local.

Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado
Indica qué operación utilizarías y explica por qué: Utilizaría un git pull, ya que sirve para traer los cambios que están en GitHub a mi computadora y de esa manerta se actualiza mi proyecto de manera local.