

##Ejercicio 3: Instalar docker.

Añadimos la clave GPG con:
```sh
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

 Ejecutamos para añadir el repositorio
 ```sh
 $ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable".
```

Actualizamos los repos:
```sh
$ sudo apt-get update
```

Para instalar Docker introducimos el comando:
 ```sh
 $ sudo apt-get install -y docker-ce
 ```

##Ejercicio 4: Instalar a partir de docker una imagen alternativa de Ubuntu y alguna adicional, por ejemplo de CentOS. Buscar e instalar una imagen que incluya MongoDB.

Lo hacemos con los comandos sudo docker pull ubuntu, sudo docker pull centos y sudo docker pull mongo. Para ver que las imágenes han sido instaladas ejecutamos sudo docker images.

##Los ejercicios 7 y 8 los he realizado sobre mi propio proyecto para la asignatura. Puede verse la configuración y el resultado [aquí](https://github.com/JaoChaos/Bot_Telegram/blob/master/README.md).
