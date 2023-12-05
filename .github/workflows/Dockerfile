# Usa una imagen base ligera de alpine
FROM alpine:latest

# Define el directorio de trabajo dentro del contenedor
WORKDIR /app

# Crea un archivo de texto simple con el mensaje "Hello, World!"
RUN echo "Hello, World!" > hello.txt

# Comando a ejecutar cuando el contenedor se inicie
CMD ["cat", "hello.txt"]
