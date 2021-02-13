# Ejercicio 2
## Configurar integración continua para nuestra aplicación usando Travis.
Siguiendo la guía de la [documentación oficial](https://docs.travis-ci.com/user/tutorial/) se añade añade un [fichero .travis.yml](https://github.com/AlbertoLejarraga/percepcion-relativa-deportistas) básico al repositorio del [proyecto](https://github.com/AlbertoLejarraga/percepcion-relativa-deportistas), parecido al que aparece en el [tema actual](https://jj.github.io/IV/documentos/temas/Integracion_continua), y se hace push. Tras esto, en el perfil de Travis, puede verse si la build ha sido o no correcta:

![build_correcta](https://github.com/AlbertoLejarraga/Autoevaluacion-IV-2020/blob/main/Semana%206_7-CI/Ejercicio%2/img/build_correcta.png)

Además, en el log de la build, puede verse como se ha pasado el test en las dos versiones determinadas en el fichero de configuración.

Fuerzo también un fallo, utilizando una versión de node antigua que se que no va a funcionar, lo que resulta en un build erroneo, como se puede ver directamente [en la interfaz de GitHub Actions](https://github.com/AlbertoLejarraga/percepcion-relativa-deportistas/runs/1881862817)

Por último se añade el badge de travis ([aquí el commit](https://github.com/AlbertoLejarraga/percepcion-relativa-deportistas/commit/9b4595436072d1152e182bc21c40543817462d78)) para mostrar el estado del repositorio, como puede verse en la pantalla inicial de este.
