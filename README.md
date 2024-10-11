# Taller de Git\n\nPasos seguidos y resultados
Pasos Seguidos:
Inicializar el repositorio: Comencé por crear el repositorio local en mi máquina usando el comando git init.

Configuración del usuario: Configuré mi nombre y correo electrónico para los commits con los comandos git config --global user.name y git config --global user.email.

Creación de la rama master: Noté que Git no creó la rama master por defecto, por lo que tuve que crearla manualmente usando git checkout -b master.

Crear una rama feature: Cree una nueva rama llamada feature usando git checkout -b feature, donde realicé varios commits modificando un archivo llamado archivo.txt.

Merge y rebase: Realicé un merge de la rama feature en master, luego revertí ese merge para practicar con rebase y apliqué un rebase de la rama feature sobre master.

Cherry-pick: Utilicé cherry-pick para aplicar un cambio crítico de la rama hotfix a master sin hacer un merge completo de la rama.

Resolución de conflictos:

Generé un conflicto intencional modificando el mismo archivo conflicto.txt tanto en la rama feature como en la rama master.
Al intentar fusionar las ramas, se produjo un conflicto.
Abrí el archivo conflicto.txt y resolví manualmente el conflicto combinando los cambios de ambas ramas.
Después de resolver el conflicto, agregué el archivo resuelto al área de preparación y completé el merge con un commit final.
Resultado Obtenido:
Logré completar todas las tareas del taller, incluyendo la creación de ramas, el uso de merge y rebase, cherry-pick, y la resolución de conflictos manual. También tuve que crear la rama master manualmente, ya que no estaba por defecto en el repositorio.# demo
