## PRÁCTICA CALCULADORA
**1.** Creé un nuevo repositorio local que se llama ["my_calculator"].
**2.** Creé otro nuevo repositorio remoto en mi cuenta de Git con el mismo nombre.
**3.** Ejecuté _nano index.html_ y abrí un archivo donde pegué el código de la calculadora con el botón "x^3" y puse mi nombre.
**4.** Ejecuté _git add index.html_ para añadir el fichero html.
**5.** Hice el primer commit al cual nombré "x^3 button".
**6.** Abrí nuevamente ["nano index.html"] e insterté en el archivo el botón "x^4" junto a su función y los guardé.
**7.** Hice el segundo commit con el nombre "x^4 button".
**8.** Ejecuté nuevamente _git add index.html_ para añadir los cambios y guardarlos en el repositorio local.
**9.** Por último creo este fichero [README.md] para explicar los pasos y ejecuté _git add README.MD_.
**10.** Hice _git push origin master_ para subir todo al repositorio remoto de Github y posteriormente colgar la entrega en moodle.


## PRÁCTICA CALCULADORA ENTREGA 4

**1.** Después de _git push origin master_ con el commit "x^4" saqué la rama "sine" del commit "x^3" con _git checkout -b sine 2626986_.
**2.** Inserté el botón de sine y su función dentro de [index.html].
**3.** Ejecuté _git merge master_ y me sale error, así que ejecuté _git log --oneline --graph --all_ para ver el esquema de las ramas.
**4.** Hice commit y abrí el editor donde puse un mensaje para hacer el commit y pasar los commits de la rama main a sine.
**5.** Ejecuté _git add index.html_ para integrar los cambios que se hicieron en la anterior prueba a sine y hacer después un commit para guardaralos.
**6.** Cambié a la rama master e hice un merge sine para juntar ambas ramas en la rama principal.
**7.** verifiqué que siriviera la calculadora e hice _git push --all_ y lo llevé todo al repositorio remoto. Quedó con este enlace https: https://github.com/agalvisg/my_calculator.git


