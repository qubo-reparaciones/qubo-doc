# Qubo reparaciones

<Ingresar logo> Sistema para gestionar los pedidos de reparaciones con un sistema que permite registrar diferentes técnicos y sucursales.
Para más detalles consultar la [wiki](https://github.com/qubo-reparaciones/qubo-doc/wiki) del proyecto.

## Para el usuario

Tener en cuenta que hay que configurar el usuario admin, que va a tener el control de los técnicos que se permiten registrar y las sucursales.
Loguearse por primera vez: `usuario: admin, contraseña: admin`. El sistema debería obligar el cambio de la contraseña. 

## Para el desarrollador

### Backend

Si querés contribuír tenés que clonarte el [repositorio de la API](https://github.com/qubo-reparaciones/qubo-be).

##### Requerimientos
- [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Gradle](https://gradle.org/install)

   
##### Ir a la raíz del proyecto

##### Para rebuildear los mappers 
 
    ./gradlew rebuildMappers 
  
##### Levantar la aplicación local en el puerto 8080
   
    ./gradlew bootRun -Dspring.profiles.active=dev -Dserver.port=8080 "link a la deb"
   
    
### Frontend

Si querés contribuír tenés que clonarte el [repositorio del cliente web!](https://github.com/qubo-reparaciones/qubo-fe).

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
