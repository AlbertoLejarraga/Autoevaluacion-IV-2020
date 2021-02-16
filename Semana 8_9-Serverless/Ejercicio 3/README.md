# Ejercicio 3

## Tomar alguna de las funciones de prueba de Netlify, y hacer despliegues de prueba con el mismo.

Se hace el registro en netlify utilizando la cuenta de github, tras lo cual se vincula el repositorio del proyecto. Hecho esto, se generan dos ficheros, por un lado el de [configuración](https://github.com/AlbertoLejarraga/percepcion-relativa-deportistas/blob/master/netlify.toml) de netlify, y por otro una [function](https://github.com/AlbertoLejarraga/percepcion-relativa-deportistas/blob/master/netlify/functions/hello.js) que es la que se desplegará para probar. Como se ve aquí, se generan las builds cada vez que se hace un push al repositorio, de igual forma a las demás herramientas utilizadas hasta ahora:

![netlify_desplegado](https://github.com/AlbertoLejarraga/Autoevaluacion-IV-2020/blob/main/Semana%208_9-Serverless/Ejercicio%203/img/netlify_desplegado.png)

Por otra parte, aquí se muestra el resultado de esta function hello, también accesible [aquí](https://percepcion-relativa-deportistas.netlify.app/.netlify/functions/hello):

![netlify_hello](https://github.com/AlbertoLejarraga/Autoevaluacion-IV-2020/blob/main/Semana%208_9-Serverless/Ejercicio%203/img/netlify_hello.png)
