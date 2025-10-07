# Variables de Entorno
### ¿Qué son las variables de entorno?

Son valores dinamicos para configuraciones del entorno de un sistema
Al ser configuraciones, sobre todo de contraseña, suelen estar ocultas y encriptadas
# COMPLETAR

### Para crear un contenedor con variables de entorno

```
docker run -d --name <nombre contenedor> -e <nombre variable1>=<valor1> -e <nombre variable2>=<valor2>
```

### Crear un contenedor a partir de la imagen de nginx:alpine con las siguientes variables de entorno: username y role. Para la variable de entorno rol asignar el valor admin.

# COMPLETAR

# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR

<img width="1120" height="127" alt="image" src="https://github.com/user-attachments/assets/c72e553e-959c-43fc-8659-a34741bd2722" />


Para ver que si se creo: docker inspect NOmbreContenedor
<img width="1222" height="604" alt="image" src="https://github.com/user-attachments/assets/da793afa-7978-4d9e-be83-4eac4561f1a6" />

### Crear un contenedor con la imagen de mysql, mapear todos los puertos
# COMPLETAR
docker run -P -d --name MYSQLXD mysql
<img width="994" height="597" alt="image" src="https://github.com/user-attachments/assets/3ca3fab9-371e-40d4-9b3d-2867c7133314" />


### ¿El contenedor se está ejecutando?
# COMPLETAR
<img width="2143" height="1427" alt="image" src="https://github.com/user-attachments/assets/7dd02c90-3c55-46a1-b3f3-d0ed8dca4e18" />
ya no 

### Identificar el problema
# COMPLETAR

### Para crear un contenedor con variables de entorno especificadas
- Portabilidad: Las aplicaciones se vuelven más portátiles y pueden ser desplegadas en diferentes entornos (desarrollo, pruebas, producción) simplemente cambiando el archivo de variables de entorno.
- Centralización: Todas las configuraciones importantes se centralizan en un solo lugar, lo que facilita la gestión y auditoría de las configuraciones.
- Consistencia: Asegura que todos los miembros del equipo de desarrollo o los entornos de despliegue utilicen las mismas configuraciones.
- Evitar Exposición en el Código: Mantener variables sensibles como contraseñas, claves API, y tokens fuera del código fuente reduce el riesgo de exposición accidental a través del control de versiones.
- Control de Acceso: Los archivos de variables de entorno pueden ser gestionados con permisos específicos, limitando quién puede ver o modificar la configuración sensible.

### Crear un contenedor con mysql, mapear todos los puertos y configurar las variables de entorno mediante un archivo
# COMPLETAR

# CAPTURA CON LA COMPROBACIÓN DE LA CREACIÓN DE LAS VARIABLES DE ENTORNO DEL CONTENEDOR ANTERIOR 

### ¿Qué bases de datos existen en el contenedor creado?
<img width="1084" height="503" alt="image" src="https://github.com/user-attachments/assets/75502e3d-b232-425f-a0f2-6fcb9098a213" />

# COMPLETAR
Tiene 4 <img width="341" height="322" alt="image" src="https://github.com/user-attachments/assets/366ad422-b877-4477-b284-65256bcb4fda" />

