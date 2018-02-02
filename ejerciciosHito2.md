

##Ejercicio 1: Hacer un pull request a este proyecto con tests adicionales, si es que faltan (en el momento que se lea este tema):

En el caso de mi proyecto, los tests pueden encontrarse en el siguiente [enlace](https://github.com/JaoChaos/Bot_Telegram/blob/master/tests.py)

##Ejercicio 2: Para la aplicación que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir tests para una nueva funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo TDD).

Hecho para el ejercicio 1. Aunque en mi caso los tests realizados para la integración continua son algo escuetos, mi intención es mejorarlos en un futuro próximo.

##Ejercicio 3: Convertir los tests unitarios anteriores con assert a programas de test y ejecutarlos desde mocha, usando descripciones del test y del grupo de test de forma correcta. Si hasta ahora no has subido el código que has venido realizando a GitHub, es el momento de hacerlo, porque lo vas a necesitar un poco más adelante.

##Ejercicio 4: Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).

Yo he usado virtualenv, que funciona muy bien en python.

Para instalarlo usamos el comando:
```sh
$ sudo pip install virtualenv
```

Podemos ver las versioes disponibles introducimos el comando:
```sh
$ virtualenv -p /usr/bin/python
```

Una vez instalado, podemos crear nuestro entorno virtual con el comando:
```sh
$ virtualenv mientorno
```

Y lo ponemos en marcha con el comando:
```sh
$ . bin/activate
```
##Ejercicio 7: Crear una descripción del módulo usando package.json. En caso de que se trate de otro lenguaje, usar el método correspondiente.

Como estoy usando Python, hay que configurar el archivo requirements.txt. Lo podemos ver en el repositorio del proyecto.

En mi caso, si decido usar pocha el archivo quedaría de la siguiente forma:

"pocha==0.13.0"
