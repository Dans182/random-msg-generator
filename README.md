# random-msg-generator
Random message generator

npm init -y => Con este comando + el flag -y inicializamos npm en nuestro nuevo repositorio, con la información por defecto de repositorios anteriores.

La clave “bin” se pone en el archivo package.json para asignarle los archivos que son ejecutables, osea, en “bin” se asignan las rutas de los archivos js que contienen el codigo de las llamadas de las funciones del paquete creado y segun entiendo si un codigo contiene llamadas de funciones es porque dicho codigo es un ejecutable.

¿Si lo anterior es correcto quiere decir que la clave “bin” solo se debe poner en el archivo package.json si el paquete creado es un ejecutable, osea, si el paquete es una libreria no debo poner “bin” en el archivo package.json?

Importante saber para que es el elemento bin, nos permite indicarle el nombre del paquete y donde se encuentra el archivo global que va a utilizar.

Tambien le indicamos con elemento preferGlobal, que será un paquete de forma global.