# Ejercicio 1
## Instalar docker y/o otro gestor de contenedores como Podman/Buildah.
Se instala el gestor de contenedores Podman siguiendo las indicaciones de [este enlace](https://www.osradar.com/how-to-install-podman-on-ubuntu/).
Tras ello se utiliza la imagen hello-world de docker-hub para comprobar que funciona:
![hello-world](https://github.com/AlbertoLejarraga/Autoevaluacion-IV-2020/blob/main/Semana%204-Contenedores/img/podman.png)
Se instala también buildah, una herramienta para instalar contenedores, de manera similar a como se utilizan los Dockerfile. Si se utiliza finalmente, se analizará más a fondo en el [fichero de herramientas](https://github.com/AlbertoLejarraga/percepcion-relativa-deportistas/tree/master/docs/herramientas.md) del repositorio del proyecto.

### Nota:
Con esta instalación de podman surge un error al lanzar los contenedores una vez parados, por lo que he tenido que desintalarlo y seguir las indicaciones de [este post](https://stackoverflow.com/a/59802479), de manera que se instale la última versión de podman con bugs como este corregidos.
