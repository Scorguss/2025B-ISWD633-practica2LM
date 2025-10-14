### Crear contenedor de Postgres sin que exponga los puertos. Usar la imagen: postgres:15-alpine3.21
# COMPLETAR
hacemos un puente entre los contenedores sin exponer los puertos se trabaja con una red interna, vinculamos  esos dos para que trabajen 
docker network create
<img width="1324" height="147" alt="image" src="https://github.com/user-attachments/assets/ad0d59c9-cbd8-48e5-bbda-b77453b94330" />

para conectarse con el cliente 
<img width="1558" height="98" alt="image" src="https://github.com/user-attachments/assets/6e2b61ec-5592-49db-a20a-e1ed08db11f0" />
entrar en la bd con el cliente y contraseñas 
<img width="1881" height="1223" alt="image" src="https://github.com/user-attachments/assets/25bfaf01-abf9-4c84-bbe4-3cdb69602d4e" />

host 8080
cliente 80
Postgres  5432 

eliminar y volver a hacer:
<img width="1848" height="261" alt="image" src="https://github.com/user-attachments/assets/6a2fceb8-bcdf-4500-917b-25c712abcb58" />

### Crear un cliente de postgres. Usar la imagen: dpage/pgadmin4
Crear un cliente de postgres. Usar la imagen: dpage/pgadmin4
# COMPLETAR

La figura presenta el esquema creado en donde los puertos son:
- a: (completar con el valor)
- b: (completar con el valor)
- c: (completar con el valor)

![Imagen](esquema-2-ejercicio.PNG)

## Desde el cliente
### Acceder desde el cliente al servidor postgres creado.
# COMPLETAR CON UNA CAPTURA DEL LOGIN
### Crear la base de datos info, y dentro de esa base la tabla personas, con id (serial) y nombre (varchar), agregar un par de registros en la tabla, obligatorio incluir su nombre.

## Desde el servidor postgresl
### Acceder al servidor
### Conectarse a la base de datos info
# COMPLETAR
### Realizar un select *from personas
# AGREGAR UNA CAPTURA DE PANTALLA DEL RESULTADO
