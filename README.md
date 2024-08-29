# jupyterDocker

Proyecto para el uso de Jupyter Lab con Docker. Preparado para poder crear un token (contraseña) personalizada e instalar requirements necesarios previos.

## Instalación

Clona este repositorio en tu máquina local:

```
git clone https://github.com/tu-usuario/jupyterDocker.git
cd jupyterDocker
```
Construye la imagen de Docker y lanza el contenedor:
```
docker-compose up --build
```
## Requisitos Previos
 - Docker
 - Docker Compose

## Uso
Una vez que el contenedor esté en funcionamiento, abre tu navegador web y dirígete a http://localhost:8888. 

Utiliza el siguiente token para acceder a Jupyter Lab: `AhB5ImyU2prh6vYJ5V1Kd`
Puedes cambiar este token personalizado en el archivo docker-compose.yml según sea necesario.

## Instalación de Requerimientos Adicionales

Para instalar librerías adicionales, añade los paquetes que necesites en el archivo `requirements.txt` en la raíz del proyecto. Luego, reconstruye la imagen Docker con:

```
docker-compose up --build
```

## Contribuciones
¡Las contribuciones son bienvenidas! 
Por favor, crea un fork del repositorio, haz tus cambios y envía un pull request. También puedes reportar problemas en la sección de Issues.

### Licencia
Este proyecto está licenciado bajo la Licencia MIT.
