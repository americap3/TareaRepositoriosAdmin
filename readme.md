# INSTALACIÓN Y CONFIGURACIÓN DE GIT EN UBUNTU

Git es una herramienta de control de versiones distribuido que es gratis y de código abierto, esta diseñado para manejar todo lo relacionado con proyectos ya sean grandes o pequeños con velocidad y eficiencia.

## Getting Started

A continuación se muestran las instrucciones para instalar la herramineta de control de versiones git.

### Prerequisites
Abre una ventana de la terminal y deberas tener instalado el gestor de paquetes apt.

```
$ sudo apt-get update
$ sudo apt-get install apt
```

### Installing

Para instalar ejecuta los siguientes comandos:

```
sudo apt update
```
```
sudo apt install git
```

## Running the tests

Para comprobar que se ha instalado correctamente y saber que versión se ha instalado, escribimos:

```
$ git --version
```


### Break down into end to end tests

Ahora, si se quiere personalizar con nombre y correo, escribe:

```
$ git config --global user.name "Tu nombre"
$ git config --global user.email "persona@correo.com"
```

### And coding style tests

Y para comprobar que el usuario se ha configurado correctamente:

```
$ git config --global user.name
```
```
$ git config --global user.email
```

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

* **Ing. Luis Antonio Ramírez Martínez**

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **América Martínez**

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
