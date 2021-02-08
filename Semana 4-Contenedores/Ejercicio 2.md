# Ejercicio 2

1. Instalar a partir de docker una imagen alternativa de Ubuntu y alguna adicional, por ejemplo de CentOS.
Instalo la imagen de ubuntu con nginx, de manera que se pueda utilizar este servidor web. Para ello hago:

  * podman pull ubuntu/nginx
  * podman run -d --name nginx-container -e TZ=UTC -p 8080:80 ubuntu/nginx

Tras esto se deja corriendo el contenedor con el puerto 8080 expuesto:
![nginx-lanzado](https://github.com/AlbertoLejarraga/Autoevaluacion-IV-2020/blob/main/Semana%204-Contenedores/img/ubuntu-nginx.png)


2. Buscar e instalar una imagen que incluya MongoDB.
Se instala una imagen basada en centos:
![centos-mongo](https://github.com/AlbertoLejarraga/Autoevaluacion-IV-2020/blob/main/Semana%204-Contenedores/img/centos-mongo.png)
