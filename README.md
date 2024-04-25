para ver si estoy conectado con un repositorio remote
git remote -v  
si todavia no estoy conectado a un repositorio remote
git init
para ver si hay aglo para commit 
git status (debe aparecer en rojo)
git status add .
para hacer un commit 
git commit -m (mensaje) 'nombre de mi commit'
para enviarlo al remote 
git push -u origin main  (main es el branch en el repositorio de origin)
puedes hacer algunas ramas (Branch) para poner tu codigo y al final la mezcla con main
para ver que Branch tiene
git branch
para cambia de branch 
git switch <nombre del branch> 
para mezclar todo en main tengo que ir primero al branch main
git switch main
traer los cambios del otro branch en main 
git merge  <nombre del branch>
ahora le puedo hacer una push al origin 
