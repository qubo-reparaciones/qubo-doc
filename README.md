
## Para el desarrollador

### Backend

Si querés contribuír tenés que clonarte el [repositorio de la API](https://github.com/cerveceria-artesanal/enlatada-be).

##### Requerimientos
- [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Gradle](https://gradle.org/install)
- [Docker](https://docs.docker.com/engine/installation/) 
- [Docker Compose](https://docs.docker.com/compose/install/) 

   
##### Ir a la raíz del proyecto

##### Para rebuildear los mappers 
 
    ./gradlew rebuildMappers 
 
##### Levantar la base de datos postgres, con docker-compose  
    
    docker-compose up
 
##### Levantar la aplicación local en el puerto 8080
   
    ./gradlew bootRun -Dspring.profiles.active=dev -Dserver.port=8080 "link a la deb"
   
    
### Frontend

Si querés contribuír tenés que clonarte el [repositorio del cliente web!](https://github.com/cerveceria-artesanal/enlatada-fe).

##### Requerimientos
- [Node](https://nodejs.org/en/)
   
##### Proceso de build
   Instalar dependencias
   
        npm install
   Levantar la aplicación
   
        npm start
 
La aplicación se abrirá en una pestaña del navegador por defecto.

##### Navegadores compatibles
● Chrome: 40+
● Firefox: 45+
