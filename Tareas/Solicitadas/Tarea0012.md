## Investigar y ejecutar los comandos necesarios para almacenar las credenciales (nombre de usuario y contraseña) de GitHub en nuestra computadora y evitar tener que ingresarlas en cada push y/o pull.
Pasos a seguir:

1. Tirar el siguiente comando:
    _`git config --global credential.helper store`_
1. Asegurarse de estar parado en una carpeta que sea un repo cualquiera
1. Hacer un pull: (esto va a funcionar aunque no haya nada que pullear)
```
git pull
```

Luego de hacer el pull te pedirá tus credenciales (username y password) y estos datos serán guardados en un archivo en el disco (en la ubicación ~/.git-credentials). Esto quiere decir que no te los pedirá mas.

Nota 1: Recordar que el archivo dicho archivo anteriormente se guarda en texto plano (también la contraseña). O sea que si tenes miedo que alguien se pueda conectar a tu VM de lubuntu con tu contraseña mucho muy segura (utnso) y robarte este archivo quizá no quieras hacerlo. Esto ultimo es bastante poco probable pero sí posible.

Nota 2: Si algún día cambias la contraseña el hacer git pull básicamente fallará y esto automáticamente borrará tus credenciales del archivo. Volver a hacer git pull una vez mas debería pedirte nuevamente tus credenciales para actualizar el archivo con las nuevas.

## ¿Qué relación hay entre una prueba unitaria y la cobertura de una prueba unitaria?

Una prueba unitaria de software es el instrumento utilizado para validar un fragmento de código fuente. La cobertura de pruebas unitarias es una métrica de QA que evalúa si los casos de prueba diseñados cubren el código de la aplicación y la cantidad de este código sometido a prueba cuando se ejecutan esos casos de prueba. Por lo tanto, la cobertura de pruebas ayuda a evaluar la efectividad de sus pruebas al ofrecer datos sobre varios elementos de cobertura.