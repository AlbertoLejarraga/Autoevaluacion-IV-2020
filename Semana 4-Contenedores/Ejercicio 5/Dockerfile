FROM alpine:latest
LABEL version="1.0.0" maintainer="alejarragar@correo.ugr.es"

WORKDIR /root/

RUN apk add nodejs git \
&& apk add --update npm \
&& git clone https://github.com/AlbertoLejarraga/percepcion-relativa-deportistas.git \
&& cd percepcion-relativa-deportistas \
&& npm install . \
&& npm test > ../resultests.txt
