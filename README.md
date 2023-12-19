# aluxion-node-api-rest
REST API to test for Aluxion

# Definición
Realizar un API Rest para una web de subida y gestión de archivos.
Entre los servicios que se tendrán que realizar están:
- Login
- Registro (Con la contraseña encriptada)
- Olvide contraseña con envío de email.
- Subida de archivos (AWS S3)
- Bajada de archivos (AWS S3)
- Gestor de archivos donde puedes: cambiar nombre y obtener enlace de
archivo. (AWS S3)
- Integrar un buscador de imagenes online usando una API externa
(Unsplash por ejemplo)
- Subir una imagen proveniente de una API externa directo a S3 (Es
decir, sin que el usuario tenga que bajar la imagen en su local y luego
subirla manualmente)

# Especificaciones
### Para el almacenamiento de los archivos usando AWS S3, te dejamos un

### Para base de datos:
El sistema que mejor consideres para el tipo de estructura.

### Para autenticación:
Un servicio de OAuth mediante Token.

# Se valorará el uso de las siguientes tecnologías:
- Arquitectura escalable
- Documentación de servicios con SWAGER.
- Uso de Docker y NestJS
- Pruebas unitarias (Jest)
