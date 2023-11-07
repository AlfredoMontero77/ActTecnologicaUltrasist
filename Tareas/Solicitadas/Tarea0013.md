## Obtener la lista de pasos que se deben llevar a cabo desde que se clona un repositorio hasta que se fusionan los cambios en la rama principal, esto en base a Gitflow.
El flujo general de Gitflow es el siguiente:

1. Se crea una rama `develop` a partir de `main`.

2. Se crea una rama release a partir de la rama develop.

3. Se crean ramas feature a partir de la rama develop.

4. Cuando se termina una rama feature, se fusiona en la rama develop.

5. Cuando la rama release está lista, se fusiona en las ramas develop y main.

6. Si se detecta un problema en main, se crea una rama hotfix a partir de main.

7. Una vez terminada la rama hotfix, esta se fusiona tanto en develop como en main.