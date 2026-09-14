Nombre: Rodríguez Reyes Juan Manuel



Matricula: 2630321



Nombre de la practica: Creación y administración de un repositorio con Git y GitHub



Objetivo de la Practica: el estudiante deberá ser capaz de crear y administrar un repositorio local con Git, utilizar el Staging Area, realizar commits, vincular un repositorio local con GitHub y sincronizar cambios utilizando git push y git pull.



Descripción del procedimiento realizado: Primero creé una carpeta para la práctica y dentro de ella inicié un repositorio con git init. Después cambié el nombre de la rama principal a main y creé los archivos README.md y datos.txt, después revisé el estado del repositorio con git status para ver qué archivos había. Utilicé git add . para pasar los archivos al Staging Area y después hice mi primer commit con git commit -m "Primer commit", luego creé el repositorio en GitHub y lo dejé vacío, ya que los archivos los iba a subir desde mi computadora. Con git remote add origin conecté mi repositorio local con el repositorio de GitHub y con git remote -v comprobé que la conexión estuviera bien, después utilicé git push -u origin main para subir los archivos a GitHub. En este proceso también configuré una llave SSH para poder conectar mi computadora con GitHub, para comprobar que también podía traer cambios desde GitHub, modifiqué el archivo datos.txt directamente desde la página de GitHub. Agregué una línea indicando que el archivo había sido modificado desde GitHub y guardé el cambio haciendo un commit, después regresé a PowerShell y utilicé git pull origin main. Esto descargó el cambio que había hecho en GitHub y lo agregó a mi archivo local y luego volví a modificar datos.txt, pero esta vez desde mi computadora. Agregué una línea diciendo que el archivo había sido modificado desde el repositorio local. Después hice git add ., creé otro commit y utilicé git push para subir el cambio nuevamente a GitHub



Comandos de Git utilizados:



git init



Sirve para crear un repositorio de Git dentro de la carpeta donde estoy trabajando



git branch -m main



Sirve para ponerle main como nombre a la rama principal



git status



Sirve para revisar qué está pasando en el repositorio, por ejemplo, si hay archivos nuevos o cambios que todavía no se han guardado en un commit



git add .



Sirve para agregar los archivos y cambios al Staging Area antes de hacer un commit



git commit -m "mensaje"



Sirve para guardar los cambios en el historial de Git. El mensaje ayuda a saber qué se hizo en ese commit



git remote add origin URL



Sirve para conectar el repositorio que tengo en mi computadora con el repositorio que tengo en GitHub



git remote -v



Sirve para comprobar qué repositorio remoto está conectado



git push



Sirve para subir a GitHub los commits que tengo en mi computadora



git pull origin main



Sirve para descargar los cambios que están en GitHub y traerlos a mi computadora



Explicación de cómo se creó el repositorio local:



Primero hice la carpeta de la práctica y entré a ella desde PowerShell y luego utilicé git init para convertir esa carpeta en un repositorio de Git y también cambié la rama principal a main y agregué los archivos que necesitaba para la práctica, después hice el primer commit para guardar esos archivos en el historial



Explicación de cómo se vinculó el repositorio local con GitHub:



Primero creé un repositorio público en GitHub sin agregar README, .gitignore ni licencia. Después copié la dirección del repositorio y utilicé git remote add origin para conectarlo con mi repositorio local y luego tuve que configurar una llave SSH para poder autenticar mi computadora con GitHub



Explicación de la sincronización Local → GitHub: Para mandar mis cambios desde la computadora hacia GitHub utilicé git push, primero subí los archivos iniciales con git push -u origin main y ya después hice otro cambio desde mi computadora, creé un nuevo commit y utilicé git push para mandarlo a GitHub



Explicación de la sincronización GitHub → Local: hice un cambio directamente desde GitHub en el archivo datos.txt y luego regresé a mi computadora y utilicé git pull origin main y con eso pude descargar el cambio que había hecho en GitHub y verlo también en mi archivo local



Descripción de los archivos contenidos en el repositorio:



README.md:



Es el archivo donde está explicada la práctica, los comandos que utilicé y lo que aprendí durante el proceso



datos.txt:



Es un archivo de texto que utilicé para hacer las modificaciones de la práctica, primero lo modifiqué desde GitHub y después desde mi computadora



CONCLUCION: Este tipo de tareas y practicas nos ayudan a recordar y repasar lo visto en clase y tenerlo en cuanta además de investigar lo que no entendemos y poderlo usarlo bien en clase, tareas o proyectos





