## ¿Qué es un commit?
Captura una instantánea de los cambios preparados en ese momento del proyecto.
El comando git commit guardará todos los cambio hechos en la zona de montaje o área de preparación (staging area).

Los commits están en el corazón del uso de Git. Puedes pensar en un commit como una captura de tu proyecto, donde se crea una nueva versión de ese proyecto en el repositorio actual.
## ¿Qué es una rama?
Es simplemente un apuntador móvil apuntando a una de esas confirmaciones. La rama por defecto de Git es la rama master . Con la primera confirmación de cambios que realicemos, se creará esta rama principal master apuntando a dicha confirmación.
## ¿Qué es un merge y en que casos se utiliza?
Permite tomar las líneas independientes de desarrollo creadas por git branch e integrarlas en una sola rama.
Se utiliza para fusionar uno o más ramas dentro de la rama que tienes activa. A continuación avanzará la rama actual al resultado de la fusión.
## ¿Qué es un rebase y en que casos se utiliza?
El comando git rebase te permite cambiar fácilmente una serie de confirmaciones, modificando el historial de tu repositorio. Puedes reordenar, editar o combinar confirmaciones.
Normalmente, se usaría git rebase para lo siguiente:
- Editar mensajes de confirmación previos.
- Combinar varias confirmaciones en una.
- Eliminar o revertir confirmaciones que ya no son necesarias.