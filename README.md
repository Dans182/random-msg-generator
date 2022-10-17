# random-msg-generator
Random message generator

# random-msg-generator

Whenever I start a new project, I don't know what to write for the first commit. After doing a “git init” there is technically nothing there...

## Install

```npm
npm install -g random-msg-generator
```

# Usage

```bash
 random-msg-generator
```

# Contributing

If someone wants to add or improve something, I invite you to collaborate directly in this repository: [random-str-msg](https://github.com/gndx/random-str-msg)

# License

funny-commit is released under the [MIT License](https://opensource.org/licenses/MIT).


npm init -y => Con este comando + el flag -y inicializamos npm en nuestro nuevo repositorio, con la información por defecto de repositorios anteriores.

La clave “bin” se pone en el archivo package.json para asignarle los archivos que son ejecutables, osea, en “bin” se asignan las rutas de los archivos js que contienen el codigo de las llamadas de las funciones del paquete creado y segun entiendo si un codigo contiene llamadas de funciones es porque dicho codigo es un ejecutable.

¿Si lo anterior es correcto quiere decir que la clave “bin” solo se debe poner en el archivo package.json si el paquete creado es un ejecutable, osea, si el paquete es una libreria no debo poner “bin” en el archivo package.json?

Importante saber para que es el elemento bin, nos permite indicarle el nombre del paquete y donde se encuentra el archivo global que va a utilizar.

Tambien le indicamos con elemento preferGlobal, que será un paquete de forma global.

npm link => Crea un enlace simbólico, para reconocer a este paquete dentro del listado de paquetes de npm, sin publicarlo todavía pero si verificar que cumple todo lo requerido:

Si no tiene vulnerabilidades, significa que está todo correcto y puede ser perfectamente integrado al listado de paquetes de npm.

Antes de integrarlos, tenemos que probarlo.

Para probarlo se deben seguir los siguientes pasos

    pwd => para saber exactamente donde se encuentra la ruta de nuestra dependencia.

    npm install g ruta-de-la-dependencia(pwd) => Simulará la instalación de la dependencia en nuestro local

    Luego ya podemos correr nuestro programa en consola:

    random-msg-generator

Ya verificado que efectivamente funciona, podemos seguir con la creación de la cuenta y :

    Vamos a la terminal

    npm adduser

    Añadimos los datos que nos pide la consola …

    Y se publica el paquete 🙌🏻

    npm publish

    Se busca en npm la dependencia y se verifica que este subida !



Semántica de versionados
    https://semver.org/lang/es/

Listado de comandos
    https://gist.github.com/Jsifontez/b3f1d34795748f1abe100f031806076d

https://luis-ariza.notion.site/NPM-Gesti-n-de-Dependencias-y-Paquetes-en-JavaScript-8d621bda1a3743f6a45f068dcdc2deb3


